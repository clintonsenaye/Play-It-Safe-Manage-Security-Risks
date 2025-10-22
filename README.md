# Internal Security Audit: Botium Toys

## Overview

This project demonstrates a comprehensive internal security audit conducted for Botium Toys, a fictional toy company. The audit evaluates the organization's current security posture, identifies vulnerabilities, and provides prioritized recommendations for improving controls and ensuring regulatory compliance.

**Skills Demonstrated:** Risk Assessment | Control Analysis | Compliance Evaluation | CISSP Security Domains | Security Frameworks

---

## Table of Contents

- [Objective](#objective)
- [Scope](#scope)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Deliverables](#deliverables)
- [Frameworks & Standards](#frameworks--standards)
- [Tools & Techniques](#tools--techniques)

---

## Objective

The primary objective of this audit was to:
- Assess Botium Toys' current security controls against industry best practices
- Identify high-risk vulnerabilities and gaps in the security program
- Evaluate compliance with relevant regulations based on business operations and payment processing
- Provide actionable, prioritized remediation recommendations

---

## Scope

The audit encompassed:
- **Asset inventory review** - Analysis of all company assets requiring protection
- **Control assessment** - Evaluation of existing administrative, technical, and physical controls
- **Compliance analysis** - Review of regulatory requirements based on:
  - Geographic operating locations
  - Payment processing methods
  - Data handling practices

---

## Methodology

### 1. Risk Assessment
Analyzed Botium Toys' audit scope, goals, and current risk landscape to understand the organization's threat profile.

### 2. Control Assessment
Systematically reviewed each security control by:
- Examining control categories (administrative, technical, physical)
- Evaluating current implementation status
- Assigning priority levels (High, Medium, Low, N/A) based on risk impact
- Identifying controls requiring immediate implementation

### 3. Compliance Evaluation
Created a comprehensive compliance checklist considering:
- Industry-specific regulatory requirements
- Geographic jurisdictions where the company operates
- Payment Card Industry (PCI) standards for payment processing
- Data protection regulations

---

## Key Findings

The audit identified critical gaps in Botium Toys' security program, including:

- **Missing or inadequate controls** requiring immediate implementation to protect organizational assets
- **Compliance gaps** that expose the company to regulatory penalties
- **High-priority vulnerabilities** that could impact business operations and customer data security

*Detailed findings and specific recommendations are documented in the deliverables below.*

---

## Deliverables

### 1. Audit Scope and Goals

**Summary:**
Perform an audit of Botium Toys' cybersecurity program. The audit needs to align current business practices with industry standards and best practices. The audit is meant to provide mitigation recommendations for vulnerabilities found that are classified as "high risk," and present an overall strategy for improving the security posture of the organization. The audit team needs to document their findings, provide remediation plans and efforts, and communicate with stakeholders.

**Scope:**
Botium Toys internal IT audit will assess the following:
- Current user permissions set in the following systems: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool.
- Current implemented controls in the following systems: accounting, end point detection, firewalls, intrusion detection system, Security Information and Event Management (SIEM) tool.
- Current procedures and protocols set for the following systems: accounting, end point detection, firewall, intrusion detection system, Security Information and Event Management (SIEM) tool.
- Ensure current user permissions, controls, procedures, and protocols in place align with necessary compliance requirements.
- Ensure current technology is accounted for. Both hardware and system access.

**Goals:**
The goals for Botium Toys' internal IT audit are:
- To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
- Establish a better process for their systems to ensure they are compliant
- Fortify system controls
- Implement the concept of least permissions when it comes to user credential management
- Establish their policies and procedures, which includes their playbooks
- Ensure they are meeting compliance requirements

### 2. Controls Assessment

**Current Assets**

Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Vendor access management
- Data center hosting services
- Data retention and storage
- Badge readers
- Legacy system maintenance: end-of-life systems that require human monitoring

#### Administrative Controls

| Control Name | Control Type and Explanation | Implementation Needed | Priority |
|-------------|------------------------------|----------------------|----------|
| **Least Privilege** | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | ✓ | High |
| **Disaster Recovery Plans** | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components | ✓ | High |
| **Password Policies** | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques | ✓ | High |
| **Access Control Policies** | Preventative; increase confidentiality and integrity of data | ✓ | High |
| **Account Management Policies** | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | ✓ | High/Medium |
| **Separation of Duties** | Preventative; ensure no one has so much access that they can abuse the system for personal gain | ✓ | High |

#### Technical Controls

| Control Name | Control Type and Explanation | Implementation Needed | Priority |
|-------------|------------------------------|----------------------|----------|
| **Firewall** | Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network | N/A | N/A |
| **Intrusion Detection System (IDS)** | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | ✓ | High |
| **Encryption** | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | ✓ | High/Medium |
| **Backups** | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | ✓ | High |
| **Password Management System** | Corrective; password recovery, reset, lock out notifications | ✓ | High/Medium |
| **Antivirus (AV) Software** | Corrective; detect and quarantine known threats | ✓ | High |
| **Manual Monitoring, Maintenance, and Intervention** | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | ✓ | High |

#### Physical Controls

| Control Name | Control Type and Explanation | Implementation Needed | Priority |
|-------------|------------------------------|----------------------|----------|
| **Time-Controlled Safe** | Deterrent; reduce attack surface/impact of physical threats | ✓ | Medium/Low |
| **Adequate Lighting** | Deterrent; limit "hiding" places to deter threats | ✓ | Medium/Low |
| **Closed-Circuit Television (CCTV) Surveillance** | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | ✓ | High/Medium |
| **Locking Cabinets (for network gear)** | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | ✓ | Medium |
| **Signage Indicating Alarm Service Provider** | Deterrent; makes the likelihood of a successful attack seem low | ✓ | Low |
| **Locks** | Preventative; physical and digital assets are more secure | ✓ | High |
| **Fire Detection and Prevention** | Detective/Preventative; detect fire in the toy store's physical location to prevent damage to inventory, servers, etc. | ✓ | Medium/Low |

### 3. Compliance Checklist

#### Federal Energy Regulatory Commission - North American Electric Reliability Corporation (FERC-NERC)

**Regulation Overview:**
The FERC-NERC regulation applies to organizations that work with electricity or that are involved with the U.S. and North American power grid. Organizations have an obligation to prepare for, mitigate, and report any potential security incident that can negatively affect the power grid. Organizations are legally required to adhere to the Critical Infrastructure Protection Reliability Standards (CIP) defined by the FERC.

**Applicability:** N/A

---

#### General Data Protection Regulation (GDPR)

**Regulation Overview:**
GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens' data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen's data is compromised, they must be informed within 72 hours of the incident.

**Applicability:** ✓ **Botium Toys needs to adhere to GDPR** because they conduct business and collect personal information from people worldwide, including the E.U.

---

#### Payment Card Industry Data Security Standard (PCI DSS)

**Regulation Overview:**
PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment.

**Applicability:** ✓ **Botium Toys needs to adhere to PCI DSS** because they store, accept, process, and transmit credit card information in person and online.

---

#### The Health Insurance Portability and Accountability Act (HIPAA)

**Regulation Overview:**
HIPAA is a federal law established in 1996 to protect U.S. patients' health information. This law prohibits patient information from being shared without their consent. Organizations have a legal obligation to inform patients of a breach.

**Applicability:** N/A

---

#### System and Organizations Controls (SOC type 1, SOC type 2)

**Regulation Overview:**
The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization's financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

**Applicability:** ✓ **Botium Toys must implement and enforce suitable user access controls** for both internal and external personnel, including third-party vendors, to minimize potential risks and guarantee the security of data.

---

## Frameworks & Standards

This audit incorporated knowledge of the following industry-recognized frameworks:

- **CISSP Eight Security Domains**
  - Security and Risk Management
  - Asset Security
  - Security Architecture and Engineering
  - Communication and Network Security
  - Identity and Access Management (IAM)
  - Security Assessment and Testing
  - Security Operations
  - Software Development Security

- **Security Control Frameworks**
  - NIST Cybersecurity Framework (CSF)
  - ISO 27001/27002
  - CIS Controls

- **Compliance Standards**
  - PCI DSS (Payment Card Industry Data Security Standard)
  - GDPR (General Data Protection Regulation)
  - SOC 2 (System and Organization Controls)

---

## Tools & Techniques

- **Control Assessment Matrices** - Structured evaluation of security controls
- **Risk Prioritization** - Classification methodology for remediation planning
- **Compliance Mapping** - Alignment of business operations with regulatory requirements
- **Gap Analysis** - Identification of discrepancies between current and desired security state

---

## Skills Applied

- Security auditing and assessment
- Risk management and analysis
- Regulatory compliance evaluation
- Control framework implementation
- Security documentation and reporting
- Stakeholder communication

---

## About This Project

This project was completed as part of the **Google Cybersecurity Professional Certificate** program, specifically within the "Play It Safe: Manage Security Risks" course. It demonstrates practical application of security audit principles, control assessment methodologies, and compliance evaluation techniques in a realistic business scenario.
