---
title: Local administrators group members were enumerated
description: Local administrators group members were enumerated
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Alert
**Local Administrators group members were enumerated**

## Description
Machine logs indicate a successful enumeration on group %{Enumerated Group Domain Name}\%{Enumerated Group Name}. Specifically, %{Enumerating User Domain Name}\%{Enumerating User Name} remotely enumerated the members of the %{Enumerated Group Domain Name}\%{Enumerated Group Name} group. This activity could either be legitimate activity, or an indication that a machine in your organization has been compromised and used to reconnaissance %{vmname}.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Informational




