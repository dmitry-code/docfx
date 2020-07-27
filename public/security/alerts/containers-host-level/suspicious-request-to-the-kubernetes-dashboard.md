---
title: Suspicious request to the kubernetes dashboard
description: Suspicious request to the kubernetes dashboard
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**Suspicious request to the Kubernetes Dashboard**

## Description
Machine logs indicate that a suspicious request was made to the Kubernetes Dashboard. The request was sent from a Kubernetes node, possibly from one of the containers running in the node. Although this behavior can be intentional, it might indicate that the node is running a compromised container.

## Intent ([Learn more](/public/security/alerts/intentions.md))
Lateral movement

## Severity
Medium




