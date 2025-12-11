The ideal candidate will be responsible for:
automating and streamlining operations and processes, 
building and maintaining tools for deployment, monitoring, and operations, 
troubleshooting and resolving issues in our development and Production environments.
 
Key Responsibilities:
  Implement, and maintain CI/CD pipelines using tools like Jenkins, GitHub Actions
  Manage infrastructure (On-prem or AWS) 
  Monitor system performance and availability.
  Collaborate with development and QA teams to ensure smooth deployment and integration.
  Automate routine tasks and improve system reliability and scalability.
  Ensure security best practices are followed in deployment and infrastructure management.
  Participate in incident response and root cause analysis.
  Support production rollouts / deployments
  Support production issues during odd hours
 
Required Skills & Qualifications:
  Bachelor’s degree in Computer Science, Engineering, or related field.
  2-3+ years of experience in DevOps
  Experience in scripting languages (e.g., Bash, Python, PowerShell).
  Experience with CI/CD tools and version control systems (e.g. Git / Bitbucket / GitHub).
  Hands-on experience with containerization.
  Understanding of VMware / AWS.
  Familiarity with monitoring and logging tools.
  Knowledge of security and compliance standards.
 
Preferred Qualifications:
  Certifications in AWS, Docker, VMware.
  Familiarity with configuration management tools (e.g., Ansible).
  Exposure to Agile and DevOps practices.
  Handling of Virtual Machines / Containers
 
Soft Skills:
  Strong problem-solving and analytical skills.
  Excellent communication and collaboration abilities.
  Ability to work in a fast-paced, team-oriented environment.

========================================================

* automating and streamlining operations and processes | Automate routine tasks | (Ansible, crond, shell scripting)
* CI/CD pipelines using Jenkins
* Manage infrastructure on AWS 
* Monitor system performance and availability.
* Ensure security best practices are followed
* Support production rollouts / deployments (kubernetes / containerization)
* scripting languages Python
* Familiarity with configuration management tool (Ansible)
* Knowledge of security and compliance standards.
========================================================
Linux - DNS, Networking, Processes, CPU, LVM, boot process, 
Aws
Docker
Kubernetes
Python
Monitoring
Ansible
Git / GitHub
CICD Jenkins (Maven, Nexus, ECS, )
========================================================
Day-2-Day tasks:

* As part of my day-2-day work I start with daily standup as we follow agile methodology, where I update what work I've done and if I block I will explain the reason the thing I've tried in my trobleshooting and looking for help on xyz thing.
* Once the daily standup is done I will head to Jira and see what are the tasks assisgned to me and I will look for high priority tasks.
* So, I was part of the Avaya's "Meeting Server" project where I work on the CI/CD pipelines using Jenkins as we have multiple repositories in the project for multiple microservices and I am one of the key member to build and maintain cicd pipelines.
* Apart from that my major activities includes writing terraform codes to provision infrastructure to deploy kubernetes cluster, as the application was in its initial phase lots of requests comes to provision the infrastructure so all the ticktes are assigned to me.
* I also create terraform modules to re-use the code and put it into the centralized location.
* Apart from that all our application are deployed to Aws which is our primary cloud platform so I work on various Aws services and also on the observability part.
* I also worked majorily on the tasks to automate maunaul tasks with the help of ansible. 
* Meanwhile we have a meetings with the Manager for the sprint planning, I actively participate in them.
* Towards the end of the day, I try to update the Jira trackers as my collegues might got reference from them. Especially our management are very focused on Jira so I try to update everything I done.
========================================================
* Avaya's meeting server is a application like zoom meet or google meet used by the US goverment officials for their daily meetings.
* The application is run onto multiple mircroservices on kubernetes platform hosted on the Aws.
========================================================
Q: Current Ansible tasks I have worked on and issue I have faced ?

Ansible   	- 
Terraform 	- 
Kubernetes 	-  
========================================================
DNS - Domain network system:  Translate ip to domain and domain to ip
========================================================
1. attach space in a volume, steps ?
2. any project in which you have appraised ?
3. any major challenge in the production you have faced ?
4. How do you handle jira story vs tickets ?
5. what happens if you dont have state file back and state file deleted?
6. ansible - send a certificate to 50 servers, steps? 
7. Any question for us?
======================================================

* kubernetes CRD's
* crossplane
* terraform modules
* terraform backend
* python aws cli integration and functions 
* aws terraform integration permissions IAM role
* monitoring prometheus query
* flux cd / GitOps approach
* Jfrog repositories - image storage
* python boto3 with aws
==============================
* what happens if facing latency in service hosting in kubernetes.
* aws private subnet instance traffic
* terraform backend.
* what all can be done with aws s3
* bastion server aws
* terraform python integration
* we want to create web service how we will start ?
* Monitoring
=====================================================================================================
* how to containerize application in docker image (python app)
* write jenkins file
* stages of jenkins file
* for each and count in terraform
* how to maintain multiple state files in terraform for 3 diff environments
========================================================================================================================
helm charts - own helm charts 
kubernetes - crds, statefulsets, taints tolerations, pod affinity,- main focus (application deployement)
aws - s3, eks, iam, sqs, rds, vpc,
argocd - not manadatory
cicd with helm
terraform basics
monitoring - prometheus, grafana, alets, query, performance metrics, (no cloudwatch)

-------------
Docker:

* Compare bridge, host, and overlay networks in Docker. When would you use each?
* A container is in “Restarting” state repeatedly — what’s your step-by-step approach to debug?
* Explain the use of cgroups and namespaces inside Docker to enforce resource limits.

Kubernetes:

* Explain how the Kubernetes handles a node failure?
* How does Kubernetes handle network communication between pods across nodes?
* Compare Deployments, StatefulSets, and DaemonSets. Give examples of when each is appropriate.
* How would you parameterize and version-control a complex Helm chart across multiple environments?
* A pod is running but cannot connect to another service. Walk through your debugging process.
* Explain how RBAC and NetworkPolicies work together for a zero-trust cluster setup.
* How does the Horizontal Pod Autoscaler (HPA) work internally? What are its limitations?
* Role of helpers.tpl in helm, conditional and function , what is define and include in helpers.tpl file.

Tell me about your day to day activity?
Tell me the how to deployment happen on k8s?(CD)
How the helm chart is deployed on k8s ?
what is helm _helpers.tpl?

I want deploy first postreSQL after that application helm chart should install?

How to achieve high availablity for application.
what is VPA k8s?

how to scale nodes in k8s cluster?
How QA team will know that after deployment application is ready to serve traffic?

I want to deploy the 1-application helm chart to 2-different namespace with different versions?how to achieve this?

what are different services in k8s?
what is ingress controller?
Having 1-major project under that having 8-9 similar code microservices, how to create helm chart with optimize manner?
I want to deploy 1-application with high availability on k8s ? How to acheive this? and One pod replica should run on every node of k8s?

# Find vimo in a given string. "Order of vimo characters should be followed in the string"
# Example 1 -> gvaabvsiaaamjjjjtkkkro -> Yes
# Example 2 -> aavaambhihjojjj -> ‘m’ is coming after ‘v’ which is an invalid case.
# Example 4 -> zzzzzzbbbvxxxxxiyyyymzzkkkobbbnntyyyyyar -> Yes
# Example 5 -> zzzzzzbbbvxxxxxiyyyyomzzkkksbbbnnyyyyyo -> No

# You can use any IDE to write this code


Create a bash script that:
Monitors system log files in /var/log
Implements log rotation for files larger than 100MB
Keeps a maximum of 5 rotated log files
Compresses rotated logs

============================================================================================================================
