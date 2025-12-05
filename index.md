---
title: Introduction
layout: home
nav_order: 1
---

# TechExcel: Understanding Sentinel datalake and graph


## Course Objective:
Enable security engineers and architects to design, configure, and operate a Microsoft Sentinel environment that is tightly integrated with Microsoft Defender XDR and the Sentinel Data Lake for unified detection, investigation, and long-term security analytics.

## Learning objectives:
At the end of this workshop, you will be able to:
- Explain how Microsoft Sentinel, Log Analytics workspaces, the Data Lake, and Microsoft Defender XDR work together in a unified architecture.
- Onboard Microsoft Sentinel to an existing Defender XDR environment and validate end-to-end alert and incident flow across portals.
- Configure Log Analytics workspaces, Data Collection Rules (DCRs), and Data Collection Endpoints (DCEs) to onboard Azure VMs and other data sources.
- Ingest first-party (1P) data such as Defender XDR, Entra ID, and Azure Activity logs, and onboard third-party/custom data using DCRs and the Codeless Connector Framework (CCF).
- Use KQL across hot (Analytics) and cold (Data Lake) tiers, including defensive query techniques, performance optimization, and scheduled KQL jobs.
- Manage tables, storage tiers, and retention policies to balance cost, compliance, and hunting effectiveness in the Sentinel Data Lake.
- Leverage graph-based capabilities and MITRE ATT&CK views to perform correlated threat hunting and build multi-stage attack timelines.

## Lab objectives:
By the end of this lab, you'll be able to:

* Provision a Sentinel lab environment, including a resource group, Azure VM, Log Analytics workspace, and Data Collection Rule.
* Onboard Microsoft Sentinel to the workspace, integrate it with Defender XDR, and enable Data Lake replication for incidents and alerts.
* Explore default and custom workspaces, review key security tables and schemas, and run KQL queries to interrogate incidents, alerts, and identity activity.
* Configure and validate first-party data ingestion (Defender XDR, Entra ID, Azure Activity) and implement custom ingestion via DCR, DCE, and Logs Ingestion API.
* Deploy and validate a Codeless Connector Framework (CCF) connector and confirm data replication into both Sentinel and the Data Lake.
* Configure table storage tiers (Analytics, Lake, Lake Only) and adjust Analytics and Lake retention to meet business and regulatory requirements.
* Compare query behavior between Analytics and Data Lake tiers, apply defensive KQL patterns, use materialization, and schedule KQL jobs for recurring analytics.
* Use hunting graphs, entity investigation graphs, MITRE-mapped hunting queries, and graph-semantic KQL to correlate entities, lateral movement, and attack progression.

## Customer scenario:

Zava Group is expanding its security operations program around Microsoft Defender XDR but is reaching the limits of short-term log retention and workspace-only analytics. The SOC needs a way to retain high-value telemetry for years, run large-scale investigations across historical data, and standardize hunting and reporting across multiple workspaces and regions.

To address this, Zava is piloting Microsoft Sentinel with the new Sentinel Data Lake. The security team will connect Defender XDR to a Sentinel workspace, mirror incidents and alerts into the Data Lake, and ingest additional sources such as Entra ID, Azure Activity, and third-party logs. They must tune table tiers and retention to control cost, while still enabling deep KQL analytics, scheduled KQL jobs, and graph-driven hunting.

In this lab, you play the role of a Zava security engineer. You will build the Sentinel environment, wire up Defender XDR and Data Lake integration, ingest first- and third-party data, tune table and retention settings, and use KQL plus graph-based capabilities to investigate and reason over the organization’s security data at scale.
