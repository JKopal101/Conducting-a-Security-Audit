# Conducting-a-Security-Audit: Case Study

## Overview
This project involves conducting a comprehensive security audit for **Botium Toys**, a fictional company introduced as part of the **Google Cybersecurity Certificate Course**. The course provides a hands-on learning experience in assessing risks, evaluating vulnerabilities, and enhancing security and compliance within an organization.

**Botium Toys** is a small U.S.-based business that develops and sells toys. The business has a single physical location serving as their main office, storefront, and warehouse. As their online presence has grown, Botium Toys is facing increasing pressures to ensure the security and compliance of its infrastructure. The goal of the audit is to identify risks, evaluate vulnerabilities, and assess the company’s compliance with relevant regulations.

## Scenario: Botium Toys Security Audit
**Botium Toys** has experienced significant growth, attracting customers both locally and internationally. The company’s IT department has expressed concerns over the lack of a solid security framework and the need to ensure compliance with regulatory requirements such as **PCI DSS** and **GDPR**. The IT manager has decided to conduct an internal audit to assess the company's security controls, identify vulnerabilities, and ensure that the company’s IT infrastructure is prepared to handle the growing demands.

### Goals
- Assess the current IT assets and systems.
- Review existing security controls and compliance status.
- Identify security risks and vulnerabilities in the company’s infrastructure.
- Provide recommendations for improving security and achieving compliance with regulatory standards.

### Current Assets
- **Physical Assets**: Storefront products, employee devices (desktops, smartphones), and in-store infrastructure.
- **Digital Assets**: Customer data, e-commerce platform, inventory management systems, accounting software, etc.
- **IT Infrastructure**: Internal networks, legacy systems, cloud storage, and disaster recovery procedures.

### Risk Assessment
#### Risk Description
Botium Toys currently lacks a comprehensive security framework and may not be fully compliant with U.S. and international regulations. There are significant risks related to the exposure of sensitive customer data, non-compliance with regulatory standards, and lack of disaster recovery planning.

#### Control Best Practices
- Implementing the **NIST Cybersecurity Framework (CSF)** to help identify and manage critical assets.
- **Risk score**: 8/10 — High due to inadequate controls and potential fines for non-compliance.

---

## Controls Assessment Checklist

### Existing Security Controls

| Does Botium Toys currently have this control in place? | Control Type           | Explanation                                                                 |
|-------------------------------------------------------|------------------------|-----------------------------------------------------------------------------|
| No                                                    | Least Privilege        | Employees currently have broad access to sensitive customer data. Access needs to be restricted. |
| No                                                    | Disaster Recovery Plan | No disaster recovery plan is in place. A plan for business continuity must be established. |
| Yes                                                   | Firewall               | A firewall is in place to block unauthorized access to the network.         |
| ?                                                     | Password Policies      | Password policies are weak and need to be strengthened to protect user accounts. |
| Yes                                                   | Antivirus              | Antivirus software is installed and actively monitored.                      |
| No                                                    | Backups                | No backup plan is in place, leaving data vulnerable in the event of an incident. |
| No                                                    | Encryption             | Sensitive customer data is not encrypted, putting it at risk.               |
| No                                                    | IDS (Intrusion Detection System) | No IDS is in place to detect potential security breaches.                   |
| Yes                                                   | CCTV                   | CCTV systems are installed and provide physical security at the storefront.  |
| Yes                                                   | Fire Detection         | Fire detection systems are in place but need regular maintenance and management. |

---

## Compliance Checklist

### Regulatory Compliance

#### **Payment Card Industry Data Security Standard (PCI DSS)**

| Best Practice                                              | Explanation                                                         |
|------------------------------------------------------------|---------------------------------------------------------------------|
| No                                                         | Authorized users have access to customer credit card data, which violates PCI DSS. |
| No                                                         | Credit card information is not stored in a secure, encrypted environment. |

#### **General Data Protection Regulation (GDPR)**

| Best Practice                                              | Explanation                                                         |
|------------------------------------------------------------|---------------------------------------------------------------------|
| No                                                         | The company does not comply with GDPR practices, putting it at risk of fines for EU customer data breaches. |
| Yes                                                        | Privacy policies are maintained, though they may need further enhancement. |

#### **System and Organization Controls (SOC)**

| Best Practice                                              | Explanation                                                         |
|------------------------------------------------------------|---------------------------------------------------------------------|
| No                                                         | User access policies have not been established for internal data.   |
| Yes                                                        | Data integrity is maintained, ensuring data is accurate and complete. |
| No                                                         | Data access is not properly restricted; employees can access all company data. |

---

## Recommendations
Based on the findings from the audit, the following recommendations should be implemented to improve **Botium Toys’** security posture:

- **Implement Least Privilege Access**: Restrict employee access to only the data necessary for their role.
- **Establish a Disaster Recovery Plan**: Ensure business continuity by implementing disaster recovery procedures.
- **Strengthen Password Policies**: Enforce strong password management practices across all systems and devices.
- **Encrypt Sensitive Data**: Implement encryption for sensitive customer and payment data to protect privacy.
- **Implement Regular Backups**: Develop and maintain an effective backup strategy to ensure data can be restored after an incident.
- **Deploy Intrusion Detection Systems (IDS)**: Introduce IDS to monitor and respond to potential security threats.
- **Ensure PCI DSS and GDPR Compliance**: Revise company practices to comply with PCI DSS and GDPR regulations to avoid legal consequences.

---
