# Kubernetes Interview Questions

Questions: 470

## Source: [Accenture/DevOps_Engineer.md](../Accenture/DevOps_Engineer.md)

- How do you set up RBAC in Amazon EKS?
- If secrets are created in AWS Secrets Manager, how can Amazon EKS access those secrets?
- You have created an IAM user in AWS and configured role-based access in EKS. How do you bind the IAM user to the EKS role?
## Source: [Accion_Labs/SRE.md](../Accion_Labs/SRE.md)

- How do you ensure high availability in Kubernetes?
## Source: [Accolite/DevOps_Engineer.md](../Accolite/DevOps_Engineer.md)

- Explain kubernetes Architecture and component and their uses.
## Source: [Alphadyne/DevOps_Engineer_1.md](../Alphadyne/DevOps_Engineer_1.md)

- One major production Kubernetes issue that I solved and still remember.
## Source: [Alphadyne/DevOps_Engineer_2.md](../Alphadyne/DevOps_Engineer_2.md)

- Object used to manage kubernetes cluster and ensure pod always has specific resources
## Source: [Altimetrik/SRE.md](../Altimetrik/SRE.md)

- Question : Considering you have different environments and you have one application or which is microservice which is finally going to get deployed into one of the pod in GKE,
- Question : You have optimized Kubernetes deployment configs. So can you explain me what have what was the role and what what have you done there?
- right? So how it is basically getting deployed in cluster? I mean the deployment is basically failing just on the pod is currently in the error state. It is getting terminated. So how are you going to troubleshoot those such kind of Kubernetes issues?
## Source: [Amadeus_Labs/SRE.md](../Amadeus_Labs/SRE.md)

- 11 . Can pod be scheduled if have below security constent .
- How Kubernetes handles service discovery can you explain .
- How to access application if Ingress is configured but not accessible to end users, how you will resolve ?
- How to fix pod-level autoscaling not happening, what will be your approach .
- suppose we have application configured with hpa where it was running fine but suddenly it is not running what will be your approach?
## Source: [Amazon/DevOps_Consultant_1.md](../Amazon/DevOps_Consultant_1.md)

- Limiting the resource usage in k8s not through deployment.yam → Through namespace
- Purpose of using CNI in K8s
- Updating worker nodes in k8s
## Source: [Amazon/DevOps_Consultant_2.md](../Amazon/DevOps_Consultant_2.md)

- How about the sticky session data if POD gets down → Yes the session data will be lost,
- If DB POD is down, will it affect the data it gets stored,
## Source: [AMEX/DevOps_Engineer.md](../AMEX/DevOps_Engineer.md)

- how did you troubleshoot the pod crashback loop
- how the end point authentication works in kubernetes
- whats the difference between docker and kubernetes
## Source: [Arrise_Solutions/DevOps_Engineer.md](../Arrise_Solutions/DevOps_Engineer.md)

- C name and namespace in docker
- CoreDNS in k8s
- How does kube-proxy communicates with nodes
- K8s architecture
- Purpose of scheduler in k8s
- What’s the purpose of CNI
## Source: [Aspire/DevOps_Engineer.md](../Aspire/DevOps_Engineer.md)

- How to find orphan resources in kubernetes and remove it?
## Source: [Blue_Yonder/DevOps_Engineer.md](../Blue_Yonder/DevOps_Engineer.md)

- • How do you do you integrate And EntraID with your AKS for authentication?
- • How do you make your AKS cluster highly available.
- • How do you perform cost optimization in AKS.
- • How do you secure your AKS cluster?
- • How do you use Azure Key vault's secrets in AKS?
- • How will the application(container/pod) fetch the latest(rotated) secrets form azure vault.
- • HPA triggers (what and all types of triggers you have used in HPA so far)
## Source: [Capgemini/DevOps_Engineer_1.md](../Capgemini/DevOps_Engineer_1.md)

- How to assign memory to pod and how to make sure if pod should not get memory constraint. What to do if it happens.
## Source: [Capgemini/DevOps_Engineer_2.md](../Capgemini/DevOps_Engineer_2.md)

- How to limit resources in Kubernetes?
- How to run 2 pods with one depending on another – how to set roles?
- kubectl apply command – how the services are used?
- Reason for taint in worker nodes
- Type of error in pod label
- What is taint and toleration?
- What is the architecture of Kubernetes?
## Source: [Capgemini/DevOps_Engineer_3.md](../Capgemini/DevOps_Engineer_3.md)

- Different types of services in Kubernetes.
- If your pod is in Pending state, then what are your troubleshoot steps?
- In a multi-cloud environment, if you want to block a pod to go into a particular node, how would you do it?
## Source: [CGI/DevOps_Engineer.md](../CGI/DevOps_Engineer.md)

- Database connection from a pod is not working only for you. How will you troubleshoot?
## Source: [Cisco/DevOps_Engineer.md](../Cisco/DevOps_Engineer.md)

- Explain the upgrade process for a Kubernetes cluster with zero downtime.
- Jenkins pipeline setup Kubernetes If a pod is getting restarted constantly, what steps are you going to follow?
- Terraform scripts for creating AWS services Jenkinsfile EKS and On Prem Kubernetes cluster upgrade steps.
## Source: [CMT/SRE.md](../CMT/SRE.md)

- architecture of Kubernetes
- how would you maintain high availability in ecs + fargate or eks
## Source: [CTS/DevOps_Engineer_2.md](../CTS/DevOps_Engineer_2.md)

- Difference between daemonset and state full set
- How will you know if a network policy is enabled or not in k8s
## Source: [CTS/DevOps_Engineer_3.md](../CTS/DevOps_Engineer_3.md)

