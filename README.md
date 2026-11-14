<div align="center">

# Hi, I'm Naveen Mamidi 👋

### AWS DevOps Engineer · Cloud Infrastructure Automation · CI/CD · Infrastructure as Code · Kubernetes

📍 Artesia, CA &nbsp;·&nbsp; 🟢 **Open to new opportunities**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naveenmamidinm)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:naveenmamidi1147@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-Download-2ea44f?style=for-the-badge&logo=readthedocs&logoColor=white)](#)

*(Resume link above is a placeholder — send me the file/URL and I'll wire it up.)*

</div>

---

## About Me

I'm an AWS and Linux DevOps Engineer with 4+ years of hands-on experience automating, deploying, and supporting production cloud infrastructure. I build Infrastructure as Code with Terraform, configuration management with Ansible, and end-to-end CI/CD pipelines with Jenkins, Git, Maven, and SonarQube — then ship the result as containerized applications on Docker, Kubernetes, and Helm.

I've led an on-premises-to-AWS migration, tightened IAM to least-privilege across environments, built high-availability/auto-scaling architectures, and kept production visible with CloudWatch, Splunk, and Nagios. I'm comfortable being the person paged at 2 AM — fast incident triage and root-cause analysis are as much a part of the job as writing the Terraform in the first place.

**At a glance**

- 🏢 4+ years across 3 enterprise client engagements — Siemens, Genisys, Solar Turbines
- ☁️ Full-lifecycle AWS delivery: greenfield builds *and* on-prem → cloud migration
- 🔁 CI/CD pipeline architecture: Jenkins, Terraform, Ansible, Docker, Kubernetes, Helm
- 🎓 AWS Certified Solutions Architect – Associate

---

## Core Competencies

**☁️ Cloud Infrastructure & Architecture**
Designing and provisioning AWS environments (EC2, VPC, subnets, route tables, IGW, security groups, S3, RDS, IAM, ELB/ALB, Auto Scaling, Lambda) using Terraform, with an emphasis on repeatable, version-controlled infrastructure over manual console changes.

**⚙️ CI/CD & Release Engineering**
Building Jenkins pipelines (scripted, Groovy, controller/agent architecture) integrated with Git, Maven, and SonarQube to automate build, test, quality-gate, and deployment stages across dev, QA, pre-prod, and prod.

**🐳 Containers & Orchestration**
Containerizing applications with Docker and operating microservices on Kubernetes (Pods, Deployments, ReplicaSets, Services), versioned and rolled back through Helm charts.

**🔧 Configuration Management & Cloud Migration**
Automating server configuration with Ansible playbooks/roles to eliminate environment drift, and running on-premises-to-AWS cloud migrations end to end — build-out, cutover, and post-migration validation.

**🔐 Security & Reliability**
Enforcing least-privilege IAM policies, designing for high availability and auto scaling, and managing backup/disaster recovery via EBS snapshots and volume management.

**📊 Observability & Incident Response**
Monitoring with CloudWatch (including custom metrics), Splunk log analysis, and Nagios; fast triage and root-cause analysis to keep incidents from becoming outages.

**🐧 Linux Systems Administration**
User/permission management, patching, and disk/memory/process troubleshooting, with Bash scripting to automate recurring operational tasks.

---

## Certifications

[![AWS Certified Solutions Architect – Associate](https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect%20--%20Associate%20(2026)-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](#)

---

## Professional Experience

### AWS DevOps Engineer · Shreyan IT Solutions Pvt Ltd — Hyderabad, India
**Nov 2019 – Sep 2023** · Consulting engineer delivering AWS DevOps work across three enterprise client engagements

<details>
<summary><strong>Client: Siemens</strong> — CI/CD Pipeline Automation & DevOps Release Management (Oct 2022 – Sep 2023)</summary>
<br>

`AWS` `Jenkins` `Terraform` `Ansible` `Docker` `Maven` `Git` `SonarQube` `Nagios` `Linux`

- Built end-to-end Jenkins CI/CD pipelines taking code from commit through quality checks, artifact creation, and deployment — one repeatable release path for dev, QA, and pre-production.
- Integrated Maven, Git, Docker, Terraform, and SonarQube into those pipelines so builds, infrastructure changes, and deployments ran as a single workflow instead of separate manual handoffs.
- Provisioned AWS environments on demand through Terraform jobs in Jenkins (VPC, EC2, RDS, ALB, Auto Scaling, IAM, S3, EBS), replacing ticket-based infrastructure requests with self-service, version-controlled builds.
- Replaced manual server setup with Ansible playbooks across dev/QA/pre-prod, keeping configuration identical between environments and removing drift as a source of failed releases.
- Enforced SonarQube quality gates on Maven builds, moving defect detection to build time instead of QA.
- Configured Nagios and CloudWatch checks across Linux servers, application services, and AWS resources to surface capacity and availability problems before users reported them.

</details>

<details>
<summary><strong>Client: Genisys</strong> — On-Premises to AWS Cloud Migration (Mar 2021 – Oct 2022)</summary>
<br>

`AWS` `Terraform` `Jenkins` `Ansible` `Git` `Maven` `Linux` `CloudWatch` `Splunk`

- Migrated applications and workloads from on-premises VMs to AWS — environment build-out, cutover, and post-migration validation — moving the business off fixed on-prem capacity.
- Codified the target AWS environment in Terraform (VPC, subnets, security groups, EC2, and supporting resources) so environments could be rebuilt identically instead of hand-assembled in the console.
- Deployed migrated applications onto managed AWS services (EC2, ELB, RDS, S3, Lambda, SQS, CloudFront) matched to each application's architecture, reducing the server footprint the team maintained.
- Rebuilt permissions around IAM roles and least-privilege policies, limiting each team/service to only the resources it needed.
- Instrumented AWS resources with CloudWatch alarms and notifications so degradation reached the team as an alert, not a user-reported outage.
- Traced recurring production failures through Splunk log analysis to fix root causes instead of repeatedly restarting services.

</details>

<details>
<summary><strong>Client: Solar Turbines</strong> — San Diego, CA · AWS Infrastructure Automation & Kubernetes Deployment (Feb 2020 – Mar 2021)</summary>
<br>

`AWS` `Jenkins` `Terraform` `Ansible` `Docker` `Kubernetes` `Helm` `Linux` `CloudWatch` `SNS`

- Automated the full AWS environment build in Terraform (VPC, subnets, route tables, IGW, EC2, RDS, S3, IAM roles, security groups, ELB, CloudWatch alarms) so environments were rebuilt from version control, not reconstructed manually.
- Scripted Jenkins pipelines in Groovy covering build, test, and deployment stages, giving every environment the same release path.
- Operated microservices on Kubernetes (Pods, Deployments, ReplicaSets, Services), handling rollouts, scaling, and pod-level troubleshooting.
- Versioned Kubernetes releases as Helm charts with source-controlled values, making any prior release recoverable in a single rollback.
- Extended CloudWatch with custom metrics for application memory/thread health and wired alarms to SNS, so the team was paged the moment a threshold broke.
- Administered Linux servers and automated recurring system/deployment tasks with shell scripts.

</details>

---

## Education

- **M.S., Computer Science** — Westcliff University, Irvine, CA *(2023 – 2026)*
- **Master of Computer Applications** — JKC College (Autonomous), Andhra Pradesh, India *(2019 – 2021)*
- **B.S., Computer Science** — JKC College (Autonomous), Andhra Pradesh, India *(2016 – 2019)*

---

## Tech Stack

**Cloud Platform (AWS)**

![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![EBS](https://img.shields.io/badge/EBS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazoniam&logoColor=white)
![ELB/ALB](https://img.shields.io/badge/ELB%2FALB-8C4FFF?style=flat-square&logo=amazonaws&logoColor=white)
![Auto Scaling](https://img.shields.io/badge/Auto%20Scaling-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![SQS/SNS](https://img.shields.io/badge/SQS%2FSNS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-8C4FFF?style=flat-square&logo=amazoncloudfront&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazoncloudwatch&logoColor=white)

**CI/CD & Version Control**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Groovy](https://img.shields.io/badge/Groovy-4298B8?style=flat-square&logo=apachegroovy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)

**Infrastructure as Code & Configuration Management**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**Systems & Scripting**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Monitoring & Logging**

![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Nagios](https://img.shields.io/badge/Nagios-000000?style=flat-square&logo=nagios&logoColor=white)

---

## Currently Sharpening

- Advanced AWS multi-account architecture and Well-Architected patterns
- Kubernetes deployment workflows and Helm chart authoring
- Terraform module design and remote state management
- DevSecOps fundamentals — shifting security checks left in the pipeline

---

## GitHub Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=NaveenMamidiAWSDevOps&show_icons=true&theme=default)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=NaveenMamidiAWSDevOps&layout=compact&theme=default)

</div>

---

<div align="center">

### 📬 Let's Connect

I'm actively exploring **AWS DevOps / Cloud Infrastructure Engineer** roles. If you're hiring or just want to talk shop about Terraform, Kubernetes, or CI/CD — reach out.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naveenmamidinm)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:naveenmamidi1147@gmail.com)

</div>
