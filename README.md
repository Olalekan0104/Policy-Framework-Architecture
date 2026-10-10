# Solstice Health Analytics: Policy Framework Architecture

This project develops a foundational policy framework for Solstice Health Analytics, a growing health analytics company that manages sensitive patient wellness data, cloud-hosted services, wearable-device data, and telehealth integrations. It establishes a policy hierarchy, selects six priority policies, and develops a Change Management Policy with defined approval and review responsibilities.

## Table of Contents

- [Project Overview](#project-overview)
- [Network Topology](#network-topology)
- [Tools and Technologies](#tools-and-technologies)
- [Configuration Steps](#configuration-steps)
- [Results and Findings](#results-and-findings)
- [Author](#author)

## Project Overview

Solstice Health Analytics has approximately 180 employees across two offices and a remote-first workforce. The company has grown without establishing a formal policy framework, creating inconsistent security practices, unclear ownership of information assets, and increased compliance risk.

The objectives of this project were to:

- Select four foundational and two advanced policies.
- Organize policies according to an appropriate document hierarchy.
- Define policy approval and review responsibilities.
- Draft a Change Management Policy covering purpose, scope, and three key policy statements.
- Establish a repeatable approach to requesting, assessing, approving, implementing, and reviewing changes.

## Network Topology

This project focuses on policy governance rather than physical or logical network configuration. The source scenario identifies Azure-hosted services, wearable-device data ingestion, telehealth partner integrations, and remote access, but does not provide IP addresses, subnet details, or a network diagram.

The policy framework follows this hierarchy:

```text
Policy Framework
       |
       v
     Policy
       |
       v
    Standard
       |
       v
   Procedure
       |
       v
   Guideline
```

- **Policy:** Defines management direction and mandatory expectations.
- **Standard:** Specifies mandatory requirements supporting a policy.
- **Procedure:** Describes the steps required to complete a process.
- **Guideline:** Provides recommended practices and advice.

## Tools and Technologies

- **Governance, Risk, and Compliance (GRC):** Policy governance and compliance management.
- **Microsoft Azure:** Cloud platform identified in the business scenario.
- **Information Security Policy:** Establishes the organization's overall security expectations.
- **Access Control Policy:** Governs access authorization and permissions.
- **Data Classification and Handling Policy:** Defines how information is classified and protected.
- **Acceptable Use Policy:** Establishes acceptable use of organizational systems and assets.
- **Mobile Device Policy:** Addresses the secure use of devices accessing company information.
- **Remote Access and VPN Policy:** Defines secure remote connectivity requirements.
- **Change Management Policy:** Establishes controls for requesting, assessing, approving, implementing, and reviewing changes.
- **PDF:** Documents the completed assessment and policy recommendations.
- **GitHub:** Stores and showcases the project as part of a GRC portfolio.

## Configuration Steps

1. **Review the business environment.** Identified the company's growth, cloud-hosted services, sensitive data, remote workforce, and lack of formal policies.

2. **Select foundational policies.** Chose Information Security, Access Control, Data Classification and Handling, and Acceptable Use policies.

3. **Select advanced policies.** Chose Mobile Device and Remote Access and VPN policies based on the company's technology environment.

4. **Define the policy hierarchy.** Distinguished policies from supporting standards, procedures, and guidelines.

5. **Assign ownership and review cycles.** Proposed policy owners, appropriate approval authority, and review schedules.

6. **Draft the Change Management Policy.** Defined its purpose and scope and developed statements covering the change lifecycle.

7. **Establish approval and implementation requirements.** Included risk assessment, documented authorization, testing, implementation evidence, and post-implementation review.

8. **Document findings and recommendations.** Prepared the final assessment with the proposed framework and implementation guidance.

## Results and Findings

The project established a proposed policy framework containing six priority policies.

Key findings included:

- The organization needs a formal policy hierarchy and clearly assigned ownership.
- Policies should be supported by standards and procedures rather than combining all document types into one.
- Change requests should include business justification, impact assessment, testing, authorization, and rollback or recovery planning where feasible.
- Changes should be implemented by authorized personnel and reviewed afterward.
- Policy exceptions, approvals, and completed reviews should be documented as evidence.

The recommended outcome is a more consistent approach to security governance, accountability, and controlled change management.

This is a proposed framework based on the supplied case study. Implementation and compliance effectiveness would require further assessment and evidence.

## Author

- **Project:** Solstice Health Analytics Policy Framework Architecture
- **Specialization:** Governance, Risk, and Compliance (GRC)
- **Focus Areas:** Policy Hierarchy, Policy Governance, Change Management, Approval and Review Lifecycle
