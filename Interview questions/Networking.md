# Networking Interview Questions

Questions: 152

## Source: [Akamai/SRE.md](../Akamai/SRE.md)

- How to check the firewall protection
## Source: [Alphadyne/DevOps_Engineer_1.md](../Alphadyne/DevOps_Engineer_1.md)

- Application is hosted on a public EC2 instance.How to migrate it to a private subnet following AWS best practices (security, networking, HA).
- Discussion around ALB/NLB, ACM certificates, routing, and security groups.
- How to provide HTTPS access to an application hosted in a private subnet.
## Source: [Alphadyne/DevOps_Engineer_2.md](../Alphadyne/DevOps_Engineer_2.md)

- Configure Network Interfaces (NICs) and attach them to the correct subnets
- Define an Azure Virtual Network (VNet) with a given IP range
## Source: [Altimetrik/SRE.md](../Altimetrik/SRE.md)

- Like you have to deploy, you have to basically create VPC and map you have to create a subnet and you have to attach let's be the public or a private submit. It's of your choice to attach it to your VPC.
- Question : I'll give you an example like let's talk about AWS. You have you're going to create a VPC and subnet And your provider is AWS and I'm asking you to write in using terraform.
## Source: [Amazon/DevOps_Consultant_1.md](../Amazon/DevOps_Consultant_1.md)

- Is it possible to create NAT gateway in private subnet ?
- Write a Terraform code to create VPC, subnet, EC2, S3 bucket.
## Source: [Amazon/DevOps_Consultant_2.md](../Amazon/DevOps_Consultant_2.md)

- You need to connect your DB running in private subnet, not using NAT gateway or NAT instance or bastion host, what are the other options,
## Source: [Arrise_Solutions/DevOps_Engineer.md](../Arrise_Solutions/DevOps_Engineer.md)

- Diff b/w Public and Private subnet
- Does NAT gateway will run in public or private subnet
- How does kube-proxy communicates with nodes
- How does SSL certs works
- How to connect your private subnet with Internet
- Types of networking in Docker and explain in detail
- Which network will be used to isolate a communication b/w two containers
## Source: [Aspire/DevOps_Engineer.md](../Aspire/DevOps_Engineer.md)

- What is mean by Nat Gateway and Nat instance?
## Source: [Capgemini/DevOps_Engineer_3.md](../Capgemini/DevOps_Engineer_3.md)

- Once you create that subnet, the instance will get created, but will it be able to communicate with the old instances?
- That we can extend the subnet CIDR once it is created?
- What is the difference between NAT Gateway and IGW?
- You want to create an EC2, and while creating the instance, you are getting an error like IP address exceeded. How will you troubleshoot and fix it?
## Source: [CMT/SRE.md](../CMT/SRE.md)

- what is dns
- what is tcp and udp
## Source: [Commonwealth_Bank/SRE_principal.md](../Commonwealth_Bank/SRE_principal.md)

- What is DNS? When you type google.com. What exactly happening in the background?
## Source: [CTS/DevOps_Engineer_1.md](../CTS/DevOps_Engineer_1.md)

- Check if any firewall/security group rules are blocking the flow of traffic
- Check SSL certificate if it has gone corrupt and is working fine
- Do nslookup for dns resolution if that works fine
- Ping/telnet won't make sense since networking side is fine
- What is Az App Gateway and how it encrypt http/https traffic
- You have deployed a web app and it was working fine but application went down, and all networking are fine and related ports are open, how to troubleshoot
## Source: [CTS/DevOps_Engineer_2.md](../CTS/DevOps_Engineer_2.md)

- Difference between nat gateway and internet gateway
- Difference between subnet and nacl
- How will you know if a network policy is enabled or not in k8s
- How would you set up networking in vpc
- How you will direct traffic to and from a instance in private subnet
## Source: [Deloitte/DevOps_Engineer_1.md](../Deloitte/DevOps_Engineer_1.md)

- For all VPCs, will you configure the Transit Gateway attachment with CIDR range?
- If we connect VPCs to the Transit Gateway, what will you update in the VPC Route Table?
- What is WAF (Web Application Firewall) and AAF (Application Access Firewall)?
## Source: [Elixr_Labs/DevOps_Engineer.md](../Elixr_Labs/DevOps_Engineer.md)

- IN general as azure specalist from ur side what is ur recomendation is it a sit-to-site vpn or Expressroute
- IN which senario we will go for site-to-site vpn and Expressroute
- lets assume consider banking sector only i dont have that much budget but since ur telling that for low budget go for site-to-site-vpn but on otherside ur saying that express-route is more secure > So how cn u justy that, because banking costumer has a limitation for him
## Source: [Emphasis/DevOps_Engineer_1.md](../Emphasis/DevOps_Engineer_1.md)

