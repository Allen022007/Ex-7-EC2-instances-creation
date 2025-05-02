# Ex.4 Deployment and Configuration of a Virtual Private Cloud (VPC) in AWS

~~~
Name : W Allen Johnston Ozario
Reg.No : 21222411004
~~~

## Aim:
To set up of a Private Cloud  in AWS.

## Setting up of a private cloud in AWS:

Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.

## Procedure:

1. Plan Your VPC:
   ● Determine your needs:
   Define your use case, including application requirements, security needs, and
   compliance standards.
   ● Plan IP address ranges:
   Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
   ● Select Availability Zones:
   Decide which Availability Zones (AZs) you'll use for your resources, considering
   redundancy and performance.
   ● Plan internet connectivity:
   Determine if you need public internet access and how to configure it.
   ● Define security:
   Plan your security groups, network ACLs, and access controls to ensure a secure
   environment.
2. Create Your VPC:
   •	Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
   •	 Choose "Create VPC": Initiate the VPC creation process.
   •	Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
   •	other necessary settings.
   •	Create subnets: Define subnets within your VPC to isolate different parts of your
   •	network.
   •	Create route tables: Specify how traffic is routed within and outside the VPC.
   •	 Create security groups: Define access control rules for your resources.
3. Deploying Resources:
   •	Launch EC2 instances: Create and launch virtual machines within your VPC.
   •	 Set up RDS instances: Deploy databases for your applications.
   •	Configure networking: Connect your resources to the appropriate subnets, security
   groups, and route tables.
   •	Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.
4.Managing and Monitoring:
   •	Use AWS CloudWatch: Monitor your VPC and resources for performance and
   health.
   •	Configure logging and auditing: Track access and activity within your VPC for
   security and compliance.
   •	Implement security best practices: Regularly review and update your security
   configuration.
   •	Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
   demands.

## Snap Shot:

## Snapshot 1: Create VPC

 ![image](https://github.com/user-attachments/assets/de934f3e-eb4b-477b-bb8c-6222bf715a89)

## Snapshot 2: Configuring Subnets

![image](https://github.com/user-attachments/assets/ae44d425-edd9-4c0c-90e3-f4b5d0c95cc6)

## Snapshot 3: Configure Subnets

 ![image](https://github.com/user-attachments/assets/df94e9b3-55b1-42d7-afcc-5cc27ab4edf8)


## Snapshot 4: Setting Internet gateway

![image](https://github.com/user-attachments/assets/e418c476-619c-47cb-983b-8c6cc06313df)

## Snapshot 5: Setting Internet gateway

![image](https://github.com/user-attachments/assets/af604bb3-40a2-4d8f-9bc3-a95059366a27)

## Snapshot 6: Setting Internet gateway

![image](https://github.com/user-attachments/assets/474ba1c9-5783-4f5f-8730-973567ea4cb9)

 
## Snapshot 7: Creating route table

![image](https://github.com/user-attachments/assets/fb0f941b-882a-4046-bf5b-e26bc3ddf6ed)

## Snapshot 8: Configuring route table

![image](https://github.com/user-attachments/assets/1410818a-cb66-420f-afcd-3d6399f3703d)

 
## Snapshot 9: Editing routes

![image](https://github.com/user-attachments/assets/689bd862-c6e6-4367-9f61-868741db29aa)

 
## Snapshot 10: Creating route table

![image](https://github.com/user-attachments/assets/e83e61a1-8c05-4744-a268-be7f8015f1b6)

## Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.

