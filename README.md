# Rebuild of Mid-2010's MSI Desktop Into Modern Film Editing Workstation
backed up the users folder from the computer while it still had windows 7 on it. 
Disconnected peripheral devices, (Asus monitor, usb expansion port, WD external hard drives). 
Remove the front plate screws to expose the inside of the tower. 
Examine if there are any connections that would allow for additional hard drives to be installed (none were found)
Remove existing 2 TB hard drive due to wear & tear. 
Using a dust vaccum, get all the dust out of the inside. 
Replaced the hard drive with a spare WD 1 TB HDD module (there were no SSD's and that the highest capacity unused HDD; external storage is attached for when that is needed).
Install Windows 10 pro via usb (this took a couple of times; ended up needing to restore the bios to default settings, checking a secure boot setting called ' ', enabling uefi, setting the boot order to the usb first, and then restarting the machine manually to get it right).
created a local admin account. 
Connected to wifi using tplink dongle. Ensured all windows 10 updates were installed. 
Ran the following powershell script to get rid of windows bloatware: https://github.com/Raphire/Win11Debloat; kept microsoft edge to avoid possibility of crashing the OS. 
In Microsoft Edge, changed the following settings: ublock origin & malwarebytes browser AV extenstions, updated to latest version, strictest permissions in 'cookies & site permissions', strictest privacy setting, 
installed the following software packages from ninite.com: Google Chrome, VLC, Audacity, Handbrake, iTunes, Everything, All Runtimes, 7Zip, ShareX, ImgBurn, Teracopy
Installed the following software not available on ninite: Partition Wizard, BCUninstaller, AVS Film Editor, Adobe Acrobat 
Configured custom rule in Windows Defender Firewall to block the following ports (ingoing AND outgoing traffic): 80 (HTTP), 22 (SSH), 23 (Telnet), 25/587 (SMTP), Port 110/995 (Pop3), Port 143/993 (Imap)
Made Google Chrome the default browser 
Configured Google Chrome settings with the following: Ublock Origin/Malwarebytes browser extensions, updated browser, block third party cookies, send a 'do not track request' 
Conducted a final round of hardware/malware scans using built in tools. 
Reimported customer data/reconnected peripheral devices. 
