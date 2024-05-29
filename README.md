# Deploy-in-Public

Deploy two Nginx servers: one in a public subnet accessible via the internet, responsible for routing traffic to the second server, which will showcase a personalized HTML page.

**What is Nginx?**

Nginx is a popular open source web server, reverse proxy server and load balancer.
https://www.geeksforgeeks.org/what-is-nginx-web-server-and-how-to-install-it/

**What is VPC?**

A VPC, or Virtual Private Cloud, is a private network space in the cloud. It's like having your own personal data center, but instead of being a physical place, it exists within a cloud provider's infrastructure, such as Amazon Web Services (AWS).

**What is Subnets?**

Subnets are subdivisions of a Virtual Private Cloud. Subnets can be classified as public or Private depends on their accessiblity to the internet.

**What is private Subnets?**

A private subnet is a subnet within your VPC that does not have a route to the Internet Gateway and thus cannot directly communicate with the internet. These subnets are typically used for internal resources that should not be directly accessible from the outside world.

**What is public Subnets?**

A public subnet is a subnet within your VPC that is configured to allow direct access to the internet. This is typically achieved by attaching an Internet Gateway (IGW) to the VPC and configuring the subnet's route table to direct traffic to the IGW.

