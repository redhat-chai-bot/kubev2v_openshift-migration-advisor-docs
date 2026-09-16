---
title: "release notes v0.24.0"
linkTitle: "release notes v0.24.0"
date: 2026-09-16
type: docs
---

# OpenShift Migration Advisor — release notes — `v0.24.0`

Compare: `v0.23.0` → `v0.24.0`

## Appliance changes

### Fixes
- Fixed horizontal scrollbar in the VMs table not being visible when columns are wide, requiring unnecessary vertical scrolling
- Fixed empty VM table in Create VM group modal that showed pagination but rendered no rows

### Internal
- Cleaned up appliance code after v1 removal — restructured service folders and renamed stores

## Console changes

### Features
- Added vCenter-level migration recommendations providing a unified view across clusters
- Added a dedicated "Migration Advisor" section in the left navigation menu on console.redhat.com

### API changes (not yet available in the UI)
- Added totalWithFaultTolerance field to inventory API for tracking VMs with fault tolerance enabled

### Fixes
- Fixed Cost estimation missing from Migration recommendations for partner users after assessment wizard refactor
