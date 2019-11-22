Docker compose:
1. Untar the contents of shared_1_2_6_1_v02.tar into the folder /var/myapp
	So, you should have the following folders:
	1. /var/myapp/appdb
	2. /var/myapp/cyclosapp
	3. /var/myapp/applb01
	4. /var/myapp/applb02/
	5. /var/myapp/apprp01/
2. Next, cd to the folder containing the 02_Docker_Compose-Multi_Tier_App.yaml file
3. Run "docker-compose up -d"