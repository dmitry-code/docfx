---
title: Detected suspicious use of the nohup command
description: Detected suspicious use of the nohup command
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**Detected suspicious use of the nohup command**

## Description
Analysis of host data has detected suspicious use of the nohup command on %{Compromised Host}. Attackers have been seen running the command nohup from a temporary directory to allow their executables to run in the background. It is not normal to see this command run on files located in a temporary directory.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




