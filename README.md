<div align="center">
    <h1>
        KnowledgeBase
    </h1>
    <p>
        <em> 
            A collection of Keyboard Shortcuts, Scripts, Tips & Tricks useful for automating common & repetitive tasks.
        </em>
    </p>
</div>


<br><br>


## Table of Contents
I. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft Windows 10 / 11](#i-microsoft-windows-10--11) <br>
II. &nbsp;&nbsp;&nbsp;&nbsp;[Client Browsers](#ii-browsers) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; II. a. &nbsp;[Google Chrome](#ii-a-google-chrome) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; II. b. &nbsp;[Microsoft Edge](#ii-b-microsoft-edge---specific-features) <br>
III. &nbsp;&nbsp;&nbsp;[Scripting - Batch / Shell / Bash / PowerShell / AHK](#iii-scripting---batch--shell--bash--powershell--ahk) <br>
IV. &nbsp;&nbsp;&nbsp;[Visual Studio Code](#iv-visual-studio-code) <br>
V. &nbsp;&nbsp;&nbsp;&nbsp;[Others / Specialized](#v-others--specialized) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; V. a. &nbsp;[How to automatically remove the empty lines from a text - using Notepad++ and RegEx](#v-a-how-to-automatically-remove-the-empty-lines-from-a-text---using-notepad-and-regex) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; V. b. &nbsp;[Nested Virtual Machines - using Hyper-V](#v-b-nested-virtual-machines---using-hyper-v) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; V. c. &nbsp;[Script for creating a Virtual Drive from an ISO Image - using PowerShell](#v-c-powershell-script-for-creating-a-virtual-drive-from-an-iso-image-is-available-in-a-separate-repo-mount_isops1) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; V. d. &nbsp;[Script for converting video files to GIFs for GitHub REPOs DEMOs - using PowerShell](#v-d-powershell-script-for-converting-video-files-eg-mkv--matroska-video-format-to-a-gif-graphics-interchange-format-is-available-in-a-separate-repo-ffmpegscriptconversionvideotogifps1)


<br><br>


## I. Microsoft Windows 10 / 11

### Links:
- https://support.microsoft.com/en-us/windows/keyboard-shortcuts-in-windows-dcc61a57-8ff0-cffe-9796-cb9706c75eec
- https://www.w3schools.com/tags/ref_keyboardshortcuts.asp

<br>

- Rename file/folder <br>
    `F2`

- Go back / up one folder <br>
    `BACKSPACE` (←)

- Create **copy** of file/folder <br>
    `Keep CTRL key pressed + left-click + drag`

- **Move** file/folder <br>
    `Keep SHIFT key pressed + left-click + drag`

- Create **shortcut** of file/folder <br>
    `Keep CTRL + SHIFT keys pressed + left-click + drag`

- Show clipboard history <br>
    `Windows Key + V`

- Paste copied text **without** text formatting (plain text) <br>
    `CTRL + SHIFT + V`

- Change sound output device <br>
    `CTRL + Windows Key + V`

- Open Run Dialog <br>
    `Windows Key + R`

- Open Windows Settings <br>
    `Windows Key + I`

- Show Emoji Panel <br>
    `Windows Key + .` *(period/dot)* <br>
    ***OR*** <br>
    `Windows Key + ;` *(semicolon)*

- Show Desktop <br>
    `Windows Key + D`

- Peek at Desktop (show Desktop temporarily while key is pressed) <br>
    `Windows Key + ,` *(comma)*

- Open Task Manager <br>
    `CTRL + SHIFT + ESC` <br>
    ***OR*** <br>
    `CTRL + ALT + DELETE` and choose "Task Manager" <br>
    ***OR*** <br>
    right-click on Taskbar and choose "Task Manager" <br>

- Create new folder <br>
    `CTRL + SHIFT + N`

- Close current app window <br>
    `CTRL + W`

- Close current app <br>
    `ALT + F4`

- Open Snipping Tool *(W11 built-in multi-tool: screenshots, color picker, text extractor)* <br>
    `Windows Key + SHIFT + S`

- Open Text Extractor Tool *(W11 built-in multi-tool)* <br>
    `Windows Key + SHIFT + T`

- Create new virtual desktop <br>
    `Windows Key + CTRL + D`

- Switch between virtual desktops <br>
    `Windows Key + CTRL + LEFT / RIGHT Arrow`

- Close current virtual desktop <br>
    `Windows Key + CTRL + F4`

- Move Window to Next Desktop <br>
    `Windows Key + Ctrl + Shift + Right Arrow`

- Move Window to Previous Desktop <br>
    `Windows Key + Ctrl + Shift + Left Arrow`

- Switch between open apps - only on current Desktop <br>
    `ALT + TAB` <br>
    *(shown on the main display; keep ALT pressed, and press TAB repeatedly to cycle through open apps)*

- Switch between open apps - on all Desktops **&** Switch between Virtual Desktops <br>
    `Windows Key + TAB` <br>
    *(shown on all displays, depending on what display the app is currently active; it also shows all currently open Virtual Desktops)*

- Switch between open windows of the same app <br>
    `CTRL + TAB` <br>
    *(keep CTRL pressed and press TAB repeatedly to cycle through open windows of the same app)*

- Switch backwards between open windows of the same app <br>
    `CTRL + SHIFT + TAB` <br>
    *(keep CTRL and SHIFT pressed and press TAB repeatedly to cycle backwards through open windows of the same app)*

> [!NOTE]
> - These work with apps like: Windows/File Explorer, Google Chrome and other browsers, Visual Studio Code, Notepad++, Adobe Acrobat Reader DC, Command Prompt, PowerShell etc. <br>

<br>

- Instant reset of graphics card driver <br>
    `Windows Key + CTRL + SHIFT + B`

> [!NOTE]
> - This may fix many display glitches, **without** the need of a **full reboot**. 
> - ***The screen will flicker or go black briefly, and you might hear a beep from the motherboard, indicating the driver has reloaded.***

<br>

- C:\Users\<username> <br>
    `%USERPROFILE%`

- C:\Users\<username>\Documents *(for current user)* <br>
    `%USERPROFILE%\Documents`

- C:\Users\<username>\AppData\ <br>
    `%APPDATA%`

- C:\Users\<username>\AppData\Local <br>
    `%LOCALAPPDATA%`

- C:\Users\<username>\AppData\Local\Temp <br>
    `%TEMP%` or `%TMP%`


- C:\Program Files <br>
    `%ProgramFiles%`

- C:\Program Files (x86) <br>
    `%ProgramFiles(x86)%`


- C:\Windows <br>
    `%SystemRoot%` or `%WINDIR%`

- C: (or the drive letter where the operating system is installed) <br>
    `%SystemDrive%`


> [!NOTE]
> These are Windows environment variable - that act as a shortcut. <br>
> They can be used in:
> - Windows Explorer
> - Run Dialog
> - CLIs - like Command Prompt and PowerShell
> - Task Scheduler
> - Search Bar
> - Desktop Shortcuts
> - Regedit (Windows Registry Editor)
> - Application Settings
> - Scripts

<br>

- Windows System Tools: Regedit (Windows Registry Editor), Task Scheduler, MSConfig (System Configuration), Computer Management, Task Manager, Command Prompt, PowerShell, Windows Features, dxdiag, Windows Sandbox

<br>

### Useful Chrome Browser Extensions are listed in a separate [REPO](https://github.com/RomulusMirauta/Useful_Tools_and_Extensions?tab=readme-ov-file#ii-useful-google-chrome-extensions)

<br>

## II. Browsers

### II. a. Google Chrome+

#### Links:
- https://developer.chrome.com/docs/devtools/shortcuts
- https://support.microsoft.com/en-us/microsoft-edge/keyboard-shortcuts-in-microsoft-edge-50d3edab-30d9-c7e4-21ce-37fe2713cfad
- https://support.mozilla.org/en-US/kb/keyboard-shortcuts-perform-firefox-tasks-quickly
- https://help.opera.com/en/latest/shortcuts/
- https://support.apple.com/guide/safari/keyboard-and-other-shortcuts-cpsh003/mac

<br>

- Hard refresh/reload page <br>
    `SHIFT + F5`

- Close current tab <br>
    `CTRL + W`

- Close all tabs inside window <br>
    `CTRL + SHIFT + W`

- Re-open last closed: tab / window of tabs <br>
    `CTRL + SHIFT + T`

- Open a new tab <br>
    `CTRL + T`

- Open a new window <br>
    `CTRL + N`

- Focus and empty browser's search/address bar <br>
    `CTRL + E` <br>
    ***OR*** <br>
    `CTRL + K`

- Highlight the entire URL in the address bar (useful for fast copy/paste) <br>
    `CTRL + L`

-  Add "www." and ".com" to a typed term (e.g., typing "google" becomes "www.google.com") <br>
    `CTRL + Enter`


- Search for text in page <br>
    `CTRL + F` <br>
  - Go to the ***next*** match <br>
    `Enter`  <br>
  - Go to the ***previous*** match <br>
    `SHIFT + Enter`  <br>


- Open browser's Task Manager <br>
    *(acts like Windows's Task Manager, showing used resources (CPU, RAM, GPU's VRAM, network etc) per tab - useful for solving performance issues)* <br>
    `SHIFT + ESC`

- Open a new window in Incognito Mode (advantages: no browser extensions, no cookies kept after session end) <br>
    `CTRL + SHIFT + N`

- Search by keyword(s) in all browser tabs (from all browser windows) <br>
    `CTRL + SHIFT + A`

- Show/hide Bookmarks Bar (useful when screen-sharing for interviews or when recording demos) <br>
    `CTRL + SHIFT + B`

- Chrome Inspect Tool / DevTools - Elements Tab - Feature: "Select an element in the page to inspect it" <br>
    `CTRL + SHIFT + C`

- Chrome Inspect Tool / DevTools - Network Tab <br>
    `CTRL + SHIFT + I`

- Chrome Inspect Tool / DevTools - Console <br>
    `CTRL + SHIFT + J`

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

### Useful Tools (SW) are listed in a separate [REPO](https://github.com/RomulusMirauta/Useful_Tools_and_Extensions?tab=readme-ov-file#i-useful-tools-mainly-available-for-windows)


<br>


### II. b. Microsoft Edge - specific features
- Paste and search or Paste and go *(if it's a URL)* = Pastes content from the clipboard into the address bar and executes the search/URL <br>
    `CTRL + SHIFT + L`

<br>

#### JavaScript Bookmarklets are available in a separate [REPO](https://github.com/RomulusMirauta/JavaScript-Bookmarklets#javascript-bookmarklet-repository) <br> *(Bookmarklet = Browser bookmark that executes JavaScript code instead of just opening a webpage)*



<br>



## III. Scripting - Batch / Shell / Bash / PowerShell / AHK

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

### Links:
- https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf
- https://code.visualstudio.com/docs/reference/default-keybindings
- https://code.visualstudio.com/docs/configure/keybindings

<br>

- Search for keyword inside current file <br>
    `CTRL + F`

- Search for keyword in projects folders <br>
    `CTRL + SHIFT + F`

- Toggle Word Wrap *(independently per file)* <br>
    `ALT + Z`

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

### V. a. How to automatically remove the empty lines from a text - using Notepad++ and RegEx
1. Open the file in Notepad++
2. Open 'Replace' sub-window by pressing `CTRL + H`
3. Type in 'Find what' field: `^\s*\R`
4. Make sure that 'Replace with' field is ***empty***
5. Change 'Search Mode' to 'Regular expression'
6. Click on 'Replace All'

> [!NOTE]
> - RegEx = Regular Expression(s)
> - Tested this on several files containing lists of keywords. <br>


<br><br><br>


### V. b. Nested Virtual Machines - using Hyper-V

<br>

#### Links
- https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/
- https://learn.microsoft.com/en-us/windows/security/application-security/application-isolation/windows-sandbox/

<br>

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
> - If you encounter errors when trying to execute PowerShell commands/scripts on host/guest VM, [**HERE**](#iii-scripting---batch--shell--bash--powershell--ahk) is the **tested** solution. <br>
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

<br><br><br>

### V. c. PowerShell script for creating a Virtual Drive from an ISO Image is available in a separate repo: [Mount_ISO.ps1](https://github.com/RomulusMirauta/Windows-Scripts#i-powershell---mounting-and-dismounting-an-iso-image)


<br><br><br>


### V. d. PowerShell script for converting video files (e.g. MKV = Matroska Video format) to a GIF (Graphics Interchange Format) is available in a separate repo: [ffmpegScriptConversionVideoToGif.ps1](https://github.com/RomulusMirauta/Windows-Scripts/blob/main/POWERSHELL/ffmpegScriptConversionVideoToGif.ps1)

<br>

#### Links
- https://obsproject.com/
- https://github.com/FFmpeg/FFmpeg

<br>

#### Steps to follow:
1. Record the video - I recommend:
   - Software = [OBS](https://obsproject.com/)
   - Recording format (output) = Matroska Video (.mkv)
   - Muting / not recording audio *(not needed)*
2. Download the script: [ffmpegScriptConversionVideoToGif.ps1](https://github.com/RomulusMirauta/Windows-Scripts/blob/main/POWERSHELL/ffmpegScriptConversionVideoToGif.ps1)
   - Right-click and choose "Save link as..."
   - ***OR***
   - Click on link and press key combination `CTRL + SHIFT + S`
3. Move/copy the script to OBS output folder *(default = "C:\Users\<username>\Videos\OBS")*
4. Rename desired file to "input" (e.g. full file name: "input.mkv", "input.mp4")
5. Run the script
   - From Windows/File Explorer - right-click and choose "Run with PowerShell"
   - Drom PowerShell CLI
       - `cd` to script's location
       - ```ps1
         powershell -ExecutionPolicy Bypass -File .\ffmpegScriptConversionVideoToGif.ps1
         ```

<br>

> [!NOTE]
> - This workflow is useful for creating DEMOs for GitHub REPOs.
>     - GitHub can display several common image formats, including PNG, JPG, **GIF**, PSD, and SVG
>     - The **MKV** *(.mkv)* file format is not officially supported as an interactive or playable format on GitHub.
> - MKV = Matroska Video = a free, open-source multimedia container format that bundles video, audio, subtitle, and image tracks into a single file
> - GIF = Graphics Interchange Format = a digital image file format supporting both static pictures and short, looping, silent animations, widely used on the internet for reactions and short clips
> - The resulting GIF file might be bigger than the video file used as input.
> - Other video file formats that are supported as input by ffmpeg: MP4, WebM, MOV, AVI, WMV, FLV, MPEG/MPG, M4V, 3GP, TS/M2TS, OGV, VOB.
