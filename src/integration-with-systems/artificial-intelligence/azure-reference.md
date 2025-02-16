---
summary: Explore the necessary Azure resources for OutSystems 11 (O11) AI components and connectors detailed in this reference guide.
tags: azure services, ai and ml, chatbots, cognitive services, luis
locale: en-us
guid: bff3062c-8092-4b41-abf7-b315d1035d39
app_type: traditional web apps, mobile apps, reactive web apps
platform-version: o11
figma:
audience:
  - full stack developers
  - backend developers
  - architects
  - platform administrators
  - data engineers
outsystems-tools:
  - none
coverage-type:
  - remember
---

# The Azure resources reference

This document lists the Azure resources you need for OutSystems AI components and connectors. The number of resources depends on the use case.

## Components

The list of the OutSystems AI components and the Azure resources they use.

### Chatbot

The chatbot component uses the following components:

* Bot Service (Web App Bot)
* Bot Framework
* QnA Maker Service
* QnA Maker Knowledge Base

## Connectors

The list of the OutSystems AI connectors and the Azure resources they use.

### Language Analysis

  * Requires a **Cognitive Services** resource.

### Azure Bot Framework Connector

  * Requires **Web App Bot**.

### Azure Cognitive Services Connector

  * Requires **Cognitive Services**.

### Azure LUIS Connector

  * Requires **Language Understanding**.
  * Requires **Language Understanding app** created in the LUIS.ai portal.

### Azure QnA Maker Connector

  * Requires **QnA Maker**. 
  * Requires **QnA Knowledge Base** created in QnA Maker portal.

### Azure ML Connector

  * Requires a **Predictive Experiment** created in Azure ML Studio.