- How private subnet connect with outside world
- What is the purpose of NAT gateway
## Source: [Emphasis/DevOps_Engineer_2.md](../Emphasis/DevOps_Engineer_2.md)

- If the RDS is in a private subnet, how do you access it securely without using public tools like MySQL
## Source: [Encora/DevOps_Engineer.md](../Encora/DevOps_Engineer.md)

- am having an range of ip address 10.0.0.0/16 , I want to have 10.0.0.0/21 subnets , how will I achieve it terraform , how do use locals word and achieve it
## Source: [EPAM/DevOps_Engineer_1.md](../EPAM/DevOps_Engineer_1.md)

- VPC, NAT gateway,s3, route53, vpc peering,transit gateway, autoscaling group
## Source: [EPAM/DevOps_Engineer_2.md](../EPAM/DevOps_Engineer_2.md)

- EC2 in a private subnet should receive inbound traffic, how to enable it ? → NOT NAT Gateway
## Source: [EPAM/DevOps_Engineer_3.md](../EPAM/DevOps_Engineer_3.md)

- How do you implement and manage network policies in Kubernetes for strict inter-service communication?
## Source: [EXL_Service/DevOps_Engineer.md](../EXL_Service/DevOps_Engineer.md)

- Two VPCs need to communicate, but their CIDR ranges overlap. Transit Gateway is not allowed. What alternative solution would you recommend?
## Source: [F5/Associate_Consultant.md](../F5/Associate_Consultant.md)

- HTTP request header and HTTP Methods,
- If thre is an instance we have security group and web application firewall enabled, DDOS attack enabled will it protect from Bot attack.
- What is DNS Resolution. Suppose I have new system with no cache what happens in the background.Step by step process.
- What is SSL/TLS Handshake.,
- What is Web Application Firewall,
## Source: [Five9/DevOps_Engineer.md](../Five9/DevOps_Engineer.md)

- AAA and CNAME in DNS
- Fail over mechanism in DNS (if one IP is not reachable)
- TLS handshakes
## Source: [Flentas/DevOps_Engineer.md](../Flentas/DevOps_Engineer.md)

- Why have you used RDS Proxy?
## Source: [HCL/DevOps_Engineer_3.md](../HCL/DevOps_Engineer_3.md)

- How does NAT gateway protect my private subnet, what concept does it use to secure the resource (same masking) = masking is protecting the private subnet ✅ (vpc)
- I have EC2 and S3 in same subnet, region how to access that bucket from instance ✅ (aws)
- Public and private subnet is there, NAT gateway is attached to private subnet what is use of that (masking of private ip) ✅ (vpc)
## Source: [IBM/DevOps_Engineer_1.md](../IBM/DevOps_Engineer_1.md)

- Reverse proxy
## Source: [Infosys/SRE.md](../Infosys/SRE.md)

- Suppose you have a VPC , and in your VPC, you have 2 subnets. One is a private subnet, and another one is a public subnet. And in these subnets you have 2 - 3 instances. And for security purposes we need to keep those instances updated right on a regular basis. The instances in the public subnet are okay. They have internet connectivity. They can get updated. How will you update the instances which are in the private subnet?
## Source: [ITC_Infotech/DevOps_Engineer.md](../ITC_Infotech/DevOps_Engineer.md)

- What is difference between coreDNS and kube-proxy.
## Source: [JPMorgan/DevOps_Engineer_senior.md](../JPMorgan/DevOps_Engineer_senior.md)

- During an Azure deployment, you receive intermittent DNS resolution issues. What can be the causes?
- Explain how you’d use Azure Application Gateway with Web Application Firewall for a sensitive banking application.
## Source: [JPMorgan/DevOps_SRE.md](../JPMorgan/DevOps_SRE.md)

- Your application is currently running on EC2 instances in a public subnet. How would you migrate it to a private subnet without any downtime? Explain the complete approach. if it doent work how would u rollback?
## Source: [Koerber_Pharma/DevOps_Engineer.md](../Koerber_Pharma/DevOps_Engineer.md)

- Difference between NAT gateway and NAT instance.
- How to achieve low latency routing? Which routing you will use?
## Source: [LTIMindtree/DevOps_Engineer_3.md](../LTIMindtree/DevOps_Engineer_3.md)

- what is the difference between firewall and nsg
## Source: [Morgan_Stanley/Release_Engineer.md](../Morgan_Stanley/Release_Engineer.md)

- Reverse proxy and forward proxy
## Source: [Netcracker/DevOps_Engineer.md](../Netcracker/DevOps_Engineer.md)

