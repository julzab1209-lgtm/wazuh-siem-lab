# Wazuh SIEM Laboratory

## Project Overview

This project demonstrates the deployment, configuration and operation of a Wazuh Security Information and Event Management (SIEM) platform in a virtual laboratory environment.

The laboratory was designed to simulate a basic Security Operations Center (SOC), enabling centralized log collection, endpoint monitoring, threat detection, and security event analysis using Linux endpoints.

---

## Objectives

The main objectives of this project were:

- Deploy a Wazuh SIEM environment.
- Configure a Linux endpoint using the Wazuh Agent.
- Collect and monitor security events.
- Perform Threat Hunting using Wazuh.
- Analyze security events using the MITRE ATT&CK framework.
- Prepare complete technical documentation of the deployment and analysis process.

---

## Lab Environment

| Component | Description |
|-----------|-------------|
| SIEM Platform | Wazuh |
| Server OS | Ubuntu Server |
| Endpoint OS | Kali Linux |
| Virtualization | Oracle VirtualBox |
| Agent | Wazuh Agent |
| Monitoring | Security Events, Threat Hunting, MITRE ATT&CK |

---

## Technologies

- Wazuh SIEM
- Ubuntu Server
- Kali Linux
- Oracle VirtualBox
- Linux
- MITRE ATT&CK
- Threat Hunting
- Security Event Monitoring
- Security Configuration Assessment (SCA)

---

## Project Features

- Centralized security monitoring
- Endpoint log collection
- Linux endpoint monitoring
- Threat Hunting
- MITRE ATT&CK mapping
- Security event correlation
- Security Configuration Assessment (SCA)

---

## Repository Structure

```text
wazuh-siem-lab
│
├── README.md
│
├── docs
│   ├── installation.md
│   ├── agent-configuration.md
│   ├── threat-hunting.md
│   └── mitre-attack.md
│
├── screenshots
│   ├── agent-service-running.jpeg
│   ├── alerts-summary.jpeg
│   ├── mitre-dashboard.jpeg
│   ├── security-events-details.jpeg
│   ├── threat-hunting-events.jpeg
│   └── wazuh-dashboard-overview.jpeg
│
└── summaries
```

---

## Documentation

The project documentation is organized into several sections describing the deployment, configuration and security monitoring process.

| Document | Description |
|----------|-------------|
| installation.md | Installation and deployment of the Wazuh SIEM environment |
| agent-configuration.md | Configuration of the monitored Linux endpoint |
| threat-hunting.md | Investigation and analysis of detected security events |
| mitre-attack.md | MITRE ATT&CK mapping of detected security events |

---

# Project Gallery

## Wazuh Dashboard

The deployed Wazuh environment with the available security monitoring modules.

![Wazuh Dashboard](screenshots/wazuh-dashboard-overview.jpeg)

---

## Threat Hunting

Detected security events collected from the monitored Linux endpoint.

![Threat Hunting](screenshots/threat-hunting-events.jpeg)

---

## Security Events

Authentication events, privilege escalation, and Rootcheck alerts detected during monitoring.

![Security Events](screenshots/security-events-details.jpeg)

---

## MITRE ATT&CK

Security events mapped to the MITRE ATT&CK framework.

![MITRE ATT&CK](screenshots/mitre-dashboard.jpeg)

---

## Alerts Summary

Summary of generated security alerts.

![Alerts Summary](screenshots/alerts-summary.jpeg)

---

## Project Summary

This laboratory project demonstrates the deployment, configuration and operation of a Wazuh SIEM environment in a virtual laboratory.

The completed environment enabled centralized log collection, endpoint monitoring, threat hunting, security event analysis, and MITRE ATT&CK correlation using a Linux endpoint.

The project also involved preparing technical documentation describing each implementation stage.

---

## Future Improvements

Possible future enhancements include:

- Windows endpoint monitoring
- Sysmon integration
- Active Response configuration
- YARA integration
- Sigma rule implementation
- Elastic Stack integration
- Multi-endpoint monitoring
