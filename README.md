Introduction
A new company, MYBIG Capital, is starting up with 50 users. MYBIG is looking to build a cloud-native Entra environment with Azure Virtual Desktop for user workstations and multiple server VM’s in Azure Cloud. MYBIG would like to automate creating servers in the Azure cloud with definable properties, such as instance type, CPU, RAM, network, etc.
Project
You are an infrastructure engineer at MYBIG Capital. Please design an AVD and Azure VM environment with all necessary configurations. Please also create automation scripts that will do the following:

Server:
Create Azure Server VM with a definable series (A-Series, Bs-Series, etc.)
Configure proper parameters for the server (resource group, networking, region, etc.)
Configure access permissions for specific teams
Create cross server access
Workstation
Create a remote desktop for a single or multiple users in AVD with definable parameters
Configure proper networking for the desktop
Configure additional NIC for the desktop
Perform troubleshooting tasks against an AVD VM, such as reboot
Management
Create a process that automates adding Win32 apps to the Intune App portal
Design a method for auto updating Intune-deployed apps on Windows workstations either via workstation-based or Intune based updates (assuming the apps do not auto-update)
Create automated reports that indicate that apps were successfully updated on the workstations
