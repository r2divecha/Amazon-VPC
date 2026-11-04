[README-5.md](https://github.com/user-attachments/files/34390264/README-5.md)[## Introducing Today's Project!

In this project, I will demonstrate how to create my very own Virtual Private Cloud (VPC). I'm doing this project to learn how to set up and manage a VPC from scratch becuase it is a vital skill for anyone looking to master cloud infrastructure.

## Virtual Private Clouds (VPCs)

### What I did in this step

In this step, I will access the VPC console in Amazon to create my very own VPC.

### How VPCs work

VPCs are private, isolated networks within AWS that keep your resources secure and let you control how they communicate.

### Why there is a default VPC in AWS accounts

There was already a default VPC in my account ever since my AWS account was created. This is so I can launch resources like EC2 instances.

![Virtual Private Clouds (VPCs)](https://nextwork.ai/appreciative_beige_glamorous_iara/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_2facf927)

### Defining IPv4 CIDR blocks

To set up my VPC, I had to define an IPv4 CIDR block, which is a way to to assign a whole block of IP addresses.

## Subnets

### What I did in this step

In this step, I will create subnets within in our 'Nextwork VPC'.

### Creating and configuring subnets

Subnets are used to group resources with similar access rules and restrictions. Some subnets might be public areas that all resources can access (public subnets) while others are private areas with limited access (private subnets). There are already subnets existing in my account, one for every Availabillity Zone.

### Public vs private subnets

The difference between public and private subnets are that public subnets are connected to the internet while private subnets aren't. For a subnet to be considered public, it has to connect to an internet gateway.

![Subnets](https://nextwork.ai/appreciative_beige_glamorous_iara/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_157c4219)

### Auto-assigning public IPv4 addresses

Once I created my subnet, I enabled auto-assign public IPv4 addresses. This setting makes sure that all EC2 instances launched within the subnet will instantly get a public IP address so that you won't have to create one manually.

## Internet gateways

### What I did in this step

In this step, I will create an internet gateway to link our VPC to the internet.

### Setting up internet gateways

Internet gateways are a way to make applications avaiable on the internet.

Attaching an internet gateway to a VPC means resources in your VPC can now access the internet. If I missed this step the applications and/or EC2 instances I launch wouldn't be connected to the internet.

![Internet gateways](https://nextwork.ai/appreciative_beige_glamorous_iara/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_4ae90410)

## Using the AWS CLI

### What I'm doing in this extension

In this project extension, I will the AWS CLI to launch our VPC's resources to compare whether its faster and more effeicent than the process we did earlier.

### Exploring CloudShell and CLI

VPC resources could also be created with CloudShell, which means it's a space for you to run code.  CLI is a software that lets you create, delete and update resources with commands instead of clicking through your console.

### Debugging my setup

To set up a VPC or a subnet, you can use the command 'create-subnet'. Make sure to avoid errors by including a CIDR block.

![Using the AWS CLI](https://nextwork.ai/appreciative_beige_glamorous_iara/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_9b2465411)

### Comparing CloudShell vs AWS Console

Compared to using the AWS Console, an advantage of using commands is efficiency, it takes minutes using a command line. An advantage of using the Console is being able to see all the options you can inlcude in your VPC. Overall, I preferred the Console learning how to create my own VPC, subnet, and internet gateway, but acknowledge that commands will come inhandy once I get used to creating them in the future.
Uploading README-5.md…]()
