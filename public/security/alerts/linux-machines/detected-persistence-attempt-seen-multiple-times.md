---
title: Detected persistence attempt seen multiple times
description: Detected persistence attempt seen multiple times
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**Detected persistence attempt [seen multiple times]**

## Description
Analysis of host data on %{Compromised Host} has detected installation of a startup script for single-user mode. It is extremely rare that any legitimate process needs to execute in that mode, so this may indicate that an attacker has added a malicious process to every run-level to guarantee persistence. This behavior was seen [x] times today on the following machines: [Machine names]

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




