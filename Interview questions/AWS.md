# AWS Interview Questions

Questions: 166

## Source: [Accenture/DevOps_Engineer.md](../Accenture/DevOps_Engineer.md)

- Assume you have 10 AWS accounts. How will you securely log in to them, considering access keys are not used for security reasons?
- Does Amazon S3 require a VPC?
- How do you set up RBAC in Amazon EKS?
- If secrets are created in AWS Secrets Manager, how can Amazon EKS access those secrets?
- What are the ways to log in to an AWS account?
- You have created an IAM user in AWS and configured role-based access in EKS. How do you bind the IAM user to the EKS role?
## Source: [Alphadyne/DevOps_Engineer_1.md](../Alphadyne/DevOps_Engineer_1.md)

- Application is hosted on a public EC2 instance.How to migrate it to a private subnet following AWS best practices (security, networking, HA).
## Source: [Altimetrik/SRE.md](../Altimetrik/SRE.md)

- Question : How do you import a resource into Terraform that was created manually in AWS or GCP? What command would you use?
- Question : I'll give you an example like let's talk about AWS. You have you're going to create a VPC and subnet And your provider is AWS and I'm asking you to write in using terraform.
## Source: [Amazon/DevOps_Consultant_2.md](../Amazon/DevOps_Consultant_2.md)

- If you’re migrating a monolithic application from on-prem to Cloud and the system has its local file system, which file system you will use in AWS.,
- Onboarded trading app into AWS, how will you make sure availability, scalability, security,
- You have been tasked to create 20 EC2 per account and you been provided with 10 AWS accounts, so totally you need to create 200 EC2 machines, how will connect all these machines. Which service will be used?,
## Source: [Arrise_Solutions/DevOps_Engineer.md](../Arrise_Solutions/DevOps_Engineer.md)

- How to connect a VPC in AWS to VPC in IBM Cloud
## Source: [Aspire/DevOps_Engineer.md](../Aspire/DevOps_Engineer.md)

- what are the different types of triggers in lambda aws?
## Source: [Belcan/DevOps_Engineer.md](../Belcan/DevOps_Engineer.md)

- Difference between elasticIP and publicIP in AWS
- Howmany Loadbalancers avaialble in AWS and explain each one
## Source: [BMW_TechWorks/DevOps_Engineer.md](../BMW_TechWorks/DevOps_Engineer.md)

- How do you perform this disk separation, and which AWS services/tools do you use?
## Source: [Capgemini/DevOps_Engineer_2.md](../Capgemini/DevOps_Engineer_2.md)

- AWS Lambda function and Step Function
- Which role to give to access services in AWS?
## Source: [Capgemini/DevOps_Engineer_3.md](../Capgemini/DevOps_Engineer_3.md)

- If we can use terraform import for existing AWS resources which are not created by Terraform, then what is the use of data source?
- Suppose you have created an EC2 instance by logging into the AWS console. And now you would like to manage it using Terraform. How shall you do it?
## Source: [Cisco/DevOps_Engineer.md](../Cisco/DevOps_Engineer.md)

- Terraform scripts for creating AWS services Jenkinsfile EKS and On Prem Kubernetes cluster upgrade steps.
## Source: [CMT/SRE.md](../CMT/SRE.md)

- design an high availability, fault tolerance system in aws
- what metrics is used to monitor ec2 instance cpu, memory in aws
- which are all the services you used in AWS
## Source: [Deloitte/DevOps_Engineer_1.md](../Deloitte/DevOps_Engineer_1.md)

- Can we create AWS backup using Shell Scripting?
- How do you take the backup of AWS Services?
- How to filter a particular IP from AWS CloudWatch Log Group?
- What are the node groups you used in AWS EKS?
- What are the types of node groups in AWS EKS?
- What is the difference between AWS Config and AWS CloudTrail?
- What types of nodes did you deploy in AWS?
## Source: [Deloitte/DevOps_Engineer_2.md](../Deloitte/DevOps_Engineer_2.md)

