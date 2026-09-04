# Security Interview Questions

Questions: 168

## Source: [Accenture/DevOps_Engineer.md](../Accenture/DevOps_Engineer.md)

- Assume you have 10 AWS accounts. How will you securely log in to them, considering access keys are not used for security reasons?
- How do you set up RBAC in Amazon EKS?
- If secrets are created in AWS Secrets Manager, how can Amazon EKS access those secrets?
- You have created an IAM user in AWS and configured role-based access in EKS. How do you bind the IAM user to the EKS role?
## Source: [Alphadyne/DevOps_Engineer_1.md](../Alphadyne/DevOps_Engineer_1.md)

- Application is hosted on a public EC2 instance.How to migrate it to a private subnet following AWS best practices (security, networking, HA).
- Discussion around ALB/NLB, ACM certificates, routing, and security groups.
## Source: [Alphadyne/DevOps_Engineer_2.md](../Alphadyne/DevOps_Engineer_2.md)

- Provision Virtual Machines (VMs) using those NICs, with username and password authentication
## Source: [Altimetrik/SRE.md](../Altimetrik/SRE.md)

- Question : Describe your experience with infrastructure administration tasks like licensing, billing, cost reduction, and security.
## Source: [Amadeus_Labs/SRE.md](../Amadeus_Labs/SRE.md)

- 11 . Can pod be scheduled if have below security constent .
## Source: [Amazon/DevOps_Consultant_1.md](../Amazon/DevOps_Consultant_1.md)

- I’m an admin but I don’t have access to the S3 bucket ? → IAM permission boundary
## Source: [Amazon/DevOps_Consultant_2.md](../Amazon/DevOps_Consultant_2.md)

- Onboarded trading app into AWS, how will you make sure availability, scalability, security,
- What are the security protocols will be taken into consideration while designing three tier architecture.,
## Source: [AMEX/DevOps_Engineer.md](../AMEX/DevOps_Engineer.md)

- how the end point authentication works in kubernetes
## Source: [Aspire/DevOps_Engineer.md](../Aspire/DevOps_Engineer.md)

- what is the difference between NACL and Security groups?
## Source: [Blue_Yonder/DevOps_Engineer.md](../Blue_Yonder/DevOps_Engineer.md)

- • How do you do you integrate And EntraID with your AKS for authentication?
- • How do you use Azure Key vault's secrets in AKS?
- • How will the application(container/pod) fetch the latest(rotated) secrets form azure vault.
## Source: [BMW_TechWorks/DevOps_Engineer.md](../BMW_TechWorks/DevOps_Engineer.md)

- Have you used HashiCorp Vault?
- If an EC2 instance has a vulnerability, how would you identify and fix it?
## Source: [Capgemini/DevOps_Engineer_1.md](../Capgemini/DevOps_Engineer_1.md)

- How mysql will interact with azure key vault and it should happen thru privately and should not go anything on public
## Source: [Capgemini/DevOps_Engineer_2.md](../Capgemini/DevOps_Engineer_2.md)

- How to create a secret service account?
- How to execute a vault file?
## Source: [Capgemini/DevOps_Engineer_3.md](../Capgemini/DevOps_Engineer_3.md)

- Because you are telling it from the IAM perspective, what about the VPC?
## Source: [CGI/DevOps_Engineer.md](../CGI/DevOps_Engineer.md)

- Security
## Source: [Cisco/DevOps_Engineer.md](../Cisco/DevOps_Engineer.md)

- And how did you managed security for application level?
- Write a playbook to deploy an Nginx server and ensure the service is started and enabled on boot. How would you manage secrets in Ansible?
- Write Terraform code to provision an EC2 instance with a security group allowing only SSH access.
## Source: [CTS/DevOps_Engineer_1.md](../CTS/DevOps_Engineer_1.md)

- Check if any firewall/security group rules are blocking the flow of traffic
- Check SSL certificate if it has gone corrupt and is working fine
## Source: [Deloitte/DevOps_Engineer_2.md](../Deloitte/DevOps_Engineer_2.md)

