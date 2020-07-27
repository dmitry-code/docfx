---
title: Detected change to a registry key that can be abused to bypass uac
description: Detected change to a registry key that can be abused to bypass uac
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected change to a registry key that can be abused to bypass UAC**

## Description
Analysis of host data on %{Compromised Host} detected that a registry key that can be abused to bypass UAC (User Account Control) was changed. This kind of configuration, while possibly benign, is also typical of attacker activity when trying to move from unprivileged (standard user) to privileged (for example administrator) access on a compromised host.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




