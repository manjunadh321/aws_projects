# aws_projects
This is my AWS project which i developed during internship in NIC-Delhi 31st july to 29 september 2023

User Data for Dependencies installations for AMAZON Linux 2:-

#!/bin/bash
sudo yum -y update
sudo yum -y install ruby
sudo yum -y install wget
cd /home/ec2-user
wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazonaws.com/latest/install
sudo chmod +x ./install
sudo ./install auto
sudo yum install -y python-pip
sudo pip install awscli
