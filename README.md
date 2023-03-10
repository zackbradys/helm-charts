---
title: Helm Charts Repository
author: Zack Brady - Field Engineer
contact: zack.brady@rancherfederal.com
---

# Helm Charts Repository

### Table of Contents
* [About Me](#about-me)
* [Configuration](#configuration)
* [Installation](#installation)

## About Me

A little bit Zack Brady, his history, and what he's done in the industry. 
- DOD/IC Contractor
- U.S. Military Veteran
- Open-Source Contributor
- Built and Exited a Digital Firm
- Active Volunteer Firefighter/EMT

## Configuration

### Adding the Helm Chart via CLI:
```bash
helm repo add zackbradys https://zackbradys.github.io/helm-charts/
helm repo update
```

### Adding the Helm Chart via Rancher Manager:
1. Authenticate into the Rancher Manager UI
2. Open the local cluster or downstream cluster
3. Click into Apps -> Charts -> Repositories 
4. Click "Create" and enter the following information:

```bash
Name: zackbradys
Target: http(s) URL to index generated by Helm
Index URL: https://zackbradys.github.io/helm-charts/
Authentication: None
```

## Installation

Install via the Helm CLI or the Rancher Manager. Instructions are a WIP