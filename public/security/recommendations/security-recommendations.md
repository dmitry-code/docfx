---
title: Azure Security Center - Recommendation
description: Azure Security Center - Recommendation
published: true
date: 2020-07-22T17:45:46.196Z
tags: 
editor: markdown
---

# Security recommendations - a reference guide

This article lists the recommendations you might see in Azure Security Center. The recommendations shown in your environment depend on the resources you're protecting and your customized configuration.

Security Center's recommendations are based on best practices. Some are aligned with the **Azure Security Benchmark**, the Microsoft-authored, Azure-specific guidelines for security and compliance best practices based on common compliance frameworks. [Learn more about Azure Security Benchmark](https://docs.microsoft.com/azure/security/benchmarks/introduction).

To learn about how to respond to these recommendations, see [Remediate recommendations in Azure Security Center](security-center-remediate-recommendations.md).

Your Secure Score is based on the number of Security Center recommendations you've completed. To decide which  recommendations to resolve first, look at the severity of each one and its potential impact on your Secure Score.

> If a recommendation's description says "No related policy", it's usually because that recommendation is dependent on a different recommendation and *its* policy. For example, the recommendation "Endpoint protection health failures should be remediated...", relies on the recommendation that checks whether an endpoint protection solution is even *installed* ("Endpoint protection solution should be installed..."). The underlying recommendation *does* have a policy. Limiting the policies to only the foundational recommendation simplifies policy management.
{.is-info}

## Network recommendations

- [Adaptive Network Hardening recommendations should be applied on internet facing virtual machines](/public/security/recommendations/network/adaptive-network-hardening-recommendations-should-be-applied-on-internet-facing-virtual-machines)
- [All network ports should be restricted on NSG associated to your VM](/public/security/recommendations/network/all-network-ports-should-be-restricted-on-nsg-associated-to-your-vm)
- DDoS Protection Standard should be enabled
- Function App should only be accessible over HTTPS
- Internet-facing virtual machines should be protected with Network Security Groups
- Non-internet-facing virtual machines should be protected with network security groups
- IP forwarding on your virtual machine should be disabled
- Management ports of virtual machines should be protected with just-in-time network access control
- Management ports should be closed on your virtual machines
- Secure transfer to storage accounts should be enabled
- Subnets should be associated with a Network Security Group
- Web Application should only be accessible over HTTPS
{.links-list}

## Container recommendations

- [Authorized IP ranges should be defined on Kubernetes Services](/public/security/recommendations/container/authorized-ip-ranges-should-be-defined-on-kubernetes-services)
{.links-list}

## App Service recommendations
- [Web Application should only be accessible over HTTPS](/public/security/recommendations/app-service/web-application-should-only-be-accessible-over-https)
{.links-list}

## Compute and app recommendations
- [Diagnostic logs in Azure Stream Analytics should be enabled](/public/security/recommendations/compute-and-app/diagnostic-logs-in-azure-stream-analytics-should-be-enabled)
{.links-list}

## Virtual machine scale set recommendations
- [Diagnostic logs in Virtual Machine Scale Sets should be enabled](/public/security/recommendations/virtual-machine-scale-set/diagnostic-logs-in-virtual-machine-scale-sets-should-be-enabled)
{.links-list}

## Data and storage recommendations

- [Access to storage accounts with firewall and virtual network configurations should be restricted](/public/security/recommendations/data-and-storage/access-to-storage-accounts-with-firewall-and-virtual-network-configurations-should-be-restricted)
{.links-list}

## Identity and access recommendations
- [MFA should be enabled on accounts with read permissions on your subscription](/public/security/recommendations/identity-and-access/mfa-should-be-enabled-on-accounts-with-read-permissions-on-your-subscription)
{.links-list}

## Deprecated recommendations
- [Access to App Services should be restricted](/public/security/recommendations/deprecated/access-to-app-services-should-be-restricted)
{.links-list}

