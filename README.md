## Module summary of the AWS Academy Cloud Foundations Course (ACFv2EN‑48161) including comparisons to equivalent services and terminology in Microsoft Azure and Google Cloud Platform (GCP):

---

### **Module 1: Introduction to Cloud Computing**

**AWS Focus:**

* Definition of Cloud Computing
* Benefits: scalability, elasticity, agility, cost-efficiency
* Cloud deployment models: Public, Private, Hybrid
* Cloud service models: IaaS, PaaS, SaaS

**Azure Equivalents:**

* Similar models and terminology
* Azure calls Public Cloud "Azure Global", offers Azure Stack for hybrid
* Azure services like Virtual Machines (IaaS), App Services (PaaS), Microsoft 365 (SaaS)

**GCP Equivalents:**

* Similar models
* Google Cloud’s hybrid solution: Anthos
* GCP Compute Engine (IaaS), App Engine (PaaS), Google Workspace (SaaS)

---

### **Module 2: Cloud Economics and Billing**

**AWS Focus:**

* Pay-as-you-go pricing
* Total Cost of Ownership (TCO)
* AWS Pricing Calculator
* Consolidated Billing and Cost Explorer
* AWS Free Tier

**Azure Equivalents:**

* Azure Pricing Calculator, Cost Management + Billing
* Azure TCO Calculator
* Azure Free Account with \$200 credit for 30 days + limited free services

**GCP Equivalents:**

* GCP Pricing Calculator
* GCP Cost Management tools
* GCP Free Tier includes always-free services and \$300 credit for 90 days

---

### **Module 3: AWS Global Infrastructure**

**AWS Focus:**

* Regions, Availability Zones, Edge Locations
* Data centers and global redundancy

**Azure Equivalents:**

* Regions, Availability Zones, and Edge Zones
* Azure Front Door and CDN for edge content

**GCP Equivalents:**

* Regions and Zones (GCP doesn't use the term Availability Zones, but "zones" are equivalent)
* GCP Cloud CDN and edge networking

---

### **Module 4: Cloud Security**

**AWS Focus:**

* Shared Responsibility Model
* IAM (Users, Groups, Roles, Policies)
* Encryption and Compliance

**Azure Equivalents:**

* Azure Active Directory (IAM equivalent)
* Shared Responsibility Model is consistent
* Azure Key Vault, Azure Policy

**GCP Equivalents:**

* Cloud Identity & Access Management (IAM)
* Shared Responsibility Model
* Cloud Key Management Service (KMS), Cloud Audit Logs

---

### **Module 5: Networking and Content Delivery**

**AWS Focus:**

* VPC, Subnets, Route Tables, Internet Gateways, NAT
* Load Balancing (ALB, NLB)
* Amazon CloudFront

**Azure Equivalents:**

* Virtual Network (VNet), Subnets, Route Tables, NSG
* Azure Load Balancer, Application Gateway
* Azure CDN

**GCP Equivalents:**

* VPC Network, Subnets, Routes, Internet Gateway
* Google Cloud Load Balancing
* Cloud CDN

---

### **Module 6: Compute Services**

**AWS Focus:**

* Amazon EC2
* Auto Scaling and Elastic Load Balancing
* AWS Lambda (serverless)

**Azure Equivalents:**

* Azure Virtual Machines
* Virtual Machine Scale Sets + Load Balancer
* Azure Functions (serverless)

**GCP Equivalents:**

* Compute Engine
* Managed Instance Groups + Load Balancing
* Cloud Functions (serverless)

---

### **Module 7: Storage Services**

**AWS Focus:**

* Amazon S3 (object), EBS (block), EFS (file)
* Storage classes and lifecycle policies

**Azure Equivalents:**

* Blob Storage (object), Managed Disks (block), File Storage (file)
* Azure Storage lifecycle rules

**GCP Equivalents:**

* Cloud Storage (object), Persistent Disk (block), Filestore (file)
* GCP Object Lifecycle Management

---

### **Module 8: Databases**

**AWS Focus:**

* Amazon RDS (relational)
* Amazon DynamoDB (NoSQL)
* Amazon Aurora
* Amazon Redshift (data warehouse)

**Azure Equivalents:**

* Azure SQL Database, Azure Database for PostgreSQL/MySQL
* Cosmos DB (NoSQL)
* Azure Synapse Analytics (data warehouse)

**GCP Equivalents:**

* Cloud SQL (relational), Cloud Spanner (scalable relational)
* Firestore / Datastore (NoSQL)
* BigQuery (data warehouse)

---

### **Module 9: Cloud Architecture**

**AWS Focus:**

* Well-Architected Framework (Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, Sustainability)
* High Availability, Fault Tolerance, Scalability

**Azure Equivalents:**

* Microsoft Azure Well-Architected Framework
* Availability Sets/Zones, Azure Monitor, Autoscale

**GCP Equivalents:**

* Google Cloud Architecture Framework
* High availability via multi-zone and regional services
* Cloud Operations suite (formerly Stackdriver)

---

### **Module 10: Cloud Support and Resources**

**AWS Focus:**

* AWS Support Plans
* Documentation, whitepapers, training resources
* AWS Trusted Advisor and AWS Personal Health Dashboard

**Azure Equivalents:**

* Azure Support Plans
* Microsoft Learn, Azure Advisor, Service Health

**GCP Equivalents:**

* GCP Support Tiers
* Google Cloud Skills Boost, Cloud Support Center, Recommender, Health Dashboard

---

### Summary Table (Quick Reference)

| **Service Category** | **AWS**                      | **Azure**                    | **GCP**                                   |
| -------------------- | ---------------------------- | ---------------------------- | ----------------------------------------- |
| Compute              | EC2, Lambda                  | VMs, Azure Functions         | Compute Engine, Cloud Functions           |
| Storage              | S3, EBS, EFS                 | Blob, Disks, File            | Cloud Storage, Persistent Disk, Filestore |
| Database             | RDS, Aurora, DynamoDB        | Azure SQL, Cosmos DB         | Cloud SQL, BigQuery, Firestore            |
| Networking           | VPC, ELB, CloudFront         | VNet, App Gateway, CDN       | VPC, Load Balancing, Cloud CDN            |
| IAM                  | IAM                          | Azure AD                     | Cloud IAM                                 |
| Support              | AWS Support, Trusted Advisor | Azure Support, Azure Advisor | GCP Support, Recommender                  |
| Architecture         | AWS WAF                      | Azure WAF                    | Google Cloud Architecture Framework       |

---
