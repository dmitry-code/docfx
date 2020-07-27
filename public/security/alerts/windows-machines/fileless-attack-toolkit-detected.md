---
title: Fileless attack toolkit detected
description: Fileless attack toolkit detected
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Fileless attack toolkit detected**

## Description
The memory of the process specified contains a fileless attack toolkit: [toolkit name]]. Fileless attack toolkits use techniques that minimize or eliminate traces of malware on disk, and greatly reduce the chances of detection by disk-based malware scanning solutions. Specific behaviors include:<br>1) Shellcode, which is a small piece of code typically used as the payload in the exploitation of a software vulnerability.<br>2) Executable image injected into the process, such as in a code injection attack.<br>3) Function calls to security sensitive operating system interfaces. See Capabilities below for referenced OS capabilities.<br>4) Contains a thread that was started in a dynamically allocated code segment. This is a common pattern for process injection attacks.

## Intent ([Learn more](/public/security/alerts/intentions.md))
DefenseEvasion

## Severity
High




