---
title: Disk encryption should be applied on virtual machines
description: Disk encryption should be applied on virtual machines
published: true
date: 2020-07-14T17:46:13Z
tags:
editor: markdown
---

## Recommendation
**Disk encryption should be applied on virtual machines**

## Description & related policy
Encrypt your virtual machine disks using Azure Disk Encryption both for Windows and Linux virtual machines. Azure Disk Encryption (ADE) leverages the industry standard BitLocker feature of Windows and the DM-Crypt feature of Linux to provide OS and data disk encryption to help protect and safeguard your data and help meet your organizational security and compliance commitments in customer Azure key vault. When your compliance and security requirement requires you to encrypt the data end to end using your encryption keys, including encryption of the ephemeral (locally attached temporary) disk, use Azure disk encryption. Alternatively, by default, Managed Disks are encrypted at rest by default using Azure Storage Service Encryption where the encryption keys are Microsoft-managed keys in Azure. If this meets your compliance and security requirements, you can leverage the default Managed disk encryption to meet your requirements.<br>(Related policy: Disk encryption should be applied on virtual machines)

## Severity
High

## Quick fix enabled?([Learn more](https://docs.microsoft.com/azure/security-center/security-center-remediate-recommendations#recommendations-with-quick-fix-remediation))
N

## Resource type
Machine




