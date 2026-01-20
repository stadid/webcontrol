# Webcontrol
**Complete easy to use self-hosted standalone solution built on top of ebusd to replace Vaillant remote control system (MultiMATIC, SensoAPP,  MyVaillant, etc.)**

***

[See Webcontrol Wiki for the program description and information on how to download, install and setup](https://github.com/stadid/webcontrol/wiki)

***

![What is required to run Webcontrol](https://github.com/stadid/webcontrol/blob/main/webcontrol.jpg?raw=true)
## Features
• Standalone solution, no external services required. No trackers / telemetry.

• Intuitive lightweight web interface accessible from any device with a web browser (phone, tablet, PC, or even a smartwatch). Most interface controls include descriptive text, helping users understand the changes they are making.

• Features the self-hosted Telegram bot for sending error notifications, current system status reports, and a remote system management.

• Always actual readings of the system settings and parameters - they are read from the system on the fly when the corresponding interface page loads.

• Easy setup: simply select which Zones and Circuits you want to display. 

• Compatible with any Vaillant system **featuring supported controller (currently supported all wired generations of VRC700 and VRC720)**. System management is performed via the controller (the same way as it's done by manufacturer).

• Management of the time windows, desired temperatures and special operating modes of the controller.

• Display of the status and error codes for the heat generator(s) installed in the system. Detailed codes explanation available for the supported families of the heat generators: turboTEC, atmoTEC, eloBLOCK, ecoTEC, ecoVIT, ecoCRAFT.

• Heat generators cascade support (for heat generators in cascade the following parameters are available: status code, temperature of the supply and return lines, error code. Sending notification in case of heat generators failure).

• Customizable display of up to 10 user-selected system parameters.

• Multiple user accounts with several permission levels: read only, normal user, specialist.

• Saving and restoring program settings via a configuration file.

• Built-in L2TP/IPsec (PSK) VPN client for remote access to the program's web interface.

• Allows changing all available (in ebusd configuration) settings for the controller and heat generator (experimental function for advanced users).

• Controller settings export into a TXT file.

• Automatic adjustment of the heat curve for selected heating circuits based on outdoor temperature (experimental function for experienced users).

• Automatic date/time correction of the controller clock using an internet-synchronized clock in the Webcontrol mini-PC.

• System control via an external contact (requires a USB GPIO device). Currently one function is implemented for the VRC700 controller.

• Supports both wired (Ethernet) and Wi-Fi connections.

• Program updates via the Internet or via downloadable ZIP package.

## Limitations
• Limited number of supported controllers (VRC700, VRC720). *Other controllers (for example, VRT380) could be added if significant user demand is shown.* No support for systems where controllers are not installed.

• Focus on heating. **Currently** no interface pages for managing cooling / ventilation (some parameters, however, could be set using direct set mode). *Could be added if user interest is shown.*

• No protection for Web interface. The system should be used only in controlled enviroment (LAN) with external access only via VPN.

• No fuel consumption / energy statistics data interface pages. *Could be added if requested.*

• No integration with smart-home systems. Acts as a pure standalone solution. 

• No virtualization support. Should be run on a real hardware only. 
