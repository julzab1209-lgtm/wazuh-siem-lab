# MITRE ATT&CK Analysis

## Overview

The Wazuh SIEM platform automatically maps detected security events to the MITRE ATT&CK framework.

This functionality provides additional context for security alerts by associating them with known adversary tactics and techniques, making incident investigation more efficient.

---

## MITRE ATT&CK Framework

The MITRE ATT&CK framework is a globally recognized knowledge base that categorizes attacker behavior based on real-world observations.

Within this laboratory environment, Wazuh correlated detected security events with MITRE ATT&CK tactics, providing additional context for security monitoring and analysis.

---

## Detected MITRE Tactics

| MITRE Tactic | Description | Example from Laboratory |
|---------------|-------------|-------------------------|
| Initial Access | Techniques used to gain initial access to a system. | SSH authentication attempts |
| Persistence | Techniques allowing continued access after initial compromise. | Continuous endpoint monitoring and agent activity |
| Privilege Escalation | Techniques used to obtain higher-level permissions. | Successful `sudo` execution |
| Defense Evasion | Techniques used to avoid detection or modify system behavior. | Rootcheck alerts and monitored system changes |

---

## Security Correlation

By mapping security events to the MITRE ATT&CK framework, Wazuh provides analysts with additional context during incident investigations.

Instead of viewing isolated alerts, related events can be grouped according to attacker tactics, improving threat visibility and prioritization.

---

## Results

The generated MITRE ATT&CK report confirmed that Wazuh successfully categorized security events observed during the laboratory exercise.

The correlation between security alerts and MITRE ATT&CK tactics demonstrated how SIEM platforms can support security analysts in identifying attacker behavior and investigating potential incidents.