- Did you configure Ingress and Egress rules?
- How did you write deployment files w.r.t microservices in your project and how did you configure services and ingress?
- What have you done in Kubernetes?
## Source: [Deloitte/DevOps_Engineer_1.md](../Deloitte/DevOps_Engineer_1.md)

- What are the node groups you used in AWS EKS?
- What are the types of node groups in AWS EKS?
## Source: [Deloitte/DevOps_Engineer_2.md](../Deloitte/DevOps_Engineer_2.md)

- Explain the folder structure of a basic Helm chart. What commands do you use to deploy with Helm?
- How do you create and manage Kubernetes clusters (using tools like Terraform), and what are the master and worker nodes?
- How do you handle authentication for EKS clusters and store secrets securely in your environment?
- How do you manage and connect services like DBs, EC2, EKS, or ECS? Include the command to connect to ECS.
- What are common Kubernetes errors you’ve faced (like CrashLoopBackOff, ImagePullError), and how did you resolve them?
- What is email signing and Helm chart signing? Which tools do you use to sign Helm charts?
- What is the command to access a pod and how can you define or create a Kubernetes class or object?
## Source: [Deloitte/DevOps_Engineer_3.md](../Deloitte/DevOps_Engineer_3.md)

- Difference between EKS and ECS?
- Explain me the high level architecture of Kubernetes?
- Generally when two or more pods are available how do you manage the load balancing? are you sure you'll be using ALB
- What are all the prerequisites for you to setup a EKS cluster with 2 worker nodes and some x no of pods?
## Source: [Deloitte/DevOps_Engineer_4.md](../Deloitte/DevOps_Engineer_4.md)

- What is the major issue that you resolved in Kubernetes
- What is your Terraform file structure for vpc, eks
- What will you do for zero-downtime when eks cluster upgrade
## Source: [Emphasis/DevOps_Engineer_1.md](../Emphasis/DevOps_Engineer_1.md)

- Explain Kubernetes architecture
- What is ingress in Kubernetes
## Source: [Encora/DevOps_Engineer.md](../Encora/DevOps_Engineer.md)

- architecture of Kubernetes
- crashloopbackoff – what are the setps you will follow to troubleshoot further
- how do you rotate the secrets in key vault and implement .pfx certificate in application gateway , along with ingress/controller in AKS
- what are the files present inside helm chart 19.what is CNI plugin
- what is daemonset and statefulset
## Source: [EPAM/DevOps_Engineer_1.md](../EPAM/DevOps_Engineer_1.md)

- How to Create and Use Custom Resources in Kubernetes
- what are name spaces in k8s
- what is difference between deployment and statefulset
- what is the ECS and eks
## Source: [EPAM/DevOps_Engineer_2.md](../EPAM/DevOps_Engineer_2.md)

- Diff b/w Fargate vs EKS worker nodes
- Updating EKS cluster
## Source: [EPAM/DevOps_Engineer_3.md](../EPAM/DevOps_Engineer_3.md)

- Can you explain how you would create a fully automated blue-green deployment in a Kubernetes-based microservices architecture?
- Explain the control plane components of Kubernetes and how you would harden them for production use.
- How do you implement and manage network policies in Kubernetes for strict inter-service communication?
- How do you implement GitOps in a Kubernetes environment?
- How do you manage secrets and config securely at scale in Kubernetes without compromising GitOps workflows?
- How would you integrate runtime threat detection in Kubernetes using tools like Falco or Sysdig?
- How would you scale a Kubernetes cluster horizontally across multiple regions and still ensure zero-downtime upgrades?
## Source: [EXL_Service/DevOps_Engineer.md](../EXL_Service/DevOps_Engineer.md)

- Explain the complete request flow when a user accesses www.ingress.com until the request reaches the application pod.
- If Git is already the source of truth, why do we need Argo CD? Why not deploy directly using the CI/CD pipeline with Helm or kubectl?
- Pods in different namespaces can communicate. How would you block that communication? Where would you implement the NetworkPolicy?
- Where do you store application configuration and secrets? (ConfigMaps, Kubernetes Secrets, HashiCorp Vault, etc.)
## Source: [EY/DevOps_Engineer_1.md](../EY/DevOps_Engineer_1.md)

- Asked about k8s ( deployment, services, and configs)
- Pod disruption budget
- Service mesh
## Source: [EY/DevOps_Engineer_2.md](../EY/DevOps_Engineer_2.md)

- Explain the Kubernetes architecture and how it works.
- How does Pod-to-Pod communication work?
- What is a ConfigMap in Kubernetes?
- What is a Deployment in Kubernetes?
- What is a Persistent Volume in Kubernetes?
- What is a Pod Disruption Budget?
- What is a Service in Kubernetes?
- What is a Service Mesh and how does it work?
- What is CrashLoopBackOff in Kubernetes?
## Source: [F5/Associate_Consultant.md](../F5/Associate_Consultant.md)

- Can I run POD inside master-node itself?,
- Have you deployed any security application on Kubernetes?
## Source: [Flentas/DevOps_Engineer.md](../Flentas/DevOps_Engineer.md)

- Have you upgraded the EKS cluster?
- I want to enable autoscaling in Kubernetes during high traffic. How will you scale both cluster
- limits of 4 vCPU / 16 GB and requests of 2 vCPU / 10 GB RAM, how many instances of the pod will
- nodes and pods?
- One node has 8 vCPU and 32 GB RAM. With pod autoscaling up to 4 replicas, each pod having
- What are requests and limits in Kubernetes?
- What is a Helm chart?
- What is a namespace in EKS?
- What is the difference between a Pod and a Container?
- When do we use VPA (Vertical Pod Autoscaler)?
- Why did you not deploy the frontend on S3 and CloudFront, and instead deployed it on EKS?
## Source: [HCL/DevOps_Engineer_2.md](../HCL/DevOps_Engineer_2.md)

