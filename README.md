
# Set Up a Web App in the Cloud

**Author:** ADAN PLAYIL  
**Email:** adanplayil7@gmail.com

---

## Set Up a Web App Using AWS and VS Code

![Image](http://nextwork.ai/appreciative_maroon_zany_mulberry/uploads/aws-devops-vscode_7a1de541)

---

## Introducing Today's Project!

In this project, I will demonstrate building a web app using AWS and VSCode. I'm doing this project to learn how a CI/CD pipeline is set up for a real-time application.

This project is part one of a series of DevOps projects where I'm building a CI/CD pipeline! I'll be working on the next project in tomorrow

I did this project because to gain knowledge about how to build a CI/CD pipeline using AWS tools and VScode

### Key tools and concepts

Services I used were how to create an environment to house the development . Key concepts I learnt include launching an EC2 instrance, How to connect the terminal and VSCode IDE to EC2 server, how Apache maven is used to build web app.

### Project reflection

This project took me approximately 2 hours.The most challenging part was Connecting the VSCode to EC2 server.It was most rewarding to connect it.

One thing I didn't expect in this project was how did we get the nextwork-web-project in the VSCode.

---

## Launching an EC2 instance

### What I did in this step

In this step, I will launch an EC2 instance, set a secure key pair, and set up network settings for the instance because this will help us connect to the instance using a SSH.

I started this project by launching an EC2 instance because we will be using it to house our development work.

![Image](http://nextwork.ai/appreciative_maroon_zany_mulberry/uploads/aws-devops-vscode_7852fbf3)

### I also enabled SSH

SSH is a secure shell used to connect to your EC2 instance. I enabled SSH so that i could access my remote server using my private key that matches the public key of the server. All data transferred is encrypted, making it an ideal connection.

### Key pairs

A key pair is like a login with your username and password with an Acess Key ID and a Secret Key. these are credentials we need to connect to our EC2 instance.

### Downloaded key pair file

Once I set up my key pair, AWS automatically downloaded a .pem file with the credentials required to access our EC2 instance.

---

## Set up VS Code

### What I did in this step

In this step, I will download VSCode and update the key pair setting in order to log onto the EC2 instance, because this will help us establish secure communication between VSCode and the virtual server.

### What is VS Code?

VS Code is software that helps you manage, create or edite code. it is an Integrated development Environment

I installed VS Code to connect to the EC2 instance.

![Image](http://nextwork.ai/appreciative_maroon_zany_mulberry/uploads/aws-devops-vscode_53d05e68)

---

## My first terminal commands

A terminal is a secure shell in which you could write instructions for your computer to follow instead of clicking. The first command I ran for this project is getting inside the folder with the .pem file.

### Updating file permissions

I also updated my private key's permissions by reseting the default permission, making sure that the i (i.e the user) has read permission for the secret key, changes in other files or the folder don't affect the permissions in this file.

![Image](http://nextwork.ai/appreciative_maroon_zany_mulberry/uploads/aws-devops-vscode_9328ada1)

---

## SSH connection to EC2 instance

### What I did in this step

In this step, I will connect to EC2 instance because then i would have established a secure connect to the EC2 instance.

### Connecting to EC2

To connect to my EC2 instance, I ran the command, which starts a secure connection to the instance with the .pem file containing the access key and the DNS IP for the instance to connect to.

### This command required an IPv4 address

A server's IPV4 DNS is a public domain name system that the server uses to find and connect to it.

![Image](http://nextwork.ai/appreciative_maroon_zany_mulberry/uploads/aws-devops-vscode_e3069dca)

---

## Maven & Java

### What I did in this step

In this step, I will install apache maven on my EC2 instance and Amazon Corretto 8 because this will help us build the web app.

### Why I'm using Maven

Apache Maven is a tool we can use to build web apps.

Maven is required in this project because it helps us set up all the web files necessary to create the structure of the web app, so we can jump into development

### Why I'm using Java

Java is a programming language used to make applications for all scale projects

Java is required in this project because we are using Maven, a Java version, to build our web app.

---

## Create the Application

### What I did in this step

In this step, I will run maven commands in the terminal to generate Java web app.

### Creating the Java web app

I generated a Java web app using the command of creating a structure for our web app, naming it, specifying that we a creating a web app, and asking it to not puase for human interaction.

### Installing Remote - SSH

I installed Remote - SSH, which is a secure way to connect to the EC2 instance. I installed it to work on the files on the EC2 server this way i could update the web files store in the EC2 instance. 

### SSH configuration details

Configuration details required to set up a remote connection include host ,Hostname, identity file and user.

![Image](http://nextwork.ai/appreciative_maroon_zany_mulberry/uploads/aws-devops-vscode_2939cf01)

---

## Create the Application

### Exploring the project structure

Using VS Code's file explorer, I could see the file with a prebuilt structure for the web app i am building

Two of the project folders created by Maven are src and webapp, which are the source code and the application files for the web app we are trying to develop.

![Image](http://nextwork.ai/appreciative_maroon_zany_mulberry/uploads/aws-devops-vscode_45f91fd7)

---

## Using Remote - SSH

### What I did in this step

In this step, I will install an extension in VS Code because this will get me access to the IDe feature of VSCode.

### Updating the web app

The index.jsp is afile used for JAVA web apps

I edited index.jsp by adding my name to it

![Image](http://nextwork.ai/appreciative_maroon_zany_mulberry/uploads/aws-devops-vscode_7a1de541)

---

## Using nano

### Additional improvements

### Terminal vs IDE

### Verifying my work

---

---
