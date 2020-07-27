---
title: Detected enabling of the wdigest uselogoncredential registry key
description: Detected enabling of the wdigest uselogoncredential registry key
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected enabling of the WDigest UseLogonCredential registry key**

## Description
Analysis of host data  detected a change in the registry key HKLM\SYSTEM\CurrentControlSet\Control\SecurityProviders\WDigest\ "UseLogonCredential". Specifically this key has been updated to allow logon credentials to be stored in clear text in LSA memory. Once enabled an attacker can dump clear text passwords from LSA memory with credential harvesting tools such as Mimikatz.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




