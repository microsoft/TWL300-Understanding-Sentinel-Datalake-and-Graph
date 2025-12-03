---
title: 'Exercise 02: Core data ingestion and Microsoft Defender XDR integration'
layout: default
nav_order: 4
has_children: true
---

# Exercise 02: Core data ingestion and Microsoft Defender XDR integration

## Exercise learning objectives
- Connect and validate Microsoft Defender XDR data ingestion into Microsoft Sentinel.
- Enable and confirm replication of incidents, alerts, and security data to the Sentinel Data Lake.
- Review and understand the correlation between Defender XDR and Sentinel workspaces.
- Explore incident details, analytics data, and schema mappings across both platforms.

## Licensing and environment
- An active Azure subscription.
- Access to the Azure portal with permissions to configure Microsoft Sentinel.
- A Log Analytics workspace with Microsoft Sentinel enabled.
- Microsoft Defender XDR active in the tenant, with required integrations available.
- Network connectivity to support ingestion, replication, and portal access.

## Roles and permissions
- Lab environment: Owner or Contributor on the subscription for configuration changes.
- Real-world deployments:
  - Contributor or Security Administrator to enable and manage Defender XDR integration.
  - Microsoft Sentinel Contributor or above to configure data connectors and validate ingestion.
  - Security Reader or higher to view incidents and alerts replicated from Defender XDR.

## Estimated time
Duration: **30–40 minutes**