#   GCP VM Auto-Scaling and Security Setup  

## Overview
This project involves creating and configuring multiple Windows 10 Virtual Machines (VMs) using VirtualBox, establishing a network connection between them, and deploying a microservice-based application. 
The setup consists of a RESTful API built with Node.js and a MongoDB database running on separate VMs, simulating a distributed system.


##   System Requirements  
- Google Cloud Platform (GCP) account with   Billing enabled  .
- Basic understanding of   GCP Console   and   Cloud Networking  .
- Google Cloud SDK (optional for CLI commands).

##   Setup Steps  
1.   Login to GCP  : Access [Google Cloud Console](https://console.cloud.google.com/) and enable billing.
2.   Create a GCP Project  : Navigate to   Project Dropdown > New Project  , set the name, and enable billing.
3.   Create a VM  : Under   Compute Engine > VM Instances  , configure and deploy a virtual machine.
4.   Configure Auto-Scaling  : Create an   Instance Template   and a   Managed Instance Group   with a CPU utilization threshold.
5.   Set Up Security  : Configure   IAM roles   for restricted access and define   Firewall rules   to control traffic.
6.   Monitor & Autoscaling Test  : Run a program with infinite loop which will increase CPU utilization to more than 40% and check auto-scaling behavior  .

##   Testing  
- Check auto-scaling by monitoring   instance groups  .
- Validate   IAM role-based restrictions  .
- Test   firewall rules   by attempting unauthorized access.

##   Conclusion  
This project sets up a   scalable and secure   cloud infrastructure on GCP. 
With   auto-scaling, IAM policies, and firewall security  , organizations can achieve   cost-efficient and secure operations   while ensuring high availability.

