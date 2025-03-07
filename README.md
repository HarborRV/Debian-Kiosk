# Debian-Kiosk
Repository for programming a Debian based kiosk display terminal on a Dell Wyse 3040

This script is designed to do the following:
Install Intune to join to your MS tenant
Configure Intune to run on Debian (MS only offers it for Ubuntu)
Set the homepage in FireFox (web-based terminal display) and configure FF to run at boot in Kiosk mode
Install unclutter to hide the cursor at idle
install openSSH and ufw for remote access
Optional: install drivers for BrosTrend AC1200 wireless adapter and auto connect to SSID
Clean up install files

Run with Sudo while connected to ethernet
Joining to Intune is still a manual process, and passwords should NOT be stored in plain text inside the program