- can we run 1 conatiner with 2 pods
- how to upgrade eks clusetr
- Supoose you have taked etcd backup and old vm corrupted ,can we create new vm with backup etcd ?
- suppose we have pods 2 running in rolling updates some are in deployments set and some pods are in statefull set , how rolling updates strategy will work here ?
- Suppose you have in satetfull 3 pods which having name mongo-0 , mongo-1, mongo-2 what happen if mongo-0 dies when new pod will create what will be pod new name ?
- what are steps to upgrade eks cluster
- what is etcd
- what is ingress controller
## Source: [HCL/DevOps_Engineer_3.md](../HCL/DevOps_Engineer_3.md)

- An init container comes up with the Kubernetes cluster ✅ (kubernetes)
- Compute reservation in manifest files ❌ (kubernetes)
- Taint and toleration in Kubernetes what it is ❌ (kubernetes)
- Wat is DaemonSet in Kubernetes and what default daemons comes up with Kubernetes ✅ (kubernetes)
## Source: [HCL/DevOps_Engineer_software.md](../HCL/DevOps_Engineer_software.md)

- In Kubernetes, how would you configure your deployment to double CPU allocation once usage crosses 70%?
## Source: [Hexaware/DevOps_Engineer.md](../Hexaware/DevOps_Engineer.md)

- what are the files available inside helm chart
- what is the output of helm chart
## Source: [IBM/Cloud_Engineer.md](../IBM/Cloud_Engineer.md)

- When deploying your application to Amazon EKS, what other services do you use along with it?
## Source: [IBM/DevOps_Engineer_1.md](../IBM/DevOps_Engineer_1.md)

- A Jenkins pipeline is randomly failing at the deployment stage to EKS. Logs show timeouts during kubectl apply.
- How to check the kubectl logs of a POD before it restarted
- How will you create HPA
- If you type kubectl get pods, what will happen in the backend.
## Source: [IBM/DevOps_Engineer_3.md](../IBM/DevOps_Engineer_3.md)

- How do pods interact with each other?
- In my EKS cluster 2 node groups are there before deploying pods , node group -2 is showing unhealthy why ? I do have all the permission to check, how to troubleshoot and step to avoid such situations on future.
- What issues did you face with EKS Cluster?
- What to do when the etcd from EKS goes down?
- Write a terraform script to create EKS Cluster.
## Source: [Infinite_Solutions/DevOps_Engineer.md](../Infinite_Solutions/DevOps_Engineer.md)

- how you are setting up ingress controller
- How you are taking backup kubernetes .
## Source: [Infosys/DevOps_Engineer_1.md](../Infosys/DevOps_Engineer_1.md)

- if application which you are trying to deploy with kubernets got crashed and you are not able to enter into pod what will be your approach
- what will be your approach if pod.yaml failed
## Source: [Infosys/DevOps_Engineer_2.md](../Infosys/DevOps_Engineer_2.md)

- ELB, Ingress questions
- If any pod/node goes down how do you troubleshoot/monitor that( via cluster and other monitoring tools)
- What are deployments, daemonset, statefulsets
- What is pod
## Source: [Infosys/DevOps_Engineer_3.md](../Infosys/DevOps_Engineer_3.md)

- Explain k8s architecture
- How many pods do you manage
- What do you work on k8s
- What is HPA and how do you implement it
- What is pod affinity
## Source: [Infosys/SRE.md](../Infosys/SRE.md)

- How were you managing your Kubernetes cluster through a helm file or the command line? Have you used Rancher or Argo CD?
- Suppose you have a Kubernetes cluster running and in the cluster there is an issue. You see that one of the pod is in the state - crashloopbackoff. So what could be the possible issues with the pod?
## Source: [Intact_Green_Services/DevOps_Engineer.md](../Intact_Green_Services/DevOps_Engineer.md)

- Can we use POD as an agent? What are the drawbacks if we do so?
- How do you deploy an application in Kubernetes?
- Type of services in Kubernetes, give their use case
## Source: [ITC_Infotech/DevOps_Engineer.md](../ITC_Infotech/DevOps_Engineer.md)

- How will you write terraform module for EKS.
- If your application is on EKS how the traffic flows if user hits the URL.
- What is difference between coreDNS and kube-proxy.
## Source: [JPMorgan/DevOps_Engineer_1.md](../JPMorgan/DevOps_Engineer_1.md)

- What is HPA
- What is the primary difference between ECS and EKS?
## Source: [JPMorgan/DevOps_Engineer_senior.md](../JPMorgan/DevOps_Engineer_senior.md)

- A user reports 10-second delays every 15 minutes in an app running on AKS. No code changes happened. How would you begin RCA?
- How would you set up an automated rollback strategy in Kubernetes for failed deployments?
- You see high CPU usage in one pod, but logs look clean. What next?
- You’ve deployed an app to Azure Kubernetes Service (AKS) and it fails health checks randomly. How do you debug this end-to-end?
## Source: [JPMorgan/DevOps_SRE.md](../JPMorgan/DevOps_SRE.md)

