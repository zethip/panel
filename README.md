# webserver by aapanel

# How to install aaPanel on Ubuntu 22.04 | 20.04 Linux server

# Step 1: Update your Ubuntu 22.04 or 20.04 Server

sudo apt update && sudo apt upgrade -y

# Step 2: Download and Execute the Installation Script

wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && sudo bash install.sh aapanel

# Step 3: Access aaPanel Web Interface

After the installation is completed, on the terminal screen you will see the IP Addresses that can be used to access the Dashboard of aaPanel. Just open your local browser that can access the server IP address and enter that along with port number “:7800“. For example, if your server’s IP address is “10.0.2.15,” you would enter “http://10.0.2.15:7800” in your browser’s address bar

# Uninstallation of aaPanel

sudo bt stop &&sudo update-rc.d -f bt remove &&sudo rm -f /etc/init.d/bt &&sudo rm -rf /www/server/panel

# Thank You.
