**************************************
  Getting data on S3 for pipeline
**************************************


* Create a role for s3 access

* Provision an EC2 instance and select the role created.

* SSH into the instance

* Install aws cli
# apt install awscli -y


* Download 1gb file
# wget http://speedtest.ftp.otenet.gr/files/test1Gb.db

# wget http://ipv4.download.thinkbroadband.com/1GB.zip


* Create a bucket in S3 and grant public write permission to it.

* Move datasets to S3
# aws s3 cp /root/1GB.zip s3://bucket/
# aws s3 cp /root/test1Gb.db s3://bucket

* Check your S3 bucket in console
