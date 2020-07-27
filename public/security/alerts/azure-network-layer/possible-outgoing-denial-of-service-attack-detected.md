---
title: Possible outgoing denial of service attack detected
description: Possible outgoing denial of service attack detected
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Possible outgoing denial-of-service attack detected**

## Description
Network traffic analysis detected anomalous outgoing activity originating from %{Compromised Host}, a resource in your deployment. This activity may indicate that your resource was compromised and is now engaged in denial-of-service attacks against external endpoints. When the compromised resource is a load balancer or an application gateway, the suspected activity might indicate that one or more of the resources in the backend pool (of the load balancer or application gateway) was compromised. Based on the volume of connections, we believe that the following IPs are possibly the targets of the DOS attack: %{Possible Victims}.  Note that it is possible that the communication to some of these IPs is legitimate.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




