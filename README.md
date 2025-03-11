1. Compute & Containers
•	Amazon EC2 – Virtual machines for hosting applications.
•	AWS Lambda – Serverless computing for running code without managing servers.
•	Amazon ECS (Elastic Container Service) – Managed container orchestration.
•	Amazon EKS (Elastic Kubernetes Service) – Managed Kubernetes service.
•	AWS Fargate – Serverless compute engine for containers.
2. CI/CD (Continuous Integration & Deployment)
•	AWS CodePipeline – Automates CI/CD workflows. 
•	AWS CodeBuild – Builds and tests code in a managed environment.
•	AWS CodeDeploy – Automates application deployments.
•	AWS CodeCommit – Managed Git repository service.
•	AWS CodeArtifact – Artifact repository for dependency management.
3. Infrastructure as Code (IaC)
•	AWS CloudFormation – Automates infrastructure provisioning using YAML/JSON templates.
•	AWS CDK (Cloud Development Kit) – Infrastructure as Code using programming languages like Python, JavaScript.
•	Terraform (third-party) – Open-source IaC tool widely used with AWS.
4. Monitoring & Logging
•	Amazon CloudWatch – Logs, metrics, and alerts for monitoring applications and infrastructure.
•	AWS X-Ray – Distributed tracing for applications.
•	AWS CloudTrail – Logs AWS account activities for security audits.
•	AWS Config – Monitors and records AWS resource configurations.
5. Networking & Security
•	Amazon VPC – Virtual private cloud for networking.
•	AWS Route 53 – Managed DNS and domain name service.
•	AWS WAF & Shield – Web Application Firewall and DDoS protection.
•	AWS IAM (Identity and Access Management) – Manages user permissions and security policies.
•	AWS Secrets Manager – Securely stores and retrieves credentials and API keys.
6. Storage & Databases
•	Amazon S3 – Object storage for backups, logs, and artifacts.
•	Amazon EBS – Block storage for EC2 instances.
•	Amazon RDS – Managed relational databases (MySQL, PostgreSQL, etc.).
•	Amazon DynamoDB – NoSQL database for scalable applications.
•	Amazon ElastiCache – Caching service for fast data retrieval (Redis, Memcached).
7. DevOps Security & Compliance
•	AWS Security Hub – Centralized security monitoring.
•	AWS GuardDuty – Threat detection service.
•	AWS Inspector – Security vulnerability assessment.
•	AWS KMS (Key Management Service) – Encrypts sensitive data.
8. Hybrid & Edge Computing
•	AWS Outposts – Runs AWS services on-premises.
•	AWS Local Zones – Extends AWS regions closer to users.
9. Messaging & Event-Driven Architectures
•	Amazon SNS (Simple Notification Service) – Push notifications and alerts.
•	Amazon SQS (Simple Queue Service) – Message queue for decoupling services.
•	AWS EventBridge – Event bus for integrating AWS services.
10. Observability & Performance Optimization
•	AWS Cost Explorer – Analyzes AWS costs and usage.
•	AWS Trusted Advisor – Provides best practice recommendations for security, cost, and performance.


DevSecOps Fits into DevOps (Integration in CI/CD Pipeline)
Stage	DevSecOps Tools & Practices
Code	Secure coding practices, SonarQube, Checkmarx
Build	Dependency scanning (Snyk, Black Duck)
Test	SAST, DAST, OWASP ZAP
Release	Security policies (Checkov, Terrascan)
Deploy	Container security (Trivy, Aqua Security)
Monitor	Threat detection (Falco, AWS Security Hub)
	
 
 
