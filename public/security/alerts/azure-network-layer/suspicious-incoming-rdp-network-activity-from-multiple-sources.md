---
title: Suspicious incoming rdp network activity from multiple sources
description: Suspicious incoming rdp network activity from multiple sources
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Suspicious incoming RDP network activity from multiple sources**

## Description
Network traffic analysis detected anomalous incoming Remote Desktop Protocol (RDP) communication to %{Victim IP}, associated with your resource %{Compromised Host}, from multiple sources. When the compromised resource is a load balancer or an application gateway, the suspected incoming traffic has been forwarded to one or more of the resources in the backend pool (of the load balancer or application gateway). Specifically, sampled network data shows %{Number of Attacking IPs} unique IPs connecting to your resource, which is considered abnormal for this environment. This activity may indicate an attempt to brute force your RDP end point from multiple hosts (Botnet)

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




