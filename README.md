# Webcontrol
**Complete easy to use self-hosted standalone solution built on top of ebusd to replace Vaillant remote control system (MultiMATIC, SensoAPP,  MyVaillant, etc.)**

[See Webcontrol Wiki for the information how to download, install and setup](https://github.com/stadid/webcontrol/wiki)

![What is required to run Webcontrol](https://github.com/stadid/webcontrol/blob/main/webcontrol.jpg?raw=true)
## Features
• Independent solution (You are your own "cloud").

• No built in trackers / telemetry.

• Easy setup. The only thing you have to do is to select what Zones and Circuits you want to display. 

• Intuitive (to the author, of course) lighweight Web interface with detailed explanation for the settings and parameters changed.

• Always actual data as parameters are read from the system "on the fly" at the time of corresponding interface page is loaded.

• Depending on the model and generation of the controller (**currently supported all generations of VRC700 and VRC720**), the program supports up to 9 circuits and up to 9 zones, plus management of the time windows, desired temperatures and special operating modes.

• Any heating system configuration **with supported controller** will work, no matter what additional equipment is used as all management is performed through the controller.

• Display and explanantion of the status and error codes for supported families of the heat generators with ebus interface (turboTEC, atmoTEC, eloBLOCK, ecoTEC, ecoVIT, ecoCRAFT).

• Support for the cascade of heat generators (for heat generators in cascade the following parameters are available: status code, temperature of the supply and return lines, error code. Sending notification in case of heat generators failure).

• Display of user-selected system parameters (up to 10 parameters).

• Sending error notifications, current status reports, and remote system management via your own Telegram bot.

• Multiple user accounts with several permission levels: read only, normal user, specialist.

• Built-in L2TP/IPsec VPN client for remote access to the program's web interface.

• The ability to change all available settings of the controller and heat generator (experimental function for experienced users).

• Export of the available controller settings into TXT file.

• Automatic change of the heat curve for selected heating circuit(s) depending on the outdoor temperature (experimental function for experienced users).

• Automatic date and time syncronization of the controller.

• Ability to control system behaviour using external contact (requires a special USB device). Currently only one function implemented for VRC700 controller.

• Supports both wired (Ethernet) and WiFi connection.

• Implementation in the form of a lightweight web interface allows access from any device with a web browser (phone, tablet, PC, even smart-watch).

• Program update via Internet or via downloadable zip package.

## Drawbacks
• Limited number of supported controllers (VRC700, VRC720). *Other controllers (for example, VRT380) could be added if significant user demand is shown.* No support for systems where controllers are not installed.

• Focus on heating. **Currently** no inerface pages for managing cooling / ventilation (some parameters, however, could be set using direct set mode). *Could be added if user interst is shown.*

• No protection for Web interface. System should be used only in controlled enviroment (LAN) with external access only via VPN.

• No fuel consumption / energy statistics data interface pages. *Could be added in case of user demand.*

• No integration with smart home systems. Acts as a pure standalone solution. 

• No virtualization support. Should be run on a real "hardware" only. 