- How do you create AWS Lambda functions and manage the artifacts for deployment? What options do you use to push artifacts to Lambda?
## Source: [Deloitte/DevOps_Engineer_3.md](../Deloitte/DevOps_Engineer_3.md)

- An AWS account is given to you and if I ask you to create a VPC, all the services required for a service in EC2 to be exposes to internet, what all services come into picture?
- What have you done with terraform in AWS space?
## Source: [Deloitte/DevOps_Engineer_4.md](../Deloitte/DevOps_Engineer_4.md)

- I want to take data of how many ec2 running and how many EBS are attached from 50 or 60 aws accounts without logging into individual account . How can we do that
## Source: [Emphasis/DevOps_Engineer_1.md](../Emphasis/DevOps_Engineer_1.md)

- I attended interview for devops role, they were asking very basic questions about devops & aws.
## Source: [Emphasis/DevOps_Engineer_2.md](../Emphasis/DevOps_Engineer_2.md)

- What AWS resources have you created using Terraform and how do you promote a read replica to primary using Terraform?
- What is AWS Lambda and how do you design a serverless application?
## Source: [EPAM/DevOps_Engineer_1.md](../EPAM/DevOps_Engineer_1.md)

- direct connect in aws
- storage gateway in AWS
## Source: [EPAM/DevOps_Engineer_2.md](../EPAM/DevOps_Engineer_2.md)

- AWS Image builder
- How to check LB health details (monitoring) through AWS service
- TGW in AWS
## Source: [EPAM/DevOps_Engineer_3.md](../EPAM/DevOps_Engineer_3.md)

- What's your approach to securing cloud-native DevOps infrastructure with Identity Federation (e.g., Azure AD + AWS IAM)?
## Source: [EXL_Service/DevOps_Engineer.md](../EXL_Service/DevOps_Engineer.md)

- A developer accidentally commits AWS credentials to Git. What is your complete incident response process?
- Give a real-world use case of AWS Lambda.
- Which AWS EC2 instance types have you used, and why did you choose them?
## Source: [Flentas/DevOps_Engineer.md](../Flentas/DevOps_Engineer.md)

- How will you pass secrets from AWS Secrets Manager to the pipeline?
## Source: [HCL/DevOps_Engineer_3.md](../HCL/DevOps_Engineer_3.md)

- Account 1 to Account 2 – send AMI but its KMS encrypted, help me do that ❌ (aws)
- ALB and NLB have you used it ✅ (aws)
- Can you use same build spec used in AWS CodeBuild ✅ (terraform)
- EC2 has IAM roles, what all things can we explore from it ✅ (aws)
- I have EC2 and S3 in same subnet, region how to access that bucket from instance ✅ (aws)
- I have EC2 instance, internet connectivity not there, how to tackle this ❌ (aws)
- KMS, Secrets Manager have you worked on it ❌ (aws)
- Manually EC2 updated from t3.medium to t3.large manually and updated the code and committed but pipeline not ran. If you run pipeline then what will happen? (nothing will happen – code is in local machine of devops) ✅ (aws)
- Two instances are there what is the best way to communicate with them, create new NIC or attach ❌ (aws)
## Source: [IBM/Cloud_Engineer.md](../IBM/Cloud_Engineer.md)

- How do you deploy your application on AWS? What services do you use?
- When deploying your application to Amazon EKS, what other services do you use along with it?
## Source: [IBM/DevOps_Engineer_2.md](../IBM/DevOps_Engineer_2.md)

- Q5: out of aws and azure what would u choose and why?
## Source: [Infosys/SRE.md](../Infosys/SRE.md)

- So what all services do you have used in AWS?
## Source: [ITC_Infotech/DevOps_Engineer.md](../ITC_Infotech/DevOps_Engineer.md)

- How to make connections between on prem to AWS suppose if we want to share files from on prem.
- What is OIDC provider in AWS.
## Source: [JPMorgan/DevOps_Engineer_1.md](../JPMorgan/DevOps_Engineer_1.md)