- Apart from actuator health-check endpoints, what other checks can you perform using Kubernetes probes?
- If a pod’s liveness or readiness probe is failing, how would you troubleshoot the issue?
- If an application has only one replica and you perform a rolling restart, will there be downtime? Also what events occur during the pod restart can you explain the sequence step by step?
- You have an application with 2 replicas. During a rollout, the first pod is successfully replaced, but when the second pod is being replaced it enters a CrashLoopBackOff state. At that moment, which pod will the load balancer route traffic to the new pod, the old pod, or both? explain
- You have two running pods in a Kubernetes cluster, but they are unable to communicate with each other. There are no errors in the logs or events, and both pods appear healthy. How would you troubleshoot and restore communication between them?
## Source: [Koerber_Pharma/DevOps_Engineer.md](../Koerber_Pharma/DevOps_Engineer.md)

- how to shecedlue a pod in specifc node
- K8s architecture, services, if application pod fails how to troubleshoot
## Source: [L_and_T/DevOps_Engineer.md](../L_and_T/DevOps_Engineer.md)

- can we delete pod and multipilte container can run in
- How you are managing secrets in kubernetes
- What is ingress controller
## Source: [LTIMindtree/DevOps_Engineer_2.md](../LTIMindtree/DevOps_Engineer_2.md)

- K8s architecture
## Source: [LTIMindtree/DevOps_Engineer_3.md](../LTIMindtree/DevOps_Engineer_3.md)

- create 3 different images and store it in ecr or acr, deploy to eks or aks - write kubernetes yml files
## Source: [LTIMindtree/DevOps_Engineer_4.md](../LTIMindtree/DevOps_Engineer_4.md)

- How do you handle when pod dies
- How do you upgrade your eks
## Source: [LTIMindtree/DevOps_Engineer_L2.md](../LTIMindtree/DevOps_Engineer_L2.md)

- How do you troubleshoot a pod that is stuck in CrashLoopBackOff?
## Source: [Morgan_Stanley/Release_Engineer.md](../Morgan_Stanley/Release_Engineer.md)

- Ingress vs Egress
## Source: [NatWest_Group/DevOps_Engineer.md](../NatWest_Group/DevOps_Engineer.md)

- how did u manage Kubernetes pods it is on Linux right?
## Source: [Netcracker/DevOps_Engineer.md](../Netcracker/DevOps_Engineer.md)

- Application is configured with Ingress but the webpage is not loading ? What are the steps will be checked
- Custom resource in k8s
- Diff between Nodeselector, node affinity VS Taint, toleration
- For junior team member, what are the roles will be provided in k8s
- I've two PODS in diff worker nodes, can they communicate ?
- I've two PODS in the same worker node, will they communicate with each other?
- Storage classes in k8s
- Upgrading the worker nodes in K8s
- What is ingress
- What's the purpose of using storage class in k8s
- While updating your worker node, you're trying to perform drain out the PODs but some PODs are not removed from the node, what you will do
## Source: [Nextturn/DevOps_Engineer.md](../Nextturn/DevOps_Engineer.md)

- Describe your approach to troubleshooting Kubernetes worker node issues beyond the basic kubectl commands.
- Kubernetes – Troubleshoot a Pod stuck in Pending, CrashLoopBackOff, or ImagePullBackOff.
- Kubernetes – Troubleshoot a worker node that goes down.
- What are the common reasons for a Kubernetes node becoming NotReady, and how would you identify the root cause?
- You have a Kubernetes cluster with 30 nodes. 29 nodes are Ready, but 1 node is NotReady. You have already checked kubectl logs, kubectl describe, and other basic commands. How will you troubleshoot the node further?
## Source: [Nice/SRE_1.md](../Nice/SRE_1.md)

- How do you handle the HELM chart ?
## Source: [Nice/SRE_2.md](../Nice/SRE_2.md)

- [ ] In Kubernetes, how do you manage application deployment, scaling, and rollback? Can you walk through a specific scenario?
## Source: [Nisum_Technologies/DevOps_Engineer.md](../Nisum_Technologies/DevOps_Engineer.md)

- If you pod is not running, how do you troubleshoot it?
## Source: [Nitor_Infotech/DevOps_Engineer.md](../Nitor_Infotech/DevOps_Engineer.md)

- How have you implemented RBAC in your EKS setup
- Networking in kubernetes, how have you implemented
- Statefulset, daemonset, Deployment
## Source: [NPCI/DevOps_Engineer.md](../NPCI/DevOps_Engineer.md)

- Kubernetes:
## Source: [NUOS_INFO_Systems/DevOps_Engineer.md](../NUOS_INFO_Systems/DevOps_Engineer.md)

- Logs are incomplete — how would you troubleshoot across AKS, Ingress, App, and Infra?
## Source: [One2N/DevOps_Engineer.md](../One2N/DevOps_Engineer.md)

- Docker Swarm/Kubernetes
- How would HPA with stateful set work
- HPA implementation in detail
## Source: [OPT_IT/DevOps_Engineer.md](../OPT_IT/DevOps_Engineer.md)

- HAVE YOU WRITTEN ANY KUBERNETES MANIFEST FILES,WHAT ARE THE KINDS YOU WROTE
- If dbs are in private subnets how do you deploy in kubernetes
## Source: [Oracle/DevOps_Engineer_2.md](../Oracle/DevOps_Engineer_2.md)

- How do you give access to the user for a namespace in kubernetes cluster
- What are the kubernetes resources you know
- What is ingress and why are you using istio ?
## Source: [Oracle/DevOps_Engineer.md](../Oracle/DevOps_Engineer.md)

- Configmap VS secrets
- Explain me all the components present under deployment.yaml file
- How to deploy a POD into a certain NODE?
- Pod Distribution budget in k8s
- Stateful vs deployment in k8s
- What's the purpose of using init containers in K8s
- When you're trying to deploy a POD, it's throwing an error, how will you investigate.
## Source: [Orion_Innovation/DevOps_Engineer.md](../Orion_Innovation/DevOps_Engineer.md)

