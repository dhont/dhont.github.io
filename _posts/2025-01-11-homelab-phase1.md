---
layout: posts
title: "My Homelab: Phase 1"
date: 2025-01-11
categories: [homelab]
tags: [homelab, planning, project]
---

### Defining Requirements

#### 1. Introduction
- Purpose of defining requirements
- Importance in the context of the project

#### 2. Project Goals
- High-level objectives
- Specific, measurable outcomes
- Long-term vision for the Homelab

#### 3. Current Infrastructure
- Overview of the existing setup
- Hardware and software currently in use
- Network configuration and connectivity

#### 4. Desired Outcomes
- Specific features and functionalities to be achieved
- Performance improvements and scalability
- Automation and maintenance goals

#### 5. Constraints
- Budget limitations
- Timeframe and deadlines
- Resource availability (hardware, software, personnel)

#### 6. Dependencies
- External services and tools
- Integration with existing systems
- Potential bottlenecks and risks

#### 7. Use Cases and User Stories
- Typical scenarios and workflows
- User interactions and expectations
- Edge cases and exceptional situations

#### 8. Requirements Gathering
- Stakeholder interviews and surveys
- Documentation and analysis of needs
- Prioritization of requirements

#### 9. Functional Requirements
- Detailed list of functionalities
- Technical specifications and criteria
- Acceptance criteria for each requirement

#### 10. Non-Functional Requirements
- Performance metrics and benchmarks
- Security considerations
- Usability and user experience standards


### Outline Standards

The purpose of outlining standards is to ensure consistency, accuracy, and compliance with project requirements. These standards provide clear guidelines on design expectations, materials, methods, and quality, helping to avoid misunderstandings and errors throughout the project. It's essential for these standards to be as agnostic as possible of the technology used, but especially in home projects where resources such as devices and existing licenses are based on availability. This helps to avoid exceeding the project budget.


- **Public Services:** Utilize services such as Azure Pipelines or GitPipelines for CI/CD.
- **GitOps Practices:** Implement Git pull requests to push changes into the system.
- **Continuous Delivery:** Ensure continuous delivery pipelines for efficient deployments.
- **Network Configuration:** Set up virtual LANs for VMs with different roles.
- **Provisioning:** Add new devices/VMs through provisioning with minimal manual steps.
- **Low Power Devices:** Use low-power on-premise devices that are not sensitive to power outages.
- **Backup Power:** Ensure critical services are on devices with backup power.
- **Silent and Energy Efficient:** Home devices should be very silent and low energy.
- **IP Independence:** Ensure services are not dependent on ISP public IP that can change anytime.
- **SSL Services:** Use SSL services with proper certificates, avoiding self-signed ones.


### High Level Design
 I will draft a visual representation of the main components. This visualization will map out the interactions between various components and ensure a thorough understanding of the system.

![Excalidraw Diagram]({{ "/assets/excalidraw/hl-design.excalidraw.png" | relative_url }})

### Propose technical stacks
 I will explore common components of technical stacks, including readily available services, online services, on-premise solutions, monitoring, deployments, provisioning, backend technologies, databases, and DevOps tools.

 