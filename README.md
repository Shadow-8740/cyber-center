CYBER CENTER

WELCOME // CHOOSE WISELY //
TOOLS DON'T THINK. OPERATORS DO.

Cyber Center is something I started building in Termux because I wanted more than just a bunch of commands I had to remember.

I wanted one place where I could open different tools, choose what I wanted to do, type in the information it asks for, and actually use the tools without remembering every command and option.

It also has the hacker/cyber terminal look I wanted, but I didn't want it to just be fake Matrix stuff or random numbers flying across the screen. The idea is for the information it shows to actually mean something.

This is still being built and changed as I come up with more ideas.

CURRENT PACKAGE

cyber-center_0.1.0_all.deb

This package currently includes:

• cyber-center
  The main Cyber Center interface.

• cyber-center-v1
  The original working version.

• cyber-center-v2
  The newer Cyber City/Cyber Center version that I'm experimenting with.

• nmap-center
  An interactive Nmap interface so you can choose different network operations and enter the hostname, IP address, network or ports instead of having to remember every Nmap command.

IDEA BEHIND IT

I want different parts of Cyber Center to actually feel different instead of everything being the same menu.

Some of the ideas I'm working toward include:

• N3TM4P // Nmap operations
• W1R3 // network quick tools
• V4ULT // file and firmware analysis
• C1PH3R // crypto tools
• PULS3 // live device monitoring
• TR4C3 // connections and routes
• NODE // device information
• L4B // security tools
• FEED // live telemetry
• SHELL // actual terminal access

Eventually I also want real changing telemetry on the screen, strange reversed/upside-down Cyber Center text, arrow-key navigation, and more stuff that makes it look alive without filling it with fake information.

INSTALLATION

This release is currently made for Termux on Android.

Download:

cyber-center_0.1.0_all.deb

Open Termux, go to wherever you saved the file, and install it with:

pkg install ./cyber-center_0.1.0_all.deb

After installation you can launch:

cyber-center

Or launch the versions individually:

cyber-center-v1
cyber-center-v2
nmap-center

IMPORTANT

Some features depend on other Termux packages such as Nmap, dialog, OpenSSL and networking/system utilities. The installer declares the core dependencies used by the current build.

Cyber Center contains network and security-related tools. Use those tools on your own systems, networks and devices, or systems you have permission to test.

This is an early build, not a finished project.

Version: 0.1.0
Platform: Termux / Android
# cyber-center