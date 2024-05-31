# host-a-static-website-on-aws
This is the first cloud project to host a static website on aws 

Services: CLI, EC2, Application Load Balancer, Auto Scaling Group, route53, GitHub etc.

Key Takeaways

1. VPC with Private and Prublic Subnets in 2 Avalability Zones.
2. Internet Gateway to allow communication between Instances in VPC and Internet.
3. NAT Gateway allows instances in Private Subnet to access internet.
4. Application Load Balancer is used to distribute web traffic across Auto Scaling Group of EC2 Instances in multiple availability zones.
5. Auto Scaling Group creates EC2 Instances to make website scalable, highly avilable, and falut tolerant.
6. Route 53 for registering domain name and create record set.
7. Store webfiles in GitHub repository.
