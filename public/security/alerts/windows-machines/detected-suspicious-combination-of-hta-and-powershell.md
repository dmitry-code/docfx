---
title: Detected suspicious combination of hta and powershell
description: Detected suspicious combination of hta and powershell
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected suspicious combination of HTA and PowerShell**

## Description
mshta.exe (Microsoft HTML Application Host) which is a signed Microsoft binary is being used by the attackers to launch malicious PowerShell commands.  Attackers often resort to having an HTA file with inline VBScript.  When a victim browses to the HTA file and chooses to run it, the PowerShell commands and scripts that it contains are executed. Analysis of host data on %{Compromised Host} detected mshta.exe launching PowerShell commands.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