- How are you provisioning your AWS services?
- How do you deploy an application to AWS?
- How do you optimize cold starts in AWS Lambda ?
- What is Serverless deployment in AWS?
- What is serverless in AWS, and how are you using it?
## Source: [JPMorgan/DevOps_SRE.md](../JPMorgan/DevOps_SRE.md)

- Are you aware of the recent AWS and Azure outages? What were your key takeaways from those incidents?
- If an entire region goes down and even a multi-cloud setup (like AWS + Azure) experiences outages how would you ensure that your data is still safe and not lost? What strategies would you use to guarantee reliable backups and recovery?
## Source: [Koerber_Pharma/DevOps_Engineer.md](../Koerber_Pharma/DevOps_Engineer.md)

- aws lambda where to use use case
- different plugins for ci/cd in jenkins using aws platform
- How are you connecting client's environment from your AWS environment.
- How to handle cost optimization in aws…how can we plan for cost optimization.
- how to manages certificate in aws. If the certificate expires how are you managing it and what's the action you are taking over here.
- How will you connect your terraform environment from aws and implement CI/CD.
- security best pracices in aws
- service to monitor spike in aws .application cpu usuage in cloud.
- Suppose you joined to a organisation, how the access would be given to you.how to secure aws account as admin.
## Source: [LTIMindtree/DevOps_Engineer_2.md](../LTIMindtree/DevOps_Engineer_2.md)

- Aws code commit flow
- how u do environmental variable in aws
## Source: [LTIMindtree/DevOps_Engineer_3.md](../LTIMindtree/DevOps_Engineer_3.md)

- write terraform script for creating app service in azure or write terraform script to create lambda in aws
## Source: [LTIMindtree/DevOps_Engineer_4.md](../LTIMindtree/DevOps_Engineer_4.md)

- How do you deploy python application on aws using jenkins pipeline
- Your aws jenkins pipeline takes high time, how will you troubleshoot
## Source: [Moodys/MLOps_Engineer.md](../Moodys/MLOps_Engineer.md)

- Apart from SageMaker, which AWS or open-source services have you used or are aware of for training ML models?
- How do you manage and version Docker images stored in Amazon ECR?
- How do you prevent misuse or unauthorized usage if someone attempts to spin up ML services in AWS?
- What strategies do you use to optimize and control AWS costs for ML workloads?
## Source: [Nextturn/DevOps_Engineer.md](../Nextturn/DevOps_Engineer.md)

- You are able to launch an EC2 instance from the AWS Console, but you cannot SSH into the instance. How would you install tree package
## Source: [Nice/SRE_2.md](../Nice/SRE_2.md)

- [ ] Other than Azure and AWS, are you familiar with any other cloud platforms or services?
## Source: [NUOS_INFO_Systems/DevOps_Engineer.md](../NUOS_INFO_Systems/DevOps_Engineer.md)

- How do you manage AWS + Azure using a single DevOps process with focus on security & cost?
## Source: [Optum/DevOps_Engineer.md](../Optum/DevOps_Engineer.md)

- How do I transfer payloads between lambda function in 2 different AWS account
- How do you ensure particular AMI image is present in AWS account using terraform
## Source: [Orion_Innovation/DevOps_Engineer.md](../Orion_Innovation/DevOps_Engineer.md)

- you have multiple VPC, how will you connect them in AWS
## Source: [Others/Cloud_Administrator_senior.md](../Others/Cloud_Administrator_senior.md)

- Project specific questions(How would you setup a new environment on AWS, Terraform code provisioning)
## Source: [Others/Cloud_Engineer.md](../Others/Cloud_Engineer.md)

- AWS Cloud Engineer role -:
- How do you did cost optimization in AWS?
- How do you implement best security policies on AWS?
## Source: [Others/DevOps_Engineer_1.md](../Others/DevOps_Engineer_1.md)

- How do you configure AWS RDS, and what factors do you consider (size, requirements, etc.)?
## Source: [Others/DevOps_Engineer_12.md](../Others/DevOps_Engineer_12.md)

