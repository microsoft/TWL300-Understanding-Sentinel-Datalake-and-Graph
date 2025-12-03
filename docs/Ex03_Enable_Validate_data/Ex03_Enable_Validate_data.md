---
title: 'Exercise 03: Enable and validate the Data Lake integration with Microsoft Defender XDR'
layout: default
nav_order: 5
has_children: true
---

# Exercise 03: Enable and validate the Data Lake integration with Microsoft Defender XDR

## Exercise learning objectives
- Verify Microsoft Sentinel Data Lake provisioning and its association with the Sentinel workspace.
- Validate that Defender XDR incidents and alerts are replicated into the Data Lake using KQL queries.
- Enable diagnostic settings for the Sentinel workspace to stream logs and metrics to a storage account.
- Explore and understand system tables and tenant-level datasets exposed through the Sentinel Data Lake.

## Licensing and environment
- An active Microsoft 365 tenant with access to `security.microsoft.com`.
- Licensing covering each workload:
  - Microsoft Defender XDR (via Microsoft 365 E5, Enterprise Mobility + Security E5).
  - Defender for Endpoint Plan 2.
  - Defender for Office 365 Plan 2.
  - Defender for Identity.
  - Defender for Cloud Apps.
  - Microsoft Entra ID P2 (for risk-based policies and Identity Protection).
- An active Azure subscription with:
  - A Log Analytics workspace onboarded to Microsoft Sentinel (`law-sentinel-xdr-lab`).
  - A Microsoft Sentinel Data Lake configuration bound to the workspace.
  - At least one onboarded device (for example, `vm-sentinel-lab`) producing Defender XDR telemetry.

## Roles and permissions
- Lab environment: Global Administrator and Owner/Contributor on the subscription.
- Real-world deployments (recommended minimum):
  - Microsoft Sentinel Reader/Contributor to query workspace and Data Lake tables.
  - Security Reader / Security Analyst / Security Administrator for Defender XDR.
  - Global Reader or Service Support Administrator to view Microsoft 365 Service Health.
  - Appropriate Azure RBAC permissions on the Sentinel workspace, storage account, and Data Lake–related resources.

## Estimated time
Duration: **35–50 minutes**