- How to restrict the communication between them ? → network policy
- How will you restart http service from VM
- What component should be added in network policy YAML file
## Source: [Nitor_Infotech/DevOps_Engineer.md](../Nitor_Infotech/DevOps_Engineer.md)

- Networking in kubernetes, how have you implemented
## Source: [NPCI/DevOps_Engineer.md](../NPCI/DevOps_Engineer.md)

- what is Container Network Interface
## Source: [One2N/DevOps_Engineer.md](../One2N/DevOps_Engineer.md)

- How would reverse proxy setup work here?
- How would you manage SSL and TLS
- How would you setup DNS here?
## Source: [Oracle/DevOps_Engineer_2.md](../Oracle/DevOps_Engineer_2.md)

- What is reverse proxy
## Source: [Orion_Innovation/DevOps_Engineer.md](../Orion_Innovation/DevOps_Engineer.md)

- application gateway TLS certificate is expired, what steps you will follow to renew it
- what is A record and what it will do in DNS
- what is CName record in DNS
- what is MXRecord in DNS
## Source: [Others/DevOps_Engineer_1.md](../Others/DevOps_Engineer_1.md)

- What are Network ACLs and Security Groups, and how do they differ?
## Source: [Others/DevOps_Engineer_12.md](../Others/DevOps_Engineer_12.md)

- how do you check the network details and traffic flows on a system and which command you will use ?
- What is DNS ?
## Source: [Others/DevOps_Engineer_13.md](../Others/DevOps_Engineer_13.md)

- How do SSL and TLS certificates work?
## Source: [Others/DevOps_Engineer_14.md](../Others/DevOps_Engineer_14.md)

- Tell me the flow of network packets starting from user hit the application url
## Source: [Others/DevOps_Engineer_15.md](../Others/DevOps_Engineer_15.md)

- How can I map SSL certificates to the ingress file ?
- What is NAT gateway?
## Source: [Others/DevOps_Engineer_16.md](../Others/DevOps_Engineer_16.md)

- How the authentication and networking is established between azure devops pipeline and azure keyvault
- Which App gateway setting is used to upload SSL certification and why
## Source: [Others/DevOps_Engineer_2.md](../Others/DevOps_Engineer_2.md)

- Can u pls write terraform file to provision the Ec2 instance in a public subnet in a VPC?
## Source: [Others/DevOps_Engineer_3.md](../Others/DevOps_Engineer_3.md)

- ) Explain TTL in DNS- how does it work, and when do we use it? Explain the Flow.
- ) How does SSL work (Certbot, Let's Encrypt, AWS)? Explain the Flow.
- ) How does weighted routing work in LB?
## Source: [Others/DevOps_Engineer_4.md](../Others/DevOps_Engineer_4.md)

- I have an Ingress object that is not routing the traffic to the Kubernetes cluster. What are the reasons and how do you troubleshoot that?
## Source: [Others/DevOps_Engineer_5.md](../Others/DevOps_Engineer_5.md)

- What will happen if the k8 master node and worker node firewall gets broken? Will the existing deployments work or impact on any new deploymentsHow will you communicate to people
## Source: [Others/DevOps_Engineer_6.md](../Others/DevOps_Engineer_6.md)

- What is the difference between NSG and Firewall.
- Why Kube-let and Kube-proxy is used for in Kubernetes.
## Source: [Others/DevOps_Engineer_7.md](../Others/DevOps_Engineer_7.md)

- What are NACLs,SecurityGroups,NAT Gateway
## Source: [Perfios/DevOps_Engineer.md](../Perfios/DevOps_Engineer.md)

- Explain amazon traffic architecture how it goes to private subnet? I write diagram and explained it
- What happens when an user hits "www.clarify.com" how the request pass through the network ?? write a diagram and explain it to me
## Source: [Persistent_Systems/DevOps_Engineer_1.md](../Persistent_Systems/DevOps_Engineer_1.md)

- Public and Private Subnet, what makes it public and private??
- Where does NATGateway reside.
## Source: [Persistent_Systems/DevOps_Engineer_3.md](../Persistent_Systems/DevOps_Engineer_3.md)

- If there is a vendor who provides VPN services for company A, his manager wants to view some dashboard but do not have AWS account. How would you help him?
- What is subnet?
## Source: [Plansource_ValueLabs/DevOps_Engineer.md](../Plansource_ValueLabs/DevOps_Engineer.md)

- difference between http and https
- what happens when youe hit DNS from browser
## Source: [Qentelli_Solutions/DevOps_Engineer.md](../Qentelli_Solutions/DevOps_Engineer.md)

- If developer sets private subnet to public, what should you do?
## Source: [RelevantZ/DevOps_Engineer.md](../RelevantZ/DevOps_Engineer.md)

