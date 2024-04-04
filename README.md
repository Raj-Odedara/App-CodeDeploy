# AWS CICD Pipeline Code Deployment to AWS EC2 Instance using AWS CodeDeploy


<b>User Data for Dependencies installations for AMAZON Linux 2:-</b>

#!/bin/bash 
sudo yum -y update
sudo yum -y install ruby 
sudo yum -y install wget 
cd /home/ec2-user 
sudo chmod +x ./install 
sudo ./install auto 
sudo yum install -y python-pip 
sudo pip install awscli
