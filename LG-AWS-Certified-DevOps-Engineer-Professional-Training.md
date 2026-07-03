# Learner Guide - AWS Certified DevOps Engineer Professional Training

> Course: AWS Certified DevOps Engineer Professional Training  
> Course Code: TGS-2025054815  
> Registration: https://www.tertiarycourses.com.sg/wsq-aws-certified-devops-engineer-training.html

This learner guide supports a practical AWS Certified DevOps Engineer Professional course. It is designed for learners preparing to automate software delivery, provision infrastructure, operate distributed systems, monitor production workloads, and improve resilience, security, compliance, and cost outcomes on AWS.

## Learning Outcomes

By the end of the labs, you should be able to:

- Establish governance, IAM, audit, and cost-safety baselines for DevOps work.
- Design infrastructure as code workflows with CloudFormation, CDK, StackSets, drift detection, and AWS Config.
- Design CI/CD pipelines with CodePipeline, CodeBuild, CodeDeploy, artifact stores, approvals, testing, and rollback.
- Compare deployment strategies across Lambda, ECS, EC2, and Elastic Beanstalk workloads.
- Use Systems Manager concepts for secure fleet operations, patching, automation, and parameter management.
- Design observability using CloudWatch, X-Ray, CloudTrail, EventBridge, dashboards, alarms, logs, and traces.
- Plan high availability, backup, disaster recovery, auto remediation, and resilience testing.
- Apply security, compliance, cost optimization, and governance controls to DevOps pipelines and operations.
- Prepare for professional-level AWS DevOps scenario questions.

## Recommended Setup

1. Use a trainer-provided AWS account where available.
2. If using your own account, enable MFA and create a budget alert before starting labs.
3. Create a working folder named `TGS-2025054815-AWS-DOP-Labs`.
4. Save screenshots, commands, architecture notes, pipeline diagrams, and comparison tables.
5. Delete temporary AWS resources after each hands-on exercise.

## Cost Safety Rules

- Use small test applications and short build runs.
- Avoid long-running compute, container services, provisioned databases, or repeated builds unless explicitly assigned.
- Delete test stacks, pipelines, build projects, alarms, functions, queues, clusters, buckets, and logs if instructed.
- Check Billing and Cost Management after hands-on labs.

## Lab 1 - Account Safety, IAM, DevOps Tooling, and Governance Baseline

### Objectives

- Establish a safe AWS DevOps baseline.
- Review IAM and service roles.
- Review governance, audit, and cost-safety services.
- Map DevOps activities to AWS services.

### Procedure

1. Sign in to the assigned AWS account.
2. Confirm account and region.
3. Open IAM and review users, groups, roles, policies, and permission boundaries.
4. Verify MFA where permitted.
5. Review service roles for CodeBuild, CodePipeline, CloudFormation, and Systems Manager.
6. Review Organizations and service control policies at a high level.
7. Review CloudTrail event history.
8. Review AWS Config compliance concepts.
9. Review Budgets and Cost Explorer.
10. Map source, build, deploy, monitor, remediate, secure, and govern activities to AWS services.
11. Save your notes.

### Checkpoint

You should be able to explain the governance baseline needed before automating AWS delivery and operations.

## Lab 2 - Infrastructure as Code with CloudFormation, CDK, Config, and Drift

### Objectives

- Review IaC components and change control.
- Understand drift detection and StackSets.
- Review AWS Config rules.
- Design an IaC governance workflow.

### Procedure

1. Review CloudFormation stacks, templates, parameters, outputs, mappings, conditions, and resources.
2. Review change sets, rollback, termination protection, and drift detection.
3. Review CDK app, stack, construct, synth, and deploy concepts.
4. Review StackSets for multi-account or multi-region deployment.
5. Review AWS Config resource inventory, managed rules, and conformance packs.
6. Create a tagging standard.
7. Design an IaC workflow with validation, change set, approval, deploy, drift check, and Config compliance.
8. Save your notes.

### Checkpoint

You should be able to describe repeatable infrastructure delivery and compliance validation using AWS IaC tools.

## Lab 3 - CI/CD with CodePipeline, CodeBuild, CodeDeploy, and Artifact Stores

### Objectives

- Design CI/CD delivery.
- Review build, test, artifact, approval, and deployment stages.
- Plan rollback and notification behavior.
- Identify IAM service roles.

### Procedure

1. Review CodePipeline stages, actions, transitions, and approvals.
2. Review CodeBuild projects, buildspec files, artifacts, reports, and logs.
3. Review CodeDeploy applications, deployment groups, lifecycle hooks, and rollback.
4. Review CodeArtifact and S3 artifact buckets.
5. Design a source-build-test-security-package-approval-deploy-validation pipeline.
6. Identify IAM roles, secrets handling, rollback triggers, and notifications.
7. Save your design.

### Checkpoint

You should be able to explain professional CI/CD design, including quality gates and rollback.

## Lab 4 - Deployment Strategies for Lambda, ECS, EC2, and Elastic Beanstalk

### Objectives

- Compare deployment strategies.
- Match deployment approaches to workload types.
- Define health checks and rollback triggers.
- Plan traffic shifting and monitoring.

