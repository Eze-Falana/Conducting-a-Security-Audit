# Conducting a Security Audit- Botium Toys
# Table of contents
1. [Introduction](#introduction)
2. [Scenario](#Scenario)
3. [Scope and Goals](#Scope-and-Goals)
4. [Risk assessment](#Risk-assessment)
5. [Compliance Checklist](#Compliance-Checklist)
6. [Recommendations](#Recommendations)
# Introduction
Part of the Google Cybersecurity course was to conduct an internal security audit on Botium toys, a fictious company. The aim is to ensure the audit aligns with industry standards and best practices. This audit must also provide recommendations to mitigate the vulnerabilities found and present an overall plan for improving the security posture of the company.

# Scenario
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

# Scope and Goals
## Scope and goals of the audit

### Scope
The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.


### Goals
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to  improve Botium Toys’ security posture.


### Current assets
Assets managed by the IT Department include: 
- On-premises equipment for in-office business needs
  

Employee equipment
- end-user devices (desktops/laptops, smartphones)
-  remote workstations
- headsets
- cables
- keyboards
- mice
- docking stations
-  surveillance cameras

  
Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management

Internet access
Internal network
Data retention and storage
Legacy system maintenance
-end-of-life systems that require human monitoring 


# Risk assessment

### Current Asset Management and Compliance Overview

At present, the management of assets at Botium Toys is inadequate. Furthermore, the company lacks several critical controls and may not be fully compliant with UK and international regulations and standards.

### Best Practices for Control Implementation

The first function of the NIST Cybersecurity Framework (CSF) is "Identify." To effectively manage their assets, Botium Toys must allocate resources to accurately identify and classify them. This also involves assessing the potential impact of losing these assets, including critical systems, on the company's ability to continue operations.

### Risk Assessment

The risk level has been assessed as 8 out of 10, indicating significant concern. This high score results from the absence of key controls and insufficient adherence to compliance best practices.

Further Observations

The potential consequences of asset loss are considered moderate, mainly because the IT department is uncertain about which assets are at risk. The risk of asset exposure or penalties from regulatory bodies is substantial since Botium Toys lacks comprehensive controls and does not fully adhere to compliance regulations designed to protect sensitive data.

Key details include:

All employees at Botium Toys currently have access to internally stored data, including potentially sensitive customer information such as credit card details and personally identifiable information (PII).
Encryption is not being used to safeguard customers' credit card data, which is stored, processed, and transmitted within the company's internal systems.
Critical access controls, such as least privilege and separation of duties, are not in place.
The IT department has taken steps to ensure data availability and integrity, including:

Implementing a firewall configured with appropriate security rules.
Installing and regularly monitoring antivirus software.
However, the department has not yet deployed an intrusion detection system (IDS) and lacks disaster recovery plans and backups for critical data.

There is a plan to notify EU customers within 72 hours in the event of a security breach. Privacy policies and procedures have been established and enforced within the IT department and among other employees to ensure proper data documentation and maintenance.

While a password policy exists, its current requirements do not meet modern standards for complexity (e.g., at least eight characters, including a combination of letters, numbers, and special characters). Additionally, the absence of a centralised password management system sometimes hampers productivity when password resets or recoveries are needed.

Legacy systems are being monitored and maintained, but there is no established schedule or clear intervention methods for these tasks.

Botium Toys’ physical locations, including the main offices, storefront, and warehouse, are equipped with adequate security measures such as locks, CCTV surveillance, and fire detection and prevention systems.

# Control and Compliance Checklist

## Controls Assessment Checklist

| Control                                    | Yes | No  | Explanation |
|--------------------------------------------|-----|-----|-------------|
| **Least Privilege**                        |     |  x  | Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach. |
| **Disaster Recovery Plans**                |     |  x  | There are no disaster recovery plans in place. These need to be implemented to ensure business continuity. |
| **Password Policies**                      |     |  x  | Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network. |
| **Separation of Duties**                   |     |  x  | Needs to be implemented to reduce the possibility of fraud/access to critical data, as the company CEO currently runs day-to-day operations and manages the payroll. |
| **Firewall**                               |  x  |     | The existing firewall blocks traffic based on an appropriately defined set of security rules. |
| **Intrusion Detection System (IDS)**       |     |  x  | The IT department needs an IDS in place to help identify possible intrusions by threat actors. |
| **Backups**                                |     |  x  | The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity. |
| **Antivirus Software**                     |  x  |     | Antivirus software is installed and monitored regularly by the IT department. |
| **Manual Monitoring of Legacy Systems**    |     |  x  | The list of assets notes the use of legacy systems. These systems are monitored and maintained, but there is not a regular schedule in place and procedures related to intervention are unclear, which could place these systems at risk of a breach. |
| **Encryption**                             |     |  x  | Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information. |
| **Password Management System**             |     |  x  | There is no password management system currently in place; implementing this control would improve IT department/other employee productivity in the case of password issues. |
| **Locks (Offices, Storefront, Warehouse)** |  x  |     | The store’s physical location, which includes the company’s main offices, storefront, and warehouse of products, has sufficient locks. |
| **CCTV Surveillance**                      |  x  |     | CCTV is installed and functioning at the store’s physical location. |
| **Fire Detection/Prevention**              |  x  |     | Botium Toys’ physical location has a functioning fire detection and prevention system. |



# Recommendations
Several controls need to be put in place to strengthen Botium Toys’ security framework and better safeguard the confidentiality of sensitive data. These include implementing least privilege access, establishing disaster recovery plans, enforcing robust password policies, ensuring separation of duties, deploying an intrusion detection system (IDS), maintaining legacy systems regularly, utilising encryption, and introducing a comprehensive password management system.

To close compliance gaps, Botium Toys must adopt measures such as least privilege access, separation of duties, and encryption. Additionally, the company should categorise its assets accurately to determine any further controls required to enhance security and protect sensitive information more effectively.







