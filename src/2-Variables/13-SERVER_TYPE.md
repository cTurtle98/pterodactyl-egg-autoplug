# Variables - Server_TYPE

## Name

```txt
Server Type
```

## Description

```txt
which Minecraft server software do you want to use?

Valid Values:
paper
purpur
waterfall
velocity
travertine

ADVANCED:
you can set an alternative server software to use by manually editing the config file with an alternatives section EX:
alternatives: 
  github: 
    repo-name: Anuken/Mindustry
    asset-name: server-release
and then this option will be ignored
```

## Enviroment Variable

```txt
Server_TYPE
```

## Default Value

```txt
paper
```

## Permissions

```txt

```

## Input Rules

```txt
required|string|in:paper,purpur,waterfall,velocity,travertine
```
