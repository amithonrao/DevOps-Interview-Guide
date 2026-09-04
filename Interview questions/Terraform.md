# Terraform Interview Questions

Questions: 238

## Source: [Accenture/DevOps_Engineer.md](../Accenture/DevOps_Engineer.md)

- What happen when we run terraform init ?
- write a terraform script to create an ec2 instance in multiple region.
- You have defined a multi-region Terraform configuration (region1, region2, region3). If you create an EC2 instance, in which region will it be deployed?
## Source: [Accion_Labs/SRE.md](../Accion_Labs/SRE.md)

- Have you written Terraform code for deployments? If yes, can you explain the implementation?
- Why do we use workspaces in Terraform?
## Source: [Alphadyne/DevOps_Engineer_2.md](../Alphadyne/DevOps_Engineer_2.md)

- Coding Task (Terraform on Azure):
## Source: [Altimetrik/SRE.md](../Altimetrik/SRE.md)

- Question : How do you import a resource into Terraform that was created manually in AWS or GCP? What command would you use?
- Question : I'll give you an example like let's talk about AWS. You have you're going to create a VPC and subnet And your provider is AWS and I'm asking you to write in using terraform.
- Question : Set up the nodes and everything. what do you write inside a terraform code basically now what will be inside your provider file provided ATF in your main dotf?
- Question : So how you are using terraform to deploy the cluster nodes?
## Source: [Amazon/DevOps_Consultant_1.md](../Amazon/DevOps_Consultant_1.md)

- Write a Terraform code to create VPC, subnet, EC2, S3 bucket.
## Source: [Amazon/DevOps_Consultant_2.md](../Amazon/DevOps_Consultant_2.md)

- Diff between local and variable in Terraform,
- You created couple of resources using Terraform, how will you make sure that resources are not modified through UI, how will you automate this check
## Source: [Aspire/DevOps_Engineer.md](../Aspire/DevOps_Engineer.md)

- what is mean by Provisioner and provider in terraform?
- what is the the use of terraform import ?
- what is the use of command terraform fmt?
## Source: [Belcan/DevOps_Engineer.md](../Belcan/DevOps_Engineer.md)

- what is the terraform statefile
- writedown the few terraform commands and explain each cmd
## Source: [Capgemini/DevOps_Engineer_3.md](../Capgemini/DevOps_Engineer_3.md)

- …resources in Terraform
- If we can use terraform import for existing AWS resources which are not created by Terraform, then what is the use of data source?
- Suppose you have created an EC2 instance by logging into the AWS console. And now you would like to manage it using Terraform. How shall you do it?
## Source: [Cisco/DevOps_Engineer.md](../Cisco/DevOps_Engineer.md)

- How would you migrate a Terraform backend from local to a remote backend like S3 with DynamoDB locking?
- Terraform scripts for creating AWS services Jenkinsfile EKS and On Prem Kubernetes cluster upgrade steps.
- What happens if the Terraform state becomes corrupted, and how would you recover from it?
- Write Terraform code to provision an EC2 instance with a security group allowing only SSH access.
## Source: [CMT/SRE.md](../CMT/SRE.md)

- terraform structure
## Source: [CTS/DevOps_Engineer_1.md](../CTS/DevOps_Engineer_1.md)

- Backend.tf file is showing in repo but it is not showing in storage account, what may be the issue
## Source: [CTS/DevOps_Engineer_2.md](../CTS/DevOps_Engineer_2.md)

- What will happen when a IaC managed resource is modified manually, how would you avoid it
## Source: [CTS/DevOps_Engineer_3.md](../CTS/DevOps_Engineer_3.md)

- Difference between Terraform destroy and refresh command
- How to prevent someone from running terraform destroy or destroying the infra?
- What have you done in Terraform and how did you do the integration?
## Source: [Deloitte/DevOps_Engineer_2.md](../Deloitte/DevOps_Engineer_2.md)

- How do you create and manage Kubernetes clusters (using tools like Terraform), and what are the master and worker nodes?
## Source: [Deloitte/DevOps_Engineer_3.md](../Deloitte/DevOps_Engineer_3.md)

