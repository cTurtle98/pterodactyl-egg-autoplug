# Configuration

## Name

```txt
AutoPlug
```

## Description

```txt
Automatic Plugin/Server/Java/Self Updater and Server Manager
```

## Docker Images

```txt
ghcr.io/pterodactyl/yolks:java_8
ghcr.io/pterodactyl/yolks:java_11
ghcr.io/pterodactyl/yolks:java_16
ghcr.io/pterodactyl/yolks:java_17
```

## Startup Command

```bash
java -Xms128M -Xmx{{SERVER_MEMORY}}M -Dterminal.jline=false -Dterminal.ansi=true -jar {{SERVER_JARFILE}}
```
