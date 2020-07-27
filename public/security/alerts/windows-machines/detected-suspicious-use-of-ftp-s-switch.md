---
title: Detected suspicious use of ftp s switch
description: Detected suspicious use of ftp s switch
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Detected suspicious use of FTP -s Switch**

## Description
Analysis of process creation data from the %{Compromised Host} detected the use of the FTP "-s:filename" switch. This switch is used to specify an FTP script file for the client to run. Malware or malicious processes are known to use this FTP switch (-s:filename) to point to a script file which is configured to connect to a remote FTP server and download additional malicious binaries.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




