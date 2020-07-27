---
title: Authorized ip ranges should be defined on kubernetes services
description: Authorized ip ranges should be defined on kubernetes services
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Recommendation
**Authorized IP ranges should be defined on Kubernetes Services**

## Description & related policy
Restrict access to the Kubernetes service management API by granting API access only to IP addresses in specific ranges. It is recommended to configure authorized IP ranges so only applications from allowed networks can access the cluster.<br>(Related policy: [Preview]: Authorized IP ranges should be defined on Kubernetes Services)

## Severity
High

## Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))
N

## Resource type
Compute resources (Containers)