- Difference between terraform and Cloud formation templates?
- What have you done with terraform in AWS space?
## Source: [Deloitte/DevOps_Engineer_4.md](../Deloitte/DevOps_Engineer_4.md)

- What is the Terraform init and Terraform refresh
- What is your Terraform file structure for vpc, eks
- Write a Terraform configuration file for ec2 with EBS volume attached
## Source: [Emphasis/DevOps_Engineer_2.md](../Emphasis/DevOps_Engineer_2.md)

- In Terraform, which parameter or code change is needed to make a read replica the primary?
- What AWS resources have you created using Terraform and how do you promote a read replica to primary using Terraform?
- What is the difference between terraform plan and terraform apply?
- Which components or resources are required to create a 3-tier architecture using Terraform?
## Source: [Encora/DevOps_Engineer.md](../Encora/DevOps_Engineer.md)

- am having an range of ip address 10.0.0.0/16 , I want to have 10.0.0.0/21 subnets , how will I achieve it terraform , how do use locals word and achieve it
- for each and count difference, provide examples in terraform
- how do you create an module and how do you refer it in terraform
- i had created an resource manually, how to do you implement it through terraform
- what is terraform lifecycle
## Source: [EPAM/DevOps_Engineer_1.md](../EPAM/DevOps_Engineer_1.md)

- how to manage state in terraform
- Terraform:
- what is terraform module.
## Source: [EPAM/DevOps_Engineer_3.md](../EPAM/DevOps_Engineer_3.md)

- Explain the internals of how Terraform handles dependencies and graph building during the planning phase.
- Have you implemented policy-as-code (e.g., Sentinel, OPA) with Terraform? Give a real use case.
- How do you manage and isolate Terraform state files across multiple environments and teams?
- How would you manage cross-region deployments using Terraform in a multi-cloud setup?
- How would you refactor a legacy Terraform codebase used by multiple teams to follow best practices like DRY and modularity?
## Source: [EXL_Service/DevOps_Engineer.md](../EXL_Service/DevOps_Engineer.md)

- Do you execute Terraform locally or through a CI/CD pipeline? Explain the complete workflow.
- Draw and explain your Terraform repository structure. How do your dev, qa, and prod environments consume shared modules like the VPC module?
- Two engineers are working on the same Terraform code. How do you prevent conflicts and handle Terraform state locking or drift?
## Source: [EY/DevOps_Engineer_1.md](../EY/DevOps_Engineer_1.md)

- Terraform
## Source: [F5/Associate_Consultant.md](../F5/Associate_Consultant.md)

- What are best practices to be followed on terraform,
- What happens if tfstate file gets deleted,
- What is terraform lock hcl file,
## Source: [Flentas/DevOps_Engineer.md](../Flentas/DevOps_Engineer.md)

- Explain the Terraform folder structure.
- How do you handle resource dependencies in Terraform?
- How do you handle secrets in Terraform?
- I have created an LB using Terraform, and some updates happened on it. Now I want to delete
- If there is a problem in Terraform, how will you roll back the changes?
- What is the difference between Terraform and Terragrunt?
- What is the state file in Terraform?
- When you ran terraform apply, did you encounter any unexpected changes?
## Source: [HCL/DevOps_Engineer_2.md](../HCL/DevOps_Engineer_2.md)

- terraform have you build the vm
## Source: [HCL/DevOps_Engineer_3.md](../HCL/DevOps_Engineer_3.md)

- Can you use same build spec used in AWS CodeBuild ✅ (terraform)
## Source: [Hexaware/DevOps_Engineer.md](../Hexaware/DevOps_Engineer.md)

- what is the command for auto approval in terraform
- Write sample terraform code (overall skeleton)
## Source: [IBM/Cloud_Engineer.md](../IBM/Cloud_Engineer.md)

- If changes have been made to an instance via the UI and you run terraform apply without first running terraform plan, what will happen? Will there be an error, and will it still execute?
- Suppose another DevOps engineer on your team has made changes to an instance via the UI, and you then run the terraform plan command. What will be the output?
- What do the "+" and "−" symbols mean in the terraform plan output ?
- What does the tfstate file actually do?
- What is a tfstate file?
- What is Terraform, and how does it work?
- Where do you run your Terraform code—on your local system or on a specific server in your organization?
- Where do you store the tfstate file in your organization?
## Source: [IBM/DevOps_Engineer_2.md](../IBM/DevOps_Engineer_2.md)

