# Chef

## Useful commands:

$ chef generate repo task1     - generate repository <br />
$ sudo chef-client -z --runlist "mynginx"     - run cookbook mynginx <br />

$ knife bootstrap 10.1.1.15 --ssh-user vagrant --sudo --identity-file ~/.ssh/private_key -E Chef-dev --node-name node1-centos --run-list 'role[web]'