- i have an local laptop, I want to access my hosted website, what service will be used in K8s
- in Kuberenets there are 10 worker nodes, I have to deploy tomcat on each pods , how will you achieve it
## Source: [Others/Cloud_Administrator_senior.md](../Others/Cloud_Administrator_senior.md)

- EKS cluster upgrade entire process
- How would you implement security for Kubernetes(both on container side and the infra side using native Kubernetes solutions)
- If you are implementing HPA for statefulsets if new pod comes the pvc would be empty? How would it be able to serve the request?
- Kubernetes architecture in depth. Every component functioning. How would you join a new node to control plane?
- Like kubelet is there any similar agent used to manage the control plane side of things?
- Pod is in pending state. Reasons?
- When would prefer on-prem Kubernetes cluster over EKS and vice-versa
- When would you implement HPA and VPA. Give an example
## Source: [Others/DevOps_Engineer_1.md](../Others/DevOps_Engineer_1.md)

- In Kubernetes, if a pod is in a pending state, how do you troubleshoot?
## Source: [Others/DevOps_Engineer_10.md](../Others/DevOps_Engineer_10.md)

- What happens if etcd stops working
## Source: [Others/DevOps_Engineer_12.md](../Others/DevOps_Engineer_12.md)

- Can you explain the Kubernetes architecture and its components ?
- What are the services in Kubernetes have ?
- What is the difference between Liveness and Readiness Probes in Kubernetes ?
- What is the difference between Pod and Deployment in Kubernetes ?
- What would you recommend: NodePort Service or LoadBalancer Service in Kubernetes and why?
## Source: [Others/DevOps_Engineer_13.md](../Others/DevOps_Engineer_13.md)

- What is the difference between a Deployment and a StatefulSet in Kubernetes?
## Source: [Others/DevOps_Engineer_14.md](../Others/DevOps_Engineer_14.md)

- Have u done k8s cluster upgrade
- k8s node pending state how to debug
- pod is pending state, due to disk issue, how to resolve
- u r unable to evict the pods from node, how to resolve
- what is kubernetes operator? If I need to run a shell script before any container to start how can i do it using operator ?
- What is the extra component/service present in Managed k8s cluster in cloud
## Source: [Others/DevOps_Engineer_15.md](../Others/DevOps_Engineer_15.md)

- How can I map SSL certificates to the ingress file ?
- How does service mesh work and any experience?
- if there are multiple pods, how do they identify each other ?
- Ingress vs ingress controllers
- K8s architecture and argocd architecture
- Pod is running fine, all the parameters looks good, but the traffic is not reaching the pod when the user is trying to access the application, what could be the possible reason ?
- Pod to pod communication
- What errors you faced when you're working with k8s
## Source: [Others/DevOps_Engineer_16.md](../Others/DevOps_Engineer_16.md)

- How will you provide access to only one pod/app to a storage account and restrict all the other pods within AKS
- Out of 32 GB memory AKS cluster, 30 GB is already utilized, Whether a new pod with request 500mb and resource limit of 4Gi can be scheduled in the same cluster using HPA/VPA
- What are the alternate ingress controllers you suggest as Nginx IGC is deprecated
## Source: [Others/DevOps_Engineer_2.md](../Others/DevOps_Engineer_2.md)

- How many containers can run in a pod?
- in ur projects how many containers u ran? can u give me the use case where can run 4-5 containers in a pod?
## Source: [Others/DevOps_Engineer_3.md](../Others/DevOps_Engineer_3.md)

- "Route 53", and "EKS and DB Automation and Administration"
- ) How to roll back a failed deployment in Docker & K8s?
- ) In K8s, as etcd is a key-value store db, can write something manually on it?
- ) There are 1 Master & 3 Worker nodes- if the master fails, what happens? Will pods keep running or they will crash?
## Source: [Others/DevOps_Engineer_4.md](../Others/DevOps_Engineer_4.md)

- I have an Ingress object that is not routing the traffic to the Kubernetes cluster. What are the reasons and how do you troubleshoot that?
- Pods fail to schedule
- What are the different types of secrets in Kubernetes?
- What are the different ways to specify the probes in Kubernetes?
- What is the difference between EKS vs ECS vs Fargate?
- What is the difference between scaling and autoscaling in Kubernetes?
- When I deploy the pods, it should be deployed on large and medium. Nodes, except small. How can I configure that?
## Source: [Others/DevOps_Engineer_5.md](../Others/DevOps_Engineer_5.md)

- Design the deployment of the pod with replica set set as 3 and having apache httpd image running as a container.
- Design the kubernetes cluster with Ingress.
- How to use the secrets in kubernetes? What encryption methods do you use?
- What will be the command to add the annotation and the labels for the existing pod?
## Source: [Others/DevOps_Engineer_6.md](../Others/DevOps_Engineer_6.md)

- Architecture of Kubernetes.
- Difference between PV/PVC in Kubernetes.
- How you can use the existing Image into the YAML file to deploy a POD.
- Namespaces in Kubernetes.
- Types of Service in Kubernetes.
- Use case of Node-Port and Cluster IP service Type in Kubernetes.
- What is PDB in Kubernetes.
- What is POD in Kubernetes.
- What is Taint/Tolerent.
- Why Kube-let and Kube-proxy is used for in Kubernetes.
## Source: [Others/DevOps_Engineer_7.md](../Others/DevOps_Engineer_7.md)

