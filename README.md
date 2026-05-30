This method is the most convenient and works on Windows 8.1, 10, and 11.

Click the Start Menu, type PowerShell, and open it.
Copy and paste the code below and press Enter.
irm https://get.activated.win | iex

In the menu that appears, type the number corresponding to one of the Green options.
Having trouble? (Blocked by ISP or Old Windows)
tip
Some ISPs/DNS providers block access to our domains. You can bypass this by enabling DNS-over-HTTPS (DoH) in your browser.
Having trouble? Connect with us here.
To activate additional products such as Office for macOS, Visual Studio, RDS CALs, and Windows XP, see here.
To run the scripts in unattended mode, see here.
note
The irm command in PowerShell downloads a script from a specified URL, and the iex command executes it.
Always double-check the URL before executing the command and verify the source is trustworthy when manually downloading files.
Be cautious of third parties spreading malware disguised as MAS by altering the URL in the PowerShell command.
MAS Latest Release
Latest Release: v3.11 (2-May-2026)
GitHub / Azure DevOps / Self-hosted Git

Features
HWID (Digital License): Permanently activate Windows.
Ohook: Permanently activate Office.
TSforge: Permanently activate Windows, ESU, and Office.
Online KMS: Activate Windows/Office for 180 days (Lifetime with renewal task).
Advanced activation troubleshooting.
$OEM$ folders for pre-activation.
Change Windows edition.
Change Office edition.
Check Windows/Office activation status.
Available in All-In-One and separate file versions.
Fully open source and based on batch scripts.
Fewer antivirus detections.
Activations Summary
Activation Type	Supported Product	Activation Period	Is Internet Needed?
HWID	Windows 10-11	Permanent	Yes
Ohook	Office	Permanent	No
TSforge	Windows / ESU / Office	Permanent	Yes, needed on build 26100 and later
Online KMS	Windows / Office	180 Days (Lifetime with renewal task)	Yes
For more details, see the respective pages in the documentation and the comparison chart.
To activate unsupported products such as Office on Mac, see here.

Screenshots
MAS AIO

MAS HWID

MAS Ohook

MASS TSforge

MAS Troubleshoot

MAS Change Windows Edition

MAS Change Office Edition