- Q7: diff b/w terraform, cloudformation and arm and what would u prefer?
## Source: [IBM/DevOps_Engineer_3.md](../IBM/DevOps_Engineer_3.md)

- Terraform tf.state file is deleted how to recover it( conditions: it was not sync with s3 or any vcs to take a backup)
- Write a terraform script to create EKS Cluster.
## Source: [Infosys/DevOps_Engineer_1.md](../Infosys/DevOps_Engineer_1.md)

- 4 write sample terraform resource file
## Source: [Infosys/DevOps_Engineer_2.md](../Infosys/DevOps_Engineer_2.md)

- What is Terraform and how do you use terraform in your project and what all resources have you provisioned
## Source: [Infosys/DevOps_Engineer_3.md](../Infosys/DevOps_Engineer_3.md)

- What are the terraform modules you use
- Why terraform is used
## Source: [Infosys/SRE.md](../Infosys/SRE.md)

- What kind of experience do you have with Terraform?
## Source: [Intact_Green_Services/DevOps_Engineer.md](../Intact_Green_Services/DevOps_Engineer.md)

- 2 Instances are created using terraform. Statefile is located locally and also in remote backend(S3). If a user deletes 1 instance what would happen? How would you handle this?
## Source: [ITC_Infotech/DevOps_Engineer.md](../ITC_Infotech/DevOps_Engineer.md)

- How will you write terraform module for EKS.
## Source: [JPMorgan/DevOps_Engineer_senior.md](../JPMorgan/DevOps_Engineer_senior.md)

- Define a plan for blue/green deployment with rollback on Azure using Terraform and pipelines.
## Source: [JPMorgan/DevOps_SRE.md](../JPMorgan/DevOps_SRE.md)

- For example, if someone modifies a security group in Terraform and opens it to 0.0.0.0/0, what mechanisms can we use in Terraform to stop such changes from being applied?
- How would you handle Terraform state management for a team? Specifically, how would you store the tfstate file securely, make sure only one person can modify it at a time, and ensure the state is not tampered with? give me answers for all 3 qns
- Just like we use code-quality and security checks (quality gates, OWASP) before building an image, how can we prevent insecure infrastructure changes from being pushed using terraform?
- You’ve joined a company where a large production infrastructure was built manually and the previous engineers have left. How would you bring that existing infrastructure under Terraform management? Walk me through your plan
## Source: [Koerber_Pharma/DevOps_Engineer.md](../Koerber_Pharma/DevOps_Engineer.md)

- How will you connect your terraform environment from aws and implement CI/CD.
- How you are creating different environment in terraform.(dev,prod,test)
- If someone deleted a resource in terraform how can you identify it and recover it. how to detect some one deleted in tf how to rectifty
- terraform provisioner
- terraform uses real time issue we faced…what are the error u faced in terraform recently
- What is terraform work space and how are you managing it.
## Source: [LTIMindtree/DevOps_Engineer_1.md](../LTIMindtree/DevOps_Engineer_1.md)

- If we have created 3 instances using terraform script and the instance names are mentioned as a list
## Source: [LTIMindtree/DevOps_Engineer_3.md](../LTIMindtree/DevOps_Engineer_3.md)

- write terraform script for creating app service in azure or write terraform script to create lambda in aws
## Source: [Moodys/MLOps_Engineer.md](../Moodys/MLOps_Engineer.md)

- How do you set up infrastructure for deploying ML models using Terraform?
## Source: [Nextturn/DevOps_Engineer.md](../Nextturn/DevOps_Engineer.md)

- In Terraform, how would you create multiple EC2 instances, each with different configurations (for example, different instance types, AMIs, tags, or volumes)?
- Terraform – Difference between terraform refresh and terraform plan.
- Terraform vs Ansible – When to use each and how they work together.
## Source: [Nice/SRE_1.md](../Nice/SRE_1.md)

- What is modules in Terraform ?
- What is terraform how you configured your project ?
## Source: [Nice/SRE_2.md](../Nice/SRE_2.md)

