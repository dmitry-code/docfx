---
title: Potential attempt to bypass applocker detected
description: Potential attempt to bypass applocker detected
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Potential attempt to bypass AppLocker detected**

## Description
Analysis of host data on %{Compromised Host} detected a potential attempt to bypass AppLocker restrictions. AppLocker can be configured to implement a policy that limits what executables are allowed to run on a Windows system. The command-line pattern similar to that identified in this alert has been previously associated with attacker attempts to circumvent AppLocker policy by using trusted executables (allowed by AppLocker policy) to execute untrusted code. This could be legitimate activity, or an indication of a compromised host.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
High




