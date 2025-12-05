\# AWS VPC \& EC2 Deployment Lab



\## Objective

To design a custom VPC, configure subnets and route tables, and successfully launch an EC2 instance.



---



\## Services Used

\- Amazon VPC

\- Subnets

\- Route Tables

\- Internet Gateway

\- EC2

\- Security Groups



---



\## VPC Configuration

\- VPC CIDR: 10.0.0.0/16

\- Region: eu-north-1



---



\## Subnet Configuration

\- Public Subnet CIDR: 10.0.1.0/24

\- Availability Zone: eun1-az1 (eu-north-1a)



---



\## Internet Gateway

\- Created and attached to the VPC



---



\## Route Table

\- Route: 0.0.0.0/0 → Internet Gateway

\- Associated with Public Subnet



---



\## EC2 Instance

\- AMI: Amazon Linux 2

\- Instance Type: t3.micro

\- Key Pair: Created

\- Security Group:

&nbsp; - SSH (22) – My IP

&nbsp; - HTTP (80) – Anywhere



---



\## Result

\- EC2 instance successfully launched

\- Public IP assigned

\- Instance reachable via SSH

\- Web server accessible via browser



---



\## Lessons Learned

\- How VPC components work together

\- Importance of route table association

\- Security group best practices



