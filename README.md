# Fleet Posture Stack for Amazon Linux 2

This repository contains the configuration and setup files to deploy an open-source device posture monitoring stack on Amazon Linux 2, including:

- FleetDM (Osquery manager and dashboard)  
- Osquery agent (enrollment configs)  
- OpenSearch + OpenSearch Dashboards (for data storage and visualization)  
- ElastAlert 2 (alerting engine)  
- Optional FastAPI backend for custom data collection  

---

## Quick start

1. Clone this repo:  
   ```bash
   git clone https://github.com/YOUR_USERNAME/fleet-posture-stack.git
   cd fleet-posture-stack
