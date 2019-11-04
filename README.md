# CS230-Homeland_Security
CS 230 Final Projec

Compute power -> EC2 

Storage -> S3

https://docs.aws.amazon.com/machine-learning/latest/dg/using-amazon-s3-with-amazon-ml.html

https://www.kaggle.com/c/passenger-screening-algorithm-challenge/notebooks

Instructions to SSH:

TO: SSH INTO MY INSTANCE 
$ ssh -fNL 8888:localhost:8888 -i "CS230.pem" ubuntu@ec2-54-218-87-149.us-west-2.compute.amazonaws.com
>>The authenticity of host 'ec2-54-218-87-149.us-west-2.compute.amazonaws.com (54.218.87.149)' can't be established.
>>ECDSA key fingerprint is SHA256:jkA4sTObQX/j5htmPf6tz6Lb5sLMr2fwVGvYHwpByD8.
>>Are you sure you want to continue connecting (yes/no)? 
$yes

$jupyter notebook --no-browser

GOTO YOUR WEB BROWSER: http://localhost:8888/

Notebook Password: Texted it to you 

_____

MY STEPS

To create Tunnel: 
$ ssh -fNL 8888:localhost:8888 -i "CS230.pem" ubuntu@ec2-54-218-87-149.us-west-2.compute.amazonaws.com
>>The authenticity of host 'ec2-54-218-87-149.us-west-2.compute.amazonaws.com (54.218.87.149)' can't be established.
>>ECDSA key fingerprint is SHA256:jkA4sTObQX/j5htmPf6tz6Lb5sLMr2fwVGvYHwpByD8.
>>Are you sure you want to continue connecting (yes/no)? 
$yes

$jupyter notebook --no-browser

GOTO YOUR WEB BROWSER: http://localhost:8888/

To access your instance:
1. Open an SSH client. (find out how to connect using PuTTY)
2. Locate your private key file (CS230.pem). The wizard automatically detects the key you used to launch the instance.
3. Your key must not be publicly viewable for SSH to work. Use this command if needed:chmod 400 CS230.pem 
4. Connect to your instance using its Public DNS:ec2-54-218-87-149.us-west-2.compute.amazonaws.com 
Password: I texted it to you 


paperswithcode
"Detecting Zones and Threat on 3D Body for Security in Airports using Deep Machine Learning"
https://github.com/abelguima/ryerson-capstone-CKME136









