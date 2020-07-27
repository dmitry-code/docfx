---
title: Detected suspicious file cleanup commands
description: Detected suspicious file cleanup commands
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected suspicious file cleanup commands**

## Description
Analysis of host data on %{Compromised Host} detected a combination of systeminfo commands that has previously been associated with one of activity group GOLD's methods of performing post-compromise self-cleanup activity.  While 'systeminfo.exe' is a legitimate Windows tool, executing it twice in succession, followed by a delete command in the way that has occurred here is rare.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
High




