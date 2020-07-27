---
title: Potentially unsafe action
description: Potentially unsafe action
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**Potentially Unsafe Action**

## Description
High privileged SQL command which is commonly used in malicious sessions has been executed in an SQL Server. Those commands are recommended to be disabled by default. In some cases, the alert detects a legitimate action (admin script running). In other cases, the alert detects a malicious action (attacker using SQL trusts to breach Windows layer).

## Intent ([Learn more](/public/security/alerts/intentions.md))
Execution

## Severity
High




