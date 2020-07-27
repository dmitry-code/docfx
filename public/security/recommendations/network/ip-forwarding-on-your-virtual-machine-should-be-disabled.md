---
title: Ip forwarding on your virtual machine should be disabled
description: Ip forwarding on your virtual machine should be disabled
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Recommendation
**IP forwarding on your virtual machine should be disabled**

## Description & related policy
Disable IP forwarding. When IP forwarding is enabled on a virtual machine's NIC, the machine can receive traffic addressed to other destinations. IP forwarding is rarely required (for example, when using the VM as a network virtual appliance), and therefore, this should be reviewed by the network security team.<br>(Related policy: [Preview]: IP Forwarding on your virtual machine should be disabled)

## Severity
Medium

## Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))
N

## Resource type
Virtual machine




