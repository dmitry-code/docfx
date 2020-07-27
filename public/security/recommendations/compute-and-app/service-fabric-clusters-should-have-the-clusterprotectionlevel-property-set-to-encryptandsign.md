---
title: Service fabric clusters should have the clusterprotectionlevel property set to encryptandsign
description: Service fabric clusters should have the clusterprotectionlevel property set to encryptandsign
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Recommendation
**Service Fabric clusters should have the ClusterProtectionLevel property set to EncryptAndSign**

## Description & related policy
Service Fabric provides three levels of protection (None, Sign, and EncryptAndSign) for node-to-node communication using a primary cluster certificate. Set the protection level to ensure that all node-to-node messages are encrypted and digitally signed.<br>(Related policy: The ClusterProtectionLevel property to EncryptAndSign in Service Fabric should be set)

## Severity
High

## Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))
N

## Resource type
Compute resources (service fabric)




