# Install Script

```bash
#!/bin/bash
#
# AutoPlug Pterodactyl Installation Script
#
# Server Files: /mnt/server

echo "### enter the server directory used by pterodactyl"
cd /mnt/server

echo "#### update apt cache"
apt update && apt upgrade -y && apt install -y curl

echo "#### download autoplug jar"
curl -o $SERVER_JARFILE https://raw.githubusercontent.com/Osiris-Team/AutoPlug-Releases/master/stable-builds/AutoPlug-Client.jar

echo "#### SERVER INSTALL COMPLETE"

```

## Script Container

```txt
ubuntu:20.04
```

## Script Entrypoint Command

```bash
bash
```
