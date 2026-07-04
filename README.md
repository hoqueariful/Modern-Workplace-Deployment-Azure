
# 🏢 Modern Workplace Deployment for Contoso Design Ltd

### Microsoft Azure • Microsoft Entra ID • Azure Administration • Identity Management • Role Based Access Control

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Entra
ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![AZ-104](https://img.shields.io/badge/AZ--104-Certified-success?style=for-the-badge)
![SC-300](https://img.shields.io/badge/SC--300-Certified-success?style=for-the-badge)
![MD-102](https://img.shields.io/badge/MD--102-Certified-success?style=for-the-badge)

*A consulting style Microsoft Azure infrastructure deployment
demonstrating identity management, Azure administration and cloud
governance.*
:::

------------------------------------------------------------------------

# 📑 Table of Contents

-   Executive Summary
-   Business Scenario
-   Business Challenges
-   Project Objectives
-   Solution Overview
-   Azure Architecture
-   Identity and Access Management
-   Governance
-   Security Implementation
-   Technologies Used
-   Repository Structure
-   Business Outcomes
-   Key Skills Demonstrated
-   Lessons Learned
-   Author
-   Future Improvements

------------------------------------------------------------------------

# 🎯 Executive Summary

## Business Challenge

Contoso Design Ltd is a growing interior design business with 25
employees, including eight members of staff working remotely. The
company relied on shared passwords, manually managed user accounts and
inconsistent IT administration. Azure resources lacked structure, user
permissions were not centrally controlled and there was no technical
documentation to support future growth.

## Solution

I designed and deployed a secure Microsoft Azure environment centred on
Microsoft Entra ID and Azure Infrastructure Services. The solution
introduced centralised identity management, departmental security
groups, Role Based Access Control (RBAC), a structured Azure resource
hierarchy, secure networking, cloud storage and administrative
documentation.

## Business Outcome

The organisation now has a structured cloud environment that is easier
to manage, more secure and ready to support future business growth.
Administrative effort has been reduced through centralised user
management, while consistent governance provides a stronger operational
foundation.

------------------------------------------------------------------------

# 🏢 Business Scenario

  Item                 Details
  -------------------- --------------------
  **Client**           Contoso Design Ltd
  **Industry**         Interior Design
  **Employees**        25
  **Office**           1
  **Remote Workers**   8

The business required a practical Microsoft Azure solution that would
improve identity management, strengthen security and introduce
consistent administrative processes without unnecessary complexity.

------------------------------------------------------------------------

# ⚠️ Business Challenges

-   Shared passwords between employees.
-   No central identity management.
-   User accounts managed manually.
-   New computers configured individually.
-   Former employees could retain access.
-   Azure resources were poorly organised.
-   No documentation existed for future administrators.

------------------------------------------------------------------------

# ☁️ Solution Overview

-   Microsoft Entra ID
-   Azure Resource Group
-   Virtual Network
-   Network Security Group
-   Windows Virtual Machine
-   Azure Storage Account
-   Resource Tags
-   Role Based Access Control

------------------------------------------------------------------------

## 🏗 Azure Architecture

<p align="center">
  <img src="./Diagrams/01_Architecture_Diagram.png" alt="Architecture Diagram" width="100%">
</p>

---

## ☁ Azure Resource Visualizer

<p align="center">
  <img src="./Diagrams/02_Azure_Resource_Visualizer.png" alt="Azure Resource Visualizer" width="100%">
</p>

------------------------------------------------------------------------

# 🛡 Governance

## Naming Convention

-   rg-contoso-prod
-   VNET-Contoso
-   NSG-Contoso
-   SRV-ADMIN01
-   stcdltd2026

## 🏷️ Resource Tags

<p align="center">
<img src="./Screenshots/09_Resource_Tags.PNG" width="95%">
</p>

<p align="center">
<i>Figure 09. Standardised Azure resource tags applied to improve governance and resource management.</i>
</p>

------------------------------------------------------------------------

# 💻 Technologies Used

  Technology               Purpose
  ------------------------ -----------------------
  Microsoft Azure          Cloud Infrastructure
  Microsoft Entra ID       Identity Management
  Azure Virtual Machines   Administrative Server
  Azure Virtual Network    Secure Networking
  Azure Storage Account    Cloud Storage
  Network Security Group   Network Protection
  Azure RBAC               Access Management

------------------------------------------------------------------------
## 📂 Repository Structure

```text
modern workplace deployment azure/
│
├── README.md
├── template.json
│
├── Documentation/
│   ├── Business_Requirements.pdf
│   └── Project_Report.pdf
│
├── Diagrams/
│   ├── 01_Architecture_Diagram.png
│   ├── 02_Azure_Resource_Visualizer.png
│   └── 03_Export_Template.png
│
└── Screenshots/
    ├── 01_Business_Requirements.png
    ├── 02_Virtual_Network.png
    ├── 03_Network_Security_Group.png
    ├── 04_Storage_Account.png
    ├── 05_Virtual_Machine.png
    ├── 06_Security_Groups.png
    ├── 07_Users.png
    ├── 08_Group_Membership.png
    ├── 09_Resource_Tags.png
    ├── 10_Storage_Containers.png
    └── 11_RBAC_Role_Assignments.png

```

------------------------------------------------------------------------

# 📈 Business Outcomes

-   Centralised identity management.
-   Standardised Azure administration.
-   Improved security through controlled permissions.
-   Better resource organisation.
-   Clear technical documentation.
-   Scalable cloud foundation for future services.

------------------------------------------------------------------------

# 🧰 Key Skills Demonstrated

-   Microsoft Entra ID Administration
-   Azure Infrastructure Deployment
-   Azure Resource Management
-   Identity and Access Management
-   Azure Networking
-   Role Based Access Control
-   Cloud Governance
-   Technical Documentation

## 🏗 Export Template

<p align="center">
  <img src="./Diagrams/03_Export Template.PNG" alt="Export Template" width="100%">
</p>


- Exported the Azure Resource Manager template of the deployed environment and included it in the repository as infrastructure evidence, confirming resource types, dependencies, and configuration state at time of export.

------------------------------------------------------------------------

# 📖 Lessons Learned

This project reinforced the importance of designing technical solutions
around business requirements rather than individual technologies. Clear
governance and documentation make Azure environments easier to support
and maintain.

------------------------------------------------------------------------

# 👨‍💻 Author

**Md Ariful Hoque**

-   MSc Cyber Security and Forensic IT
-   Microsoft Certified: Azure Administrator Associate (AZ-104)
-   Microsoft Certified: Identity and Access Administrator Associate
    (SC-300)
-   Microsoft Certified: Endpoint Administrator Associate (MD-102)
-   CompTIA Security+

------------------------------------------------------------------------

# 🚀 Future Improvements

-   Microsoft Intune
-   Conditional Access
-   Multi Factor Authentication
-   Microsoft Defender for Cloud
-   Azure Backup
-   Azure Monitor
-   Azure Policy
-   Microsoft Sentinel
