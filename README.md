# KnowledgeBase


# Table of Contents
I. Windows / basic
II. Google Chrome
III. Batch
IV. PowerShell
V. Visual Studio Code
VI. Others / specialized


<br>


I. Windows / basic

Create **copy** of file/folder <br>
`CTRL + drag `

<br>

Create **shortcut** of file/folder <br>
`CTRL + SHIFT + drag`

<br>

Instant reset of graphics card driver <br>
`Windows Key + Ctrl + Shift + B`

> This may fix many display glitches, **without** the need of a **full reboot**. 
> The screen will flicker or go black briefly, and you might hear a beep, indicating the driver has reloaded.


II. Google Chrome

Hard refresh <br>
`SHIFT + F5`

<br>

Scrollshot (Scrolling screenshot) - like on smartphone <br>
1. F12
2. `CTRL + SHIFT + P`
3. Type "screens"
4. Choose "Capture full size screenshot"

>Notes: <br>
>- "Capture full area screenshot" = Current view <br>
>- This feature does not work on any page!




III. Batch

How to find computer name & logged user <br>
`whoami`

> Format: ComputerName\LoggedUser
> E.g.: desktop-gs4a616\romulus
> Also works in PowerShell


IV. PowerShell

*If you encounter errors when trying to execute PowerShell commands/scripts on a host/VM, here is the workaround: <br>
`Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`

> Sets the Execution Policy to Remotely Signed *(allows to run any scripts created locally, without a digital signature)* for Current Windows User *(currently logged-in user)* <br>
> Error, e.g. "npm : File C:\Program Files\nodejs\npm.ps1 cannot be loaded because running scripts is disabled on this system. For more information, see..."

<br>


PowerShell - Keyboard & Mouse Shortcuts <br>

Select text <br>
`left-click` <br>

Copy text <br>
`Select text + right-click` <br>

Paste copied text <br>
`right-click` <br>


<br>

*Bash / Shell / PowerShell

cls clear screen, clear the terminal

cd change directory
cd .. previous directory
cd / go to root directoty
CTRL + C - cancel operation (in-progress OR aborts writing current command)
arrows - cycling previous commands

select text - left click
copy text - right click
paste copied text - right click

Select all text in terminal
`CTRL + SHIFT + A`


Change Directory - Changing the working drive
while currently in C:\
cd /d D:\







V. Visual Studio Code

Alt + Shift + F => Beautify Code
Ctrl + F => search for keyword inside current file
Ctrl + Shift + F => search for keyword in projects folders

Edit same variable name in multiple occurrences
double-click the variable name
CTRL + D
edit it

Open terminal CTRL + `
Open new terminal CTRL + SHIFT + `


Trigger the auto-complete pop-up menu
`CTRL + SPACE`








## VI. Others / specialized

### How to automatically remove the empty lines from a file using Notepad++ and RegEx (Regular Expressions)
1. Open the file in Notepad++
2. Open 'Replace' sub-window by pressing `CTRL + H`
3. Type in 'Find what' field: `^\s*\R`
4. Make sure that 'Replace with' field is ***empty***
5. Change 'Search Mode' to 'Regular expression'
6. Click on 'Replace All'

> Tested this on several files containing lists of keywords.


### Nested Virtual Machines using Hyper-V

#### Links
- https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/
- 

<br>

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
- Get the name of the recently created VM - using PowerShell <br>
`get-vm`
- Expose Virtualization Extensions from Host to guest VM <br>
`Set-VMProcessor -VMName "<VMName>" -ExposeVirtualizationExtensions $true`
9. Boot and connect to VM
10. Open Hyper-V, create desired VM
11. Boot and connect to nested VM

<br>

*If you encounter errors when trying to execute PowerShell commands/scripts on host/VM, here is the workaround: <br>
- Set Execution Policy to Remotely Signed *(allows to run any scripts created locally, without a digital signature)* for Current Windows User *(currently logged-in user)* - using PowerShell <br>
`Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`

<br>

**If you encounter errors at booting-up the nested VM, here is the workaround:
- Set Hypervisor Launch Type to auto - using Command Prompt <br>
`bcdedit /set hypervisorlaunchtype auto`

Note: Workflow tested with W11 in W11 in W11