- About Kubernetes architecture
- U handled any debug/troubleshoot for kubernetes?
## Source: [Others/DevOps_Engineer_8.md](../Others/DevOps_Engineer_8.md)

- Do you know what is HPA?
- Have you worked on the Kubernetes?So what deployment strategy are you following?
- suppose you deploy one application okay and you found some issue, you wanted to roll back using the kubernetes how you roll back to the particular version, what is the command?
- What is the stateful set in the Kubernetes?
## Source: [Others/SRE.md](../Others/SRE.md)

- Commands used for Kubernetes,Docker and Ansible..
- Explain Kubernetes Structure, Config Map and Schedular..
## Source: [Persistent_Systems/DevOps_Engineer_1.md](../Persistent_Systems/DevOps_Engineer_1.md)

- How do you upgrage k8s cluster.
- HPA & VPA.
- K8s Architecture.
- Pod Affinity and Node Affinity.
## Source: [Persistent_Systems/DevOps_Engineer_2.md](../Persistent_Systems/DevOps_Engineer_2.md)

- In azure monitor which metrics is used for monitoring kubernetes
## Source: [Persistent_Systems/DevOps_Engineer_3.md](../Persistent_Systems/DevOps_Engineer_3.md)

- How do you ensure POD to POD communication?
- How do you scale EKS? What are the metrics considered and where do you add your inputs and How? Explain how you have done auto-scaling in your project
- If you are given a project eg EC2 or EKS or anything else what are the things you would take into consideration from prerequisite till output?
- What is ECS & EKS and when would you choose either of it?
- What is hierarchy of Kubernetes?
## Source: [Persistent_Systems/DevOps_Engineer_4.md](../Persistent_Systems/DevOps_Engineer_4.md)

- Can you write a Jenkinsfile for a Node.js application to build, push Docker image, and deploy to Kubernetes? Please also explain it in detail.
## Source: [Plansource_ValueLabs/DevOps_Engineer.md](../Plansource_ValueLabs/DevOps_Engineer.md)

- how you scale your EKS cluster based metrics/logs
## Source: [Publicis_Global_Delivery/DevOps_Engineer.md](../Publicis_Global_Delivery/DevOps_Engineer.md)

- Kubernetes cluster upgrade from one version to another version? What is the approach?
- What is PDP in Kubernetes?
- You have one stateful application, that needs to be deployed specified node in k8s, how?
## Source: [Qburst/DevOps_Engineer.md](../Qburst/DevOps_Engineer.md)

- How can you can you migrate one node pool vms to another node pool in gcp?
- How can you restrict public access to load balancers either standalone or gke?
- K8s command to list the pods with specific nodes?
## Source: [Rapidsoft/DevOps_Engineer.md](../Rapidsoft/DevOps_Engineer.md)

- Explain terms in deployment.yml file in kubernetes
## Source: [RelevantZ/DevOps_Engineer.md](../RelevantZ/DevOps_Engineer.md)

- how do you login into pods using kubectl command
- tell me some commands on kubernetes – how do you troubleshoot it
## Source: [SAP/DevOps_Engineer.md](../SAP/DevOps_Engineer.md)

- Can we perform Blue Green deployment under the same namespace? If yes, how will you manage them?
- Suppose a new deployment was implemented, suddenly all the PODs (new and old ones) crashed, what's the reason for this ? → New deployment exhausted the resource limit, so we need to use "limit" in our deployment.yaml file
- You did a deployment with Canary, when you will delete the old pods, what are the KPIs to cross check before deleting them.
- You’re trying to schedule a new POD but the new PODs are not deploying properly, what checks will be done.
## Source: [Sapient/DevOps_Engineer.md](../Sapient/DevOps_Engineer.md)

- I have an S3 bucket, and there is some file inside it — my pod wants to access that S3 bucket. How will it access it?
- If your cluster is in a private subnet, then outside kubectl will not be working, right? How are you accessing that?
- In which subnet are you placing your EKS cluster and which networking components have you used?
- In which way are you managing your cluster — using kubectl commands or something else?
- What is EBS and EFS in Kubernetes?
## Source: [Sigmoid/DevOps_Engineer_1.md](../Sigmoid/DevOps_Engineer_1.md)

- K8s backup policies
## Source: [Sigmoid/DevOps_Engineer_2.md](../Sigmoid/DevOps_Engineer_2.md)

- *It should've a ReadinessProbe which executes the command 'stat /tmp/ready' . This means once the file exists the Pod should be ready.
- Have you integrated Global LB with K8s cluster
- How to limit the resource usage in K8s
- Terraform taint
## Source: [Sigmoid/DevOps_Engineer_3.md](../Sigmoid/DevOps_Engineer_3.md)

- Which deployment strategy is best, assuming that you have only one POD is running
## Source: [Sigmoid/DevOps_Engineer_4.md](../Sigmoid/DevOps_Engineer_4.md)

