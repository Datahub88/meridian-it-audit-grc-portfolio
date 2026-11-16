# Meridian Financial Services — IT Audit & GRC Portfolio

> **Educational simulation:** Meridian Financial Services is a fictional organization created for an independent cybersecurity, IT audit, and governance, risk, and compliance (GRC) portfolio project. All organizational records, roles, approvals, systems, evidence, findings, and test results are simulated unless explicitly identified as actual home-lab components. This repository does not represent work performed for a real client or employer.

## Project objective

Build and document a practical, risk-based IT audit lifecycle that demonstrates the application of CISA concepts and commonly used IT audit practices. The project will progress from governance and risk assessment through audit planning, control testing, reporting, and remediation validation.

## Scenario organization

Meridian Financial Services is a fictional financial services organization. It provides a consistent business scenario for developing audit documentation, identifying technology risks, evaluating controls, and communicating results.

## Repository roadmap

| Folder | Contents |
|---|---|
| `01-Governance` | IT Audit Charter, governance model, roles and responsibilities |
| `02-Risk-Assessment` | Risk universe, risk register, risk analysis and prioritization |
| `03-Audit-Planning` | Audit objectives, scope, criteria, work program and sampling approach |
| `04-Control-Testing` | Control test plans, procedures, evidence logs and test results |
| `05-Audit-Findings` | Draft findings, root-cause analysis, risk ratings and reporting |
| `06-Remediation` | Corrective action plans, ownership, due dates and validation |
| `07-References` | Framework references, definitions and supporting material |

## Home-lab environment

The current hands-on lab components are:

- **Ubuntu:** Wazuh server for security monitoring and log analysis.
- **Windows 10:** Endpoint with the Wazuh agent installed.
- **Kali Linux:** Virtual machine used for controlled security-testing exercises.
- **VirtualBox:** Current virtual-machine networking is configured using NAT.

Active Directory and a Windows Server domain controller are **not currently implemented**. Any future expansion will be documented as planned until it is built and tested. Testing is limited to systems owned and controlled within this educational simulation.

## Audit approach and working principles

1. Establish the audit mandate, independence, objectives, scope, and criteria before testing.
2. Understand the process and assess relevant risks before selecting controls.
3. Evaluate control design separately from operating effectiveness.
4. Obtain sufficient, relevant, and reliable evidence.
5. Use inquiry, inspection, observation, and reperformance appropriately; corroborate inquiry where necessary.
6. Investigate exceptions, assess their cause and impact, and expand testing when justified.
7. Document findings using condition, criteria, cause, effect/risk, and recommendation.
8. Track corrective actions and validate remediation using evidence.
9. Clearly distinguish simulated artifacts and results from actual home-lab activity.

## Project status

**Phase 1 — Governance:** Initial IT Audit Charter, Version 1.0, prepared for this simulation. The charter includes a clearly labeled simulated approval record; it is not evidence of authorization by a real organization.

**Next phase:** Define Meridian's simulated organizational structure, business processes, technology environment, and initial risk universe.

## Disclaimer

This repository is an educational portfolio and home-lab simulation. Meridian Financial Services, its personnel, governance bodies, approvals, business records, audit results, and findings are fictional. The project does not represent an actual audit, an actual financial institution, or professional IT audit work performed for an employer or client.