- Are you aware of security scanning tools? How do you scan Docker images—both during build and at the registry level? Are you using any extensions or tools for image scanning?
- How do you handle authentication for EKS clusters and store secrets securely in your environment?
## Source: [Emphasis/DevOps_Engineer_1.md](../Emphasis/DevOps_Engineer_1.md)

- What is difference between NACL & security groups
## Source: [Encora/DevOps_Engineer.md](../Encora/DevOps_Engineer.md)

- how do you rotate the secrets in key vault and implement .pfx certificate in application gateway , along with ingress/controller in AKS
- there are multiple micro services and multiple websites, I want to ensure security how do you handle it
## Source: [EPAM/DevOps_Engineer_2.md](../EPAM/DevOps_Engineer_2.md)

- Enabling tight security to my LB
## Source: [EPAM/DevOps_Engineer_3.md](../EPAM/DevOps_Engineer_3.md)

- How do you design an end-to-end DevSecOps pipeline for a fintech application with strict compliance requirements (e.g., PCI-DSS)?
- How do you enforce compliance and auditability in your CI/CD processes across global regions (e.g., GDPR, HIPAA)?
- How do you manage secrets and config securely at scale in Kubernetes without compromising GitOps workflows?
- What's your approach to securing cloud-native DevOps infrastructure with Identity Federation (e.g., Azure AD + AWS IAM)?
- What's your strategy for managing container image security across all stages of a DevOps pipeline?
## Source: [EXL_Service/DevOps_Engineer.md](../EXL_Service/DevOps_Engineer.md)

- Where do you store application configuration and secrets? (ConfigMaps, Kubernetes Secrets, HashiCorp Vault, etc.)
- Where do you store CI/CD secrets such as pipeline credentials?
## Source: [EY/DevOps_Engineer_2.md](../EY/DevOps_Engineer_2.md)

- Have you used any security tool integrations in your pipelines?
## Source: [F5/Associate_Consultant.md](../F5/Associate_Consultant.md)

- Best practices to be followed for cloud security.,
- Have you deployed any security application on Kubernetes?
- If thre is an instance we have security group and web application firewall enabled, DDOS attack enabled will it protect from Bot attack.
- If we have security group configured in the instance do we really need nacl.,
## Source: [Flentas/DevOps_Engineer.md](../Flentas/DevOps_Engineer.md)

- How do you handle secrets in Terraform?
- How will you pass secrets from AWS Secrets Manager to the pipeline?
## Source: [HCL/DevOps_Engineer_1.md](../HCL/DevOps_Engineer_1.md)

- How to integrate azure key vault in jenkins / azure pipeline
## Source: [HCL/DevOps_Engineer_3.md](../HCL/DevOps_Engineer_3.md)

- EC2 has IAM roles, what all things can we explore from it ✅ (aws)
- I have multiple IAM user which is best approach: 1. attach policy individual to user OR 2. add that user to group and attach policy ✅ (iam)
- Inline policy or attaching policy which is right approach ❌ (iam)
- KMS, Secrets Manager have you worked on it ❌ (aws)
## Source: [HCL/DevOps_Engineer_software.md](../HCL/DevOps_Engineer_software.md)

- What top-level security risks from OWASP do you usually check for?
## Source: [IBM/Cloud_Engineer.md](../IBM/Cloud_Engineer.md)

- Are you following any other approach to store secret credentials securely?
- If it's a production server and you encounter a vulnerability, what will you do?
- If it’s a Python application and a vulnerability is found in production and fixing it may take 6 months, what is your approach and solution?
- Suppose you're running an application and a vulnerability occurs, how would you handle it? Briefly explain.
## Source: [IBM/DevOps_Engineer_1.md](../IBM/DevOps_Engineer_1.md)

- How do you securely manage TF state files, secrets, and environment isolation?
- How will you check the vulnerability of your code
## Source: [Infosys/DevOps_Engineer_3.md](../Infosys/DevOps_Engineer_3.md)

- What is security group and what is the default traffic rule in sg
## Source: [Infosys/SRE.md](../Infosys/SRE.md)

