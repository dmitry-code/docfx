---
title: Detected suspicious execution of vbscript encode command
description: Detected suspicious execution of vbscript encode command
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected suspicious execution of VBScript.Encode command**

## Description
Analysis of host data on %{Compromised Host} detected the execution of VBScript.Encode command. This encodes the scripts into unreadable text, making it more difficult for users to examine the code. Microsoft threat research shows that attackers often use encoded VBscript files as part of their attack to evade detection systems. This could be legitimate activity, or an indication of a compromised host.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




