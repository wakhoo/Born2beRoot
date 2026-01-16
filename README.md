## Born2beroot — System Administration & Server Configuration Project

Born2beroot is a system administration project focused on learning the fundamentals of Linux server configuration, security hardening, and virtualization.
The goal is to install, configure, and secure a virtual machine from scratch, following strict requirements that mimic real-world DevOps and SysAdmin practices.

Note:
This project does not include source code, as all work is done through virtual machine setup, system configuration, and shell commands rather than programming files.

⸻

### 🏗️ Project Overview

The project consists of installing a minimal Linux distribution (typically Debian), configuring essential system services, enforcing security rules, and documenting everything in a mandatory report.

I learned how to:
	•	Install and manage a Linux server in a constrained environment
	•	Harden system security following strict rules
	•	Configure users, groups, password policies
	•	Understand UFW or FirewallD
	•	Set up and monitor system services
	•	Manage partitions and file system permissions
	•	Use AppArmor or another mandatory access control (MAC) system
	•	Understand virtualization through VirtualBox or another hypervisor
	•	Create automated monitoring using shell scripting

⸻

### 🔐 Key Features & Requirements

1. Virtual Machine Setup
	•	Install a fresh Debian (stable) OS
	•	Use LVM (Logical Volume Manager) during installation
	•	Configure partitions following required structure

2. User & Group Management
	•	Create a non-root user with sudo privileges
	•	Configure custom groups
	•	Restrict root login
	•	Enforce strong password policies (complexity, expiration, attempts lockout)

3. Security Hardening
	•	Install and configure sudo with proper logging
	•	Enable and configure UFW
	•	Setup secure SSH configuration
	•	Custom port
	•	No root login
	•	Key-based authentication recommended

4. System Monitoring Script

You must create a shell script that outputs real-time system information such as:
	•	CPU load
	•	RAM usage
	•	Disk usage
	•	LVM status
	•	Active processes
	•	Number of user logins
	•	Network information

This script is executed via a cron job every 10 minutes.

5. Mandatory Access Control
	•	Install AppArmor
	•	Ensure profiles are loaded and enforced
	•	Validate AppArmor status on the VM

6. Validation of System Integrity
	•	Check proper permissions
	•	Verify sudo behavior
	•	Test firewall rules
	•	Confirm SSH access works securely
	•	Validate partition & LVM configuration

⸻

### 🚀 Skills & Concepts Learned
	•	Linux system administration
	•	Virtualization fundamentals
	•	Security hardening & best practices
	•	User, group & privilege management
	•	Firewall configuration
	•	LVM partitioning
	•	Shell scripting
	•	Server monitoring
	•	Understanding MAC systems like AppArmor

⸻

### 📦 Technologies Used

Debian, VirtualBox, UFW, LVM, AppArmor, sudo, cron, bash, SSH

⸻

### 📚 Project Summary

Born2beroot builds the foundation of DevOps and SysAdmin skills, teaching how to deploy and secure a Linux system from the ground up.
It’s a fully hands-on project that simulates real server setup and security processes without writing application code.
