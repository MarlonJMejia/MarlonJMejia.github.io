<header>
:::: title

# Marlon Mejia
::::
::: download

**Download in** [PDF](resume.pdf) || [DOCX](resume.docx)
:::

::: contact

**Phone:** [1-631-480-7675](tel:1-631-480-7675) | **E-Mail:** <a href="mailto:marlon.junior.mejia@gmail.com">marlon.junior.mejia@gmail.com</a> | **LinkedIn:** [marlon-mejia](https://www.linkedin.com/in/marlon-mejia/) | **Github:** [marlon-mejia](https://github.com/MarlonJMejia)
:::
</header>

<aside>

::: Skills

# Skills

### Tools:

>Terraform, Ansible, Docker, Active Directory<br>
AWS CodePipeline, Github Actions, Jenkins

### Operating Systems:

>Linux, Windows

### Programming:

> Bash, Python, Powershell

### Software:

> Jira, Grafana, Splunk, Humio

:::

::: certifications

# Certifications

- [RHCSA](https://rhtapps.redhat.com/verify?certId=220-057-368) - Apr 08, 2022
- [EX200 Red Hat Certified System Administrator](https://rhtapps.redhat.com/verify?certId=220-057-368) - Apr 08, 2022
- [AWS SAA-C03](https://www.credly.com/badges/838a30cd-0701-4069-b4be-68fe22d6962a) - March 31, 2023
- [Comptia Security+](https://www.credly.com/badges/136d58c4-24d3-4487-aad5-c51e120a3e7f) - November 02, 2020
- [Comptia A+](https://www.credly.com/badges/89fca521-f3de-4c36-90f5-7552f9c4c26e) - May 22, 2020
- API Security Architect - Jan 20 2024

:::
</aside>
---

<main>

# Bloomberg LP 
**Datacenter Operations Engineer**  
*Nov 2020 - Present*

- **Issue Diagnosis and Resolution**:
  - Addressed Layer 1 & 2 connectivity issues across 1000+ servers, switches, routers, and firewalls.
  - Resolved system issues across various operating systems, including Windows and Linux (Red Hat, Debian) to ensure consistent and reliable functionality.
- **Automation and Scripting**: Collaborated with hardware vendors to automate case opening and log gathering on multiple systems and network devices using **REST APIs** and **Python**, reducing operation time from 10 minutes to 30 seconds, resulting in approximately 823 hours saved per year.
- **Legacy Systems Modernization**: Contributed to the modernization of legacy programs, scripts, and applications, as well as the overhaul of outdated documentation on GitHub. Used **Python**, **Bash**, and markup languages to improve functionality, maintainability, and support collaborative content updates across teams in multiple sites.
- **Containerization**: Developed over 50 **Dockerfiles** to containerize applications, facilitating consistent deployment and testing of Python programs and Bash scripts.
- **Incident Management**: Utilized **Jira** to plan, track, support tickets, and manage incidents, ensuring efficient resolution.
- **Monitoring and Analysis**: Oversaw operating systems and network hardware across datacenters, tracking disruptions, resource utilization, and power consumption using **Grafana**, **Splunk**, and **Humio**.
- **Cross-Team Collaboration**: Collaborated across multiple functional and technical teams to deliver Agile-based projects, ensuring seamless communication and coordination.
- **Data Center Optimization**: Executed regular audits of data center operations, identifying improvement opportunities and implementing strategies to enhance performance and reduce costs.
- **Documentation Modernization**: Modernized legacy documentation to align with current industry standards while enhancing operational efficiency through advanced **Bash** and **Python** automation tools.
- **System Maintenance and Upgrades**: Managed routine maintenance, including hardware upgrades, firmware updates, and patch management, to ensure peak system performance.

# NYI - New York Internet
**Datacenter Technician**  
*Jul 2020 - Nov 2020*

- **Core Responsibilities**: Possess comprehensive knowledge of network operations center functions, including network management, server monitoring, system administration, network system testing and troubleshooting, network analysis and enhancements, preventative maintenance, and network security.

- **Customer Support**: Provide remote hands and technical support for clients, performing tasks such as mounting KVM switches, hot-swapping drives, cross-connecting cables, moving cables, rebooting devices, configuring equipment, and offering expert advice and recommendations for optimizing client device performance.

- **Network Monitoring**: Utilize tools such as LogicMonitor, ConnectWise, and Meraki to monitor over 1000+ pieces of onsite equipment for outages, circuit issues, switch and router interface problems, and networking issues like DDoS attacks, abuse reports, and DNS record discrepancies. Quickly respond to and resolve incidents and outages in the environment.

- **Automation**: Developed Python scripts to automate Google Drive tasks, including copying, editing, and uploading spreadsheets, documents, and files.

- **Hardware Management**: Expertly mount and rack servers, switches, and routers in client cabinets, ensuring organized and efficient setups through methodical cable and power management. Perform racking/stacking, decommissioning of hardware, RJ45 cabling, and fiber cable runs. Test copper and fiber cable runs using Fluke equipment.

- **Customer Interaction**: Regularly engage with customers, offering professional and welcoming communication. Inform clients about new services and provide general tips to enhance their experience with our department.

- **Documentation**: Maintain detailed documentation for client servers, in-house servers, and personal methodologies for task execution. Ensure clear and thorough internal messages are left to facilitate seamless task handover to colleagues.


</main>
----

# Side Projects

### CI/CD Project for AWS and GitHub Pages

- **Objective**: Developed a robust CI/CD pipeline to automate the deployment of a static website hosted on AWS.
- **Technologies Used**:
  - **AWS Services**: Utilized S3 for object storage, CloudFront for content distribution, and Route 53 for domain and DNS management. Implemented SSL certificates using AWS Certificate Manager for enhanced security.
  - **Development**: Created content in Markdown for ease of editing and used `pandoc` to convert Markdown files into multiple formats such as PDF and DOCX.
  - **Automation**: Implemented CI/CD pipelines using CodePipeline and GitHub Actions to automate the deployment and testing processes, ensuring seamless updates and multi-format document generation.
- **Outcome**: Achieved a streamlined and automated workflow for static website deployment and maintenance, resulting in increased efficiency and reduced manual intervention.

### Reverse Proxy Setup on Oracle Cloud for Local Service Access via Wireguard

- **Objective**: Designed and automated the deployment of secure and scalable cloud infrastructure on Oracle Cloud.
- **Technologies Used**:
  - **Image Creation**: Utilized Packer to create a golden image for Wireguard VPN, ensuring consistent and secure deployments.
  - **Infrastructure as Code**: Employed Terraform to provision and manage cloud resources on Oracle Cloud.
  - **Configuration Management**: Leveraged Ansible to automate the installation and configuration of Wireguard VPN and NGINX on the provisioned infrastructure.
  - **Reverse Proxy**: Configured the provisioned infrastructure to securely route traffic to a Grafana local endpoint and a local website hosted behind a Wireguard connection between an OPNsense firewall and the OCI instance.
  - **Security**: Installed CrowdSec on OPNsense to enhance protection for the reverse proxy and mitigate potential security threats.
- **Outcome**: Delivered a highly automated and reliable infrastructure setup, enhancing security and performance for local-hosted services while reducing manual configuration efforts.

### Automated Provisioning with Proxmox, Terraform, and Ansible

- **Objective**: Streamlined the provisioning and configuration of LXC and VM instances on Proxmox to enhance infrastructure management.
- **Technologies Used**:
  - **Provisioning**: Employed Terraform to automate the provisioning of LXC containers and VM instances on Proxmox.
  - **Configuration Management**: Utilized Ansible to configure and manage the instances post-provisioning, ensuring consistent setup and operational efficiency.
  - **Backups**: Implemented regular backups using **Kopia**, with infrastructure code stored in GitHub for version control and recovery.
- **Outcome**: Achieved a more efficient and automated infrastructure setup, reducing manual intervention and improving consistency in instance configuration.
