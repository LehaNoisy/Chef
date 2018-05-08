Vagrant.configure("2") do |config|  
    config.vm.define :main2 do |main2|
        main2.vm.provider :virtualbox do |v|
            v.name = "Chef_Virtual"
        end

        main2.vm.box = "bento/centos-7.3"
        main2.vm.network :private_network, ip: "10.0.0.10"
        main2.ssh.forward_agent = true
	end
end
