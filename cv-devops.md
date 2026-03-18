# Pierre Courteille
**DevOps - Cloud Engineer (AWS - 4x Certified)**

📞 (+33) 6 08 04 22 44 | 📧 pierre.courteille@gmail.com

## Profile
- AWS-focused DevOps / Cloud Engineer designing secure, scalable, and highly available infrastructures
- Strong emphasis on multi-account / multi-region patterns, isolation, and operational observability
- Infrastructure as Code (AWS CDK / Terraform) and CI/CD automation with proven delivery patterns

## Certifications
- AWS Certified DevOps Engineer - Professional (DOP-C02) — 2025
- AWS Certified Solutions Architect - Associate (SAA-C03) — 2025
- AWS Certified Developer - Associate (DVA-C02) — 2025
- AWS Certified Cloud Practitioner (CLF-C02) — 2025

## Education
- **Master MOCA (Modeling, Optimization, Combinatorics, Algorithms)** - Universite de Montpellier - 2015
- **Bachelor's Degree in Mathematics & Computer Science** - Universite de Nantes - 2013
- **Scientific Baccalaureat with High Honors** - Fougeres - 2009

## Experience

### DevOps / Cloud Engineer (Freelance) - IEC
Geneva (Switzerland) | September 2025 - Present

- Designed and implemented a SaaS platform using a full silo isolation model (1 tenant = 1 dedicated AWS account), aligned with AWS SaaS best practices for strict isolation, security, and compliance requirements.

**Achievements**
- SaaS Architecture & Isolation
  - Built a multi-tenant SaaS architecture based on the Silo Isolation model (1 tenant = 1 AWS account, fully isolated stack)
  - Prioritized security, compliance, and blast-radius reduction over economies of scale
  - Implemented strong isolation boundaries across:
    - Networking: dedicated VPC per tenant, strict Security Group policies
    - IAM: account-level isolation, least-privilege access
- Infrastructure as Code & Deployment
  - Built a single reusable AWS CDK project capable of deploying standardized tenant stacks including:
    - containerized microservices (Docker, ECS Fargate)
    - scalable and highly available services
    - consistent, reproducible infrastructure patterns across tenants
  - Ensured environment parity and standardized deployment patterns across hundreds of isolated stacks
- Monitoring, Logging & Observability (Multi-Account / Multi-Region)
  - Designed a centralized observability platform using a dedicated AWS monitoring account within AWS Organizations
  - Implemented CloudWatch Observability Access Manager (OAM) to ingest centralized metrics, logs, and traces from tenant accounts securely (no data duplication)
  - Deployed Amazon Managed Grafana integrated with:
    - CloudWatch metrics and logs
    - Prometheus-compatible metrics ingestion
  - Implemented synthetic monitoring using CloudWatch Synthetics Canaries:
    - end-to-end user journey validation (login, critical paths)
    - proactive availability and latency detection
  - Integrated alerting and incident notifications using:
    - CloudWatch Alarms
    - SNS topics for operational and on-call notifications
  - Provisioned monitoring, logging, and alerting fully via AWS CDK to keep consistency across regions

**Results**
- Highly secure and compliant SaaS foundation suitable for regulated / security-sensitive customers
- Predictable tenant isolation with minimal blast radius
- Centralized, scalable observability across hundreds of isolated AWS accounts
- Fully automated, CDK-driven tenant onboarding and operations

**Tech Stack**
- AWS: ECS Fargate, IAM, VPC, ALB, CloudWatch, CloudWatch OAM, Synthetics, SNS, S3, KMS, Organizations
- Amazon Managed Grafana, Prometheus
- AWS CDK, Terraform, Docker, GitLab CI, Python
- Infrastructure as Code; multi-account and multi-region AWS architecture

---

### DevOps / Cloud Engineer (Freelance) - Premaccess
Paris (France) | June 2019 - September 2025

Premaccess is a Franco-Swiss company specializing in AWS digital transformation and managed services. Supported multiple customers (Smartpush, Atatech, Cap Adrenaline, BNC, Fitizzy, Truffaut, Prestigia, ...) across AWS migration, evolution, and continuous optimization.

