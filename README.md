# Adoption Virtual Assistant (AVA)

## Overview

The Adoption Virtual Assistant (AVA) was an AI-powered virtual assistant developed during my internship.

AVA was developed using **Microsoft Copilot Studio** to help users access adoption-related guidance, resources, and best practices through a conversational interface. The project aimed to reduce dependency on manual support while making relevant adoption knowledge easier to access.

> **Note:** This repository contains documentation and selected project information only. The original Copilot Studio agent, internal documents, datasets, prompts, and other company materials are not included due to confidentiality and access restrictions.

---

## Problem Statement

The UTDI Adoption team maintained a collection of resources and guidance related to digital adoption. Users could require support in understanding adoption processes, finding relevant resources, or determining which tools and approaches were suitable for their needs.

As the project progressed, there was a need for a more accessible way for users to obtain adoption-related information without relying entirely on direct assistance from the Adoption team.

AVA was developed to provide a conversational interface for accessing this knowledge.

---

## Project Objectives

The main objectives of AVA were to:

* Provide users with conversational access to adoption-related knowledge.
* Guide users according to their level of familiarity with adoption concepts.
* Reduce repetitive manual enquiries to the Adoption team.
* Improve accessibility to existing adoption resources.
* Provide answers based on verified internal reference materials.
* Support users in finding relevant tools, guidance, and examples.

---

## Solution

AVA was implemented using **Microsoft Copilot Studio** and integrated with the Microsoft 365 environment.

The solution consisted of a parent agent supported by specialised child agents designed around different user experience levels:

```text
                    AVA
                     │
        ┌────────────┼────────────┐
        │            │            │
    Beginner     Intermediate   Matured
      Guide         Guide        Guide
        │            │            │
        └────────────┼────────────┘
                     │
             Adoption Knowledge
                     │
       ┌─────────────┼─────────────┐
       │             │             │
    Guidance      Tools        Resources
```

The different guides were designed to support users with different levels of familiarity with digital adoption.

### Beginner Guide

Designed for users who were relatively new to adoption concepts and required introductory guidance.

### Intermediate Guide

Designed for users who understood the general adoption concept but required practical guidance, templates, examples, or information on how to begin an adoption activity.

### Matured Guide

Designed for users with more specific or advanced questions who required detailed information, analysis, examples, or best practices.

---

## Technology Used

| Technology               | Purpose                                        |
| ------------------------ | ---------------------------------------------- |
| Microsoft Copilot Studio | AI agent development                           |
| Microsoft Teams          | User access and deployment                     |
| Microsoft 365            | Integration with the existing work environment |
| SharePoint               | Knowledge and reference source                 |
| GPT-4.1                  | Generative AI capabilities                     |
| Microsoft Power Platform | Supporting the development environment         |

---

## Knowledge Sources

AVA was designed to retrieve information from verified internal adoption resources.

The project involved working with different types of organisational content, including:

* SharePoint documents
* PDF documents
* PowerPoint presentations
* Excel files
* Microsoft Lists
* Power BI resources

The knowledge structure covered adoption concepts, guidance, tools, examples, and best practices.

Due to the confidential nature of these materials, the original source files are not included in this repository.

---

## Development Process

The project followed an iterative development approach.

### 1. Requirement Understanding

The existing adoption process and common user information needs were reviewed to identify areas where a virtual assistant could provide value.

### 2. Knowledge Preparation

Relevant adoption resources were identified, organised, and prepared as knowledge sources for the Copilot agent.

### 3. Agent Development

The main AVA agent and supporting specialised agents were configured using Microsoft Copilot Studio.

### 4. Testing

The agent was tested using different types of user questions to evaluate:

* Answer relevance
* Source utilisation
* Accuracy
* Topic routing
* User experience
* Handling of unanswered questions

### 5. Refinement

The agent configuration and knowledge structure were refined based on testing results and observed response behaviour.

### 6. Deployment

AVA was subsequently made available through the Microsoft 365 environment, including Microsoft Teams.

---

## My Contribution

During the project, my responsibilities included:

* Designing the overall structure of the virtual assistant.
* Developing the AVA agent using Microsoft Copilot Studio.
* Structuring the parent and child agent architecture.
* Preparing and organising knowledge sources.
* Configuring topics and conversational flows.
* Testing agent responses against expected information.
* Identifying and resolving response and routing issues.
* Refining the agent to improve answer relevance and reliability.
* Supporting deployment through the Microsoft 365 environment.
* Monitoring usage and evaluating the assistant's performance.

---

## Project Outcome

The deployed assistant was evaluated using usage and response analytics.

The recorded project results included:

| Metric               | Result |
| -------------------- | -----: |
| Source utilisation   |    70% |
| Questions answered   |    81% |
| Questions unanswered |    19% |
| Response quality     |    98% |
| Sessions             |    182 |
| Engagement           |    81% |
| Satisfaction         |    5/5 |

These results were used to identify areas for further improvement, particularly for questions that could not be answered using the available knowledge sources.

---

## Key Challenges

### Knowledge Accuracy

One of the main challenges was ensuring that the assistant provided information based on the available reference materials rather than generating unsupported responses.

This required continuous testing and refinement of the agent's knowledge structure and configuration.

### Multi-Agent Configuration

The project used multiple specialised agents to support different user experience levels. Managing the relationship between the parent agent and child agents required testing to ensure that queries were routed appropriately.

### Knowledge Source Management

The assistant relied on a collection of organisational resources. Maintaining consistent and relevant knowledge sources was important to ensure that responses remained useful and aligned with the available documentation.

### Confidentiality

The project involved internal organisational information. Therefore, the original agent, internal documents, and company-specific data cannot be publicly shared.

This repository provides a portfolio-safe overview of the project without exposing confidential materials.

---

## Skills Demonstrated

This project allowed me to develop experience in:

* Microsoft Copilot Studio
* Generative AI applications
* Conversational AI
* AI agent architecture
* Knowledge-grounded AI
* Microsoft 365 integration
* SharePoint knowledge management
* Prompt and topic configuration
* Agent testing and evaluation
* Data and knowledge organisation
* User experience design
* AI solution development

---

## Project Context

**Project:** Adoption Virtual Assistant (AVA)
**Platform:** Microsoft Copilot Studio
**Environment:** Microsoft 365 / Microsoft Teams
**Project Type:** Internship Project
**Focus:** Digital Adoption & Generative AI

---

## Confidentiality Notice

This repository is intended to document my technical experience and contribution to the project.

The original project environment contained proprietary and confidential organisational information. Therefore, internal documents, datasets, agent exports, conversation data, credentials, internal URLs, and other restricted materials are intentionally excluded from this repository.

The information presented here has been limited to non-confidential project descriptions and technical concepts suitable for portfolio documentation.
