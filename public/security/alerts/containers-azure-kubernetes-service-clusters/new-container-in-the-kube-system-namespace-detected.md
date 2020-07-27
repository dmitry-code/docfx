---
title: New container in the kube system namespace detected
description: New container in the kube system namespace detected
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**New container in the kube-system namespace detected**

## Description
Kubernetes audit log analysis detected a new container in the kube-system namespace that isn't among the containers that normally run in this namespace. The kube-system namespaces shouldn't contain user resources. Attackers can use this namespace to hide malicious components.

## Intent ([Learn more](/public/security/alerts/intentions.md))
Persistence

## Severity
Low




