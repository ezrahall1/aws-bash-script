<h1>Creating bash script in AWS</h1>

<h2>Description</h2>
In this project I will demonstrate how I created a simple bash script and execute it. Bash script is an important part of process automation in Linux. It saves you time because you don't have to write certain commands again and again. You can perform daily tasks efficiently and even schedule them for automatic execution.
<br />


<h2>Services Used</h2>

- <b>EC2</b> 

<h2>Environments Used </h2>

- <b>AWS</b>
- <b>Putty</b>

<h2>YouTube Demonstration </h2>

[Creating bash script in AWS - video walk-through guide](https://youtu.be/GOg6z4CBDLI)


<h2>Program walk-through:</h2> 
<H3>Step 1 - Creating EC2 instance</H3>

Once I haved logged into my AWS account, I clicked on services and navigate to EC2. From there I entered the name of the EC2 instanc and select Amazon Linux.
In the network settings section I left "allow SSH traffic from" ticked as well as leaving the rest of the seeting as defualt ad clicking launch instance.


Once you have log into the AWS account you would need to click on services and navigate to EC2. Enter the name of the EC2 select Amazon Linux, make sure the Amazon Machine Image (AMI) says free tier eligible.
For the instance type make sure you select free tier eligible or you would be charged. Create a new key pair if you do not already have one. In the network settings section leave "allow SSH traffic from" ticked. Leave the rest as default and click launch instance.

<img src="https://i.imgur.com/fdVAGzB.png" height="80%" width="80%" alt="Image 1"/>


<H3>Step 2 – Connecting to EC2 instance </H3>
Once the EC2 instance is in a running state you would need to connect to it. Right click and select connect.

<img src="https://i.imgur.com/kaoMGqH.png" height="80%" width="80%" alt="Image 2"/>

<img src="https://i.imgur.com/WQEebAw.png" height="80%" width="80%" alt="Image 3"/>



There are many applications you can use to connect to your EC2 instance. For this project I will be using [Putty](https://www.putty.org).
Once you have successfully connected to your EC2 instance using Putty you should see something like this:
<img src="https://i.imgur.com/wsd36ox.png" height="80%" width="80%" alt="Image 4"/>

<H3>Step 3 – Creating bash script and variables</H3>
The next step is you need to create the bash script name for example testscript.sh and create the variables in a text editor using this command nano testscript.sh .

<img src="https://i.imgur.com/nb0aNT5.png" height="80%" width="80%" alt="Image 5"/>

Once you have enter your script you would need to save it and make the bash script is executable by running command chmod +x testscript.sh.
Now you are able to run the bash script using the command ./testscript.sh

<img src="https://i.imgur.com/WtDE4tp.png" height="80%" width="80%" alt="Image 6"/>

</p>

