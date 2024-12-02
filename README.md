### Small business enterprise

### Table of content
- [1. Plan](#1-plan)
- [2. Before preparation](#2-before-preparation)
- [3. Needed hardware](#3-needed-hardware)
  - [3.1 Virtual infrastructure](#31-virtual-infrastructure)
  - [3.2 Pysical infrastructure](#32-pysical-infrastructure)
- [4. Learning points](#4-learning-points)



## 1. Plan
- The plan is to make a infrastructure for a small business enterprise, with similar functionality with other companies such as ``Stiftelsen Pilar``.



## 2. Before preparation
- The main task is to create the infrastrucutre using only virtual machines (VMs). The reasoning why I want to start with VMs and not pysical machines (PMs) is that VMs are way safer in the way that if something goes sideways, I can just rollback to my last *"checkpoint"* and VMs are supposed to also be better for the goal achievement *(måloppnåelsen)*. On pysical machines its way harder to revert back befor I did the change, sometimes its not even possible to revert back from a big change.



## 3. Needed hardware
The infrastructure will be containing:
-  ``1 Firewall`` 
-  ``2 Servers``
-  ``Minimum 1 Client PC``*(extras if I have time)*.  

### 3.1 Virtual infrastructure
Main objective is making the virtual infrastructure
- ``1 Firwall`` with ``OPENsense``
- ``2 Servers`` with ``Windows Server 2022``. 
  - **SRV-01**: ``Primary server``, ``AD DS``, ``DNS`` & ``DHCP``
  - **SRV-02**:``Secondary server (backup server)``, ``AD DS`` & ``DNS``
- **Minimum 1 Client PC**
  - **ClientPC-01**: ``Windows 11``
  - **ClientPC-02**: ``Linux Ubuntu``
  - **ClientPC-03**: ``Windows 10``
  - **ClientPC-04**: ``macOS`` 

### 3.2 Pysical infrastructure
After making the virtual infrastrucutre I will be creating the exact same infrastrucutre just pysically **IF I HAVE TIME**. For extra safety measures I will be doing every big change on the VMs so I dont mess anything up on the pysical machines.
- ``1 Firwall`` with ``OPENsense``. **This will be a VM.**
- ``2 Servers`` with ``Windows Server 2022``. 
  - **SRV-01**: ``Primary server``, ``AD DS``, ``DNS`` & ``DHCP``
  - **SRV-02**:``Secondary server (backup server)``, ``AD DS`` & ``DNS``
- **Minimum 1 Client PC**
  - **ClientPC-01**: ``Windows 11``
  - **ClientPC-02**: ``Linux Ubuntu``
  - **ClientPC-03**: ``Windows 10``
  - **ClientPC-04**: ``macOS`` 

<img src="IndieCompanyInfrastructure.png" alt="Picture of infrastructure" />



## 4. Learning points
I think I will learn several things from this:
- How to handle memory sticks
  - ``Format Hard Drives``
  - ``Bootable Drives (Using Rufus)``
- How to configure ``Windows Server 2022``
- ``Microsoft Azure``
- Problem solving, how to search the ``web`` for solutions
- Infrastructure planning
- The meaning and functions of ``AD DS``, ``DNS`` & ``DHCP``
- Security measures



