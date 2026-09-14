![Kainã Roque — Network Analyst & Network Automation](assets/header.svg)

I build practical automation for network operations — collecting device data,
turning CLI output into structured information, and using it for **auditing,
inventory and anomaly detection**.

I work as a **Network Analyst** in enterprise environments, so the projects here
are shaped by real operational needs across switching, wireless, network access
control, security and network services.

> **Read-only first:** I automate collection and analysis before I automate change.

---

## What I build

| Area | What I do |
| :--- | :--- |
| **Network data collection** | Automated SSH/CLI collection from network devices using Python and Netmiko |
| **Parsing & normalization** | Transforming unstructured CLI output into structured data for analysis |
| **Network auditing** | Validating configurations against technical baselines and operational rules |
| **Inventory & topology** | Building structured views of interfaces, VLANs, LAGs and network neighbors |
| **Anomaly detection** | Identifying configuration inconsistencies and unexpected network states |
| **Network APIs** | Evolving CLI-based workflows toward REST APIs and structured network data |

```text
 network devices
      │
      │ SSH / API
      ▼
  collection
      │
      ▼
    parsing
      │
      ▼
 structured data
      │
      ├──────────▶ inventory
      ├──────────▶ audit
      ├──────────▶ topology
      └──────────▶ anomaly detection
