# Windows10PinballFocus
This is A FORK Based On ChrisTitusTech and DaddyMadu's debloat and optimize windows 10 script for the lowest latency and best gaming experience, the Ultimate Windows 10 Script is a creation from multiple debloat scripts and gists from github. This fork is my edit intended for my virtual pinball cabinet, if you helps you cool.
```
Warrning: I am NOT responsible for what you do to your Devices/Systems, so follow these instructions at your own risk. Make sure you know what you're doing, it's best to understand the process rather than just copy and paste commands and such.
```

## Changelog!

27 June 2021
```
- Disabling New Windows 10 News and Interests Feed.
- Movilng Updates to slower release ring.
- Delaying Windows Feature Updates by 45 Days to Ensure a Bug Free Build.
- Delaying Windows Quality Updates by 7 Days to Ensure a Bug Free security updates.
- much more fixes forget to remember!
```
## This Script Does The Following!

- Dark Mode.
- One Command to launch and run.
- Chocolatey Install.
- O&O Shutup10 CFG and Run.
- Added Install Programs.
- Added Debloat Microsoft Store Apps.
- Removing Bloadwares.
- Disable Microsoft Windows Defender and related Processes.
- Disable "Microsoft Software Protection Platform Service” that Cause High CPU Usage in some older systems.
- Disable Enable Wsappx to Fix 100% Disk Usage in Windows 10 in older systems.
- Disabling Telemetry.
- Disabling Wi-Fi Sense.
- Disabling SmartScreen Filter.
- Disabling Bing Search in Start Menu.
- Disabling Application suggestions.
- Disabling Activity History.
- Disabling Background application access.
- Disabling Location Tracking.
- Disabling automatic Maps updates.
- Disabling Feedback.
- Disabling Tailored Experiences.
- Disabling Advertising ID.
- Disabling Cortana.
- Disabling Error reporting.
- Restricting Windows Update P2P only to local network.
- Stopping and disabling Diagnostics Tracking Service.
- Stopping and disabling WAP Push Service.
- Lowering UAC level.
- Setting current network profile to private.
- Setting unknown networks profile to private.
- Disabling automatic installation of network devices.
- Enabling F8 boot menu options.
- Disabling Meltdown (CVE-2017-5754) compatibility flag.
- Enabling Malicious Software Removal Tool offering.
- Enabling driver offering through Windows Update.
- Disabling Windows Update automatic restart.
- Stopping and disabling Home Groups services.
- Disabling Shared Experiences.
- Disabling Remote Assistance.
- Enabling Remote Desktop w/o Network Level Authentication.
- Disabling Autoplay.
- Disabling Autorun for all drives.
- Disabling Storage Sense.
- Disabling scheduled defragmentation.
- Stopping and disabling Superfetch service.
- Starting and enabling Windows Search indexing service.
- Setting BIOS time to UTC.
- Disabling Hibernation.
- Enabling Sleep start menu and keyboard button.
- Disabling display and sleep mode timeouts.
- Disabling Fast Startup.
- Disabling Action Center.
- Enabling Lock screen.
- Enabling Lock screen (removing scheduler workaround).
- Disabling Sticky keys prompt.
- Showing task manager details.
- Showing file operations details.
- Disabling file delete confirmation dialog.
- Hiding Taskbar Search icon / box.
- Hiding Task View button.
- Hiding People icon.
- Showing all tray icons.
- Disabling search for app in store for unknown extensions.
- Disabling 'How do you want to open this file?' prompt.
- Adjusting visual effects for performance.
- Enabling NumLock after startup.
- Enabling Dark Mode
- Stopping Edge from taking over as the default .PDF viewer 
- Showing known file extensions.
- Hiding hidden files.
- Hiding sync provider notifications.
- Hiding recent shortcuts.
- Changing default Explorer view to This PC.
- Hiding Music icon from This PC.
- Hiding Music icon from Explorer namespace.
- Hiding Videos icon from This PC.
- Hiding Videos icon from Explorer namespace.
- Hiding 3D Objects icon from This PC.
- Hiding 3D Objects icon from Explorer namespace.
- Enabling thumbnails.
- Enable creation of Thumbs.db.
- Option to Enable & Install Or Disable & Uninstall Microsoft OneDrive.
- Disabling built-in Adobe Flash in IE and Edge.
- Installing Windows Media Player.
- Uninstalling Internet Explorer.
- Uninstalling Work Folders Client.
- Uninstalling Linux Subsystem.
- Setting Photo Viewer association for bmp, gif, jpg, png and tif.
- Adding Photo Viewer to "Open with.
- Installing Microsoft Print to PDF.
- Disabling power throttling(Laptop).
- Setting Processor scheduling for Best Performance.
- Disabling aero shake.
- Show BSOD details instead of the sad smiley.
- Disabling start menu live tiles.
- Setting Wallpaper Quality to 100%.
- Disabling search history.
- Disabling "- Shortcut" Word.
- Disabling Mouse Keys Keyboard Shortcut.
- Disabling Windows Transparency.
- Turning Off Safe Search.
- Disabling Cloud Search.
- Disabling Device History.
- Disabling Windows Remote Assistance.
- Disabling Search Histroy.
- Disabling annoying Get even more out of Windows.
- Disabling Hide Scroll bars.
- Disabling smooth scrolling.
- Disabling microsoft usertracking.
- Disabling more of Un nessessary Services For Gaming.
- Disabling New Microsoft MeetNow.
- Unbinned StartMenu Titles and forced apps only view.
- Show taskbar buttons only on taskbar where window is open.
- Disabling GameDVR1.
- Disabling GameDVR2.
- Disabling Full ScreenOptimization.
- Apply Gaming Optimization Fixs.
- Disable DMA memory protection and cores isolation ("virtualization-based protection").
- Disable Process and Kernel Mitigations.
- Disallow drivers to get paged into virtual memory.
- Use big system memory caching to improve microstuttering.
- Force contiguous memory allocation in the DirectX Graphics Kernel.
- Tell Windows to stop tolerating high DPC/ISR latencies.
- Decrease mouse and keyboard buffer sizes.
- Applying PC Optimizations (SystemResponsiveness & NetworkThrottlingIndex).
- Auto detect Windows screen Scale setting and apply Mouse fix accordingly for 100% Raw Mouse Input, Thanks To (http://donewmouseaccel.blogspot.com/2010/03/markc-windows-7-mouse-acceleration-fix.html).
- Auto detect Nvidia GPU and Apply Power and Latency Tweaks.
- Auto Detect AMD GPU and Apply Latency Tweaks.
- Adding option to enable or disable MSI Mode (Please read the WARNNINGS First!) .
- Disabling High Precision Event Timer.
- Enabling Gaming Mode.
- Enabling HAGS.
- Disable Windows 10 Core Parking On Current PowerPlan "Ultimate Performance".
- Optimizing Network and applying Tweaks for no throttle and maximum speed!.
- Disabling Nagle’s Algorithm.
- disabled any power saving option under any network device.
- disabled offloading, Green Ethernet, Giga Lite, EEE, Advanced EEE, Energy Efficient from all network devices.
- Removing Edit with Paint 3D from context menu.
- Running DaddyMadu Ultimate Cleaner => Temp folders & Flush DNS + Reset IP.
- Fix issue with games shortcut that created by games lunchers turned white.
- Clearing Temp folders.

# Notice Before Use!

- Kindly note that if you choose to disable Microsoft Store and WSAPPX Service and wanted to enable it again, you have to run the script with this setting enabled then restart pc and rerun it again with the same settings to get Microsoft Store back! it a limitition of windows 10 as this registry tweak needs restart to take effect before script is trying to install microsoft store!
- When disabling Microsoft Store & WSAPPX Service, This PC Properties will only be accessible from File Explorer!
- disabling "Microsoft Software Protection Platform Service" will render microsoft activation Service not active hence any microsoft apps, windows, office, etc will show not activated state! 

# How To Use!

Simply Run cmd (Command Prompt) as Administrator and paste the following!
```
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('http://tweaks.daddymadu.gg')"
```
if error then use the following!
```
powershell -NoProfile -ExecutionPolicy unrestricted -Command "[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; &iex(New-Object Net.WebClient).DownloadString('http://tweaks.daddymadu.gg')"
```
Or Run Powershell As Administrator and paste the following!
```
iex(New-Object Net.WebClient).DownloadString('http://tweaks.daddymadu.gg')
```
To enable Action Center, put the following into Powershell run As Administrator!
```
Write-Host "Enabling Action Center..."
	Remove-ItemProperty -Path "HKCU:\SOFTWARE\Policies\Microsoft\Windows\Explorer" -Name "DisableNotificationCenter" -ErrorAction SilentlyContinue
	Remove-ItemProperty -Path "HKCU:\SOFTWARE\Microsoft\Windows\CurrentVersion\PushNotifications" -Name "ToastEnabled" -ErrorAction SilentlyContinue 
	Write-Host "Done - Reverted to Stock Settings"
```
## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
