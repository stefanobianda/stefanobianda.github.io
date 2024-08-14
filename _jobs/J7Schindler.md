---
title: "Head of Software Development by R&D-CO"
permalink: /jobs/J3Schindler/
layout: single
excerpt: "Schindler"
redirect_from:
  - /theme-setup/
author_profile: true
toc: true
order_number: 7
header:
  overlay_image: /assets/images/schindler-cabin-inside.jpg
  og_image: /assets/images/schindler-cabin-inside.jpg
  teaser: /assets/images/schindler-cabin-inside.jpg
prev:
  url: /jobs/J2LaPosta/
  title: J2LaPosta
next:
  url: /jobs/J4Viseca/
  title: J4Viseca
---

# Head of Software Development by R&D-CO

From  September 2005 to December 2011

## Description
Responsible for the entire software development of the BIONIC elevator sold in nearly all parts of the world.
- 70000 installation/year (New installation and Modernization)
- Lead 25 software engineers (Locarno, Ebikon, Stuttgart, Luzern - BBV)
- budget 4M CHF/


Thanks to my great team, we are extending the capabilities of our product.
We support different traction system, different doors type, double entrances, duplex system, 25 floors.


The main controller software and the Car Operating Panel (COP) are written in C++, 
the Landing Operating Panels (LOP) are written in assembler.

The common used protocol for the communication is the CAN bus,
exception are the LOP's that are using a proprietary protocol called Biobus.

## Main Tasks
- Responsible for the real time embedded core software of Schindler's elevator
- Lead teams (on-site, near and offshore), hiring
- Budget overview
- Requirement, iteration plan, quality improve and test strategy
- Managing team’s backlog and product quality
- Finalization of official releases
- Developing the team’s technical proficiency and growing
- Code languages
  - C++
  - C
  - Assempler

## Tools Used
- Clear Case
- Clear Quest
- Rational Rose 98
- MS project

## Technologies
- C++ (main controller)
- C (Low level)
- Assembler (LOPs)
- CAN protocol
- Unix
- Multi-Thread
- Embedded
- OOAD
- UML
- Code Generation
- SRS
- Test Case and Test Suite


# Achievements

## Budget monitoring and release planning.
Successfully managed conflicts and ensured customer satisfaction within timelines and budgets despite changes in project schedules and priorities (ALM, Clear Case, Clear Quest, UCM).

## Application of Object-Oriented Analysis and Design (OOAD) methodology with UML modeling.
Application of OOAD methodology for the development of embedded core software for the elevator.

I used the OOAD methodology, overseeing the architecture while ensuring adherence to SOLID principles and the appropriate use of design patterns.

Some of the used pattern:
- Singleton: Ensures a class has only one instance and provides a global point of access to it.
- Abstract Factory: Provides an interface for creating families of related or dependent objects without specifying their concrete classes.
- Facade: Provides a simplified interface to a complex subsystem, making it easier to use.
- Observer: Defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.
- State: Allows an object to alter its behavior when its internal state changes, appearing to change its class.

## Code generation from UML model (Rational Rose, Rhapsody).
Definition of classes and methods in the UML model and generation of the C++ code from the model.

Utilizing the code generation from the model ensures that the model remains up-to-date, thereby maintaining accurate the documentation of the developed code.

## Documentation of Software Requirement Specification (SRS).
Documentation of behavior for a complex real-time multitasking project using SRS. 

Detailed SRS covering initial conditions, trigger, expected behavior, final condition, and alternatives for unexpected events.
Simple and simplified example of an elevator:
- Initial condition
  - Door is open
- Trigger
  - Timer door open has expired 
- Expected behavior
  - Door is closing
  - Door is closed
- Final condition
  - Door is closed

- Alternatives: Photocell activated
  - Door is opening
  - Door is open
  - DoorOpen Timer is started


## Adherence to SOLID principles and application of design patterns.
Development of robust and maintainable software, respecting the SOLID principles and using design patterns.

SOLID principles:
- Single Responsibility Principle (SRP)
- Open/Closed Principle (OCP)
- Liskov Substitution Principle (LSP)
- Interface Segregation Principle (ISP)
- Dependency Inversion Principle (DIP)

## Development of a single software for new installations and modernization..
New installations or modernizations, although with different hardware and peripherals, always using the same software.

A new installation has a defined type of drive, door, Car Operating Panel (COP), and Landing Operating Panel (LOP).
In contrast, a modernization installation features different drives, different door types, and different COPs and LOPs.
The main board for new installations and modernization system is different, with varying CPUs, input/output capabilities, and memory sizes.
The software, upon startup, handles all types of hardware and performs a learning trip to gather all necessary information for correct operation.

With the implemented layer, we were able to develop a windows simulator running on a PC for testing purposes

## Adoption of an Agile mindset with monthly sprint planning.
One-month sprint with management of customer requests and feedback.

I was responsible for planning all aspects of software development with one-month iterations. 
Each sprint involved defining new requirements, creating implementation plans, assigning tasks to developers, managing the backlog by prioritizing bug fixes, setting testing goals, and prioritizing discovered bugs.


## Continuous improvement and team collaboration (Locarno, Stuttgart, Ebikon, Lucern).
Continuous improvement through optimal management of the backlog, team collaboration working on bugfix

In each iteration, I planned complex bug fixes by discussing the necessary tasks with the team.

The Mean Time Between Failures (MTBF) has increased from 2 months to 12 months.

## Agile Release finalization for specific target (New, Mod, EU, ASIA, ...)
The finalization of a release involved discussions with the Product Owners and customer feedback; the plan underwent redefinition according to the priorities of each project.

The release was often finalized by project and specific geographic area. 
This means that the analyzed backlog was limited to the geographic area, its specific functions and hardware. 
New features were finalized in accordance with customer feedback through pre-release versions only for Schiundler towers test.

## Remote monitoring and error log detection
Implementation of a remote connection to the elevator for operation monitoring. 
Logging of events prior to a fatal error (installation freeze) for verification of occurrences.

Through recording the events preceding fatal errors, we were able to identify the root causes of the problems, which helped us solve several complex cases (not all software-related!).


# Notable results
- Quality: 
  - Improvement of Mean Time Between Failures (MTBF) from 2 months to 12 months.
- Increase of functionalities:
  - from 10 floors to 25 floors
  - added double doors functionality
  - from 10 to 50 fire fighter solutions
  - added semi-automatic and manual door system
  - from single to double installation (3 installations was in planing)
  - added multiple drive type for modernization


![Schindler](/assets/images/schindler-hd-logo-thumbnail.png)

[www.schindler.ch](https://www.schindler.ch)