- suppose a DB is there in private subnet, I want to communicate only with specific people , how do achieve it
## Source: [Sapient/DevOps_Engineer.md](../Sapient/DevOps_Engineer.md)

- Can you tell about your VPC structure and networking architecture used in your project?
- Have you created DNS record?
- If your cluster is in a private subnet, then outside kubectl will not be working, right? How are you accessing that?
- In which subnet are you placing your EKS cluster and which networking components have you used?
- Purpose of DNS in your project.
- Why are you keeping your web application in a public subnet?
## Source: [Sigmoid/DevOps_Engineer_2.md](../Sigmoid/DevOps_Engineer_2.md)

- DNS Custom resolver
## Source: [Sigmoid/DevOps_Engineer_4.md](../Sigmoid/DevOps_Engineer_4.md)

- Explain each component in your architecture which is involved from a user requesting from the UI to the request reaching the backend pod, and how they are connecting with each other to ensure inbound and outbound flow(including the firewall, NACl, security groups, route tables etc).
- How can you tell a subnet is pubic or private, what things needs to be in place.
- How is an end user able to access the app which is running inside pods of private subnet nodes.
- If you used a service with type: LoadBalancer and as you told its in private subnet , then how its able to launch a loadbalancer in public subnet, how its getting access to do it from within private subnet. Which component of the control plane takes care of it.
- What is the requirement of NAT gateway in your cluster, where should it placed to make it work as intended.
- Why do we need extra load balancing capabilities like host based, path based routing etc to our pods, if services are anyways handling the traffic to route to right pod, what actuslly is the issue where just tradional standalone service cannot handle it. For example, if an end user is traversing accross various product details , how is frontend able to fetch details from the right pod (backend which in turn gets the actual product data from db), explain how the api calls to backend and to db is handled.
## Source: [Sonata_Software/DevOps_Engineer_1.md](../Sonata_Software/DevOps_Engineer_1.md)

- what is the networking you are using in AKS
- where do you store the application gateway (TLS/SSL certificate) ?
## Source: [Sonata_Software/DevOps_Engineer_2.md](../Sonata_Software/DevOps_Engineer_2.md)

- Can you tell me the difference between NAT Gateway and Internet Gateway?
## Source: [Sony/DevOps_Engineer.md](../Sony/DevOps_Engineer.md)

- (Storage, networking, controllers, quorum, recovery)
- Design a multi-tenant Kubernetes platform where teams must not affect each other’s resource usage, network traffic, or upgrade cycles.
- Explain the complete request flow when using Gateway API with multiple GatewayClasses across regions. How do you prevent split-brain routing?
- How would you implement zero-trust networking inside Kubernetes without using a service mesh?
## Source: [SquareOps/DevOps_Engineer.md](../SquareOps/DevOps_Engineer.md)

- 🌐 VPC & Networking
- Does IP X fall in CIDR Y?
- How to calculate whether an IP is inside a CIDR block?
- Q10. If NACL denies a CIDR, but SG allows same IP, can the IP access LB?
- Q16. During peak traffic, ingress controller is routing requests slowly. How do you debug it?
- Which VPC/subnet configuration did you use?
## Source: [Techdome/DevOps_Engineer.md](../Techdome/DevOps_Engineer.md)

- Explain Docker networking and types of network. What is the default network.
## Source: [Virtusa/Tech_Lead.md](../Virtusa/Tech_Lead.md)

- suppose you are having an ecs task definition, I have an website , the developer is hitting the url or website, what will be the flow of traffic , fargate is a serverless – how do you achieve configuration DNS or website over there
## Source: [Wipro/DevOps_Engineer_3.md](../Wipro/DevOps_Engineer_3.md)

- If you have a Kubernetes cluster with pods running, but when you hit the URL you get HTTP errors (403, 404, 503), what would be your troubleshooting steps?
## Source: [Wipro/DevOps_Engineer_4.md](../Wipro/DevOps_Engineer_4.md)

- ⁠diff bet Nat gateway and igw
- ⁠what is route table
- ⁠where does route table is placed (private subnet of private subnet)
## Source: [Zensar/DevOps_Engineer.md](../Zensar/DevOps_Engineer.md)

- In terms of Cost optimisation which one should we use, Az App gateway or network gateway?
- What is docker networking
## Source: [ZS_Associates/DevOps_Engineer.md](../ZS_Associates/DevOps_Engineer.md)

- Calico and VPC CNI plugin difference. Why one is preferred over other. How would they help in setting up networking for pod.
- How is an ip address allocate to a pod. Does CNI plugin use same CIDR range which is provided by VPC or different?
- Suppose we configured a load balancer but it’s not accepting HTTPS request what would you do?
- Without installing certificate how would you divert the traffic coming from http to https
