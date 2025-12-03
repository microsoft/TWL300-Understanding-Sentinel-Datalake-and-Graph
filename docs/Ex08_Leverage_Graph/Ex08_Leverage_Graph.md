---
title: 'Exercise 08: Leverage Graph capabilities for threat hunting and correlation'
layout: default
nav_order: 10
has_children: true
---

# Exercise 08: Leverage Graph capabilities for threat hunting and correlation

## Exercise learning objectives
- Explore how Microsoft Sentinel and Microsoft Defender XDR use graph relationships for threat analysis.
- Use hunting graphs, investigation graphs, and MITRE ATT&CK mapping for multi-entity correlation.
- Apply KQL-based graph analytics to visualize relationships and lateral movement.
- Build unified attack timelines using telemetry from multiple data sources.

## Licensing and environment
- An active Azure subscription with Microsoft Sentinel and Microsoft Defender XDR access.
- Access to:
  - Hunting graph
  - Investigation graph
  - MITRE ATT&CK matrix
  - Advanced Hunting (Defender portal)
- Telemetry sources such as SecurityAlert, SigninLogs, AuditLogs, AzureActivity, and entity-based hunting data.

## Roles and permissions
- **Lab environment:** Global Administrator or Security Administrator for full graph/hunting access.
- **Real-world deployments:** recommended minimum roles:
  - Security Reader / Security Analyst for graph and hunting features.
  - Sentinel Reader/Contributor for correlated telemetry analysis.
  - Defender XDR permissions required for entity graph and incident investigation.

## Estimated time
Duration: **45–60 minutes**