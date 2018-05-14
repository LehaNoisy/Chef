# Chef

## Task3

###### 1. Setup new Vagrant VM and install chef server. 
###### 2. Install chef client on your local PC and configure knife to work with your chef server <br />
###### 3. Create new branch from master in your cookbooks git repository. <br />
###### 4. Upload  your cookbooks to chef server using knife / berks <br />
###### 5. Create new Chef-dev environment using knife <br />
###### 6. Add “application repo” environment attribute and set its value to http://www.cumulogic.com/download/Apps/hudson.zip <br />
###### 7. Download hudson.zip to your pc, unpack and extract hudson.xml. Modify xml values: change <engine>Tomcat-7.0.12</engine> to jboss and remove load balancer section. <br />
###### 8. Create databag with your xml file and modify recipes to replace original xml before application deploy. <br />
###### 9. Modify your existing Jboss cookbooks to deploy application from link in environment attribute and upload them to chef server using knife <br />
###### 10. Create new JBOSS role and add required recipes to setup new Jboss server with Hudson app. <br />
###### 11. Setup new Vagrant VM and bootstrap chef client with JBOSS role using “knife bootstrap” command <br />
###### 12. Commit and push your changes to your branch. Create Pull request to master. <br />

## Useful commands:

$ chef generate repo task1     - generate repository <br />
$ sudo chef-client -z --runlist "mynginx"     - run cookbook mynginx <br />
