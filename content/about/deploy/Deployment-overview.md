<!--
title: "What to Expect When You're Deploying"
description: "Introduction to Contrast customer deployment"
tags: "Contrast about setup onboarding deployment assess protect"
-->


Getting started with Assess and Protect can be as simple as [setting up the Contrast application and installing an agent](https://docs.contrastsecurity.com/installation-setup.html#quick-start). Alternatively, the following steps prepare an organization to reap the full benefits of Assess and Protect, and quantify the value they receive.

## Steps

The following steps introduce Contrast to an organization, integrate it into their workflow and quantify the value it has brought to the initial adopters of the technology. (Steps dedicated specifically to Assess or Protect are marked.)

* **Kickoff:** Introductions, align vision and quantify success metrics.
* **Solution Architecture:** Tailor implementation.
* **Project Plan:** Agree on details and timing.
* **Contrast UI Preparation:** Get ready to add applications.
* **Application Baseline:** Initial analysis of applications. (Assess)
* **Vulnerability Management:** How vulnerabilities are analyzed, communicated and tracked. (Assess)
* **Pre-production:** Integrate into ecosystem and perform Initial analysis. (Protect)
* **Production Monitor:** Observe in monitor mode and validate workflow. (Protect)
* **Contrast Business Review:** Quantify the gained value.

Contrast’s Customer Success team will continue working with you to help your organization increasingly gain value from the time and money you’ve invested.

## Roles and Responsibilities

The following roles may represent one or more people. One person may also play multiple roles. (Roles related specifically to Assess or Protect are marked.)

* **Project Manager:** Works with Contrast on deployment schedule, tracks internal milestones and task completion, and is responsible for internal communications.
* **Contrast UI Administrator:** Prepares technical environment; manages users, access controls, reports, upgrades and communications; interfaces with Contrast Support.
* **Application Security Lead:** Creates and governs policy, security controls and the vulnerability management process.
* **Development Leads:** Manages vulnerability remediation and build integration. (Assess)
* **QA Leads:**	Oversees performance and QA testing of Protect-enabled servers as well as installation of agent(s) in QA environments. (Protect)
* **Operations:** Pushes Protect-enabled servers into Production. (Protect)
* **Executive Sponsor - Security:** Executive from the security group who oversees Contrast deployment.
* **Executive Sponsor - Development:** Executive from the development group who oversees Contrast deployment.

## Kickoff

The focus of the Kickoff meeting is to introduce all the parties, and get everyone aligned on the current business issues, reasons for purchasing Contrast, strategic vision for Contrast as well as the scope and success metrics for the initial applications to be onboarded. The Customer Success team will also review the Contrast Quick Value deployment methodology and the Contrast Security Maturity Model, project roles and responsibilities, and a plan for the next stage: Solution Architecture.

### Before You Start

To prepare for this meeting, Contrast representatives will meet with the primary stakeholder, who will participate in each role in this deployment. Each attendee also should have [a high-level understanding of Contrast Security](https://www.youtube.com/watch?v=Gviz-SiJGWk).


## Solution Architecture

In this critical stage of the project, Contrast will gather information about your current state, then recommend the Contrast best practices for your specific process and technical needs during the initial phase. This will require a detailed, technical conversation on requirements - including security policy, metrics/reporting, integrations, user authentication, training and access control - as well as the vulnerability management process and system design. The Contrast team will also work with you to designate up to three applications to onboard for your initial baseline.

### Before You Start

To prepare for this meeting, you'll need verify the following information: 

* A list of candidate servers to be included in your initial onboarding. 
* A list of candidate applications to be included in your initial baseline. 
* Meet the technical requirements for [Java](https://docs.contrastsecurity.com/installation-java.html#java-supported), [.NET](https://docs.contrastsecurity.com/installation-net.html#net-supported), [Node](https://docs.contrastsecurity.com/installation-node.html#node-supported) or [Ruby](https://docs.contrastsecurity.com/installation-ruby.html#ruby-supported).
* A list of tools used by development teams: integrated development environments (IDEs), bug trackers, continuous integration and access management.
* A workflow of how vulnerabilities are triaged, managed and communicated to developers.
* Known [security controls](https://docs.contrastsecurity.com/admin-policymgmt.html#security).


## Project Plan

Once all the requirements and solution design are finalized in the Solution Architecture stage, it’s time to map out a project plan. Contrast will select one of its proven project plan templates, and collaborate with you to tailor it to your specific needs. You will also decide on 
project governance - status meetings, tracking of issues, etc. - and get buy-in from key stakeholders.

### Before You Start

To prepare for this meeting, you'll need verify the following information: 

* List of important dates for candidate applications and their servers (e.g., start of next sprint, code freezes and planned configuration changes).
* List of owners of [continuous integration](github.com/Contrast-Security-OSS/) and [alerting tools](https://docs.contrastsecurity.com/admin-orgintegrations.html) in your ecosystem. (Protect)


## The Contrast Application 

To prepare the Contrast application, sometimes called “TeamServer”, some training and configuration is in order. For Assess, you will set configurations, teach administrators about applicable features, install the first agent, implement security policy and demonstrate reporting. For Protect, you will set configurations, enable rules and whitelists/blacklists, teaching administrators about available features, and train users how the application finds and delivers alerts.

### Before You Start

To prepare for this meeting, you'll need verify the following information: 

* A list of names and email address of users who will be involved in the initial applications and servers, and need access to the Contrast application.
* Identify the first application to be onboarded, and invite the Agent Administrator to the meeting. (Assess)
* Identify administrators to be trained. (Assess)
* Finalize security policy. (Assess)
* If **on-premises**, verify that you meet [technical environmental requirements](https://docs.contrastsecurity.com/installation-setup.html#contrast-reqs) before installing the Contrast application.


## Baseline Initial Applications

Establish a baseline of true vulnerabilities for the initial applications, as well as a list of their third-party libraries.

### Objectives

* Install one of the agents: 
 * [Java](https://docs.contrastsecurity.com/installation-java.html#java-supported)
 * [.NET](https://docs.contrastsecurity.com/installation-net.html#net-supported)
 * [Node](https://docs.contrastsecurity.com/installation-node.html#node-supported) 
 * [Ruby](https://docs.contrastsecurity.com/installation-ruby.html#ruby-supported)
* Exercise the application and possibly run functional and/or regression tests.
* Discuss found vulnerabilities.
* Apply any [security controls](https://docs.contrastsecurity.com/admin-policymgmt.html#security) and [exclusions](https://docs.contrastsecurity.com/admin-policymgmt.html#exclude) that are needed.

Preparation for this meeting: 

* A separate scheduled meeting with each application team to baseline the application.
* A list of known [security controls](https://docs.contrastsecurity.com/admin-policymgmt.html#security) used by existing vulnerability detection tools.
* An introduction to owners of [continuous integration](https://github.com/Contrast-Security-OSS) tools in your ecosystem.


## Manage Vulnerabilities

Your next focus is integrating your security management process and security policy governance.

### Objectives

* Define where alerts should be routed.
* [Integrate with tools](https://docs.contrastsecurity.com/admin-orgintegrations.html) in your ecosystem: IDEs, Bug Trackers and continuous integration.
* Generate and verify reports.

Preparation for this meeting: 

* List of owners of tools in your ecosystem: IDEs, bug trackers, continuous integration and access management.
* An explanation of your vulnerability mitigation workflow for each application.


## Contrast Business Review

At the beginning of the onboarding process, Contrast worked with you to define your desired business outcomes and associated KPIs for the initial deployment of Assess. It’s now time to verify and quantify the value you’re receiving from using Assess, and communicate the results to your executives and key stakeholders. 

### Objectives

* Align on business outcome attainment and the value you’re receiving from Assess.
* Agree on a plan to increase user/application adoption and value creation as you move forward.

Preparation for this meeting: 

* Provide results for KPIs where Contrast doesn’t have access to the data.
* Have appropriate stakeholders preview the Contrast Business Review deck to ensure alignment.
* Project Manager to coordinate scheduling of Contrast Business Review with Exec Sponsors.


**Note:** Follow-up after the Contrast Business Review meeting typically includes plans for user/application adoption, increasing value, and addressing key challenges and issues.




