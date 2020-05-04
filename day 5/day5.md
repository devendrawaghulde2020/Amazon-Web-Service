# CLI or SDK Use:
> + We use CLI or SDK to communicate between ec2 and s3.
> + We have to install CLI(Command Line Interface) on our system using CMD.\

*Steps:*
> + Run aws s3 ls command.
> + It will say to configure aws, 
so run *aws configure* command.
> + go to AWS Educate
> + open account details
> + click on show
> + copy the id in a temporary file.
> + paste access id,secret access key one by one on CMD.
> + after it copy the whole credentials data and paste it in C/users/devendra/.aws/credentials in credendtial delete what it existed before and paste you copied from aws website.
> + After successful configuration you can operate on S3 files which are on aws server from your computer.
> + You can use *aws s3 ls* command to list out buckets on your S3.

# Lambda:

> + Lambda is an AWS service in which multiple users can access a same function at a same time.
 > + This achieves parallelization and hence no restrictions for limited access.
 > + There are multiple languages available to create a function such as nodeJS,Java,Python,etc.
 > + In case of Java we have to upload a .rar or zip file of Java function code.


