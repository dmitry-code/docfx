---
title: Suspicious outgoing rdp network activity
description: Suspicious outgoing rdp network activity
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Suspicious outgoing RDP network activity**

## Description
Network traffic analysis detected anomalous outgoing Remote Desktop Protocol (RDP) communication to %{Victim IP} originating from %{Compromised Host} (%{Attacker IP}), a resource in your deployment. When the compromised resource is a load balancer or an application gateway, the suspected outgoing traffic has been originated from to one or more of the resources in the backend pool (of the load balancer or application gateway). Specifically, sampled network data shows %{Number of Connections} outgoing connections from your resource, which is considered abnormal for this environment. This activity may indicate that your machine was compromised and is now used to brute force external RDP end points. Note that this type of activity could possibly cause your IP to be flagged as malicious by external entities.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
High




