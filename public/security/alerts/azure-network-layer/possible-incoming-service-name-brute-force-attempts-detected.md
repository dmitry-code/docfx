---
title: Possible incoming service name brute force attempts detected
description: Possible incoming service name brute force attempts detected
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Possible incoming %{Service Name} brute force attempts detected**

## Description
Network traffic analysis detected incoming %{Service Name} communication to %{Victim IP}, associated with your resource %{Compromised Host} from %{Attacker IP}. When the compromised resource is a load balancer or an application gateway, the suspected incoming traffic has been forwarded to one or more of the resources in the backend pool (of the load balancer or application gateway). Specifically, sampled network data shows suspicious activity between %{Start Time} and %{End Time} on port %{Victim Port}. This activity is consistent with brute force attempts against %{Service Name} servers.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




