# Lab 4 - Deployment Strategies for Lambda, ECS, EC2, and Elastic Beanstalk

## Objectives

- Compare deployment strategies for different AWS compute platforms.
- Review blue/green, canary, linear, rolling, immutable, and all-at-once deployments.
- Understand traffic shifting, health checks, and rollback.
- Design a deployment plan for multiple workload types.

## Scenario

Different workloads require different deployment strategies. You will compare controlled release patterns and choose safe deployment approaches.

## Steps

1. Review Lambda versions and aliases.
2. Review Lambda traffic shifting with CodeDeploy concepts.
3. Review ECS services, task definitions, deployment controllers, and rolling updates.
4. Review blue/green deployments for ECS using CodeDeploy at a high level.
5. Review EC2 Auto Scaling rolling or immutable deployment concepts.
6. Review Elastic Beanstalk deployment policies.
7. Create a deployment strategy matrix for Lambda, ECS, EC2, and Elastic Beanstalk.
8. For each workload, choose a strategy for low-risk production releases.
9. Define health check signals.
10. Define rollback triggers.
11. Define monitoring and alarm requirements.
12. Define how feature flags or parameterized configuration could reduce risk.
13. Save your notes.

## Deliverables

- Deployment strategy matrix
- Health check and rollback notes
- Traffic shifting notes
- Monitoring requirements

## Checkpoint

You should be able to select a deployment strategy based on workload type, risk, rollback needs, and availability requirements.