- Suppose you have a VPC , and in your VPC, you have 2 subnets. One is a private subnet, and another one is a public subnet. And in these subnets you have 2 - 3 instances. And for security purposes we need to keep those instances updated right on a regular basis. The instances in the public subnet are okay. They have internet connectivity. They can get updated. How will you update the instances which are in the private subnet?
## Source: [ITC_Infotech/DevOps_Engineer.md](../ITC_Infotech/DevOps_Engineer.md)

- What is OIDC provider in AWS.
## Source: [JPMorgan/DevOps_Engineer_1.md](../JPMorgan/DevOps_Engineer_1.md)

- Are actuator endpoints accessed without authentication?
- How have you implemented security in your project?
## Source: [JPMorgan/DevOps_Engineer_senior.md](../JPMorgan/DevOps_Engineer_senior.md)

- How do you ensure secure and dynamic secret rotation in Azure DevOps pipelines?
## Source: [JPMorgan/DevOps_SRE.md](../JPMorgan/DevOps_SRE.md)

- For example, if someone modifies a security group in Terraform and opens it to 0.0.0.0/0, what mechanisms can we use in Terraform to stop such changes from being applied?
- Just like we use code-quality and security checks (quality gates, OWASP) before building an image, how can we prevent insecure infrastructure changes from being pushed using terraform?
## Source: [Koerber_Pharma/DevOps_Engineer.md](../Koerber_Pharma/DevOps_Engineer.md)

- how to manages certificate in aws. If the certificate expires how are you managing it and what's the action you are taking over here.
- security best pracices in aws
## Source: [L_and_T/DevOps_Engineer.md](../L_and_T/DevOps_Engineer.md)

- How you are managing secrets in kubernetes
- what is ansible vault
## Source: [LTIMindtree/DevOps_Engineer_4.md](../LTIMindtree/DevOps_Engineer_4.md)

- How do you provide security in docker
## Source: [LTIMindtree/DevOps_Engineer_L2.md](../LTIMindtree/DevOps_Engineer_L2.md)

- How do you manage secrets securely in GitOps or deployment pipelines?
## Source: [Marsh_McLennan/DevOps_Engineer.md](../Marsh_McLennan/DevOps_Engineer.md)

- Have you used HashiCorp Vault for secret management?
- How do you store and retrieve secrets from HashiCorp Vault?
- What are the different authentication methods or injectors supported by HashiCorp Vault?
## Source: [Nextturn/DevOps_Engineer.md](../Nextturn/DevOps_Engineer.md)

- Azure DevOps – Variable Groups, Environment Variables, and Secrets.
## Source: [Nice/SRE_2.md](../Nice/SRE_2.md)

- [ ] Did you create the Azure Key Vault access policies yourself, or did someone else do it for you?
- [ ] Do you have experience using Azure Key Vault?
- [ ] Have you integrated Azure Key Vault into your pipelines or branches in any project?
## Source: [Nisum_Technologies/DevOps_Engineer.md](../Nisum_Technologies/DevOps_Engineer.md)

- How do you fix security issues in Docker images?
## Source: [Nitor_Infotech/DevOps_Engineer.md](../Nitor_Infotech/DevOps_Engineer.md)

- How have you implemented RBAC in your EKS setup
## Source: [NUOS_INFO_Systems/DevOps_Engineer.md](../NUOS_INFO_Systems/DevOps_Engineer.md)

- How do you manage AWS + Azure using a single DevOps process with focus on security & cost?
- How to write a multistage Dockerfile for a Node.js app — removing secrets and unnecessary layers?
- How would you use Azure DevOps REST API to apply a security policy to all repos programmatically?
- Recommended tools for CI/CD, artifact storage, vulnerability scanning, and container registry in a hybrid (on-prem + Azure) setup?
## Source: [Optum/DevOps_Engineer.md](../Optum/DevOps_Engineer.md)

- How do you ensure the least privilege access to the IAM users
## Source: [Oracle/DevOps_Engineer.md](../Oracle/DevOps_Engineer.md)

- Configmap VS secrets
## Source: [Orion_Innovation/DevOps_Engineer.md](../Orion_Innovation/DevOps_Engineer.md)

- application gateway TLS certificate is expired, what steps you will follow to renew it
- you want to store the secrets in Jenkins pipeline , how will you do it
## Source: [Others/Cloud_Administrator_senior.md](../Others/Cloud_Administrator_senior.md)

