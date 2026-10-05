<div align="center">

# ADITYA CHOURASIYA

### DevOps · SRE · Cloud Infrastructure · CI/CD · Automation

<p>
  <a href="https://www.linkedin.com/in/aditya-chourasiya-4aa111249">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat-square&logo=linkedin&logoColor=white">
  </a>
  <a href="https://github.com/Rightplacecom">
    <img src="https://img.shields.io/badge/GitHub-Rightplacecom-181717?style=flat-square&logo=github&logoColor=white">
  </a>
  <a href="mailto:adityalearner6@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white">
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=Rightplacecom&label=Profile%20Views&color=0A66C2&style=flat-square">

</div>

---

## 👋 About

I'm a **BCA student focused on DevOps and Site Reliability Engineering**, with an interest in **cloud infrastructure, CI/CD automation, containerization, monitoring, and reliable production systems**.

I enjoy taking an application from:

**Code → Build → Test → Package → Deploy → Monitor → Recover → Improve**

My projects focus on automating engineering workflows, reducing deployment friction, and building infrastructure that is **reliable, observable, secure, and repeatable**.

---

## ✦ Selected DevOps / SRE Work

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ CI/CD Infrastructure

**DevOps · Jenkins · Automation**

A CI/CD environment designed to automate application delivery from source control to deployment.

**Engineering scope**

- Jenkins controller + agent architecture
- Automated build pipelines
- GitHub integration
- Multi-stage deployment workflow
- Health-check based deployment
- Secure credential management

<a href="https://github.com/Rightplacecom">
<b>View Projects →</b>
</a>

</td>

<td width="50%" valign="top">

### ☁️ AWS Infrastructure

**Cloud · Linux · Infrastructure**

Building and managing cloud infrastructure for application deployment and automation.

**Engineering scope**

- AWS EC2
- Linux server administration
- IAM
- Security Groups
- SSH-based infrastructure
- Cloud deployment workflows

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🐳 Containerized Applications

**Docker · CI/CD · Deployment**

Containerizing applications to create consistent environments across development and deployment.

**Engineering scope**

- Docker image creation
- Container lifecycle management
- Docker Compose
- Application packaging
- CI/CD container builds
- Deployment environments

</td>

<td width="50%" valign="top">

### 📊 Monitoring & Reliability

**SRE · Observability · Operations**

Exploring reliability practices for detecting failures and understanding application and infrastructure health.

**Engineering scope**

- Grafana
- Infrastructure monitoring
- Health checks
- Logs
- Metrics
- Service availability
- Failure detection

</td>
</tr>
</table>

---

## 🔄 DevOps Thinking

<div align="center">

| PLAN | BUILD | DEPLOY | OPERATE |
|:---:|:---:|:---:|:---:|
| 🎯 | ⚙️ | 🚀 | 📊 |
| Define workflow | Automate delivery | Release safely | Monitor systems |

</div>

### What I look for

**Reliability**
→ Can the system continue working when something fails?

**Automation**
→ Which repetitive manual operation can be automated?

**Deployment**
→ Can software be released consistently and safely?

**Observability**
→ Can we understand what is happening inside the system?

**Security**
→ Are credentials, permissions, and access properly controlled?

**Recovery**
→ What happens when deployment or infrastructure fails?

---

## 🧰 DevOps / SRE Toolkit

<table>
<tr>
<td width="33%" valign="top">

### Cloud

- AWS
- EC2
- IAM
- VPC
- Security Groups
- EBS
- Cloud Infrastructure

</td>

<td width="33%" valign="top">

### CI/CD

- Jenkins
- GitHub
- Jenkins Pipelines
- Webhooks
- Jenkins Agents
- Automated Builds
- Deployment Pipelines

</td>

<td width="33%" valign="top">

### Containers

- Docker
- Docker Compose
- Kubernetes
- Container Images
- Container Deployment
- Application Packaging

</td>
</tr>

<tr>
<td valign="top">

### Infrastructure

- Terraform
- Infrastructure as Code
- Variables
- Outputs
- Modules
- State Management
- AWS Provisioning

</td>

<td valign="top">

### Monitoring

- Grafana
- Metrics
- Logs
- Health Checks
- System Monitoring
- Service Monitoring
- Observability

</td>

<td valign="top">

### Systems

- Linux
- Ubuntu
- Networking
- SSH
- Bash
- Python
- Server Administration

</td>
</tr>
</table>

---

## 🏗️ DevOps Architecture

```text
                         DEVELOPER
                             │
                             ▼
                         GitHub
                             │
                             ▼
                    ┌─────────────────┐
                    │     Jenkins     │
                    │   Controller    │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │  Jenkins Agent  │
                    └────────┬────────┘
                             │
                 ┌───────────┼───────────┐
                 ▼           ▼           ▼
              Build        Test       Security
                 │           │           │
                 └───────────┼───────────┘
                             ▼
                         Docker
                             │
                             ▼
                           AWS
                             │
                             ▼
                       Deployment
                             │
                             ▼
                     Health Checks
                             │
                    ┌────────┴────────┐
                    │                 │
                  PASS              FAIL
                    │                 │
                    ▼                 ▼
                Production          STOP
                    │
                    ▼
                 Monitor
                    │
                    ▼
                 Grafana