- As a Devops engineer , you have to make a decision according to best and optimized solution for each component that you decide, like - should the db be run as statefullset or RDS/any cloud db managed solution is better, how do we deploy frontend-whether as pod or S3+cloudfront etc.
- Consider there is a MySQl operator running in one of your pod in one of your node of a k8s cluster. How the Mysql database managed by this is different from the normal pod that is started with a mysql image from deployment/pod template? Apart from just handling the updates, version changes, lifecycle, vulnerabilitites , security issues, it provides lot more advantages, please explain the use cases by giving some scenarios.
- Explain each component in your architecture which is involved from a user requesting from the UI to the request reaching the backend pod, and how they are connecting with each other to ensure inbound and outbound flow(including the firewall, NACl, security groups, route tables etc).
- How is an end user able to access the app which is running inside pods of private subnet nodes.
- How will you alert if CPU usage stays above 90% for 5 minutes, but only if the number of running pods is below 5?
- If there was an issue introduced in recent deployment , then how do we rollback the deployment , is it just the kubectl rollout undo command , how does it know which image it should revert to,does it take from the image repo or somewhere else?
- What are operators in kubernetes. How is the Elasticsearch working , is there some Elastic operator involved?
- What is k8s API. Can you connect to a k8s API using REST api calls directly from any external app, like how kubectl connects to the API endpoints exposed on the kube API server?
- What is taint in terraform, give a scenario where you need to use taint , explain how it works.
- Why did you choose eks cluster over ecs.
- Why do we need extra load balancing capabilities like host based, path based routing etc to our pods, if services are anyways handling the traffic to route to right pod, what actuslly is the issue where just tradional standalone service cannot handle it. For example, if an end user is traversing accross various product details , how is frontend able to fetch details from the right pod (backend which in turn gets the actual product data from db), explain how the api calls to backend and to db is handled.
## Source: [Sonata_Software/DevOps_Engineer_1.md](../Sonata_Software/DevOps_Engineer_1.md)

- do you use helmchart for AKS deployements
- how do you monitor if pods goes down
- how do you protect your endpoints in AKS
- what is the networking you are using in AKS
## Source: [Sony/DevOps_Engineer.md](../Sony/DevOps_Engineer.md)

- Describe a real production incident where a misconfigured HPA caused cascading failure. How would you redesign autoscaling to avoid this?
- Design a multi-tenant Kubernetes platform where teams must not affect each other’s resource usage, network traffic, or upgrade cycles.
- How do you debug intermittent pod restarts when liveness probes pass, readiness passes, but the pod is still killed by the node?
- How do you guarantee zero‑downtime deployments in Kubernetes?
- How do you start troubleshooting when a Kubernetes cluster feels slow?
- How would you design a Kubernetes cluster that must survive a full AZ failure without data loss, while running stateful workloads at scale?
- How would you design container images for ultra-fast cold starts in serverless or autoscaled Kubernetes environments?
- How would you implement zero-trust networking inside Kubernetes without using a service mesh?
- So how do you guarantee zero downtime deployments in Kubernetes.
- What happens internally when etcd latency spikes above 500ms? How does it impact the scheduler, controllers, and API server?
## Source: [SquareOps/DevOps_Engineer.md](../SquareOps/DevOps_Engineer.md)

- → AWS Auth ConfigMap
- ☸️ EKS & Kubernetes
- 💾 Kubernetes Storage
- 🧠 Kubernetes Reliability & Troubleshooting
- Check ingress controller logs?
- Check pod replicas?
- Do you create EC2/EKS/ECS resources?
- Do you handle IAM + RBAC in Kubernetes?
- Do you use autoscaling (HPA)?
- How do you bootstrap kubectl access?
- How do you deploy to EKS through GitHub Actions?
- Is rollback handled by CI/CD or Kubernetes?
- Q10. Can a public Helm chart be customized?
- Q11. How do you add extra Kubernetes manifest files to a public Helm chart?
- Q12. How to implement shared storage across multiple pods running on multiple nodes in EKS?
- Q13. If there is one node but multiple pods, can we use EBS for shared storage?
- Q14. What is a Pod Disruption Budget (PDB)?
- Q15. What is your approach to debug a CrashLoopBackOff?
- Q16. During peak traffic, ingress controller is routing requests slowly. How do you debug it?
- Q17. Should we increase ingress controller replicas permanently or dynamically?
- Q3. On which compute platform are the applications hosted? (Expected: EKS)
- Q4. Have you created an EKS cluster? Explain the process.
- Q5. Have you upgraded an EKS cluster before? How?
- Q6. If your teammate also wants access to the same cluster through kubectl, what steps do you follow?
- Q7. In which Kubernetes resource do you map IAM users/roles?
- Show the folder structure of a Helm chart.
- What happens to old pods?
- What is aws-auth ConfigMap?
- When to use HPA?
- Why EKS over ECS?
## Source: [Syncortex/Release_Engineer.md](../Syncortex/Release_Engineer.md)

- How will take a backup of K8s clusters regularly
- How will you investigate POD failure
- Taint and Tolerations
- What are the parameters are used for HPA in K8s?
## Source: [Synechron/DevOps_Engineer_1.md](../Synechron/DevOps_Engineer_1.md)

- How to troubleshoot if pod is failed in AKS, commands please
## Source: [Synechron/DevOps_Engineer_2.md](../Synechron/DevOps_Engineer_2.md)

- Tell me about Docker Compose and Kubernetes ?
## Source: [Synechron/DevOps_Engineer_3.md](../Synechron/DevOps_Engineer_3.md)

- Can you describe the main components of a Kubernetes cluster and explain the role each one plays?
- Can you explain how you would deploy a Kubernetes application using Jenkins? What plugins or tools would you use?
- How do you monitor the health and performance of your Kubernetes pods in a production environment?
- What is Helm, and why do you prefer to use it for managing Kubernetes applications instead of deploying them normally?
## Source: [TCS/DevOps_Engineer_2.md](../TCS/DevOps_Engineer_2.md)

- what are all the deployment startgies you use in deployments in k8s , explain canary and blue green strategies
## Source: [TCS/SRE_1.md](../TCS/SRE_1.md)

- How does Kubernetes work — how do the master and worker nodes communicate, and what runs inside them?
- What is a PVC in Kubernetes?
- What is ConfigMap and Scheduler in Kubernetes?
- What is CrashLoopBackOff, and how do you troubleshoot it?
- What is the command for rolling back to a specific revision in Kubernetes?
- What is the difference between PV and PVC in Kubernetes?
- Why does a pod show a “Pending” status in Kubernetes?
## Source: [TCS/SRE_2.md](../TCS/SRE_2.md)

