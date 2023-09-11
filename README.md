# ec2-project
dev-ops aws ec2 project


this is ec2 project

1 - login ti aws ( Amazon web services)

2 - select lunch insteance
3 - select t3 micro - as an computing options
4 - key pair name - wordpress .ppk
5 - allow all the security groups
6 - lunch instance and click the instunce id
7 - createing ubuntu system
8 - connect to the instance
9 - instull apachi web server
 
sudo apt update && sudo apt upgrade
when needed press y
sudo apt install apache2
when nedded press y

check apache2 version - apache2 -v
sudo service apache2 start
sudo service apache2 status

copy the ips adress number
cd /var/www/html
ls
sudo rm index.html
sudo nano index.html
sudo servive apache2 restart


sudo service apache2 status


