# Webcontrol
**Complete easy to use self-hosted standalone solution built on top of ebusd to replace Vaillant remote control system (MultiMATIC, SensoAPP,  MyVaillant, etc.)**

***

[See Webcontrol Wiki for the program description and information on how to download, install and setup](https://github.com/stadid/webcontrol/wiki)

***

![What is required to run Webcontrol](https://github.com/stadid/webcontrol/blob/main/webcontrol.jpg?raw=true)
## Features
• Independent solution (You are your own "cloud").

• No built in trackers / telemetry.

• Easy setup: simply select which Zones and Circuits you want to display. 

• Intuitive lightweight web interface (to the author’s taste) with detailed explanations for settings and parameters changed.

• Always up-to-date data, as parameters are read from the system on the fly when the corresponding interface page loads.

• Depending on the model and generation of the controller (**currently supported all wired generations of VRC700 and VRC720**), the program supports up to 9 circuits and up to 9 zones, plus management of the time windows, desired temperatures and special operating modes.

• Any system configuration **with supported controller** will work, no matter what additional equipment is used as all management is performed through the controller (the same way as it's done by manufacturer).

• Display and explanation of the status and error codes for supported families of the heat generators with ebus interface (turboTEC, atmoTEC, eloBLOCK, ecoTEC, ecoVIT, ecoCRAFT).

• Heat generators cascade support (for heat generators in cascade the following parameters are available: status code, temperature of the supply and return lines, error code. Sending notification in case of heat generators failure).

• Display of user-selected system parameters (up to 10 parameters).

• Sending error notifications, current status reports, and remote system management via your own Telegram bot.

• Multiple user accounts with several permission levels: read only, normal user, specialist.

• Saving and restoring program settings via a configuration file.

• Built-in L2TP/IPsec (PSK) VPN client for remote access to the program's web interface.

• Ability to change all available settings of the controller and heat generator (experimental function for experienced users).

• Export of available controller settings to a TXT file.

• Automatic adjustment of the heat curve for selected heating circuits based on outdoor temperature (experimental function for experienced users).

• Automatic date/time correction of the controller clock using an internet-synchronized clock in the Webcontrol mini-PC.

• Ability to control system behavior using an external contact (requires a special USB GPIO device). Currently only one function is implemented for the VRC700 controller.

• Supports both wired (Ethernet) and Wi-Fi connections.

• Lightweight web interface accessible from any device with a web browser (phone, tablet, PC, or even a smartwatch).

• Program updates via the Internet or via downloadable ZIP package.

## Drawbacks
• Limited number of supported controllers (VRC700, VRC720). *Other controllers (for example, VRT380) could be added if significant user demand is shown.* No support for systems where controllers are not installed.

• Focus on heating. **Currently** no interface pages for managing cooling / ventilation (some parameters, however, could be set using direct set mode). *Could be added if user interest is shown.*

• No protection for Web interface. The system should be used only in controlled enviroment (LAN) with external access only via VPN.

• No fuel consumption / energy statistics data interface pages. *Could be added if requested.*

• No integration with smart-home systems. Acts as a pure standalone solution. 

• No virtualization support. Should be run on a real hardware only. 
