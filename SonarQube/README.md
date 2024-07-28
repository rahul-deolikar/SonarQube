[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Profile-informational?style=flat&logo=linkedin&logoColor=white&color=0D76A8)](https://www.linkedin.com/in/abhipraydhoble/)

# SonarQube
## Steps to Install SonarQube:
sudo apt update -y
## Step1->install java
sudo apt-get update && sudo apt-get install openjdk-11-jdk
## step2->
apt install unzip
user root:
#adduser sonarqube
user sonarqube:
#wget https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-9.4.0.54424.zip
unzip *
user root:
#chmod -R 755 /home/sonarqube/sonarqube-9.4.0.54424
#chown -R sonarqube:sonarqube /home/sonarqube/sonarqube-9.4.0.54424
user sonarqube:
#cd sonarqube-9.4.0.54424/bin/linux-x86-64/
#./sonar.sh start

## publicIP:9000 (by default username & password is admin)
Create the token

## SonarQube Plugin in jenkins:
SonarQube Scanner (Install without restart)

Goto Jenkins Dashboard → Manage Jenkins → Credentials → Add Secret Text. 

After adding sonar token

Click on Apply and Save

The Configure System option is used in Jenkins to configure different server

Global Tool Configuration is used to configure different tools that we install using Plugins

We will install a sonar scanner in the tools.

