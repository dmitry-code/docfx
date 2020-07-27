---
title: Container with a sensitive volume mount detected
description: Container with a sensitive volume mount detected
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**Container with a sensitive volume mount detected**

## Description
Kubernetes audit log analysis detected a new container with a sensitive volume mount. The volume that was detected is a hostPath type that mounts a sensitive file or folder from the node to the container. If the container gets compromised, the attacker can use this mount to gain access to the node.

## Intent ([Learn more](/public/security/alerts/intentions.md))
PrivilegeEscalation

## Severity
Medium




