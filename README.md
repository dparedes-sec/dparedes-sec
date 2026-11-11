# Hi, I'm Daniel Paredes

### Junior SOC/SecOps Professional | Alert Triage · Detection Engineering · Incident Response

Civil Informatics Engineer focused on SOC operations, security monitoring, and evidence-based incident documentation.

I build controlled security labs to investigate alerts, document detection logic, and understand the applications and containers behind security telemetry. My development background in Python, FastAPI, and Docker supports my work in AppSec and DevSecOps.

> All security testing in this portfolio is limited to owned laboratory environments, synthetic data, or intentionally vulnerable applications authorized for testing.

## Core Focus

- SOC alert triage and investigation
- Detection engineering with Wazuh and Falco
- Phishing, firewall, endpoint, and vulnerability analysis
- MITRE ATT&CK mapping and incident response documentation
- Container, API, and software supply-chain security
- Reproducible security labs with sanitized evidence

## Selected Security Projects

### 1. [Mini-SOC with Wazuh](https://github.com/dparedes-sec/mini-soc-wazuh)

**Primary focus:** SOC Operations / Detection Engineering  
**Status:** In progress

A self-contained laboratory for collecting and investigating security telemetry with Wazuh and containerized components.

**Demonstrates:**

- Wazuh deployment in an owned Docker laboratory
- SSH authentication monitoring and brute-force detection
- MITRE ATT&CK mapping for documented detection scenarios
- Vulnerability monitoring
- Runtime security experimentation with Falco
- Incident investigation notes and response runbooks

**Evidence standard:** Sanitized logs, reproducible test steps, positive and negative validation, expected alert fields, false-positive considerations, and documented limitations.

**Technologies:** Wazuh · Falco · Docker · Linux · MITRE ATT&CK

---

### 2. [Secure Biological Data API](https://github.com/dparedes-sec/bio-api-secure)

**Primary focus:** Application Security / DevSecOps  
**Status:** Active laboratory project

A FastAPI service used to demonstrate security controls for authentication, authorization, input validation, audit logging, and container execution.

**Demonstrates:**

- JWT-based authentication
- Role-based access control
- Pydantic input validation
- Rate limiting and security headers
- Audit logging without intentionally storing sensitive personal data
- Non-root Docker execution
- OWASP API Security Top 10 review

**Evidence standard:** Control definitions, positive and negative tests, sample sanitized logs, known limitations, and remediation notes.

**Technologies:** FastAPI · Python · PostgreSQL · JWT · Docker · GitHub Actions

---

### 3. [Cybersecurity Laboratory](https://github.com/dparedes-sec/cybersecurity-lab)

**Primary focus:** Vulnerability Analysis / Security Documentation  
**Status:** Controlled learning laboratory

A documented environment for assessing intentionally vulnerable applications and translating findings into clear technical reports.

**Demonstrates:**

- Testing restricted to authorized laboratory targets
- Reproducible finding documentation
- CVSS and OWASP classification
- Sanitized evidence collection
- Risk explanation and remediation guidance
- Positive and negative validation where applicable

**Technologies:** OWASP Juice Shop · DVWA · OWASP ZAP · Linux

## Investigation and Documentation Approach

For each detection, alert, or security control, I aim to document:

| Field | Purpose |
|---|---|
| Data source | Identifies where the telemetry or application event originates |
| Detection or control logic | Explains what behavior is detected or prevented |
| Security mapping | MITRE ATT&CK for detection scenarios or OWASP for application controls |
| Severity | Uses documented impact and confidence criteria |
| False positives | Describes legitimate activity that may trigger the logic |
| Positive test | Shows the controlled action expected to generate the result |
| Negative test | Confirms that benign or unauthorized conditions do not produce the same result |
| Response | Defines initial triage, containment, escalation, or remediation steps |
| Limitations | States what the detection or control cannot prove or prevent |

No production data, third-party targets, persistence mechanisms, or unauthorized exploitation are used in these projects.

## Technical Toolkit

**SOC and Security Operations**

`Wazuh` `EDR Triage` `Firewall Analysis` `Phishing Analysis` `MITRE ATT&CK` `Incident Documentation`

**Runtime and Infrastructure Security**

`Falco` `Docker` `Linux` `Vulnerability Management`

**Application Security and DevSecOps**

`FastAPI` `Python` `REST APIs` `JWT` `RBAC` `OWASP` `GitHub Actions`

## Professional Direction

I am developing practical, documented experience for junior roles in:

- SOC Analysis and SecOps
- Security Monitoring and Detection Engineering
- Application Security
- DevSecOps and Container Security

My main professional identity is **SOC/SecOps**. AppSec and DevSecOps are supporting capabilities that help me investigate telemetry in context and collaborate with development teams.

## Languages

- Spanish: Native
- English: Professional working proficiency

## Contact

- [LinkedIn](https://linkedin.com/in/daniel-paredes-ojeda/)
- GitHub: `@dparedes-sec`

## Ethics and Scope

All demonstrations are performed in owned laboratories, with synthetic data, public datasets authorized for research, or intentionally vulnerable applications. Any simulated event, log, screenshot, or result is labeled as simulated. Findings are presented for defensive education, detection validation, and remediation.