- How would you implement security for Kubernetes(both on container side and the infra side using native Kubernetes solutions)
## Source: [Others/Cloud_Engineer.md](../Others/Cloud_Engineer.md)

- How do you implement best security policies on AWS?
## Source: [Others/DevOps_Engineer_1.md](../Others/DevOps_Engineer_1.md)

- How do you enable passwordless authentication between two servers?
- What are Network ACLs and Security Groups, and how do they differ?
## Source: [Others/DevOps_Engineer_11.md](../Others/DevOps_Engineer_11.md)

- Difference between Iam users.. GitHub Oidc role and terraform io role.. which is secured and when to use use GitHub Oidc and when to use terraform io role
- Difference between secret manager and parameter store
## Source: [Others/DevOps_Engineer_12.md](../Others/DevOps_Engineer_12.md)

- How you secure secrets and credentials in your CI/CD process ?
- What is IAM and how it works ?
## Source: [Others/DevOps_Engineer_13.md](../Others/DevOps_Engineer_13.md)

- Follow-up for Q23: If you are using GitHub Marketplace actions, which are third-party tools, how do you ensure security concerns regarding them?
- How do you handle secrets in your project?
## Source: [Others/DevOps_Engineer_15.md](../Others/DevOps_Engineer_15.md)

- How did you manage secrets in your project?
- some questions went around API and diff between authorization and authentication.
- what are secrets ? for what type of applications we may need them?
## Source: [Others/DevOps_Engineer_16.md](../Others/DevOps_Engineer_16.md)

- delete the inline policy for users where * is mentioned in the iam users list
- How the authentication and networking is established between azure devops pipeline and azure keyvault
- so list the usrs who has not accessed the keys in iam for more than 90 days
- what all the types of polices we have in iam
## Source: [Others/DevOps_Engineer_2.md](../Others/DevOps_Engineer_2.md)

- about IAM/Fargate/EC2/Lambda?
- about RBAC
## Source: [Others/DevOps_Engineer_4.md](../Others/DevOps_Engineer_4.md)

- diff between IAM Users and Roles
- how you ensure the best possible security for high availability architectures for 3 tier applications.
- What are the best password security practices used by your organisation?
- What are the different types of secrets in Kubernetes?
- What are the security parameters we must consider while we are creating an EC2 instance for production?
## Source: [Others/DevOps_Engineer_5.md](../Others/DevOps_Engineer_5.md)

- How to use the secrets in kubernetes? What encryption methods do you use?
## Source: [Others/DevOps_Engineer_8.md](../Others/DevOps_Engineer_8.md)

- So how many types of policy, IAM policy are there? IAM policies?
- What is the difference between Security groups and NACL?
## Source: [Others/DevOps_Engineer_9.md](../Others/DevOps_Engineer_9.md)

- EC2 instance is unreachable, and it’s not a security group issue. What’s your next step?
- Terraform script to provision an EC2 instance with a custom security group and user data script.
## Source: [Others/DevOps_Engineer_behavioral.md](../Others/DevOps_Engineer_behavioral.md)

- Have you ever dealt with a security vulnerability in your DevOps pipeline? How did you detect and respond to it?,
## Source: [Publicis_Global_Delivery/DevOps_Engineer.md](../Publicis_Global_Delivery/DevOps_Engineer.md)

- How does authentication happen in Jenkins pipeline to use aws with particular login, if you have 1 logout?
## Source: [Qentelli_Solutions/DevOps_Engineer.md](../Qentelli_Solutions/DevOps_Engineer.md)

- what are security options in aws
## Source: [RelevantZ/DevOps_Engineer.md](../RelevantZ/DevOps_Engineer.md)

- have you ever automated .csr – .cer - .pfx certificate activity
- how do you store secrets in azure devops
- what do you do with azure recovery service vault
## Source: [SAP/DevOps_Engineer.md](../SAP/DevOps_Engineer.md)

- How will you maintain your base image, vulnerability free?
## Source: [Sigmoid/DevOps_Engineer_2.md](../Sigmoid/DevOps_Engineer_2.md)

