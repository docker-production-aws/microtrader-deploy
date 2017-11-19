# Docker in Production using AWS - Microtrader Deployment Playbook

This repository provides an Ansible playbook and CloudFormation template for deploying the Microtrader application into an AWS development and production environment, as described in the Pluralsight course [Docker in Production using Amazon Web Services](https://app.pluralsight.com/library/courses/docker-production-using-amazon-web-services/table-of-contents).

## Quick Start

See the [AWS Starter repository README](https://github.com/docker-production-aws/aws-starter) for instructions on how to work with this repository.

## Branches

This repository contains two branches:

- [`master`](https://github.com/docker-production-aws/microtrader-deploy/tree/master) - represents the initial starting state of the repository as viewed in the course.  Specifically this is an empty repository that you are instructed to create in the module **Defining ECS Applications using Ansible and CloudFormation**.

- [`final`](https://github.com/docker-production-aws/microtrader-deploy/tree/final) - represents the final state of the repository after completing all configuration tasks as described in the course material.

> The `final` branch is provided as a convenience in the case you get stuck, or want to avoid manually typing out large configuration files.  In most cases however, you should attempt to configure this repository by following the course material.

To clone this repository and checkout a branch you can simply use the following commands:

```
$ git clone https://github.com/docker-production-aws/packer-ecs.git
...
...
$ git checkout final
Switched to branch 'final'
$ git checkout master
Switched to branch 'master'
```

## Repository Timeline

The following provides links to commits in this repository that represent important milestones in the course material:

- [Defining ECS Applications using Ansible and CloudFormation](https://github.com/docker-production-aws/microtrader-deploy/tree/defining-ecs-applications) - this commit represents the state of the repository once you have completed the Defining ECS Applications using Ansible and CloudFormation module.  This module establishes the supporting infrastructure for the Microtrader application.

- [Microtrader First Deploy](https://github.com/docker-production-aws/microtrader-deploy/tree/microtrader-first-deploy) - this commit represents the state of the repository at the point you perform the first deployment of the Microtrader stack in the Deploying ECS Applications using Ansible and CloudFormation module.

- [Deploying ECS Applications using Ansible and CloudFormation](https://github.com/docker-production-aws/microtrader-deploy/tree/deploying-ecs-applications) - this commit represents the state of the repository once you have completed the Deploying ECS Applications using Ansible and CloudFormation module.  This module establishes the EC2 container service elements of the Microtrader application.

- [Creating CloudFormation Custom Resources using AWS Lambda](https://github.com/docker-production-aws/microtrader-deploy/tree/creating-custom-resources) - this commit represents the state of the repository once you have completed the Creating CloudFormation Custom Resources using AWS Lambda module.

- [Managing Secrets in AWS](https://github.com/docker-production-aws/microtrader-deploy/tree/managing-secrets-in-aws) - this commit represents the state of the repository once you have completed the Managing Secrets in AWS module.

- [Managing ECS Infrastructure Lifecycle](https://github.com/docker-production-aws/microtrader-deploy/tree/managing-ecs-infrastructure-lifecycle) - this commit represents the state of the repository once you have completed the Managing ECS Infrastructure Lifecycle module.

- [Auto Scaling ECS Applications](https://github.com/docker-production-aws/microtrader-deploy/tree/autoscaling-ecs-applications) - this commit represents the state of the repository once you have completed the Auto Scaling ECS Applications module.

- [Continuous Delivery using CodePipeline](https://github.com/docker-production-aws/microtrader-deploy/tree/continuous-delivery-codepipeline) - this commit represents the state of the repository once you have completed the Continuous Delivery using CodePipeline module.

## Errata

No known issues.

## Further Reading

- [CloudFormation User Guide](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)
- [CloudFormation Template Reference](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html)