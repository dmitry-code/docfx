---
title: Possible outgoing port scanning activity detected
description: Possible outgoing port scanning activity detected
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Possible outgoing port scanning activity detected**

## Description
Network traffic analysis detected suspicious outgoing traffic from %{Compromised Host}. This traffic may be a result of a port scanning activity. When the compromised resource is a load balancer or an application gateway, the suspected outgoing traffic has been originated from to one or more of the resources in the backend pool (of the load balancer or application gateway). If this behavior is intentional, please note that performing port scanning is against Azure Terms of service. If this behavior is unintentional, it may mean your resource has been compromised.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




