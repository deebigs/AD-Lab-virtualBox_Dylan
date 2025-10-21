# AD-Lab-virtualBox_Dylan
A homelab using Oracle VirtualBox &amp; Windows Server 2019 to simulate a corporate environment with over 1000 users to practice my technical skills in IT to prepare for my transfer to SDSU and to practice professional IT workflows. 

📂 Active Directory Infrastructure & Automation Lab

Project Overview:
This project demonstrates proficiency in fundamental enterprise IT infrastructure setup, system administration, and automation. I independently designed and deployed a secure, fully functional Active Directory domain within a virtual environment (Oracle VirtualBox), focusing on core Identity and Access Management (IAM) and network services.

The primary achievement of this project is to practice & get familiar with Windows Server 2019, Active Directory, & Powershell to further my technical skil & grow my aptitude for growing my career in Information Technology.

🛠️ Technology Stack

Operating System: Windows Server 2019 (Domain Controller)

Virtualization: Oracle VirtualBox

Core Services: Active Directory Domain Services (AD DS)

Automation: PowerShell Scripting

Networking: DHCP, DNS, NAT Routing (RRAS)

Client OS: Windows 11

🔑 Key Deliverables & Impact:

-Domain Controller Setup
    -Infrastructure Development : Established the foundation for centralized security and policy management.

-Bulk User Provisioning
     -PowerShell Automation : Developed a script to create over 1,000 user accounts and required OUs, reducing manual configuration time by 98%.

-Network Configuration
      -Network Administration (Tier 1) : Configured DHCP, DNS, and NAT routing to ensure network segmentation and secure, controlled client-to-internet access.

-System Validation
       -End-to-End Troubleshooting : Successfully joined a Windows 11 client to the domain and validated end-user authentication and access policies.

🚀 How to Run the Script (caution to only do as homelab)
1) Open PowerShell IDE
2) Type, set-ExecutionPolicy Unrestricted
3) Enter
4) Type, cd c:\users\username_of_domain_controller\location_where_you_put_scriptZipFile\Ad_Ps-master
5) Enter
6) Type, LS
   



📄 Documentation and Artifacts

For detailed steps on the initial Domain Controller, DHCP, DNS, and NAT routing configuration, please refer to the following files:

/Scripts/New-BulkUsers.ps1: The complete PowerShell code for bulk user creation.

/Documentation/DC_Setup_Notes.txt: Step-by-step administrative notes on DC installation and service configuration.

Project completed by [Your Name] for foundational IT infrastructure experience.
