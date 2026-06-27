# Day 3 - Create Subnet

## Objective

Create a subnet inside the default VPC.

## What is a Subnet?

A subnet is a smaller network inside a VPC. It divides the VPC into multiple logical sections for better organization and security.

## Why Do We Use Subnets?

- Organize cloud resources.
- Improve network security.
- Separate public and private resources.
- Efficient IP address management.

## Types of Subnets

### Public Subnet
- Has internet access.
- Used for web servers.

### Private Subnet
- No direct internet access.
- Used for databases and backend servers.

## Task Performed

- Created subnet under the Default VPC.
- Subnet Name: `datacenter-subnet`
- Region: `us-east-1`

## Challenges Faced

- Initial subnet CIDR overlapped with an existing subnet.
- Learned that each subnet must have a unique CIDR block.
- Also learned that resource names must exactly match the task requirements.

## Learning Outcome

- Understood the relationship between VPC and Subnets.
- Learned how CIDR blocks work.
- Learned to create subnets without overlapping IP ranges.

## Status

✅ Completed (Concept Learned)
