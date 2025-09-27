# WebApplication
Deploying Flask with AWS Elastic Beanstalk and RDS MySQL

Please check my blog for step by step deploy and hosting:
https://preranask.hashnode.dev/deploying-flask-with-aws-elastic-beanstalk-and-rds-mysql

Commands which I used to setup:
connect with Webapplication instance
PS C:\Users\Prerana> ssh -i .\Desktop\awskey\110-pem ec2-user@13.204.209.10
install MySql
[ec2-user@ip-172-31-8-168 ~]$ sudo yum install mariadb105 -y
set connection with database
[ec2-user@ip-172-31-8-168 ~]$ mysql -h insured.c3yas4w8qteq.ap-south-1.rds.amazonaws.com -P 3306 -u admin -p
