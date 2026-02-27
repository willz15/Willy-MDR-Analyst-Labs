# Lab Name: Lab-1-Persistence.md
**Date:** 2026-XX-XX
**Category:** [e.g., Endpoint Forensics / Threat Hunting]
**Tools Used:** [e.g., OSQuery, Sysmon, PowerShell]

## 1. Objective
A brief summary of what you were trying to achieve or the "threat" you were hunting for.

## 2. Environment Setup
* **Endpoint:** Windows 10/11 VM (Home Lab)
* **Security Tooling:** OSQuery / Sophos XDR
* **Attack Tool:** Manual Registry Edit 

## 3. Investigation Steps (The "Process")
Describe the steps you took. Use code blocks for commands.
1. **Activity Generation:** How did you "break" it?
2. **Observation:** Where did you look first?
3. **The Hunt:** What specific queries or tools did you use to find the evidence?

## 4. Findings & Artifacts
This is the most important part. Show your proof.
* **Evidence 1:** [Screenshot of OSQuery result]
* **Evidence 2:** [Screenshot of Event Viewer or Process Explorer]

## 5. Analysis & MITRE Mapping
* **Technique:** [e.g., T1547.001 - Boot or Logon Autostart Execution]
* **Analysis:** Explain *why* this is malicious. (e.g., "The process was running from a temp folder with a non-standard parent process.")

## 6. Conclusion / Remediation
How would you fix this or alert on it in a real MDR environment?
