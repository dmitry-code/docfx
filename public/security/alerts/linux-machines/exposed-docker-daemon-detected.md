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
Machine logs indicate that your Docker daemon (dockerd) exposes a TCP socket. By default, Docker configuration, does not use encryption or authentication when a TCP socket is enabled. This enables full access to the Docker daemon, by anyone with access to the relevant port.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




