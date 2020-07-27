---
title: Suspect service installation
description: Suspect service installation
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Suspect service installation**

## Description
Analysis of host data has detected the installation of tscon.exe as a service: this binary being started as a service potentially allows an attacker to trivially switch to any other logged on user on this host by hijacking RDP connections; it is a known attacker technique to compromise additional user accounts and move laterally across a network.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




