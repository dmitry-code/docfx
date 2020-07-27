---
title: Possible credential dumping detected seen multiple times
description: Possible credential dumping detected seen multiple times
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Possible credential dumping detected [seen multiple times]**

## Description
Analysis of host data has detected use of native windows tool (e.g. sqldumper.exe) being used in a way that allows to extract credentials from memory. Attackers often use these techniques to extract credentials that they then further use for lateral movement and privilege escalation. This behavior was seen [x] times today on the following machines: [Machine names]

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