- How did you migrate an application from an on-premise server to AWS?, Can you explain the process and the method you followed ?
- How would you optimize AWS resource costs? Can you explain the methods you would use ?
- You have a microservices application that needs to scale dynamically based on traffic. How would you design an architecture for this using AWS services ?
## Source: [Others/DevOps_Engineer_13.md](../Others/DevOps_Engineer_13.md)

- How do you configure a pipeline with AWS or Docker?
## Source: [Others/DevOps_Engineer_2.md](../Others/DevOps_Engineer_2.md)

- How comfortable with AWS and how much rate urself out of 5?
## Source: [Others/DevOps_Engineer_3.md](../Others/DevOps_Engineer_3.md)

- ) How does SSL work (Certbot, Let's Encrypt, AWS)? Explain the Flow.
## Source: [Others/DevOps_Engineer_4.md](../Others/DevOps_Engineer_4.md)

- How can you connect from AWS to on-prem servers?
- How can you protect the data in an AWS instance?
- How do you scan the vulnerabilities specially for AWS instances.
- Suppose in your DevOps team, new team members are added to your team. How can you provide AWS access to your new users, what is the behavior of login to the console?
## Source: [Others/DevOps_Engineer_5.md](../Others/DevOps_Engineer_5.md)

- AWS event bridge creation and setup via terraform
## Source: [Others/DevOps_Engineer_7.md](../Others/DevOps_Engineer_7.md)

- What are the services u were used in AWS
## Source: [Others/DevOps_Engineer_8.md](../Others/DevOps_Engineer_8.md)

- Have you worked on the AWS, right?
- Two AWS accounts are there in same organisation. Account A has Ec2 instance and Account B has some tokens. Need to access the tokens from Ec2 instance.
## Source: [Others/DevOps_Engineer_9.md](../Others/DevOps_Engineer_9.md)

- Design a highly available backend on AWS – what services and architecture would you use?
## Source: [Persistent_Systems/DevOps_Engineer_1.md](../Persistent_Systems/DevOps_Engineer_1.md)

- Cloud watch & how do you create a custom metric in AWS CloudWatch.
## Source: [Persistent_Systems/DevOps_Engineer_3.md](../Persistent_Systems/DevOps_Engineer_3.md)

- If there is a vendor who provides VPN services for company A, his manager wants to view some dashboard but do not have AWS account. How would you help him?
- What are the AWS resources you have used in your previous role?
- What is AWS lambda and where have u used?
## Source: [Persistent_Systems/DevOps_Engineer_4.md](../Persistent_Systems/DevOps_Engineer_4.md)

- Do you have experience with AWS DevOps services like CodeDeploy, CodeBuild, and CodePipeline? How would you set up a pipeline using them?
## Source: [Plansource_ValueLabs/DevOps_Engineer.md](../Plansource_ValueLabs/DevOps_Engineer.md)

- how Autocaling happens in aws ECS
## Source: [Publicis_Global_Delivery/DevOps_Engineer.md](../Publicis_Global_Delivery/DevOps_Engineer.md)

- How does authentication happen in Jenkins pipeline to use aws with particular login, if you have 1 logout?
## Source: [Qburst/DevOps_Engineer.md](../Qburst/DevOps_Engineer.md)

- What is major vpc difference between aws & gcp vpcs?
## Source: [Qentelli_Solutions/DevOps_Engineer.md](../Qentelli_Solutions/DevOps_Engineer.md)

- How do you secure your environments in aws
- what are security options in aws
- Your aws billing spikes, what should you check
## Source: [Sapient/DevOps_Engineer.md](../Sapient/DevOps_Engineer.md)

- How many AWS storage services does it have?
- In AWS, what all the services you have used?
## Source: [Sigmoid/DevOps_Engineer_4.md](../Sigmoid/DevOps_Engineer_4.md)

- Did you use AWS accounts? How did you handle the segregation of various environments within AWS.
- There is a new requirement from platform team to design a 3 tier architecture, with frontend , backend and database with all the security best practices , high availability , low latency. (AWS)
- There was an issue last time with some config changes in TF resource which had lead to slight downtime of the AWS resource during apply. What might have caused this downtime, how do you handle this in terraform for futurue config changes, for ensuring least possible downtime and maximum possible availability. Write a terraform code to handle this situation.
## Source: [Sonata_Software/DevOps_Engineer_2.md](../Sonata_Software/DevOps_Engineer_2.md)

- AWS Questions
- Have you worked on AWS Auto Scaling?
- How do you encrypt secrets in AWS Secrets Manager?
- How do you retrieve secrets from AWS Secrets Manager using Python?
- Say if you have both explicit deny and allow policy to a user in AWS IAM, what happens?
- What are the AWS services that you have worked on?
## Source: [Sony/DevOps_Engineer.md](../Sony/DevOps_Engineer.md)

- How would you design a system to survive if one AWS region goes down?
- How would you investigate a sudden three‑times increase in the AWS bill?
- How would you manage Terraform when multiple teams deploy to the same AWS account but must not overwrite each other’s resources?
## Source: [SquareOps/DevOps_Engineer.md](../SquareOps/DevOps_Engineer.md)

- → AWS Auth ConfigMap
- ☁️ AWS & Cloud Concepts
- ☁️ AWS Cloud Responsibilities
- ☁️ AWS Hands-On Services (Round 2)
- Do you use AWS Secrets Manager?
- Is everything on AWS or multi-cloud?
- Q1. Which AWS services do you have the most hands-on experience with?
- Q2. What exactly do you do in AWS Cloud in this project?
- What is aws-auth ConfigMap?
- Where is aws-auth stored?
## Source: [Synechron/DevOps_Engineer_3.md](../Synechron/DevOps_Engineer_3.md)

- How does an AWS CodePipeline differ from a Jenkins pipeline? Can you give an example of when you would choose one over the other?
## Source: [TCS/SRE_1.md](../TCS/SRE_1.md)

- Explain the AWS architecture shown in the diagram (CodePipeline, CodeBuild, CodeDeploy, CloudFormation, CloudWatch).
- How do you restrict access to AWS resources for a specific user?
- What is the difference between Interface Endpoint and Gateway Endpoint in AWS?
- What types of nodes did you deploy on AWS?
## Source: [Turning/Cloud_Engineer.md](../Turning/Cloud_Engineer.md)

- AWS CDK commands
## Source: [UST/Cloud_Platform_Engineer.md](../UST/Cloud_Platform_Engineer.md)

- Write Terraform code to create an AWS EC2 instance and include variables for instance_type and region.
## Source: [Verizon/DevOps_Engineer.md](../Verizon/DevOps_Engineer.md)

- AWS secret manager vs parameter store
## Source: [Wipro/DevOps_Engineer_2.md](../Wipro/DevOps_Engineer_2.md)

- Could you elaborate your experience with automating and optimizing the deployment over large infrastructure using AWS and other tools like Terraform and Ansible from your previous roles?
- What is Cloud-agnostic strategies? how do you leverage conditionals to make a role cloud-agnostic, particularly for environments like AWS, Azure and GCP.
## Source: [Wipro/DevOps_Engineer_4.md](../Wipro/DevOps_Engineer_4.md)

- They were mainly looking for terraform and Aws experience
## Source: [Wipro/DevOps_Engineer_5.md](../Wipro/DevOps_Engineer_5.md)

- Application on AWS EC2 behind the loadbalancer suddenly unavailable, how do you troubleshoot
- AWS billing increased suddenly, how do you identify the costs
- In AWS how do you configure subdomains (like godady/bigrock)
## Source: [ZopSmart/DevOps_Engineer.md](../ZopSmart/DevOps_Engineer.md)

- you are using jenkins server as open source s/w tool like in aws service which service is available to implement CICD Pipeline
- you are using K8S Cluster as open source s/w tool like in aws service which service is available to create K8S Cluster
