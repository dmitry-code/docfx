---
title: Detected suspicious use of pcalua exe to launch executable code
description: Detected suspicious use of pcalua exe to launch executable code
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected suspicious use of Pcalua.exe to launch executable code**

## Description
Analysis of host data on %{Compromised Host} detected the use of pcalua.exe to launch executable code. Pcalua.exe is component of the Microsoft Windows "Program Compatibility Assistant" which detects compatibility issues during the installation or execution of a program. Attackers are known to abuse functionality of legitimate Windows system tools to perform malicious actions, for example using pcalua.exe with the -a switch to launch malicious executables either locally or from remote shares.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




