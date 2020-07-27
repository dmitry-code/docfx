---
title: Exposed docker daemon detected
description: Exposed docker daemon detected
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**Exposed Docker daemon detected**

## Description
Machine logs indicate that your Docker daemon (dockerd) exposes a TCP socket. By default, Docker configuration doesn't use encryption or authentication when a TCP socket is enabled. Anyone with access to the relevant port can then get full access to the Docker daemon.

## Intent ([Learn more](/public/security/alerts/intentions.md))
Exploitation / Execution

## Severity
Medium




