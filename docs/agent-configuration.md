# Agent Configuration

## Overview

After deploying the Wazuh SIEM server, a Linux endpoint was connected to the environment using the Wazuh Agent.

The objective was to enable centralized log collection and endpoint monitoring.

---

## Monitored Endpoint

| Component | Description |
|-----------|-------------|
| Operating System | Kali Linux |
| Agent | Wazuh Agent |
| Connection | Wazuh Server |

---

## Configuration Process

### 1. Agent deployment

The Wazuh Agent package was installed on the Kali Linux virtual machine.

### 2. Server configuration

The endpoint was configured to communicate with the Wazuh Server using the server IP address.

### 3. Agent registration

The endpoint successfully registered in the Wazuh Dashboard.

### 4. Verification

The communication between the endpoint and the SIEM server was verified using the Wazuh Dashboard.

The endpoint status changed to **Active**, confirming successful deployment.

---

## Result

The Linux endpoint successfully transmitted security events to the Wazuh SIEM platform.

The environment became ready for security monitoring and threat analysis.

---

## Skills Demonstrated

- Endpoint monitoring
- Wazuh Agent deployment
- Linux administration
- SIEM configuration
- Security monitoring
