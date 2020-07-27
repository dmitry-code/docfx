---
title: Suspicious download using certutil detected seen multiple times
description: Suspicious download using certutil detected seen multiple times
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**Suspicious download using Certutil detected [seen multiple times]**

## Description
Analysis of host data on %{Compromised Host} detected the use of certutil.exe, a built-in administrator utility, for the download of a binary instead of its mainstream purpose that relates to manipulating certificates and certificate data. Attackers are known to abuse functionality of legitimate administrator tools to perform malicious actions, for example using certutil.exe to download and decode a malicious executable that will then be subsequently executed. This behavior was seen [x] times today on the following machines: [Machine names]

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