- [ ] Are you familiar with Terraform?
- [ ] Can you describe a real-time scenario where you used Terraform to provision a highly scalable infrastructure?
## Source: [Nisum_Technologies/DevOps_Engineer.md](../Nisum_Technologies/DevOps_Engineer.md)

- what is difference between content and tuple in terraform?
- what is diffrence between list and string in terraform?
## Source: [Nitor_Infotech/DevOps_Engineer.md](../Nitor_Infotech/DevOps_Engineer.md)

- How do you handle infrastructure code for multiple environments using terraform
- State locking in terraform
- Terraform refresh command
## Source: [NUOS_INFO_Systems/DevOps_Engineer.md](../NUOS_INFO_Systems/DevOps_Engineer.md)

- How do you enforce Azure Policies (like tag or location restrictions) using Terraform at scale?
- How do you export Azure resources into Terraform code?
- How do you scale a Terraform pipeline that takes 25+ mins?
- Tech stack— mainly around Terraform, Azure, DevOps, Docker, and Git
- What happens to the Terraform state file if someone deletes resources from Azure?
## Source: [Optum/DevOps_Engineer.md](../Optum/DevOps_Engineer.md)

- How do you ensure particular AMI image is present in AWS account using terraform
- What are terraform provisioners
- What are the terraform lifecycle policies
- What is meta-arguments in terraform
- What is terraform external command and when it should be used
- Why do we use workspace in terraform
## Source: [Others/Cloud_Administrator_senior.md](../Others/Cloud_Administrator_senior.md)

- How are you provisioning infra using terraform via CI/CD
- Project specific questions(How would you setup a new environment on AWS, Terraform code provisioning)
## Source: [Others/DevOps_Engineer_1.md](../Others/DevOps_Engineer_1.md)

- In Terraform, what is the purpose of init, plan, and apply commands?
- What happens if the Terraform state file is accidentally deleted?
## Source: [Others/DevOps_Engineer_10.md](../Others/DevOps_Engineer_10.md)

- terraform state file locking
## Source: [Others/DevOps_Engineer_11.md](../Others/DevOps_Engineer_11.md)

- Difference between Iam users.. GitHub Oidc role and terraform io role.. which is secured and when to use use GitHub Oidc and when to use terraform io role
- What CICD is using in your project for terraform infrastructure.
- Write a terraform code to provision an Ec2
## Source: [Others/DevOps_Engineer_12.md](../Others/DevOps_Engineer_12.md)

- Create Terraform S3 resources, and ensure that the resource is deleted automatically after 7 days ?
- What is Terraform lifecycle management, and what does it does ?
## Source: [Others/DevOps_Engineer_13.md](../Others/DevOps_Engineer_13.md)

- Can the same Terraform code be used for different cloud providers?
## Source: [Others/DevOps_Engineer_15.md](../Others/DevOps_Engineer_15.md)

- How do you manage the state file in terraform and where do you store it?
## Source: [Others/DevOps_Engineer_16.md](../Others/DevOps_Engineer_16.md)

- least privileage in cft for the stacks and terraform
- then cloudformation and terraform differences
## Source: [Others/DevOps_Engineer_2.md](../Others/DevOps_Engineer_2.md)

- Can u pls write terraform file to provision the Ec2 instance in a public subnet in a VPC?
## Source: [Others/DevOps_Engineer_3.md](../Others/DevOps_Engineer_3.md)

- ) If the tfstate file is lost, what do you do? With & without backup?
## Source: [Others/DevOps_Engineer_4.md](../Others/DevOps_Engineer_4.md)

- I have created an EC2 instance through Terraform. I don't have a backup of the Terraform state file, it is not in the remote state and locally not available. Now when I do apply, what can I do?
- What are the provisioners available in Terraform and can you explain the use cases?
- What is the difference between a map of objects in Terraform and how can you write an example?
## Source: [Others/DevOps_Engineer_5.md](../Others/DevOps_Engineer_5.md)

- AWS event bridge creation and setup via terraform
## Source: [Others/DevOps_Engineer_6.md](../Others/DevOps_Engineer_6.md)

- What is lock file in Terraform.
- What is state file in Terraform.
## Source: [Others/DevOps_Engineer_7.md](../Others/DevOps_Engineer_7.md)

