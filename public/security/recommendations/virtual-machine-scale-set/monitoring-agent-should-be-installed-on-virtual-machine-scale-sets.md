---
title: Monitoring agent should be installed on virtual machine scale sets
description: Monitoring agent should be installed on virtual machine scale sets
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Recommendation
**Monitoring agent should be installed on virtual machine scale sets**

## Description & related policy
Security Center uses the Microsoft Monitoring Agent (MMA) to collect security events from your Azure virtual machine scale sets. You cannot configure auto-provisioning of the MMA for Azure virtual machine scale sets. To deploy the MMA on virtual machine scale sets (including those used by Azure managed services such as Azure Kubernetes Service and Azure Service Fabric), please follow the procedure in the remediation steps.

## Severity
High

## Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))
**Y**

## Resource type
Virtual machine scale set




