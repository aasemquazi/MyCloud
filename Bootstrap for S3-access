#!/bin/bash
sudo su
apt-get update -y
apt install apache2 -y
curl -O https://bootstrap.pypa.io/get-pip.py
python3 get-pip.py
pip install awscli
aws s3 cp s3://rick-buck /var/www/html/ --recursive
service apache2 start
