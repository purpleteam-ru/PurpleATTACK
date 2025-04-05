# MITRE ATT&CK® Enterprise Framework Overview

## 🌐 Framework Purpose
MITRE ATT&CK® (Adversarial Tactics, Techniques, and Common Knowledge) is a **globally-accessible knowledge base** of adversary behaviors and tactics observed in real-world attacks against enterprise networks.

## 📊 Core Components
| Component       | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| **Tactics**     | The "why" of an attack (e.g., Initial Access, Persistence)                  |
| **Techniques**  | The "how" - specific implementation methods (e.g., Spearphishing Attachment)|
| **Procedures**  | Real-world examples from threat actors                                      |
| **Mitigations** | Defensive recommendations                                                   |
| **Detections**  | Detection methods for each technique                                        |

## 🔥 Enterprise Tactics Breakdown
1. **Reconnaissance (TA0043)**  
   - Gathering victim identity/network information pre-attack

2. **Resource Development (TA0042)**  
   - Establishing infrastructure/accounts for operations

3. **Initial Access (TA0001)**  
   - Entry vectors like phishing or exploiting public apps

4. **Execution (TA0002)**  
   - Running malicious code via command lines/scripts

5. **Persistence (TA0003)**  
   - Maintaining foothold via registry changes/trojans

6. **Privilege Escalation (TA0004)**  
   - Gaining higher-level permissions

7. **Defense Evasion (TA0005)**  
   - Avoiding detection (e.g., file deletion, code signing)

8. **Credential Access (TA0006)**  
   - Stealing credentials via keylogging/Mimikatz

9. **Discovery (TA0007)**  
   - Network/account reconnaissance post-compromise

10. **Lateral Movement (TA0008)**  
    - Pivoting through networks (RDP/WMI/SMB)

11. **Collection (TA0009)**  
    - Data aggregation from target systems

12. **Command and Control (TA0011)**  
    - Establishing communication channels

13. **Exfiltration (TA0010)**  
    - Data theft techniques

14. **Impact (TA0040)**  
    - Disrupting systems (wiper malware, ransomware)

## 🛡️ Practical Applications
- **Threat Intelligence** - Mapping adversary TTPs
- **Detection Engineering** - Building detection rules
- **Red Teaming** - Emulating real-world attacks
- **Gap Analysis** - Identifying security weaknesses

🔗 Official Resources

    ATT&CK Matrix Navigator
    Techniques by APT Group
