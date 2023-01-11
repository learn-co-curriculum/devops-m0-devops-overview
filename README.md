# DevOps Overview

## Learning goals

- Understand what DevOps is and how it fits into the software development life cycle
- Learn the principles of DevOps, including continuous integration, continuous delivery, and infrastructure as code
- Learn the basics of what CI/CD and IaC are and their relationship to DevOps

## Introduction

**DevOps** is a set of practices that focus on bringing together the two backbones of the software development pipeline: *software development* and *IT operations*. A DevOps engineer leverages a wide range of tools and technologies in order to automate processes/builds, tests, and deploy software both faster and more reliably.

## Roles and responsibilities

In a traditional software development environment, developers are mostly responsible for writing code, and operators deploy and maintain it. While it makes sense on the surface, this can actually lead to disconnects between the two teams! For example, developers might only worry about adding new features, whereas operators might only focus on stability and reliability.

By bringing in DevOps practices into scope, both developers *and* operations staff are responsible for the entire software development life cycle (with differing priorities).

This close collaboration allows organizations and teams to deploy software faster and with fewer errors.

## Practices

While there are too many practices to count when it comes to DevOps, you can narrow down the foundation to two: *CI/CD* and *Infrastructure as Code (IaC)*.

**CI/CD** stands for continuous integration and continuous development. 

**Continuous integration (CI)** encompasses the practice where developers regularly merge their code changes into a central repository, which is then automatically built and tested, allowing teams to detect and fix errors early on in the development process.

**Continuous deployment (CD)** on the other hand, is an extension of CI, that takes it a step further by automating the deployment of code changes to production environments.

For example, a team making use of CI/CD in their development pipeline could deploy an app to an app store by having tests run on the code automatically, and if the tests are successful, automatically deploy the updated app to the store.

The other side of this foundation is *Infrastructure as Code (IaC)*. **IaC** is another practice that treats infrastructure resources (could be servers, networks, etc.) as if they were software. Instead of manually configuring these resources, teams can use code to define and manage them, similar to the way you would manage an application.

Managing your infrastructure as code has many benefits:

- Allows teams to automate provisioning/configuration of infrastructure resources, reducing the risk of human error and increasing reliability
- Enables teams to track changes to their infrastructure over time
- Makes it easy to roll-back or modify existing configurations
- Makes it easy for teams to replicate and scale their infrastructure

## Conclusion

As you can probably garner from this short introduction, a lot of skills are required in order to become a successful DevOps engineer. In this course we will focus on building up all the necessary skills; everything from server administration and scripting, to automating builds and managing infrastructure as code.
