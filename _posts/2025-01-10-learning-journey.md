---
layout: posts
title: "Streamlining My Homelab Setup: A Learning Journey"
date: 2025-01-10
categories: [homelab]
tags: [homelab, planning, project]
---

## Streamlining My Homelab Setup: A Learning Journey

### Introduction
This is the first in a series of quite afew posts documenting my approach to optimizing and automating my Homelab environment by levering free Azure services and affordable refurbished hardware that I can easily proqure online from EBay, OLX, etc such as Mini Pcs or evenlaptops. The project aims to set up a Homelab with a couple of well known services such as Plex, Home Assistant, *arr suite and a lot more. 

Setting up a Homelab can seem daunting, with approaches ranging from simple manual setups to full-scale home cloud implementations. My approach strikes a balance, leveraging existing resources and progressively implementing automation to ensure easy maintenance and intervention when issues arise. In all fairness I am using this project to get further knowledge and practice in setting up Azure Arc on premise, making use of the Azure Portal and DevOps Pipelines to provision VMs and deploy Azure Kubernetes Services.

I will explore two main dimensions: utilizing free or inexpensive automation tools and service offerings, and identifying optional steps where professional solutions could be integrated. The initial assumption is that I have PC/laptop capable of Running Windows and Hyper-V for virtualization. Additional devices will be introduced throughout the guides to practice key concepts, such as clustering, GitOps, Provisioning, PXE, etc.

### Project Overview
Since this project involves getting acquainted with several technology stacks, my initial approach is to ensure I have a few essential services up and running on my home network before going through more elaborate approach. For this purpose, I found an old Lenovo ThinkPad T480 laptop running Windows. (These devices are easily available online and are a good start for such projects due to their affordability and reliability.)

Although the usual approach for such projects is using Linux, I chose Windows as an initial control plane because it is typically pre-installed and licensed on these devices, making it an accessible starting point. I installed Plex Media Server and used the built-in Hyper-V feature to set up a simple Docker Compose file within an Ubuntu Virtual Machine. This setup allows me to test a few key concepts and actually having and understand how I can leverage this project effectively. Running Docker on Windows requires some tweaking, especially for Linux containers, but there are numerous guides available online.


### Phase 1

1. **Defining Requirements:** I will outline the project’s goals, current infrastructure, desired outcomes, and any constraints.
2. **Outline Standards:** I will outline the standards I am following so I will set some guard rails in terms of defining a solution later on
3. **High Level Design:** I will draft a visual representation of the main components. This visualization will map out the interactions between various components and ensure a thorough understanding of the system.
4. **Propose technical stocks:** I will explore common components of technical stacks, including readily available services, online services, on-premise solutions, monitoring, deployments, provisioning, backend technologies, databases, and DevOps tools.

### Phase 2

1. **Provision Resources:** I will start by allocating the necessary computing power, storage, and network capabilities for my project's infrastructure.
2. **Setup Deployment:** I will establish a deployment pipeline to deply  applications and services into environments with minimal manual intervention.
3. **Implement:** I will develope and configure the necessary components, integrating them into the overall system, and ensuring they function as intended.
4. **Monitoring:** I will implement a monitoring system to quickly identify and address issues, ensuring everything runs smoothly.

