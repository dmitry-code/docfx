---
title: All network ports should be restricted on nsg associated to your vm
description: All network ports should be restricted on nsg associated to your vm
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Recommendation
**All network ports should be restricted on NSG associated to your VM**

## Description & related policy
Harden the network security groups of your Internet-facing VMs by restricting the access of your existing allow rules.<br>This recommendation is triggered when any port is opened to *all* sources (except for ports 22, 3389, 5985, 5986, 80, and 1443).<br>(Related policy: Access through internet facing endpoint should be restricted)

## Severity
High

## Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))
N

## Resource type
Virtual machine




