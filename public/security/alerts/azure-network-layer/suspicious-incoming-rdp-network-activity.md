---
title: Suspicious incoming rdp network activity
description: Suspicious incoming rdp network activity
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Suspicious incoming RDP network activity**

## Description
Network traffic analysis detected anomalous incoming Remote Desktop Protocol (RDP) communication to %{Victim IP}, associated with your resource %{Compromised Host}, from %{Attacker IP}. When the compromised resource is a load balancer or an application gateway, the suspected incoming traffic has been forwarded to one or more of the resources in the backend pool (of the load balancer or application gateway). Specifically, sampled network data shows %{Number of Connections} incoming connections to your resource, which is considered abnormal for this environment. This activity may indicate an attempt to brute force your RDP end point

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




