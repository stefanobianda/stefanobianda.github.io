---
title: "Head IT Application Development"
permalink: /jobs/J4Viseca/
excerpt: "Viseca Payment Services SA"
layout: single
redirect_from:
  - /theme-setup/
author_profile: true
toc: true
order_number: 6
header:
  overlay_image: /assets/images/cicd-pipeline-art.jpg
  og_image: /assets/images/cicd-pipeline-art.jpg
  teaser: /assets/images/cicd-pipeline-art.jpg
prev:
  url: /jobs/J3Schindler/
  title: J3Schindler
---

# Head IT Application Development

From April 2012 to August 2023 

## Description

Responsible for developing applications for credit card payments using Agile methodology with Scrum.
- Product Owner & Scrum Master
- Lead 50 Software Engineers (internal and external)
- budget 3M CHF/year

## Main Tasks
- Product Owner and Scrum Master of CICD shared pipeline
- Leading team, agile methodology, test driven development, code review
- Iterative and continuous improvement
- Managing team’s backlog and product quality
- Developing the team’s technical proficiency and growing
- Introduces and improves to software development automations (CI/CD)
- Keep CICD infrastructure up-to-date, LCM activities
- Responsible for the Aduno Gruppe (now Viseca) applications
- WEB sites, WEB applications, Web Services, CRM Issuing, Acquirer Suite
  - Aduno Website (dismissed)
  - [Viseca](https://www.viseca.ch)
  - [Surprize](https://one-digitalservice.ch/public/en/surprize) today moved on [One](https://one-digitalservice.ch/)
  - [Cashgate](https://www.cashgate.ch/) (sell to Cembra)
  - AGIOS (Internal CRM, JAVA)
  - Trident (dismissed, PLSQL Suite)
- Developing with ITIL and AGILE methodology, use of TDD and CICD pipeline
- Leading teams in different areas, hiring
  - Java
  - .Net
  - SQL
- Implement a common strategy to align all teams on the same development process and tools 
- Maintenance and support for applications in the credit card payment environment
- Support the new application Surprize
- Support the Terminal Card Reader

## Tools Used
- Source Control: GitHub Enterprise
- Build Server: Jenkins (controller and nodes)
- Static Code Analysis: Sonarqube
- DML, Dependency repositories: Jfrog Artifactory
- Software Composition Analysis (SCA): Jfrog Xray
- Deployment DevOps automation: Octopus Deploy
- Programming languages: Groovy and Java
- Enterprise resource planning (ERP): ServiceNow SNOW
- Project Management: Jira

## Technologies:
- Docker
- Java
- .NET
- .NET core
- C#
- TypeScript 
- Python
- PL/SQL
- Web Services

# Achievements

## Budget monitoring and release planning.
Successfully managed conflicts and ensured customer satisfaction within timelines and budgets despite changes in project schedules and priorities (ERP ServiceNow).

When the company introduced ITIL and ServiceNow, costs and production releases were under control. 

I highlighted to my superiors that the process conflicted with Agile, particularly for website development. They didn't listen and forced me to follow the defined process. Delays in implementing simple changes led to the loss of website development projects.

## Standardization of the development process and automation
Standardized the development process and automated it through a shared CI/CD pipeline for Java, .NET, .NET Core, TypeScript, Python, and Docker images

The shared pipeline is developed independently of the project. The project needs to manage two simple files and follow standardization:

1. Jenkins file: Specifies the shared pipeline release and the environment to use.
1. Config file: Details the project specifics and the functions to run.

All new features of the shared pipeline are immediately available to all projects. To use new functionality, the project must update the configuration file and the pipeline release.

## Migration to a common SCM tool (Github Enterprise)
Transition of source code management to GitHub Enterprise (60 projects), with preservation of all code and revision history without loss.

When I took over the development team, each project operated independently. The company used 4 different source code management tools. I proposed unifying them by choosing a Git-based solution, specifically GitHub Enterprise, and enforced the use of Gitflow as the Git branching model.

## Implementation of the Build Server infrastructure (Jenkins)
Define and implement the build server infrastructure (Jenkins), establishing the foundation for the CI/CD pipeline. The build is triggered on each commit and provide unit test feedback.

Embracing DevOps, I automated the development process using a Jenkins controller-nodes-agents configuration to establish the foundation of the shared CI/CD pipeline.

By centralizing the build process in Jenkins, I gained governance over the entire application portfolio.

Isolated environment builds addressed production release issues related to overlooked dependencies.

## Establishment of a unit testing culture
Establishment of a unit test culture and promotion of Test-Driven Development (TDD) practices where applicable.

When I took over the development team, no project included unit tests. I initiated unit testing to improve code quality (shift left), implementing simple unit tests for legacy code and promoting Test-Driven Development (TDD) for new projects, which was successful, as demonstrated by the data migration project. Test coverage is continuously increasing, improving code quality.

## Automation of Quality Gates (SonarQube)
Integrated static analysis with SonarQube into the pipeline, significantly enhancing code quality and system security.

Through the use of SonarQube, we maintain quality control over the code produced in the company. The adoption of quality gates ensures continuous improvement. Making the quality levels of each project public has motivated developers to improve their code.
 
## Implementation of company’s Definitive Media Library (Artifactory)
Configuration of JFrog Artifactory as the company’s DML for artifact storage and dependency repositories. 

All versions are identified using SemVer2, with development and production releases cataloged in separate repositories.
Developer access to Artifactory for dependency downloads from known repository.

Type of packages: Maven, NuGet, PyPI (python), Docker, Conda, Helm, npm, Bower

## Verification of dependency Security Gates (Xray)
Integration of security checks on package dependencies with Xray into the pipeline, with processing stoppage in case of high risk.

Security is becoming increasingly relevant, and monitoring the dependencies used in developed applications has become very important. 
Xray is an easy way to proactively identify vulnerabilities on open source and license compliance violations.

## Automatic deploy in all environments (Octopus Deploy)
Configuration of automatic deployment with Octopus Deploy across various environments.

I am proud to have proposed and collaborated with the fantastic team of One to successfully achieve the goal of the first fully automated deployment in a production environment using Octopus Deploy.

## Backlog and sprint planning (Jira, Confluence)
Oversight of the agile development of the CI/CD pipeline, including code reviews, backlog management, and sprints iteration.

## Regular update of the CI/CD infrastructure (security patches)
Maintenance of the CI/CD infrastructure through tool updates and application of security patches.

Regular updates of the tools every three months, or sooner in the case of critical vulnerabilities. Planning of upgrades, often with significant impacts on the pipeline, while minimizing changes on projects.

## Innovation culture advocate (Automation, Docker, IaC, TDD)
Innovation activities resulting in new process or new technology

- Automation of the development process
- Promotion of Docker and Kubernetes
- Promotion of Infrastructure as Code (IaC) through Ansible
- Implementation of TDD methodology in new projects

## Continuous improvement and team collaboration (DevOps)
My leadership established a collaborative and competitive environment optimal for continuous improvement.

After the migration to GitHub Enterprise, presenting an animated representation of the commits with the developer's name strengthened the team spirit and their commitment to the team, see [gource](https://gource.io/).

I was excited to see so many engineers voluntarily taking evening training sessions outside of working time.

Making the static code analysis produced by SonarQube public has motivated every developer to improve their own code.

Proud to be the first manager to have collaborated with various teams: architecture, development, and infrastructure.
Unfortunately, my boss was not very enthusiastic about it.


# Notable results
- Migration of over 60 projects to GitHub Enterprise, preserving history without loss
- Implementation of Unit Test in over 40 projects (NUnit, XUnit, JUnit, Selenium)
- Use of TDD methodology in some projects
- Over 50 projects utilize the shared CI/CD pipeline (Java, .NET, .NET Core, TypeScript, Python, and Docker images)
- First automatic deploy with Octopus Deploy in PROD environment (now over 10 projects).
- Proactive security dependency detection, resulting in the discovery of the first security issue.


![Viseca](/assets/images/L_VIS_MCV_A4_4f_rgb_1707.png)

[www.viseca.ch](https://www.viseca.ch/)
