---
title: Suspect integrity level indicative of rdp hijacking
description: Suspect integrity level indicative of rdp hijacking
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Suspect integrity level indicative of RDP hijacking**

## Description
Analysis of host data has detected the tscon.exe running with SYSTEM privileges - this can be indicative of an attacker abusing this binary in order to switch context to any other logged on user on this host; it is a known attacker technique to compromise additional user accounts and move laterally across a network.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




