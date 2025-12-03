---
title: 'Before you go: Delete resources'
layout: default
nav_order: 11
has_children: true
---

# Delete resources

## Exercise learning objectives
- Clean up Azure resources created during the lab.
- Delete resource groups containing Sentinel, Data Lake, virtual machines, and supporting services.
- Prevent unnecessary Azure consumption and restore the subscription to a clean state.

## Licensing and environment
- Azure portal access with permissions to delete resource groups.
- Resource groups created during this lab:
  - `rg-sentinel-lab`
  - `rg-sentinel-custom-lab` (if created)

## Roles and permissions
- Required role in the lab environment:
  - Contributor or higher on the subscription or specific resource groups.
- Deleting resource groups removes all contained resources, including:
  - Virtual machines  
  - Storage accounts  
  - Log Analytics workspaces  
  - Sentinel configurations  
  - Networking components  

## Estimated time
Duration: **10–15 minutes**