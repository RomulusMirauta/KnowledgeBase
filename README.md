# KnowledgeBase


# Table of Contents
I. Windows / basic
Batch
PowerShell
Others / specialized


## Nested Virtual Machines using Hyper-V

### Links
- https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/
- 

Note: Hyper-V is Microsoft's native hypervisor.

Steps to create Nested VMs
1. enable CPU virtualization in system's BIOS
2. go to Windows Features - enable Hyper-V related features *(on host)*
3. restart the system as promted
4. open Hyper-V, create desired VM
5. boot and connect to VM
6. go to Windows Features - enable Hyper-V related features *(on guest VM)*
7. shutdown guest VM
8. On Host:
- Get the name of the recently created VM - using PowerShell
`get-vm`
- Expose Virtualization Extensions from Host to guest VM
`Set-VMProcessor -VMName "<VMName>" -ExposeVirtualizationExtensions $true`
9. Boot and connect to VM
10. Open Hyper-V, create desired VM
11. Boot and connect to nested VM

*If you encounter errors at booting-up the nested VM, here is the workaround:
- Set Hypervisor Launch Type to auto - using Command Prompt
`bcdedit /set hypervisorlaunchtype auto`

Note: Workflow tested with W11 in W11 in W11
