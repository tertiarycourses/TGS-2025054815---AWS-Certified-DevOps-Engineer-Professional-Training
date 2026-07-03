# TGS-2025054815 - AWS Certified DevOps Engineer Professional Training

> Course: AWS Certified DevOps Engineer Professional Training  
> Course Code: TGS-2025054815  
> Register here: https://www.tertiarycourses.com.sg/wsq-aws-certified-devops-engineer-training.html

Hands-on AWS Certified DevOps Engineer Professional labs for learners preparing for the AWS Certified DevOps Engineer - Professional exam. The labs cover SDLC automation, infrastructure as code, CI/CD, deployment strategies, configuration management, monitoring, logging, incident response, resilience, security, governance, cost optimization, and exam-style review.

## Courseware

| Item | Description |
| --- | --- |
| [Learner Guide](LG-AWS-Certified-DevOps-Engineer-Professional-Training.md) | Detailed step-by-step guide for completing the labs and preparing final deliverables. |
| [Lab Guide](labs/README.md) | Lab catalogue grouped by AWS DevOps Engineer Professional skill area. |
| [Tools Reference](labs/tools.md) | Recommended AWS tools, cost-safety notes, and learner setup checklist. |

## How to Use

1. Create or use an AWS account provided by your trainer.
2. Create a working folder named `TGS-2025054815-AWS-DOP-Labs`.
3. Complete the labs in sequence because later labs reuse IAM, CloudFormation, CodePipeline, monitoring, and reliability concepts.
4. Record screenshots, commands, templates, pipeline diagrams, and configuration notes for each lab.
5. Delete paid resources when the lab asks you to clean up.

## Lab Catalogue

### Domain 1 - SDLC Automation and Infrastructure as Code

| Lab | Title | Focus |
| --- | --- | --- |
| [Lab 1](labs/lab-01-account-iam-devops-tooling-baseline.md) | Account Safety, IAM, DevOps Tooling, and Governance Baseline | IAM, roles, permissions boundaries, Organizations, CloudTrail, budgets |
| [Lab 2](labs/lab-02-cloudformation-cdk-config-drift.md) | Infrastructure as Code with CloudFormation, CDK, Config, and Drift | Stacks, change sets, drift detection, StackSets, AWS Config, tagging |
| [Lab 3](labs/lab-03-codepipeline-codebuild-codedeploy-cicd.md) | CI/CD with CodePipeline, CodeBuild, CodeDeploy, and Artifact Stores | Source, build, test, deploy, artifacts, approvals, rollback |

### Domain 2 - Deployment, Configuration, and Operations

| Lab | Title | Focus |
| --- | --- | --- |
| [Lab 4](labs/lab-04-deployment-strategies-ecs-lambda-beanstalk.md) | Deployment Strategies for Lambda, ECS, EC2, and Elastic Beanstalk | Blue/green, rolling, canary, linear, immutable, traffic shifting |
| [Lab 5](labs/lab-05-systems-manager-automation-patch-parameter.md) | Systems Manager, Automation, Patch, Parameter Store, and Run Command | Fleet operations, automation runbooks, patching, parameters, secrets awareness |

### Domain 3 - Monitoring, Incident Response, and Resilience

| Lab | Title | Focus |
| --- | --- | --- |
| [Lab 6](labs/lab-06-observability-cloudwatch-xray-eventbridge.md) | Observability with CloudWatch, X-Ray, CloudTrail, EventBridge, and Alarms | Metrics, logs, traces, dashboards, anomaly detection, events |
| [Lab 7](labs/lab-07-resilience-backup-ha-disaster-recovery.md) | High Availability, Backup, Disaster Recovery, and Auto Remediation | Multi-AZ, Auto Scaling, Route 53, Backup, fault injection, runbooks |
| [Lab 8](labs/lab-08-security-cost-optimization-exam-review.md) | Security, Compliance, Cost Optimization, and Exam Review | Guardrails, KMS, Secrets, Security Hub, Trusted Advisor, Cost Explorer, timed review |

## Reference

- AWS Certified DevOps Engineer - Professional: https://aws.amazon.com/certification/certified-devops-engineer-professional/
- Course registration: https://www.tertiarycourses.com.sg/wsq-aws-certified-devops-engineer-training.html
- AWS Documentation: https://docs.aws.amazon.com/
- AWS Skill Builder: https://skillbuilder.aws/

## Free Tools Used

- AWS Free Tier eligible services where possible
- AWS Management Console
- AWS CloudShell
- AWS CLI
- AWS CloudFormation
- AWS CodePipeline
- Amazon CloudWatch
- AWS Systems Manager
- AWS Pricing Calculator
