---
title: 'Exercise 06: Understand the capabilities and limitations of KQL in the Data Lake'
layout: default
nav_order: 8
has_children: true
---

# Exercise 06: Understand the capabilities and limitations of KQL in the Data Lake

## Exercise learning objectives
- Compare Lake-based KQL and traditional Sentinel workspace KQL capabilities.
- Understand limitations such as real-time analytics, schema consistency, and query depth.
- Identify performance considerations and cost implications of large-scale queries.
- Apply best practices for efficient querying and data modeling within the Data Lake.
- Evaluate latency differences and optimize queries using defensive and performance-focused techniques.

## Licensing and environment
- An active Azure subscription with Microsoft Sentinel enabled.
- Access to both:
  - Sentinel analytics (hot) workspace
  - Sentinel Data Lake (cold tier) via Data Lake Exploration
- KQL query permissions for both tiers.
- Data sources including SecurityAlert, AuditLogs, and other standard Defender/Sentinel tables.

## Roles and permissions
- **Lab environment:** Owner or Contributor for full access to workspace and Data Lake queries.
- **Real-world deployments:** recommended minimum roles:
  - Microsoft Sentinel Reader/Contributor to run KQL queries.
  - Security Reader or higher to access Defender XDR data.
  - Log Analytics Reader for workspace-based hot-tier queries.

## Estimated time
Duration: **45–60 minutes**