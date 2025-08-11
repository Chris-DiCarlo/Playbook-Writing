# Writing & Updating Incident Response Playbooks

This project demonstrates my ability to design, write, and maintain comprehensive Incident Response (IR) playbooks to standardize and enhance security operations. These playbooks provide detailed, actionable procedures for SOC and Incident Response teams, ensuring consistency, speed, and accuracy during security incidents. The work covered the full lifecycle—from initial development to periodic reviews and updates—aligning with evolving threats, organizational needs, and security frameworks such as NIST and MITRE ATT&CK.

---

## Tools & Technologies Used
- **Microsoft Sentinel** – SIEM platform for detection and alerting
- **Reports/Logic Apps** – Automation of repetitive IR tasks
- **Microsoft Defender** – Endpoint and email incident response
- **Microsoft Purview & Proofpoint DLP** – Data Loss Prevention playbook creation
- **CrowdStrike Falcon** – Endpoint detection and response integration
- **MITRE ATT&CK** – Threat behavior mapping
- **NIST 800-61** – Guideline for IR lifecycle
- **Confluence / SharePoint** – Documentation management
- **Service Now Secops** – Documentation of incidents

---

## Steps Taken

1. **Requirements Gathering**  
   - Interviewed analysts, IR leads, and management to identify priority incident types.  
   - Reviewed historical incidents to understand common response workflows and gaps.
   - Reviewed painpoints with Analysts.

2. **Playbook Development**  
   - Created detailed step-by-step procedures for incident categories such as phishing, malware, insider threats, cloud account compromise, email compromise, unauthorized disclosures, spill in, geo-improbables, member firm escalations.  
   - Incorporated decision trees, escalation paths, and verification checklists.  
   - Mapped each step when relevant to MITRE ATT&CK techniques and detection rules.

3. **Automation Integration**  
   - Leveraged python,powershell, javascript to automate repetitive tasks like indicator enrichment, user lookups, and ticket creation.  
   - Ensured automation aligned with manual fallback processes.

4. **Review & Validation**  
   - Conducted tabletop exercises to simulate incidents and validate playbook effectiveness.  
   - Collected feedback from SOC teams and updated content accordingly.

5. **Version Control & Updates**  
   - Established quarterly review cycles to update playbooks with new detection rules, tooling changes, and emerging threats.  
   - Maintained change logs for audit and compliance tracking.

---

## Lessons Learned
- The importance of **cross-functional collaboration** for practical, usable playbooks.  
- Regular reviews are essential to keep procedures relevant in a constantly evolving threat landscape.  
- Automation should supplement—not replace—analyst decision-making.  

---

## Skills Learned
- **Incident Response Lifecycle Management**  
- **Playbook & Runbook Development**  
- **Threat Mapping with MITRE ATT&CK**   
- **Cross-Team Communication & Process Alignment**  
- **Technical Writing & Documentation Best Practices**  
