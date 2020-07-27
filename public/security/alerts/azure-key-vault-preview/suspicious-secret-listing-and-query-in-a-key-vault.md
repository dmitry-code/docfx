---
title: Suspicious secret listing and query in a key vault
description: Suspicious secret listing and query in a key vault
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Suspicious secret listing and query in a Key Vault**

## Description
A Secret List operation was followed by many Secret Get operations. Also, this operation pattern isn't normally performed by the user on this vault. This indicates that someone could be dumping the secrets stored in the Key Vault for potentially malicious purposes.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




