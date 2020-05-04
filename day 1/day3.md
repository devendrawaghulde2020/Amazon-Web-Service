# S3-upload/download
> + On s3 we can do web hosting but condition is that u can host static websites only.If you want to host dynamic pages then by using react we can host it.
> + In bucket ,we can creat folder ,In folder we can create the another folder or we can upload the file.
Now if I want to host 1 webpage in a bucket ,So for that make 1 web page and save it into the desktop. Let say welcome.html
> + So let create 1 new folder inside the bucket 
Create bucket>dac>save>click on folder>upload>add files>upload
Click on welcome.html .In this bucket all is private so no one can able to access it unless and until you don’t give the access to it.

> + When you make the remote login at that time linux made command for it known as SSH( Secure Server Shell).
> + **Mobaxterm** is tool so that there is no need to write ssh cmd at the backend.
SSH- username@ipaddress
Password:
> + Before some time username and password was assumed as a better
But ,because of inceasing computing power,and awareness , brute force attack (if my password is the combination of char and int
Then char are a-z,A-Z & 0-9)
Then computer will generate factorial combinations for 62 elements.
And hackers can try to hack by using this combination!
In a bank website,3 times it gives option if it is invalid it will block that website.
So To prevent this they invented public and private key.

*Private key*->.pem  file is a private file. It is in the encrypted format
We can not decypt it

*Public key*->aws stores it into the ec2
Ssh –i .private file path username@ipaddress
In our system 
Run the linux instane open  mobaxterm
In that ec-2 user is username @ ip address

So pem file content will match and it will allow to make a login
If u want to go to root user cmd is
Sudo su sudo means root
Write >sudo su ->It will go ino the root directory
You will see # there
Now Im in a root user and I want to go into the ec-2 user
Type cmd>exit
So tht again you will redirect to the ec2-user.
> + In linux u have cmds  
1)ls>List Directory\
2)pwd->Print Working Directory
 
Next service of cloud is:
Software as a service
Database as a service->We will create mysql servr and connect it to 
the system.When you want to use you can use it and if u don’t want to use u ccan close it

# RDS
Relational Database Service
It not just give mysql but it also gives sqlserver,oracle,arora,etc.
So because of the AWS provided all these as a service.  
1]There is no need have expertise knowledge
2]No need to pay the money for license.
