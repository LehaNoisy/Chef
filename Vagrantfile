# -*- mode: ruby -*-
# vi: set ft=ruby :

NODE_COUNT = 2

Vagrant.configure("2") do |config|
 config.vm.define "server" do |subconfig|
    subconfig.vm.box = "centos-7.4-x86_64-minimal.box"
    subconfig.vm.hostname = "server"
    subconfig.vm.network :private_network, ip: "10.0.0.10"
    v.name="server"
    end
 end
end

Vagrant.configure("2") do |config|
 config.vm.define "node1" do |subconfig|
    subconfig.vm.box = "centos-7.4-x86_64-minimal.box"
    subconfig.vm.hostname = "node1"
    subconfig.vm.network :private_network, ip: "10.0.0.15"
    v.name="node1"
    end
  end
end
