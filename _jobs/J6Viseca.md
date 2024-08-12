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
## Head IT Application Development

### Working Period
From April 2012 to August 2023 

## Description

Responsible for developing applications for credit card payments using Agile methodology with Scrum: Product Owner, Scrum Master (50 Software Engineers, budget 3M CHF/year)

## Achievements

### Budget control and meeting deadlines
Successfully managed conflicts and ensured customer satisfaction within timelines and budgets despite changes in project schedules and priorities (ERP ServiceNow).

When the company introduced ITIL and ServiceNow, I highlighted to my superiors that the process conflicted with Agile, particularly for website development. They didn't listen and forced me to follow the defined process. Delays in implementing simple changes led to us losing website development projects.

### Standardization of the development process and automation
Standardized the development process and automated it through a shared CI/CD pipeline for Java, .NET, .NET Core, TypeScript, Python, and Docker images

The shared pipeline is developed independently of the project. The project needs to manage two simple files and follow standardization:

1. Jenkins file: Specifies the shared pipeline release and the environment to use.
1. Config file: Details the project specifics and the functions to run.

All new features of the shared pipeline are immediately available to all projects. To use new functionality, the project must update the configuration file and the pipeline release.

### Migration to a common SCM tool (Github Enterprise)
Transition of source code management to GitHub Enterprise (60 projects), with preservation of all code and revision history without loss.

When I took over the development team, each project operated independently. The company used 4 different source code management tools. I proposed unifying them by choosing a Git-based solution, specifically GitHub Enterprise, and enforced the use of Gitflow as the Git branching model.

### Implementation of the Build Server infrastructure (Jenkins)
Define and implement the build server infrastructure (Jenkins), establishing the foundation for the CI/CD pipeline. The build is triggered on each commit and provide unit test feedback.

Embracing DevOps, I automated the development process using a Jenkins controller-nodes-agents configuration to establish the foundation of the shared CI/CD pipeline.

By centralizing the build process in Jenkins, I gained governance over the entire application portfolio.

Isolated environment builds addressed production release issues related to overlooked dependencies.

### Establishing a unit testing culture (NUnit, XUnit, JUnit, Selenium)
Establishing a unit test culture and promotion of Test-Driven Development (TDD) practices where applicable.

When I took over the development team, no project included unit tests. I initiated unit testing to improve code quality (shift left), implementing simple unit tests for legacy code and promoting Test-Driven Development (TDD) for new projects, which was successful, as demonstrated by the data migration project. Test coverage is continuously increasing, improving code quality.

### Automation of Quality Gates (SonarQube)
Integrated static analysis with SonarQube into the pipeline, significantly enhancing code quality and system security.

Through the use of SonarQube, we maintain quality control over the code produced in the company. The adoption of quality gates ensures continuous improvement. Making the quality levels of each project public has motivated developers to improve their code.
 
### Implementation of company’s Definitive Media Library (Artifactory, maven, nuget)
### Verification of dependency Security Gates (Xray)
### Automatic deploy in all environments (Octopus Deploy)
Configuration of automatic deployment with Octopus Deploy across various environments.

I am proud to have proposed and collaborated with the fantastic team of One to successfully achieve the goal of the first fully automated deployment in a production environment using Octopus Deploy.

### Backlog and planning (Jira, Confluence)
Oversight of the agile development of the CI/CD pipeline, including code reviews, backlog management, and iterative releases of new versions.

### Regular update of the CI/CD infrastructure (security patches)
Maintenance of the CI/CD infrastructure through tool updates and application of security patches.

### Innovator culture promoter (Docker, Ansible, TDD)
### Continuous improvement and collaborative environment (DevOps)
Fostering of a collaborative environment, with initiatives to make project data visible driving continuous improvement in applications.


## Tools Used
Source Control: GitHub Enterprise

Responsible for the tools:
- GitHub
- Jenkins
- Sonarqube
- Jfrog Artifactory
- Jfrog Xray
- Octopus Deploy

Programming languages: Groovy and Java

ServiceNow SNOW

JIRA

MS Project

## Main Tasks
Product Owner and Scrum Master of CICD shared pipeline

Leading team, agile methodology, test driven development, code review

Iterative and continuous improvement

Managing team’s backlog and product quality

Developing the team’s technical proficiency and growing

Introduces and improves to software development automations (CI/CD)

Keep CICD infrastructure up-to-date, LCM activities

Responsible for the Aduno Gruppe (now Viseca) applications

WEB sites, WEB applications, Web Services, CRM Issuing, Acquirer Suite
- Aduno Website (dismissed)
- [Viseca](https://www.viseca.ch)
- [Surprize](https://one-digitalservice.ch/public/en/surprize) today moved on [One](https://one-digitalservice.ch/)
- [Cashgate](https://www.cashgate.ch/) (sell to Cembra)
- AGIOS (Internal CRM, JAVA)
- Trident (dismissed, PLSQL Suite)

Developing with ITIL and AGILE methodology, use of TDD and CICD pipeline

Leading teams in different areas, hiring
- Java
- .Net
- SQL

Implement a common strategy to align all teams on the same development process and tools 

Maintenance and support for applications in the credit card payment environment

Support the new application Surprize

Support the Terminal Card Reader

## Job reference
I will send the reference by e-mail on request.

![Viseca](/assets/images/L_VIS_MCV_A4_4f_rgb_1707.png)

[www.viseca.ch](https://www.viseca.ch/)
