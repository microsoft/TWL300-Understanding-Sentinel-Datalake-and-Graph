---
title: 'Exercise 04: Ingest data into the Data Lake (XDR and other sources)'
layout: default
nav_order: 6
has_children: true
---

# Exercise 04: Ingest data into the Data Lake (XDR and other sources)

## Exercise learning objectives
- Ingest data from Microsoft Defender XDR, Entra ID, Azure Activity, and custom sources into the Sentinel Data Lake.
- Install and configure first-party (1P) data connectors such as Entra ID and Azure Activity.
- Simulate service principal activity and validate ingestion using KQL queries.
- Create and ingest third-party (3P) or custom logs using Data Collection Rules (DCRs) and Data Collection Endpoints (DCEs).
- Build and validate a custom table and ingest data using the Azure Logs Ingestion API.
- Deploy a Codeless Connector Framework (CCF) connector and verify data replication into both Microsoft Sentinel and the Data Lake.

## Licensing and environment
- An active Azure subscription.
- Access to the Azure portal and permissions to configure:
  - Microsoft Sentinel
  - Log Analytics workspaces
  - Data Collection Rules (DCR)
  - Data Collection Endpoints (DCE)
  - CCF connector deployments
- A Microsoft 365 tenant with:
  - Microsoft Defender XDR enabled
  - Entra ID Audit and Sign-in logs available
- A lab virtual machine with required scripts preinstalled in `C:\LabFiles`.

## Roles and permissions
- Lab environment: Owner or Contributor on the subscription to deploy connectors, tables, DCR/DCE resources, and ARM templates.
- Real-world deployments (recommended minimum):
  - Microsoft Sentinel Contributor to configure data connectors and run KQL queries.
  - Security Reader / Security Analyst / Security Administrator to view Defender XDR and Entra ID data.
  - Log Analytics Contributor for workspace table creation and ingestion configuration.
  - Sufficient Azure RBAC permissions for DCR/DCE creation and deployment of ARM-based connectors.

## Estimated time
Duration: **60–75 minutes**