- About Ansible,Terraform
## Source: [Others/DevOps_Engineer_8.md](../Others/DevOps_Engineer_8.md)

- Write a Terraform code to create multiple S3 buckets
## Source: [Others/DevOps_Engineer_9.md](../Others/DevOps_Engineer_9.md)

- Terraform script to provision an EC2 instance with a custom security group and user data script.
## Source: [Persistent_Systems/DevOps_Engineer_2.md](../Persistent_Systems/DevOps_Engineer_2.md)

- Suppose there are 1000 of lines in terraform, as a period of time it grows, it becomes slow in future, how to approach this issue, please explain
- What is the module approach in terraform, explain on it
## Source: [Persistent_Systems/DevOps_Engineer_3.md](../Persistent_Systems/DevOps_Engineer_3.md)

- Explain terraform move command?
- Explain terraform statefile
- What is terraform state mv?
## Source: [Plansource_ValueLabs/DevOps_Engineer.md](../Plansource_ValueLabs/DevOps_Engineer.md)

- How you manage varibles in pipeline for terraform for different enevironments(dev/live/feture)
## Source: [Qburst/DevOps_Engineer.md](../Qburst/DevOps_Engineer.md)

- How can you handle terraform different environments?
- Is it possible to move terraform state file to remote configuration once created?
- Terraform provisioned resource should not delete by deleteing resource configuration in terraform code how can you do it?
## Source: [Qentelli_Solutions/DevOps_Engineer.md](../Qentelli_Solutions/DevOps_Engineer.md)

- create s3 bucket with terraform
- How you maanage resources in terraform
## Source: [Rapidsoft/DevOps_Engineer.md](../Rapidsoft/DevOps_Engineer.md)

- Terraform has errors while provisioning infrastructure. How to do investigate those? Basically how do you validate the terraform file
## Source: [RelevantZ/DevOps_Engineer.md](../RelevantZ/DevOps_Engineer.md)

- suppose there are 100 lines of code am writing in terraform, I want to avoid it, how do I achieve it
- suppose there are multiple persons executing terraform commands, what problem will happen
- what is terraform drift
- you have two environments, I should not deploy anything on one environment and another environment infrastructure should deploy via terraform, what strategy you will use
## Source: [Sapient/DevOps_Engineer.md](../Sapient/DevOps_Engineer.md)

- Explain Terraform state file –
- In which file you will define where Terraform state file should be generated and where it has to be maintained (which config file)?
- What are modules in Terraform?
## Source: [Sigmoid/DevOps_Engineer_2.md](../Sigmoid/DevOps_Engineer_2.md)

- If terraform deployment got failed, what will be the approach
- Purpose of using "null resource" in Terraform
- Terraform taint
- You created a resource through Terraform but it failed during provision, what will happen
## Source: [Sigmoid/DevOps_Engineer_3.md](../Sigmoid/DevOps_Engineer_3.md)

- How to enable Debug logs in Terraform
## Source: [Sigmoid/DevOps_Engineer_4.md](../Sigmoid/DevOps_Engineer_4.md)

- Explain what are terraform workspaces, what is the main requirement to use them.
- How is data block different from resource block in terraform. Explain a scenario in which both of them are used in conjunction.
- There is a requirement as part of some new integration in terraform managed resources, where couple of resources needs to be completely out of terraform lifecycle and they completely need to be handled manually. Come up with a solution to approach this without causing disruption to those resources, so that they are untouched and are not destroyed while also making it independant resource.
- There was an issue last time with some config changes in TF resource which had lead to slight downtime of the AWS resource during apply. What might have caused this downtime, how do you handle this in terraform for futurue config changes, for ensuring least possible downtime and maximum possible availability. Write a terraform code to handle this situation.
- What is taint in terraform, give a scenario where you need to use taint , explain how it works.
## Source: [Sonata_Software/DevOps_Engineer_1.md](../Sonata_Software/DevOps_Engineer_1.md)

- have you ever used terraform cloud
- how do you upgrade an module in terraform
- how will write terraform module
- share your screen and write terraform structure please
- what is the time you will take to write an IAC code and deploy to app service ?
## Source: [Sonata_Software/DevOps_Engineer_2.md](../Sonata_Software/DevOps_Engineer_2.md)