- If a pod is created with a Deployment and another with a StatefulSet, will the StatefulSet pod always remain on the same node?
- If we can run MySQL with a Deployment and PVC, why do we need a StatefulSet?
- What types of services exist in Kubernetes, apart from ClusterIP, NodePort, and LoadBalancer?
- Why do we need a StatefulSet when we can attach a PVC to a Deployment and make it stateful?
- Why does a pod created from a Deployment have two sets of random characters in its name?
## Source: [Techdome/DevOps_Engineer.md](../Techdome/DevOps_Engineer.md)

- Kubernetes architecture
## Source: [Verizon/DevOps_Engineer.md](../Verizon/DevOps_Engineer.md)

- Any reason why we cannot place our app pods in master node by default
- disadvantage of using ebs volumes in eks
- Etcd is sql or no sql database and reason
- how many clusters u have in ur project and how many pods in nodes
- In k8s architecture which component is not running as pod
- k8s QOS (quality of service)
- requests and limits in k8s
- what are the disadvantages of each deployment models in k8s
- what is context in k8s
- what version of k8s u used and did u perform any cluster upgrade
## Source: [Virtusa/Tech_Lead.md](../Virtusa/Tech_Lead.md)

- am having some min max pods running, suppose on festival day traffic increases at that time I have to increase pods, when no traffic is there I have reduce the pods, how will you achieve it in K8
- difference between deployement and replicaset and daoemonset and statefulset (what key words you will be writing over the, for ex : deployement.yml – rolling update, canary)
- what files will be present in helm chart
- what is node affinity and pod affinity in K8
- what is taint and tolerations in K8
## Source: [Volkswagen_Group_Digital/DevOps_Engineer.md](../Volkswagen_Group_Digital/DevOps_Engineer.md)

- what are all production issues that you faced in k8s?
## Source: [Wipro/DevOps_Engineer_1.md](../Wipro/DevOps_Engineer_1.md)

- Contents written inside deployment.yaml or heml chart
- How to deploy an app to k8s cluster in terms of app deploy only ( basically explain CD part)
- If secret is stored in vault inside a pod and that pod is down then how to tsg
- If there is file which is being used by 2 customers, and need to deploy that file in k8s cluster and on prem as well, how to do that?
## Source: [Wipro/DevOps_Engineer_2.md](../Wipro/DevOps_Engineer_2.md)

- Describe the security implications of using Kubernetes secret in etcd without encryption?
- How would you structure a multi-stage pipeline that builds, tests and deploys a containerized application to kubernetes using Github Actions.
## Source: [Wipro/DevOps_Engineer_3.md](../Wipro/DevOps_Engineer_3.md)

- If you have a Kubernetes cluster with pods running, but when you hit the URL you get HTTP errors (403, 404, 503), what would be your troubleshooting steps?
- Is a service mesh always needed, or are alternative tools sometimes enough?
- Since some features of service mesh are also available through other tools, is it worth adding the burden of installing Istio service mesh into the estate?
- What security measures and policies should be put in place when using a service mesh?
- When designing a microservices-oriented infrastructure, what technologies and components (like load balancer, service mesh, Kubernetes) would you bring in, and how would you design the estate?
- When you have many services in a service mesh, how do you decide the number of control planes and data planes needed?
## Source: [Wipro/DevOps_Engineer_5.md](../Wipro/DevOps_Engineer_5.md)

- In kubernetes a pod is going to crashloopbackoff, how do you troubleshoot.
- In pod configuration what we should do from Production perspective
- Kubernetes deployment done successfully but unable to access the application externally, how do you troubleshoot.
- When kubernetes node fails what will happen.
## Source: [Zensar/DevOps_Engineer.md](../Zensar/DevOps_Engineer.md)

- How configmap and secrets can be used in k8s
- If 2 pod are in diff namespace then how can we make them communicate to each other securely?
- What is etcd and its use
- What is ingress
- Why k8s is need if docker volume is there? (Dont remember exact Q framing but sounded like this)
## Source: [ZopSmart/DevOps_Engineer.md](../ZopSmart/DevOps_Engineer.md)

- how to implement authentication in k8s cluster?
- what are the commands do you know in k8s ?
- you are using K8S Cluster as open source s/w tool like in aws service which service is available to create K8S Cluster
## Source: [ZS_Associates/DevOps_Engineer.md](../ZS_Associates/DevOps_Engineer.md)

- A backend pod needs to interact with S3 and lambda. How would you achieve it
- A replica set has 3 pods. One pod is not coming up. What maybe be the reason
- After implementing HPA also some pods are in pending state. What maybe the reason
- Argo CD. How do you manage CI/CD in your organisation. How many EKS clusters you manage, no of nodes
- Calico and VPC CNI plugin difference. Why one is preferred over other. How would they help in setting up networking for pod.
- Can you deploy mongo db database in EKS cluster. If yes how and what all configuration things you would need to keep in mind
- How is an ip address allocate to a pod. Does CNI plugin use same CIDR range which is provided by VPC or different?
- How to handle the extra traffic coming onto pods? Which solution you can implement
- Ingress, Gateway API
- Possible reasons for pod to be stuck in Crashloopbackoff
- There are 3 backend pods in 3 different region. If one pod goes down how would the request be managed
- Two pods which are part of same replica set are not able to communicate with each other what may be the reason
- Want to create a module for EKS cluster. What would be the structure
