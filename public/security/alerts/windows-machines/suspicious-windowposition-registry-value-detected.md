---
title: Suspicious windowposition registry value detected
description: Suspicious windowposition registry value detected
published: true
date: 2020-07-14T17:46:14Z
tags:
editor: markdown
---

## Alert
**Suspicious WindowPosition registry value detected**

## Description
Analysis of host data on %{Compromised Host} detected an attempted WindowPosition registry configuration change that could be indicative of hiding application windows in non-visible sections of the desktop.  This could be legitimate activity, or an indication of a compromised machine: this type of activity has been previously associated with known adware (or unwanted software) such as Win32/OneSystemCare and Win32/SystemHealer and malware such as Win32/Creprote. When the WindowPosition value is set to 201329664,  (Hex: 0x0c00 0c00, corresponding to X-axis=0c00 and the Y-axis=0c00) this places the console app's window in a non-visible section of the user's screen in an area that is hidden from view below the visible start menu/taskbar. Known suspect Hex value includes, but not limited to c000c000

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Low