- How to enable RBAC to Service accounts
## Source: [Sigmoid/DevOps_Engineer_4.md](../Sigmoid/DevOps_Engineer_4.md)

- Consider there is a MySQl operator running in one of your pod in one of your node of a k8s cluster. How the Mysql database managed by this is different from the normal pod that is started with a mysql image from deployment/pod template? Apart from just handling the updates, version changes, lifecycle, vulnerabilitites , security issues, it provides lot more advantages, please explain the use cases by giving some scenarios.
- Explain and draw the architecture diagram of your current project flow end to end, while also explaining the measures you have taken for ensuring the security and best practicies to comply with SLA.
- Explain each component in your architecture which is involved from a user requesting from the UI to the request reaching the backend pod, and how they are connecting with each other to ensure inbound and outbound flow(including the firewall, NACl, security groups, route tables etc).
- The flow from dev to prod. What are the security checks that you follow within CI pipeline of your current project.
- There is a new requirement from platform team to design a 3 tier architecture, with frontend , backend and database with all the security best practices , high availability , low latency. (AWS)
## Source: [Sonata_Software/DevOps_Engineer_1.md](../Sonata_Software/DevOps_Engineer_1.md)

- where do you store the application gateway (TLS/SSL certificate) ?
## Source: [Sonata_Software/DevOps_Engineer_2.md](../Sonata_Software/DevOps_Engineer_2.md)

- Can you tell me the difference between managed policy and inline policy in IAM?
- How do you encrypt secrets in AWS Secrets Manager?
- How do you protect the secrets in Secrets Manager?
- How do you retrieve secrets from AWS Secrets Manager using Python?
- Say if you have both explicit deny and allow policy to a user in AWS IAM, what happens?
## Source: [Sony/DevOps_Engineer.md](../Sony/DevOps_Engineer.md)

- What are the vulnerability reports in your sonarqube.
## Source: [SquareOps/DevOps_Engineer.md](../SquareOps/DevOps_Engineer.md)

- 🔐 IAM & Policies
- Do you avoid committing secrets in values.yaml?
- Do you handle IAM + RBAC in Kubernetes?
- Do you manage VPC/subnets/security groups?
- Do you use AWS Secrets Manager?
- How do you handle secrets in pipelines?
- How to get Sonar token?
- IAM?
- Q2. Create an EC2 IAM role that allows access only to S3 + DynamoDB and denies access to all other services.
- Q7. In which Kubernetes resource do you map IAM users/roles?
- Q9. Request comes from Internet → enters VPC through IGW → what is the first security layer? NACL or SG?
- What IAM policy do you attach?
- What is Sealed Secrets?
- What mistakes can break authentication?
- Where to store token?
- Why is storing secrets in plaintext dangerous?
## Source: [Verizon/DevOps_Engineer.md](../Verizon/DevOps_Engineer.md)

- AWS secret manager vs parameter store
- How will u ensure docker container security while writing docker file
## Source: [Volkswagen_Group_Digital/DevOps_Engineer.md](../Volkswagen_Group_Digital/DevOps_Engineer.md)

- how do you run security checks in docker image?
## Source: [Wipro/DevOps_Engineer_1.md](../Wipro/DevOps_Engineer_1.md)

- How azure key vault is integrated in cicd
- If secret is stored in vault inside a pod and that pod is down then how to tsg
## Source: [Wipro/DevOps_Engineer_2.md](../Wipro/DevOps_Engineer_2.md)

- Describe the security implications of using Kubernetes secret in etcd without encryption?
## Source: [Wipro/DevOps_Engineer_3.md](../Wipro/DevOps_Engineer_3.md)

- What security measures and policies should be put in place when using a service mesh?
## Source: [Zensar/DevOps_Engineer.md](../Zensar/DevOps_Engineer.md)

- How configmap and secrets can be used in k8s
## Source: [ZopSmart/DevOps_Engineer.md](../ZopSmart/DevOps_Engineer.md)

- how to implement authentication in k8s cluster?
- what is IAM Role
## Source: [ZS_Associates/DevOps_Engineer.md](../ZS_Associates/DevOps_Engineer.md)

- Without installing certificate how would you divert the traffic coming from http to https