### Procedure

1. Review Lambda versions, aliases, and traffic shifting.
2. Review ECS rolling and blue/green deployments.
3. Review EC2 Auto Scaling deployment concepts.
4. Review Elastic Beanstalk deployment policies.
5. Create a matrix for blue/green, canary, linear, rolling, immutable, and all-at-once strategies.
6. Choose safe production strategies for Lambda, ECS, EC2, and Elastic Beanstalk.
7. Define health checks, alarms, rollback triggers, and monitoring requirements.
8. Save your notes.

### Checkpoint

You should be able to choose safe deployment strategies for different AWS workloads.

## Lab 5 - Systems Manager, Automation, Patch, Parameter Store, and Run Command

### Objectives

- Review secure fleet operations.
- Compare Systems Manager capabilities.
- Design patching and automation workflows.
- Manage parameters and secrets awareness.

### Procedure

1. Review Systems Manager managed nodes.
2. Review Run Command, Session Manager, Automation, Patch Manager, State Manager, Distributor, and Inventory.
3. Review Parameter Store strings, secure strings, hierarchies, and parameter policies.
4. Compare Parameter Store and Secrets Manager.
5. Design a patching workflow.
6. Design an automation runbook for service restart or log collection.
7. Identify IAM permissions and audit logs required.
8. Save your notes.

### Checkpoint

You should be able to explain how Systems Manager supports secure operations and remediation.

## Lab 6 - Observability with CloudWatch, X-Ray, CloudTrail, EventBridge, and Alarms

### Objectives

- Design monitoring and incident signals.
- Use metrics, logs, traces, dashboards, and alarms.
- Review distributed tracing and audit events.
- Route events for response.

### Procedure

1. Review CloudWatch metrics, namespaces, dimensions, dashboards, and alarms.
2. Review CloudWatch Logs, metric filters, subscription filters, anomaly detection, and composite alarms.
3. Review X-Ray service maps, traces, segments, and sampling.
4. Review CloudTrail audit events.
5. Review EventBridge rules and targets.
6. Design observability for a web application.
7. Define SLIs, alarms, log retention, trace sampling, and incident routing.
8. Save your notes.

### Checkpoint

You should be able to design observability that supports troubleshooting and automated response.

## Lab 7 - High Availability, Backup, Disaster Recovery, and Auto Remediation

### Objectives

- Review HA and DR patterns.
- Plan backup and restore.
- Define RTO and RPO.
- Design auto remediation.

### Procedure

1. Review Multi-AZ and multi-region concepts.
2. Review Auto Scaling and Elastic Load Balancing health checks.
3. Review Route 53 routing policies and health checks.
4. Review AWS Backup plans, vaults, retention, and restore.
5. Review RDS backup, snapshots, Multi-AZ, and replicas.
6. Review S3 versioning, replication, lifecycle, and object lock.
7. Compare backup and restore, pilot light, warm standby, and multi-site active-active DR.
8. Review Fault Injection Service concepts.
9. Design HA and DR for a three-tier application.
10. Define RTO, RPO, alarms, and remediation actions.
11. Save your notes.

### Checkpoint

You should be able to explain resilience and automated recovery patterns for AWS systems.

## Lab 8 - Security, Compliance, Cost Optimization, and Exam Review

### Objectives

- Review security and compliance guardrails.
- Plan DevOps cost optimization.
- Map labs to exam domains.
- Complete timed practice.

### Procedure

1. Review Security Hub, GuardDuty, IAM Access Analyzer, KMS, Secrets Manager, and Parameter Store.
2. Review AWS Config, SCPs, and permission boundaries.
3. Review Trusted Advisor, Cost Explorer, and Budgets.
4. Create a security and compliance checklist.
5. Create a cost optimization checklist for pipelines, builds, logs, compute, storage, and data transfer.
6. Map labs to exam domains.
7. Complete a timed 30-question practice set.
8. Mark weak topics and create a revision plan.
9. Clean up temporary resources.
10. Save final notes.

### Checkpoint

You should be ready to reason through advanced AWS DevOps delivery, operations, security, and resilience scenarios.

## Final Submission Checklist

- Lab notes or screenshots
- IaC governance workflow
- CI/CD pipeline design
- Deployment strategy matrix
- Systems Manager runbook outline
- Observability and incident response design
- HA and DR checklist
- Security and cost optimization checklist
- Timed practice score
- Weak-topic revision plan

## Suggested Course Flow

| Segment | Focus | Labs |
| --- | --- | --- |
| Segment 1 | Governance, IAM, IaC, CI/CD | Labs 1-3 |
| Segment 2 | Deployment strategies and operations automation | Labs 4-5 |
| Segment 3 | Observability, resilience, security, cost, exam review | Labs 6-8 |

## Clean Up

1. Delete temporary stacks, pipelines, build projects, deployment groups, and artifact buckets if instructed.
2. Delete temporary Lambda functions, ECS services, queues, alarms, dashboards, and test resources if instructed.
3. Stop or delete any provisioned resources that may incur cost.
4. Keep budget alerts active until the trainer confirms cleanup.
5. Save notes for final revision.
