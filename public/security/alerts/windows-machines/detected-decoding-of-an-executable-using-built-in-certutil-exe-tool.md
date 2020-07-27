---
title: Detected decoding of an executable using built in certutil exe tool
description: Detected decoding of an executable using built in certutil exe tool
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected decoding of an executable using built-in certutil.exe tool**

## Description
Analysis of host data on %{Compromised Host} detected that certutil.exe, a built-in administrator utility, was being used to decode an executable instead of its mainstream purpose that relates to manipulating certificates and certificate data. Attackers are known to abuse functionality of legitimate administrator tools to perform malicious actions, for example using a tool such as certutil.exe to decode a malicious executable that will then be subsequently executed.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
High




