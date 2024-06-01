#!/bin/bash

# Download TeamViewer .deb package
echo "Downloading TeamViewer package..."
wget -qO /tmp/teamviewer_amd64.deb https://download.teamviewer.com/download/linux/teamviewer_amd64.deb

# Install TeamViewer
echo "Installing TeamViewer..."
sudo dpkg -i /tmp/teamviewer_amd64.deb

# Install dependencies (if any)
echo "Installing dependencies..."
sudo apt-get -f install -y

# Cleanup downloaded package
echo "Cleaning up..."
rm /tmp/teamviewer_amd64.deb

echo "TeamViewer installation completed."
