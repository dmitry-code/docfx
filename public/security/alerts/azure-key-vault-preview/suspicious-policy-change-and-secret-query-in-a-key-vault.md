---
title: Suspicious policy change and secret query in a key vault
description: Suspicious policy change and secret query in a key vault
published: true
date: 2020-07-14T17:46:15Z
tags:
editor: markdown
---

## Alert
**Suspicious policy change and secret query in a Key Vault**

## Description
A Key Vault policy change has been made and then operations to list and/or get secrets occurred. In addition, this operation pattern isn't normally performed by the user on this vault. This is highly indicative that the Key Vault is compromised and the secrets within have been stolen by a malicious actor.

## Intent ([Learn more](/public/security/alerts/intentions.md))
\-

## Severity
Medium




