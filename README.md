Active Directory Home Lab Setup (Windows Server 2022)

This repository contains documentation and setup instructions for building a local Active Directory (AD) Domain Controller home lab using Oracle VM VirtualBox and Windows Server 2022 Evaluation.

This lab demonstrates essential IT administration skills, including VM provisioning, static IP configuration, Active Directory Domain Services (AD DS) installation, forest domain promotion, and Organizational Unit (OU) structure creation.

📋 Overview & Prerequisites

Prerequisites

 Host OS: Windows, macOS, or Linux

 Hypervisor: Oracle VM VirtualBox (v7.0+)

 ISO Image: Windows Server 2022 Evaluation ISO (64-bit)

 Minimum System Requirements:

 8 GB RAM (allocated to VM)

 4 CPU Cores

 80 GB free disk space

🛠️ Step-by-Step Lab Implementation

1 Virtual Machine Provisioning 
configure hardware and ISO settings in VirtualBox

2 Windows Server 2022 Installation
Deploy the base OS via GUI
desktop experience

3 Host Customization & Network
Configuration
Assign hostname and static IP address
A. Computer Renaming
B. Static IP Configuration

4 AD DS Installation & Domain Promotion
Install AD DS role and configure the root domain forest

5  Active Directory Verification &
Management Setup
Log in with domain credentials and create basic organizational structure

🎯 Verification Checklist

 [x] VM booted and running Windows Server 2022 Desktop Experience.

 [x] Host name modified and static IP address assigned.

 [x] AD DS and DNS roles installed without errors.

 [x] Root Forest successfully promoted (⁠.local⁠ domain).

 [x] Active Directory Administrative Center & Users/Computers tools fully operational.

 [x] Organizational Unit structure created.

