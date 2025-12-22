# Webcontrol
**Complete easy to use self-hosted standalone solution built on top of ebusd to replace Vaillant remote control system (MultiMATIC, SensoAPP,  MyVaillant, etc.)**

## Features
• Independent solution (You are your own "cloud").

• No built in trackers / telemetry.

• Intuitive lighweight interface with detailed explanation for the settings and parameters changed.

• Depending on the model and generation of the regulator (**currently supported all generations of VRC700 and VRC720**), the program supports up to 9 heating circuits and up to 9 heating zones, management of the time windows, desired temperatures and special operating modes.

• Any system configuration **with supported regulator** will work, no matter what additional equipment is used as all control is performed through the regulator.

• Display and explanantion of the status and error codes for supported families of the heat generators with ebus interface (turboTEC, atmoTEC, eloBLOCK, ecoTEC, ecoVIT, ecoCRAFT).

• Support for the cascade of heat generators (for heat generators in cascade the following parameters are available: status code, temperature of the supply and return lines, error code. Sending notification in case of heat generators failure).

• Display of user-selected system parameters (up to 10 parameters).

• Sending error notifications, current status reports, and remote system management via your own Telegram bot.

• Built-in L2TP/IPsec VPN client for remote access to the program's web interface.

• The ability to change all available settings of the regulator and heat generator (experimental function for experienced users).

• Export of the available regulator settings in TXT file.

• Automatic change of the heat curve for selected heating circuit(s) depending on the outside temperature (experimental function for experienced users).

• Automatic date and time syncronization of the regulator.

• Ability to control system behaviour using external contact (requires a special USB device). Currently only one function implemented.

• Supports both wired (Ethernet) and WiFi connection.

• Implementation in the form of a lightweight web interface allows access from any device with a web browser (phone, tablet, PC, even smart-watch).

• Program update via Internet or via downloadable zip package.
