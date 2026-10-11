kunal**@**cloud:\~$

[architecture](#arch)[projects](#projects)[skills](#skills)[journey](#journey)[contact](#contact)

Open to work · Pune · Relocating to Hyderabad, Mumbai, Chennai

# Hi, I'm Kunal. I build & secure cloud infrastructure.

Fresher Cloud Support, Linux Administrator and NOC Engineer. Trained in Multi-Cloud with DevOps at Naresh IT, Hyderabad, with hands-on AWS projects: a live 3-tier app on a custom VPC and a Jenkins CI/CD pipeline.

[View projects](#projects)[GitHub ↗](https://github.com/Kunal-Karale)[Hire me](#contact)

**$** whoami\
kunal-karale\
**$** cat role.txt\
*Cloud Support | Linux Admin | NOC*\
**$** aws sts get-caller-identity\
skills: EC2 S3 IAM VPC RDS\
**$** curl -I https://dhopaticloud.in\
HTTP/2 *200 OK*\
**$**

**3-Tier**live app on AWS, 2 AZs

**8**layered Security Groups

**0**public SSH ports (SSM only)

**SAA**AWS certification in progress

// flagship

## SKYBASE request flow

Every request follows this path: two Availability Zones, private tiers, HTTPS on a custom domain, and no public SSH.

// work

## Projects

Built by hand in the AWS console and on Linux servers. Source is on my GitHub.

### SKYBASE: 3-Tier Infrastructure on AWS flagship · Aug 2026

A web, app and database architecture on a custom VPC, live at dhopaticloud.in over HTTPS.

- Custom VPC, 2 AZs, public/private subnets, IGW, NAT, route tables
- Web tier (Nginx + React) and app tier (Node.js + PM2) connected to RDS MySQL
- Internal and external ALBs with Auto Scaling Groups on both tiers
- Route 53 custom domain + ACM SSL certificate
- 8 least-privilege Security Groups; IAM + SSM Session Manager replace public SSH

VPCEC2RDSALBASGRoute 53ACMSSMIAMNginxNode.js

[View on GitHub ↗](https://github.com/Kunal-Karale/SKYBASE-PROJECT)

### CodeFlow / AUTO-SHIP CI/CD DevOps

Automatic build, code quality and deployment of a Java application through a CI/CD pipeline.

- Jenkins master-slave on 2 EC2 instances
- GitHub → Maven build → SonarQube analysis
- .war artifacts stored in Amazon S3
- Hands-off deploy to Apache Tomcat; Ansible used for deployment

JenkinsMavenSonarQubeS3TomcatAnsible

[View on GitHub ↗](https://github.com/Kunal-Karale/AUTO-SHIP-PROJECT)

### LAMP Stack Hosting Linux

Frontend and backend application hosted on a classic Linux, Apache, MySQL, PHP stack.

- Apache web server configuration
- MySQL database for the backend
- PHP application served on Linux

LinuxApacheMySQLPHP

[View on GitHub ↗](https://github.com/Kunal-Karale/LAMP-Stack-Project)

Also on GitHub: [devops-scripts](https://github.com/Kunal-Karale/devops-scripts), a forked collection of shell scripts for DevOps practice.

// toolbox

## Skills

Strongest where I have shipped projects. Tools beyond that come from my course and practice labs.

### AWS hands-on

EC2 · S3 · IAM · VPC · RDS · Route 53 · ACM · CloudWatch · ALB · Auto Scaling · SSM

Proficiency

### Linux hands-on

Ubuntu · CentOS · users and permissions · services · Nginx · Apache · shell scripting

Proficiency

### Networking solid basics

TCP/IP · DNS · subnetting · routing · NAT · load balancing · Security Groups

Proficiency

### CI/CD & DevOps project-based

Git · GitHub · Jenkins · Maven · SonarQube · Ansible · Nexus

Proficiency

### Containers & IaC trained

Docker · Kubernetes · Terraform

Proficiency

### Monitoring & Multi-Cloud trained

Prometheus · Grafana · CloudWatch · Azure · GCP

Proficiency

Git**›**Jenkins**›**Maven**›**SonarQube**›**Nexus**›**Docker**›**Kubernetes

// path

## Learning journey

**AWS Certified Solutions Architect – Associate**In progress · expected 2026

**Cyber Awareness AI Basic**NIIT Foundation · Cyber Suraksha Plus · Mar 2026

**Multi-Cloud with DevOps**Naresh IT, Hyderabad · completed

**B.Sc. Computer Science**Annasaheb Magar Mahavidyalaya, Hadapsar, Pune

**HSC (61.50%) · SSC (73.20%)**Residential Highschool, Shevgaon

// let's talk

## Looking for a Cloud Support, Linux or NOC fresher?

I can start on a support or NOC desk from day one and keep learning on the job.

[dhopaticloud@gmail.com](mailto:dhopaticloud@gmail.com) +91-8087566195 [LinkedIn ↗](https://linkedin.com/in/kunal-karale) [GitHub ↗](https://github.com/Kunal-Karale)

© 2026 Kunal Namdev Karale · Pune, Maharashtra