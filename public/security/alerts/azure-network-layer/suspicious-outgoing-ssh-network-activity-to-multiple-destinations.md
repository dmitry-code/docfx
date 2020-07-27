---
title: Suspicious outgoing ssh network activity to multiple destinations
description: Suspicious outgoing ssh network activity to multiple destinations
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Suspicious outgoing SSH network activity to multiple destinations**

## Description
Network traffic analysis detected anomalous outgoing SSH communication to multiple destinations originating from %{Compromised Host} (%{Attacker IP}), a resource in your deployment. When the compromised resource is a load balancer or an application gateway, the suspected outgoing traffic has been originated from to one or more of the resources in the backend pool (of the load balancer or application gateway). Specifically, sampled network data shows your resource connecting to %{Number of Attacked IPs} unique IPs, which is considered abnormal for this environment. This activity may indicate that your resource was compromised and is now used to brute force external SSH end points. Note that this type of activity could possibly cause your IP to be flagged as malicious by external entities.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




