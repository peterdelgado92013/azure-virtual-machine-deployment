# Azure Virtual Machine (VM – Virtual Machine) Deployment

## Overview
This project demonstrates how to deploy, secure, and access a Linux-based Azure Virtual Machine (VM – Virtual Machine) using Microsoft Azure.  
The goal was to build a basic but secure cloud environment following best practices for networking, access control, and cost management.

---

## Problem Statement
Organizations need scalable and secure computing resources without purchasing physical hardware.  
This project shows how a Cloud Engineer can create a Virtual Machine in the cloud, restrict access, verify connectivity, and manage cost effectively.

---

## Architecture Overview
- Resource Group (RG – Resource Group)
- Virtual Network (VNet – Virtual Network)
- Network Security Group (NSG – Network Security Group)
- Virtual Machine (VM – Virtual Machine)
- Secure Shell (SSH – Secure Shell) access

---

## Tools & Technologies Used
- Microsoft Azure Portal
- Azure Virtual Machines
- Azure Virtual Network
- Azure Network Security Group
- Ubuntu Linux
- Secure Shell (SSH)

---

## Steps Performed

### 1. Resource Group Creation
- Created a Resource Group to logically organize all Azure resources for this project.

### 2. Virtual Network Setup
- Created a Virtual Network to provide network connectivity for the Virtual Machine.

### 3. Network Security Group Configuration
- Created a Network Security Group to control inbound traffic.
- Allowed Secure Shell (SSH) access on port 22 from my IP address only.

### 4. Virtual Machine Deployment
- Deployed an Ubuntu Linux Virtual Machine.
- Selected a small VM size to minimize cost.
- Attached the VM to the Virtual Network and Network Security Group.

### 5. Secure Shell (SSH) Access
- Connected to the Virtual Machine using Secure Shell (SSH).
- Verified successful access by logging into the system.

### 6. System Verification
- Verified the host name of the Virtual Machine.
- Confirmed the private IP address using Linux networking commands.

### 7. Cost Management
- Stopped (deallocated) the Virtual Machine after testing to prevent unnecessary charges.

---

## Screenshots
Screenshots documenting each step of the deployment and verification process are included in this repository:
- Resource Group overview
- Virtual Network overview
- Network Security Group inbound rules
- Virtual Machine deployment status
- Secure Shell (SSH) connection
- Host name and IP address verification
- Virtual Machine stopped state

---

## Security Considerations
- Restricted Secure Shell (SSH) access to my IP address only.
- Used Network Security Group rules to limit inbound traffic.
- Followed least-privilege principles.

---

## What I Learned
- How to deploy and manage an Azure Virtual Machine.
- How cloud networking and security controls work together.
- How to securely connect to a Linux system using Secure Shell (SSH).
- The importance of shutting down resources to manage cloud costs.

---

## Future Improvements
- Add Azure Bastion for browser-based secure access.
- Automate deployment using Infrastructure as Code (Terraform or ARM templates).
- Add monitoring and alerting using Azure Monitor.

---

## 🎥 Video Walkthrough
A full walkthrough video of this project will be added soon.
