# Description:
This project involved executing a buffer overflow attack on a vulnerable machine within a controlled environment, designed to explore advanced offensive cybersecurity techniques. Using reconnaissance and enumeration strategies, I identified the target machine’s vulnerabilities, ultimately leveraging the EternalBlue exploit to gain administrative access. Persistence was achieved by modifying the administrator password and deploying a custom service for backdoor access, ensuring ongoing control.

## Process Overview:

Initial Access & Reconnaissance: Identified network devices using Nmap and confirmed vulnerabilities with Metasploit, employing EternalBlue for initial access.
Persistence: Established persistent access by modifying admin credentials and initiating a backdoor service, “HungerGamesChat.”
Buffer Overflow Exploitation: Located the buffer overflow vulnerability using a fuzzer and identified the Extended Instruction Pointer (EIP). Developed a payload tailored to exploit this vulnerability, allowing system control and flag retrieval.
Analysis & Payload Execution: Utilized debugging tools (e.g., Immunity Debugger) to refine the payload, leveraging SLmail scripts to deliver it effectively.
Recommendation Summary:
To mitigate buffer overflow risks, the project recommended input validation, deployment of compiler tools (StackGuard, StackShield), and runtime protections (DEP, ASLR). These preventive measures enhance system resilience against similar exploitation attempts.

## Outcome:
Successfully executing the buffer overflow attack demonstrated a deep understanding of exploiting system weaknesses and maintaining system control in a penetration testing scenario. This project significantly enhanced my practical knowledge of exploit development, payload crafting, and risk assessment in cybersecurity.
