---
title: Detected suspicious use of cacls to lower the security state of the system
description: Detected suspicious use of cacls to lower the security state of the system
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected suspicious use of Cacls to lower the security state of the system**

## Description
Attackers use myriad ways like brute force, spear phishing etc. to achieve initial compromise and get a foothold on the network. Once initial compromise is achieved they often take steps to lower the security settings of a system. Cacls—short for change access control list is Microsoft Windows native command-line utility often used for modifying the security permission on folders and files. A lot of time the binary is used by the attackers to lower the security settings of a system. This is done by giving Everyone full access to some of the system binaries like ftp.exe, net.exe, wscript.exe etc. Analysis of host data on %{Compromised Host} detected suspicious use of Cacls to lower the security of a system.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




