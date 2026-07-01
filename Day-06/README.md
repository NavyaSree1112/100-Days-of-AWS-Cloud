# Day 06 - Launch Amazon EC2 Instance

Today I learned how to launch an **Amazon EC2 (Elastic Compute Cloud)** instance on AWS.

Amazon EC2 is a cloud computing service that allows users to create virtual servers on demand. Instead of buying physical hardware, we can launch virtual machines within minutes and use them to host applications, websites, databases, and services.

In DevOps, EC2 instances are the backbone of cloud infrastructure. They are used to deploy applications, run web servers, host CI/CD tools like Jenkins, execute automation scripts, and manage scalable environments.

## Steps Performed

- Logged into the AWS Management Console.
- Opened the **Amazon EC2** service.
- Clicked **Launch Instance**.
- Entered the required instance name.
- Selected the Amazon Machine Image (AMI).
- Chose the required instance type.
- Selected the existing Key Pair.
- Configured the default Security Group.
- Reviewed the configuration.
- Clicked **Launch Instance**.
- Verified that the EC2 instance was created successfully and reached the **Running** state.

## What I Learned

- Amazon EC2 provides scalable virtual servers in the cloud.
- An **AMI (Amazon Machine Image)** contains the operating system and required software.
- The **Instance Type** determines CPU, memory, and performance.
- A **Key Pair** is required to securely connect to the instance using SSH.
- A **Security Group** acts as a virtual firewall controlling inbound and outbound traffic.
- The **Running** state indicates that the EC2 instance is ready for use.

## Commands Used

No Linux commands were required. The task was completed using the **AWS Management Console**.

## Lab Status

✅ Successfully launched an **Amazon EC2 instance** and verified that the instance entered the **Running** state.