**Achievements**
- Full Migrations to AWS and Continuous Evolution
  - Led full migrations to AWS and continued delivery improvements over successive growth stages
  - Adopted tailored AWS services depending on each stage (containers, serverless, data, edge, ...)
- Network Architecture and Security
  - Designed multi-AZ VPCs with public, private, and isolated subnets
  - Hardened Security Groups and Network ACLs
  - Implemented VPC Endpoints and VPC Flow Logs
  - Centralized identity and access management (IAM Identity Center, IAM, SCPs)
  - Systematic encryption using KMS
- Compute and Orchestration
  - Containers: ECS (Fargate) and EKS for high-availability microservices
  - Serverless: Lambda + API Gateway for event-driven workloads
  - EC2: Auto Scaling Groups and Load Balancers (ALB/NLB) for custom needs
- Databases and Caching
  - RDS (Aurora MySQL/PostgreSQL, Serverless v2) for managed relational databases
  - DynamoDB for low-latency, highly scalable NoSQL workloads
  - ElastiCache (Redis, Memcached) for caching and performance improvement
  - Amazon Redshift for large-scale data analytics (data warehousing, complex analytical queries)
- Messaging and Streaming
  - SQS, SNS, EventBridge for asynchronous communication and event-driven integration
- Edge and Distribution
  - CloudFront (with OAC/OAI, WAF) for global distribution of static and dynamic content
  - Route 53 and Certificate Manager for automated DNS and TLS management
- CI/CD and IaC
  - Infrastructure as Code (AWS CDK, CloudFormation, Terraform when requested)
  - CI/CD pipelines: CodePipeline, CodeBuild, CodeDeploy, GitLab CI, and Jenkins
- Other
  - Built serverless architectures using AWS SAM to industrialize Lambda functions and REST APIs, integrated with DynamoDB and CloudWatch Logs

**Tech Stack**
- AWS: EC2, ASG, ALB/NLB, ECS, EKS, Lambda, RDS, DynamoDB, ElastiCache, SQS, SNS, EventBridge, CloudFront, S3, KMS, WAF, Route 53, ...
- Python, Node.js, .NET Core
- AWS CDK, CloudFormation
- GitLab, Jenkins, CodeCommit
- Docker, Kubernetes

---

### .NET Technical Instructor - ISIKA
Paris (France) | March 2020 - June 2023

- Delivered the C# training module with a strong focus on software development best practices and pedagogy.
- Covered C#, object-oriented programming, and data persistence using MySQL, emphasizing clean code, proper architecture, and maintainability.
- Guided students through learning and helped them apply best practices to build a lightweight .NET application used as the final project.

**Achievements**
- Introduction to C#
- Object-Oriented Programming (classes, inheritance, ...)
- WinForms, WebForms
- Data persistence (LINQ, Entity Framework)
- Development of lightweight client applications using ASP.NET
- Use of the MVC design pattern
- Front-end HTML/CSS

**Tech Stack**
- C#, Visual Studio, Entity Framework 6, LINQ, MySQL, HTML/CSS, MVC, ASP.NET

---

### Quality Manager - Bassetti
Kolkata (India) | 2016 - 2018

- Sent to India to build and lead a Quality Assurance department from scratch in a fast-growing international company developing the TEEXMA platform.
- Recruited, trained, and managed a QA team of up to 25 engineers, establishing testing processes, tools, and best practices to support large-scale enterprise clients such as Airbus, Continental, and Lafarge.

**Achievements**
- Built a QA department from scratch in an international context
- Led recruitment, onboarding, and mentoring of up to 25 QA engineers
- Developed a high-performance automated testing platform (10,000 tests/hour)
- Integrated automated testing into CI/CD pipelines with scheduled executions
- Bridged QA and development teams to improve software quality and delivery speed
- Drove adoption of DevOps and continuous improvement practices

**Tech Stack**
- C#, Selenium, .NET, SVN, Sheets API, Jenkins, XML, Excel

