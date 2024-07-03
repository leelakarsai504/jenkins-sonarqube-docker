# jenkins-sonarqube-docker
create 3 EC2-Instances with t2-meduim configuration gor jenmins,sonarqube and docker
ssh -i <jenkinspip.pem> <username>@<ip_address>

if any permission denied error of the key (ssh key is too open)
chmod 400 <keyname.pem>
install openjdk-11-jre
install jenkins
change Intial Admin password
and install required plugind
configure webhook gitrepo setting--> Webhook
