<h1 align="center">
KnowledgeBase
</h1>


<br>


## Table of Contents
I. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MS Windows / Basic](#i-ms-windows--basic) <br>
II. &nbsp;&nbsp;&nbsp;&nbsp;[Google Chrome](#ii-google-chrome) <br>
III. &nbsp;&nbsp;&nbsp;[Scripting - Batch / Shell / Bash / PowerShell](#iii-scripting---batch--shell--bash--powershell) <br>
IV. &nbsp;&nbsp;&nbsp;[Visual Studio Code](#iv-visual-studio-code) <br>
V. &nbsp;&nbsp;&nbsp;&nbsp;[Others / Specialized](#v-others--specialized) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; V. a. &nbsp;[How to automatically remove the empty lines from a file using Notepad++ and RegEx](#v-a-how-to-automatically-remove-the-empty-lines-from-a-file-using-notepad-and-regex) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; V. b. &nbsp;[Nested Virtual Machines using Hyper-V](#v-b-nested-virtual-machines-using-hyper-v) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; V. c. &nbsp;[PowerShell script for creating a Virtual Drive from an ISO Image](#v-c-useful-powershell-script-for-creating-a-virtual-drive-from-an-iso-image-is-available-in-a-separate-file-mount_isops1)


<br>


## I. MS Windows / Basic

- Create **copy** of file/folder <br>
    `Keep CTRL key pressed + left-click + drag `

- Create **shortcut** of file/folder <br>
    `Keep CTRL + SHIFT keys pressed + left-click + drag`

- Paste copied text **without** text formatting <br>
    `CTRL + SHIFT + V`

- Instant reset of graphics card driver <br>
    `Windows Key + CTRL + SHIFT + B`

> [!NOTE]
> - This may fix many display glitches, **without** the need of a **full reboot**. 
> - ***The screen will flicker or go black briefly, and you might hear a beep from the motherboard, indicating the driver has reloaded.***

<br>

## II. Google Chrome

- Hard refresh page <br>
    `SHIFT + F5`

- Closes current tab <br>
    `CTRL + W`

- Closes all tabs inside window <br>
    `CTRL + SHIFT + W`

- Re-opens last closed: tab / window of tabs <br>
    `CTRL + SHIFT + T`

- Chrome Inspect Tool / DevTools - feature: "Select an element in the page to inspect it" <br>
    `CTRL + SHIFT + C`

> [!NOTE]
> - Most if not all of the above-mentioned keyboard shortcuts are also working for:
>     - Chromium-based browsers like: Microsoft Edge, Opera, Brave, Vivaldi, DuckDuckGo, Samsung Internet [Samsung DeX, Link To Windows *(old)*, Phone Link *(new)*], Yandex Browser, Arc
>     - Non-Chromium-based browsers like: Mozilla Firefox, Safari, Waterfox, Pale Moon, Falkon, Ladybird, LibreWolf, Tor Browser

<br>

- Scrollshot (scrolling screenshot) - like on smartphone <br>
    1. Press `F12`
    2. Press key combination `CTRL + SHIFT + P`
    3. Type "screens"
    4. Choose "Capture full size screenshot"
    5. Save the file

> [!NOTE]
> - "Capture full area screenshot" option = Current view <br>
> - ***This feature might not work on every page!***

<br>

## III. Scripting - Batch / Shell / Bash / PowerShell

- If you encounter errors when trying to execute PowerShell commands/scripts on a host/VM, here is the workaround: <br>
    ```ps1
    Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
    ```

> [!NOTE]
> - Sets the Execution Policy to Remotely Signed *(allows to run any scripts created locally, without a digital signature)* for Current Windows User *(currently logged-in user)* <br>
> - Error, e.g. "npm : File C:\Program Files\nodejs\npm.ps1 cannot be loaded because running scripts is disabled on this system. For more information, see..."

<br>

- How to find computer name & logged user <br>
    ```bat
    whoami
    ```

> [!NOTE]
> - Format: ComputerName\LoggedUser <br>
> - E.g.: desktop-gs4a616\romulus

<br>

- Clear screen / clear the terminal <br>
    ```bat
    cls
    ```

- Change working directory - **folder** <br>
    ```bat
    cd
    ```

- Go back to previous directory <br>
    ```bat
    cd ..
    ```


- Go to parent/root directory <br>
    ```bat
    cd /
    ```

- Change directory - changing the working **drive** <br>
*while currently in ' C:\ '* <br>
    ```bat
    cd /d E:\
    ```

- Cancel operation (in-progress OR aborts writing current command) <br>
    `CTRL + C`

- Cycling through previous commands <br>
    `arrow keys (UP / DOWN)`

- Select all text in terminal <br>
    `CTRL + SHIFT + A`

<br>

### Keyboard & Mouse Shortcuts - On Windows <br>

- Select text <br>
    `left-click` <br>

- Copy text <br>
    `Select text + right-click` <br>

- Paste copied text <br>
    `right-click` <br>

<br>


### Useful AHK (AutoHotkey) scripts are available in a separate folder: [AHK](https://github.com/RomulusMirauta/Windows-Scripts/tree/main/AHK)

<br>

### Useful BATCH scripts are available in a separate folder: [BATCH](https://github.com/RomulusMirauta/Windows-Scripts/tree/main/BATCH)

<br>

### Useful Shell commands for GIT BASH are available in a separate file: [GIT_COMMANDS.sh](https://github.com/RomulusMirauta/Windows-Scripts/blob/main/GIT/GIT_COMMANDS.sh)

<br>

### Scripting Languages Comparison Table is available in a separate file: [README-ADD.md](./README-ADD.md)


<br>

## IV. Visual Studio Code

- Search for keyword inside current file <br>
    `CTRL + F`

- Search for keyword in projects folders <br>
    `CTRL + SHIFT + F`

- Beautify Code <br>
    `ALT + SHIFT + F`

- Trigger the auto-complete pop-up menu <br>
    `CTRL + SPACE`

- Edit variable with same name that has multiple occurrences in the code
    1. double-click the variable name
    2. `CTRL + D`
    3. edit the variable name - all occurrences will be changed simultaneously

- Open terminal <br>
    `CTRL +`*`<grave apostrophe/backtick character>`* **( ` )**

- Open new terminal  <br>
    `CTRL + SHIFT +`*`<grave apostrophe/backtick character>`* **( ` )**


- Reload all windows that are currently open, **without restarting** VS Code
    1. Press key combination `CTRL + SHIFT + P`
    2. Type "Reload Window"
    3. Press `ENTER`

> [!NOTE]
> - Useful when having visual glitches/errors, e.g.: "Error loading webview: Error: Could not register service worker: InvalidStateError: Failed to register a ServiceWorker: The document is in an invalid state."
> - This may happen after installing/updating extensions, or after updating VS Code itself. <br>


<br>


## V. Others / Specialized

### V. a. How to automatically remove the empty lines from a file using Notepad++ and RegEx
1. Open the file in Notepad++
2. Open 'Replace' sub-window by pressing `CTRL + H`
3. Type in 'Find what' field: `^\s*\R`
4. Make sure that 'Replace with' field is ***empty***
5. Change 'Search Mode' to 'Regular expression'
6. Click on 'Replace All'

> [!NOTE]
> - RegEx = Regular Expression(s)
> - Tested this on several files containing lists of keywords. <br>

<br>

### V. b. Nested Virtual Machines using Hyper-V

#### Links
- https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/
- 

#### Steps to create Nested VMs
1. enable CPU virtualization in system's BIOS
2. go to Windows Features - enable Hyper-V related features *(on host)*
3. restart the system as promted
4. open Hyper-V, create desired VM
5. boot and connect to VM
6. go to Windows Features - enable Hyper-V related features *(on guest VM)*
7. shutdown guest VM
8. On Host:
    - Get the name of the recently created VM - using PowerShell <br>
    ```ps1
    get-vm
    ```

    - Expose Virtualization Extensions from Host to guest VM <br>
    ```ps1
    Set-VMProcessor -VMName "<VMName>" -ExposeVirtualizationExtensions $true
    ```
9. Boot and connect to VM
10. Open Hyper-V, create desired VM
11. Boot and connect to nested VM

<br>

> [!IMPORTANT]
> - If you encounter errors when trying to execute PowerShell commands/scripts on host/guest VM, [**HERE**](#iii-scripting---batch--shell--bash--powershell) is the **tested** solution. <br>
> - If you encounter errors at booting-up the **nested VM**, here is the solution: <br>
>     - Set Hypervisor Launch Type to auto - using Command Prompt/PowerShell, on the **guest VM** <br>
>         ```bat
>         bcdedit /set hypervisorlaunchtype auto
>         ```

<br>

> [!NOTE]
> - Explaining utilized terms:
>    - Host (Machine) = The actual physical computer, which components will be shared/virtualized
>    - VM = Virtual Machine
>    - Guest VM = VM running on Host
>    - Nested VM = VM running on Guest VM
>    - Hyper-V = Microsoft's native hypervisor
> - Tested the above workflow with W11 in W11 in W11.

<br>

### V. c. Useful PowerShell script for creating a Virtual Drive from an ISO Image is available in a separate repo: [Mount_ISO.ps1](https://github.com/RomulusMirauta/Windows-Scripts#i-powershell---mounting-and-dismounting-an-iso-image)
