# Altschool-christmas-holiday-project

This is a documentation for the christmas holiday project I was given at AltSchool.

Instructions:
You are required to perform the following tasks

1. Set up 2 EC2 instances on AWS (use the free tier instances).
<br>
2. Deploy an Nginx web server on these instances (you are free to use Ansible). 
<br>
3. Set up an ALB (Application Load balancer) to route requests to your EC2 instances. 
<br>
4. Make sure that each server displays its own Hostname or IP address. You can use any programming language of your choice to display this.
<br>
5. Work on building a personal portfolio and CV (Check out resumeworded.com).

Important points to note:

1. I should not be able to access your web servers through their respective IP addresses. Access must be only via the load balancer.
<br>
2. You should define a logical network on the cloud for your servers.
<br>
3. Your EC2 instances must be launched in a private network.
<br>
4. Your Instances should not be assigned public IP addresses.
<br>
5. You may or may not set up auto scaling(I advice you do for knowledge sake).
<br>
6. You must submit a custom domain name (from a domain provider e.g. Route53) or the ALB’s domain name.
<br>
