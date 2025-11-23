NOTE: This needs to be customized per client as appropriate, especially section 3 (Notification & Communication).

# Incident Response & Service Continuity Plan

**Entity:** Northwest Intelligence Solutions LLC

**Primary Lead:** TBD

**Last Updated:** November 2025

**Compliance:** WA RCW 19.255.010 / NIST SP 800-171

## Trigger Events (When to Act)

This plan is activated immediately upon the detection of:

- **Security Breach:** Unauthorized access to the on-premise server (physical or digital).
- **Data Loss:** Ransomware infection, accidental deletion, or drive failure without immediate backup recovery.
- **Service Outage:** Power/Internet failure exceeding 4 hours during active project windows.

## 2. Immediate Response Protocol (The "First Hour")

### Containment (0-60 Minutes)

1. **Disconnect:** Immediately sever the server's internet uplink (unplug Ethernet/disable Wi-Fi) to stop data exfiltration.
1. **Assess:** Determine if the issue is Hardware (outage/fire) or Cyber (ransomware/breach).
    - *If Cyber:* Do **NOT** reboot or power down (preserves RAM evidence). Leave system running but isolated.
	- *If Fire/Physical:* Prioritize human safety; use Type C extinguisher if safe.
1. **Log:** Record timestamp and visual observations in the Physical Entry Log.

## 3. Notification & Communication

**Regulatory Deadline (WA State):** Notification to affected WA residents must be made within **30 days** of discovery (RCW 19.255.010). **Client Contract Standard:** Most engineering contracts require notice within **72 hours**.

| Stakeholder | Contact Info | Trigger Condition |
| --- | --- | --- |
| **Primary IT Support** | TBD | Technical assistance needed. |
| **Legal Counsel** | TBD 555-555-5555 email@example.com | Confirmed data breach/liability. |
| **Client Point of Contact** | TBD 555-555-5555 email@example.com | **REQUIRED** if client data is impacted. |
| **Cyber Insurance Carrier** | Policy # / Claim Phone # | Suspected breach or ransomware. |

## 4. Continuity & Recovery (Getting Back Online)

- **Backup Restoration:**
    - *Primary*: Restore from local encrypted NAS (Network Attached Storage).
    - *Secondary*: Restore from cold storage (encrypted drives held in a separate physical location).
- **Data Sanitization:** If a drive is compromised but functional, it is wiped via DoD 5220.22-M before re-use or disposal.

## 5. Post-Incident Review (Lessons Learned)

Within 5 business days of incident resolution, the Primary Lead will:

1. Document the root cause (e.g., "Phishing email clicked," "Unpatched GPU driver").
1. Update this IRP with new preventative measures.
1. Retain all logs and evidence for 3 years (statute of limitations).
