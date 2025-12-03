---
title: 'Exercise 05: Manage tables and retention policies in the Data Lake'
layout: default
nav_order: 7
has_children: true
---

# Exercise 05: Manage tables and retention policies in the Data Lake

## Exercise learning objectives
- Manage data lifecycle and retention policies within the Sentinel Data Lake.
- Explore table structures across Analytics, Lake, and Lake Only tiers.
- Configure retention periods for both hot (Analytics) and cold (Lake) storage.
- Optimize storage tiers for cost, performance, and compliance requirements.
- Validate retention and table behavior using KQL queries.

## Licensing and environment
- An active Azure subscription with access to Microsoft Sentinel.
- A Log Analytics workspace connected to Sentinel.
- Permissions to view and modify:
  - Table tiering (Analytics / Lake / Lake Only)
  - Analytics retention
  - Lake retention
- A Microsoft 365 tenant with Defender XDR data available (e.g., SecurityIncident, SecurityAlert, DeviceProcessEvents).

## Roles and permissions
- **Lab environment:** Owner or Contributor on the subscription for full table and retention configuration.
- **Real-world deployments:** recommended minimum roles:
  - Microsoft Sentinel Contributor to modify table tiers and retention.
  - Security Reader / Security Analyst / Security Administrator for viewing Defender XDR data.
  - Log Analytics Contributor for workspace-level data management.

## Estimated time
Duration: **45–60 minutes**