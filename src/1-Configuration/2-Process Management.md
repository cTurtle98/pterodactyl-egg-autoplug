# Process Management

## Stop Command

```bash
.stop both
```

## Log Configuration

```json
{}
```

## Configuration Files

```json
{
  "autoplug/updater-config.yml": {
    "parser": "yaml",
    "find": {
      "updater-config.java-updater.enable": "false",
      "updater-config.java-updater.profile": "AUTOMATIC",
      "updater-config.java-updater.version": "17",
      "updater-config.server-updater.enable": "{{server.build.env.SERVER_UPDATE_ENABLE}}",
      "updater-config.server-updater.profile": "{{server.build.env.SERVER_UPDATE_PROFILE}}",
      "updater-config.server-updater.software": "{{server.build.env.SERVER_TYPE}}",
      "updater-config.server-updater.version": "{{server.build.env.SERVER_VERSION}}",
      "updater-config.plugins-updater.enable": "{{server.build.env.PLUGIN_UPDATE_ENABLE}}",
      "updater-config.plugins-updater.profile": "{{server.build.env.PLUGIN_UPDATE_PROFILE}}"
    }
  },
  "server.properties": {
      "parser": "properties",
      "find": {
          "server-ip": "0.0.0.0",
          "server-port": "{{server.build.default.port}}"
      }
  }
}
```

## Start Configuration

```json
{
    "done": ")! For help, type "
}
```
