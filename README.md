# Chef

## Task4: <br />
###### 1. From previous tasks you have node with role web_server and one node with role jboss_server./tomcat on 2 different instances.<br />
###### 2. Create cookbooks that provides web_server & app_server custom resources.<br />
###### 3. Resource web_server should have 2 actions “attach” and “detach” (proxy pass rule for application)<br />
###### 4. Attach and detach actions should use property: role. These actions will find the nodes with the role in the environment, using search and should add or remove that nodes from proxy config.<br />

## Useful commands:

$ chef generate repo task1     - generate repository <br />
$ sudo chef-client -z --runlist "mynginx"     - run cookbook mynginx <br />

$ knife bootstrap 10.1.1.15 --ssh-user vagrant --sudo --identity-file ~/.ssh/private_key -E Chef-dev --node-name node1-centos --run-list 'role[web]'


