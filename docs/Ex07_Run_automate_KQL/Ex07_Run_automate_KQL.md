---
title: 'Exercise 07: Run and automate KQL jobs in the Lake'
layout: default
nav_order: 9
has_children: true
---

# Exercise 07: Run and automate KQL jobs in the Lake

## Exercise learning objectives
- Create and execute KQL jobs directly in the Sentinel Data Lake for large-scale queries.
- Automate recurring KQL jobs for operational analytics and incident trend detection.
- Monitor job performance and interpret results in structured dashboards.
- Understand KQL job scheduling, resource limits, and performance optimization techniques.

## Licensing and environment
- An active Azure subscription with Microsoft Sentinel enabled.
- Access to:
  - Data Lake Exploration (KQL jobs, KQL queries)
  - Sentinel workspace for analytics/hot-tier validation
- Workload data available in tables such as SecurityAlert, SigninLogs, and other Defender/Sentinel logs.

## Roles and permissions
- **Lab environment:** Owner or Contributor for full access to create and manage jobs.
- **Real-world deployments:** recommended minimum roles:
  - Microsoft Sentinel Contributor to create/manage jobs and output tables.
  - Security Reader or Security Analyst for viewing Defender XDR data.
  - Log Analytics Contributor for workspace access where job output tables are stored.

## Estimated time
Duration: **40–50 minutes**