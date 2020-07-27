---
title: Detected encoded executable in command line data
description: Detected encoded executable in command line data
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected encoded executable in command line data**

## Description
Analysis of host data on %{Compromised Host} detected a base-64 encoded executable. This has previously been associated with attackers attempting to construct executables on-the-fly through a sequence of commands, and attempting to evade intrusion detection systems by ensuring that no individual command would trigger an alert. This could be legitimate activity, or an indication of a compromised host.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
High




