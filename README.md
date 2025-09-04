# CloudWatch-agent-setup
A guide on how to setup CloudWatch Agent using SSH connection.

## Repository Structure

```
CloudWatch-agent-setup/
│
├── README.md
│
└── config-files/
    ├── AU-ISLHD/
    │   ├── backend/
    │   │   ├── file_amazon-cloudwatch-agent.json
    │   │   ├── file_app_logs.json
    │   │   ├── file_metrics.json
    │   │   └── file_sys_logs.json
    │   │
    │   └── event-scheduler/
    │       ├── file_amazon-cloudwatch-agent.json
    │       ├── file_event_scheduler_logs.json
    │       ├── file_metrics.json
    │       └── file_sys_logs.json
    │
    └── SG-UAT/
        ├── backend/
        │   ├── file_amazon-cloudwatch-agent.json
        │   ├── file_app_logs.json
        │   ├── file_metrics.json
        │   └── file_sys_logs.json
        │
        └── event-scheduler/
            ├── file_amazon-cloudwatch-agent.json
            ├── file_event_scheduler_logs.json
            ├── file_metrics.json
            └── file_sys_logs.json
```

## Configuration Files Overview

This repository contains CloudWatch Agent configuration files organized by:

- **Environment**: AU-ISLHD (Australia - ISLHD) and SG-UAT (Singapore - UAT)
- **Service Type**: backend and event-scheduler

### File Types

- `file_amazon-cloudwatch-agent.json` - Main CloudWatch Agent configuration
- `file_app_logs.json` - Application log collection configuration  
- `file_event_scheduler_logs.json` - Event scheduler specific log configuration
- `file_metrics.json` - System metrics collection configuration
- `file_sys_logs.json` - System log collection configuration
