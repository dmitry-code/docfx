---
title: Privileged container detected
description: Privileged container detected
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**Privileged container detected**

## Description
Kubernetes audit log analysis detected a new privileged container. A privileged container has access to the node's resources and breaks the isolation between containers. If compromised, an attacker can use the privileged container to gain access to the node.

## Intent ([Learn more](/public/security/alerts/intentions.md))
PrivilegeEscalation

## Severity
Low




