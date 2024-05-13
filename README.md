# OpenLiteSpeed + WordPress Setup Script
This bash script automates the installation of OpenLiteSpeed and WordPress on a Linux VPS. It simplifies the process of setting up a web server and deploying a WordPress site, making it suitable for quick deployments or testing environments.

# Prerequisites
Before running this script, ensure you have:
- A Linux VPS running Ubuntu 20.04 or later.
- Root or sudo access to the VPS.

 
# Installation
```bash
wget -O setup.sh https://raw.githubusercontent.com/UncutDevs/litespeedwordpress/main/OpenLiteSpeedWP.sh
chmod +x setup.sh
bash setup.sh
```
# Notes
This script installs OpenLiteSpeed, PHP, MariaDB, and WordPress with default settings. Modify the script as needed for production use.
After installation, ensure to secure your server, configure SSL, and adjust server settings based on your requirements.

For troubleshooting and advanced configurations, refer to the <a href="https://docs.openlitespeed.org/">OpenLiteSpeed Documentation.</a>

