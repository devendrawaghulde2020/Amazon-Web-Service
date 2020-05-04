
# VPC
Virtual private cloud
Internet is not owned by us.
There is common platform through whch we are connected

#### ISP(Internet service provider)\
Ex.Reiance,airtel,etc.
> + So they plugin the wire and through router they plugin wire leased line 
Then we can connect it through the LAN to computer 
Then they hide something like they have to ctrl some things like speed
VPC-virtual private cloud which is on organization level
They ctrl the configuration like accessibility pf port 
In bank application we cant get the access
 
Ipv4 CIDR>these are the range of ip addresses public and private IP
subnets somes under VPC.
They have made different availability zones subnets

#### Route table(Router)
> + When we apply router route table can help to communicate with the internet\
> + It helps to connect with the world.
It has internet gateways
internet gateways
It normally provides the internet connection so that we can communicate with the internet.\
So like this  vpc is get configured
> + If I have aws account in which we have 1 vpc-default
In that we have subnets like public &  private.

# Cloud watch and cloud trail

> + Go to cloud watch services>In that>logs on lhs. It will show thw wlog grpps>It will shoe all thelogs
> + It gives the features like search,query
> + In inside option>you can query
> + U can create the dashboards
Status checks>they can check all the things like
Instance proper working or not and tehe network
If there is failure due to which instance is affecting then they will inform it.
> + For that w can create the alarm
If there is notification it will give the alarm

*Cloud watch	Cloud trail
Monitor resources(ec2)
And applications
Like the web appications*

Cat test.txt->to see content under the file.\
It can execute as a root user
In user data u cn pass any o thee commands or pass shellscript depends on the os you Use.

Ls
Cd instances/
Ls
It will give the instance id
Cd id
Ls

# Lambda(function)
 
> + Console.log for print
Exports style to make function
In cpp code start from main
Void sum()
{}
Int main()
{
	Sum();
}
 
Index(filename).handler is a function which we wat to create as a entry point
 
> + Aws works on event
Imstance creation is event
To create file in s3 is an event
Lambda uses are:\
1]event drven automation\
2]lambda as API->request and response

Services>s3>we an configure event>If anyone try to upload file in y bucket>create lambda function which will take that file data and will print it.