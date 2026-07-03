# Lab 3 - CI/CD with CodePipeline, CodeBuild, CodeDeploy, and Artifact Stores

## Objectives

- Design a CI/CD pipeline.
- Review buildspec, artifacts, test stages, approvals, and deployment stages.
- Compare CodePipeline, CodeBuild, CodeDeploy, and CodeArtifact concepts.
- Plan rollback and failure handling.

## Scenario

DevOps engineers automate safe application delivery. This lab designs a CI/CD workflow with testing, artifact management, approvals, deployment, and rollback.

## Steps

1. Open CodePipeline.
2. Review pipeline stages, actions, transitions, and approvals.
3. Open CodeBuild.
4. Review build projects, build environments, buildspec files, artifacts, reports, and logs.
5. Open CodeDeploy.
6. Review applications, deployment groups, deployment configurations, lifecycle hooks, and rollback.
7. Open CodeArtifact if available and review package repository use cases.
8. Review S3 artifact bucket concepts.
9. Create a pipeline design with source, build, unit test, integration test, security scan, package, approval, deploy, and post-deploy validation.
10. Identify IAM service roles required by each stage.
11. Identify environment variables and secrets handling.
12. Identify rollback triggers.
13. Identify notifications through SNS or EventBridge.
14. Save your pipeline design.

## Deliverables

- CI/CD service comparison table
- Pipeline architecture
- IAM role notes
- Rollback and notification notes

## Checkpoint

You should be able to explain professional CI/CD design, including artifacts, approvals, validation, and rollback.
