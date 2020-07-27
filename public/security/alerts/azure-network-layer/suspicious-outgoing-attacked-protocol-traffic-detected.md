---
title: Suspicious outgoing attacked protocol traffic detected
description: Suspicious outgoing attacked protocol traffic detected
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Suspicious outgoing %{Attacked Protocol} traffic detected**

## Description
Network traffic analysis detected suspicious outgoing traffic from %{Compromised Host} to destination port %{Most Common Port}. When the compromised resource is a load balancer or an application gateway, the suspected outgoing traffic has been originated from to one or more of the resources in the backend pool (of the load balancer or application gateway). This behavior may indicate that your resource is taking part in %{Attacked Protocol} brute force attempts or port sweeping attacks.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