- Can you tell me what is Data Block in Terraform?
- Have you worked on Terraform?
- How do you handle multiple environments in Terraform?
- Say I created an S3 bucket using Terraform and want to modify the bucket name. Is it possible? How would you do this?
- Terraform Questions
- What are modules in Terraform?
## Source: [Sony/DevOps_Engineer.md](../Sony/DevOps_Engineer.md)

- Describe a production failure caused by terraform apply. What guardrails would you implement to prevent it permanently?
- Explain how Terraform handles dependency graphs internally. How can circular dependencies still appear in real projects?
- How do you safely refactor a Terraform monorepo with hundredsgg of state files into a module-based architecture without downtime?
- How would you manage Terraform when multiple teams deploy to the same AWS account but must not overwrite each other’s resources?
- If I want to start an ec2 instance once the cpu is utilised 80% what terraform code will you write and it also should copy the image from S3.
## Source: [SquareOps/DevOps_Engineer.md](../SquareOps/DevOps_Engineer.md)

- 🧱 Terraform
- 🧱 Terraform Advanced
- Did you use console, CLI, or Terraform?
- outputs.tf?
- providers.tf?
- Q18. Terraform generated RDS password, you didn’t save it. Can you retrieve it?
- Q19. Do you know what a custom Terraform module is?
- Q21. What is in main.tf?
- Q23. Have you used Terraform?
- variables.tf?
- Where does Terraform store generated values?
## Source: [Syncortex/Release_Engineer.md](../Syncortex/Release_Engineer.md)

- How will you implement multi region Terraform code
## Source: [Synechron/DevOps_Engineer_1.md](../Synechron/DevOps_Engineer_1.md)

- What is terraform drift command
## Source: [Synechron/DevOps_Engineer_2.md](../Synechron/DevOps_Engineer_2.md)

- Explain to me Terraform architecture ?
## Source: [TCS/SRE_1.md](../TCS/SRE_1.md)

- What is a Terraform state file interpreter?
- What to do if a terraform apply takes too much time?
## Source: [TCS/SRE_2.md](../TCS/SRE_2.md)

- What is Terraform drift?
## Source: [Techdome/DevOps_Engineer.md](../Techdome/DevOps_Engineer.md)

- Terraform provisioners.
- Terraform statefile
## Source: [UST/Cloud_Platform_Engineer.md](../UST/Cloud_Platform_Engineer.md)

- If somebody has deleted the Terraform state file locally, what can be done?
- If something is created on the cloud platform and it is not present in Terraform, how will you achieve it?
- Terraform apply is creating all the resources again. What can be the possible problem?
- Write Terraform code to create an AWS EC2 instance and include variables for instance_type and region.
- You need to create 50 instances in one go. How will you create them in Terraform?
## Source: [Virtusa/Tech_Lead.md](../Virtusa/Tech_Lead.md)

- difference between cloud formation and terraform
- suppose there are multiple ec2 instances manually created via console, I have to update those ec2 instances via terraform, what is the command
- what is module in terraform
- what is the terraform command for unlock statefile
## Source: [Wipro/DevOps_Engineer_2.md](../Wipro/DevOps_Engineer_2.md)

- Could you elaborate your experience with automating and optimizing the deployment over large infrastructure using AWS and other tools like Terraform and Ansible from your previous roles?
## Source: [Wipro/DevOps_Engineer_4.md](../Wipro/DevOps_Engineer_4.md)

- ⁠did you come across a scenario where you used terraform destroy
- ⁠explain your terraform modules
- They were mainly looking for terraform and Aws experience
- What commands you know in terraform
## Source: [ZopSmart/DevOps_Engineer.md](../ZopSmart/DevOps_Engineer.md)

- what are the commands do you know in terraform?
- what do terraform init
- what do terraform Terraform plan?
## Source: [ZS_Associates/DevOps_Engineer.md](../ZS_Associates/DevOps_Engineer.md)

- For each in terraform. Explain with an example
- How do you implement state locking in terraform
- I have made some changes in the module for one resource, the resource should get updated but it should not get destroyed and recreated again when we do terraform apply. How would you approach
- If you want to deploy EC2 instances in 3 different region what would the terraform code structure look like
