---
title: All authorization rules except rootmanagesharedaccesskey should be removed from service bus namespace
description: All authorization rules except rootmanagesharedaccesskey should be removed from service bus namespace
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Recommendation
**All authorization rules except RootManageSharedAccessKey should be removed from Service Bus namespace**

## Description & related policy
Service Bus clients should not use a namespace level access policy that provides access to all queues and topics in a namespace. To align with the least privilege security model, you should create access policies at the entity level for queues and topics to provide access to only the specific entity.<br>(Related policy: All authorization rules except RootManageSharedAccessKey should be removed from Service Bus namespace)

## Severity
Low

## Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))
N

## Resource type
Compute resources (service bus)




