# Security-Monitoring-Controls-and-Auditing

# Scenario
Your practical context
Your organisation relies on Linux systems for business-critical services. Management has approved controls for authentication monitoring, privileged access, system auditing, vulnerability management and configuration assessment, but internal assurance reviews show that evidence is being collected inconsistently.

You are acting as a Security Control Assurance Analyst. Your responsibility is to inspect an assigned authorised Linux system, generate and analyse security evidence, identify events or weaknesses that require governance attention, and translate the technical evidence into a structured control-monitoring record and management-level audit report.

All practical work must be completed only within the Linux environment assigned to you for training.

# Objectives
What you must demonstrate
Configure and analyse Linux system auditing using auditd; use ausearch and aureport to retrieve and summarise security-relevant audit events; investigate authentication, privilege-use and system events using journalctl, grep and Linux log sources; perform a security assessment using Lynis; identify findings requiring governance attention; link technical evidence to security-control objectives, ownership, status, remediation and retesting; and explain how Linux security evidence can support SIEM, automated monitoring and continuous control assurance.

# Laboratory guidance
Assume the role of Security Control Assurance Analyst for an organisation that depends on Linux systems for business-critical services.

Using only your assigned authorised Linux practice environment, you will configure and examine Linux auditing, analyse authentication and system logs, review privilege-use activity, and perform a security assessment using Lynis.

You must preserve evidence of your work and identify at least three events, weaknesses or conditions that require governance attention. You will then translate your findings into a control-monitoring table showing the relevant control objective, evidence source, control owner, observed status, KPI/KRI or threshold, security significance, remediation action and retest requirement.

The laboratory also requires you to explain how host-level evidence from auditd, Linux logs and Lynis could contribute to SIEM, automated alerting and continuous control monitoring.

Submit one concise professional Linux Security Monitoring and Audit Report together with the required supporting practical evidence. Read the attached assessment brief completely before beginning.

Do not modify, test, scan or attempt authentication against any system outside your assigned authorised lab environment.

# Required evidence
Evidence Bundle 1 Auditd Configuration and Events: Evidence that auditd is active; loaded custom audit rules; ausearch evidence; aureport evidence; and interpretation of at least one audit event.

Evidence Bundle 2 Linux Log Analysis: journalctl evidence; authentication and/or privilege-use review; system error/warning analysis; and a security-event findings table.

Evidence Bundle 3 Lynis Security Assessment: Lynis execution evidence; version and assessment summary; hardening index where available; at least three warnings, suggestions or notable findings; and prioritised remediation recommendations.

Evidence Bundle 4 Control Monitoring and Governance: A completed control-monitoring table containing at least five control/evidence rows, with at least three based directly on evidence collected during the lab. Include control owner, status, threshold, significance, remediation and retesting.

Evidence Bundle 5 SIEM and Automation Mapping: A one-page diagram or structured table showing how Linux audit/log evidence could feed enterprise SIEM or continuous monitoring, including which conditions should remain operational alerts and which require governance escalation.

Evidence Bundle 6 Final Audit Report: Executive summary, scope and authorisation, methodology, findings, evidence, risk/priorities, recommendations, remediation owners, control-monitoring table and retest plan.

The detailed source lab already requires students to generate and query audit records with ausearch/aureport, inspect system and authentication logs, and run Lynis assessments; the polished brief turns those activities into formal governed evidence
