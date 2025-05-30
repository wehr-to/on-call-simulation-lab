# 🚨 oncall-scenarios

This repo simulates real-world on-call incidents to build muscle memory around triage, communication, tooling, and escalation. It’s built for security analysts, infra engineers, and operations-minded devs who want to be **ready when production breaks**.

## 🔥 Why This Exists

Being on-call means responding calmly, methodically, and responsibly under pressure.

This repo simulates what it’s like to:
- Get paged at 2AM
- Calmly investigate the unknown
- Use logs, alerts, and intuition to isolate the issue
- Communicate clearly to users or stakeholders
- Capture lessons learned in retrospectives

## 🧪 Sample Scenarios

| Scenario | Focus |
|----------|-------|
| `cpu-spike-in-prod` | Performance issue tied to runaway process |
| `dns-outage-sunday-night` | Caching + zone TTLs lead to partial outage |
| `ssl-cert-expired` | Downtime due to expired public cert |
| `slow-authentication` | DB latency or caching failure |
| `unknown-host-traffic` | Potential security event or misrouted traffic |

Each scenario includes:
- Symptoms (logs, alerts, user complaints)
- Timeline and response flow
- Root cause
- Retro with prevention ideas

## 🛠 Tooling Reviewed

Quick references and commands for:
- `lsof`, `netstat`, `ss`, `tcpdump`
- `journalctl`, `top`, `dmesg`
- Cloud-native tools (CloudWatch, Azure Monitor, etc.)
- Web troubleshooting (`curl`, `dig`, `openssl s_client`)

## 🧰 Example Playbooks

- How to quickly assess disk fill-up
- Restarting daemons vs killing zombie processes
- Diagnosing DNS failures
- Dealing with auth outage patterns
- Confirming TLS misconfig from client or server side

## 🧠 Ideal For

- SREs and junior DevOps engineers
- Security engineers simulating alert triage
- Cloud engineers prepping for on-call
- Developers joining rotation for the first time


