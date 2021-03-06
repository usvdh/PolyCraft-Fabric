# Polycraft

Version 2.0 of the private Minecraft survival server Polycraft. Check the releases page for the configurations for specific versions of Minecraft.

## Getting Started

This repo will include everything that is needed to reproduce a similar server, with the exception of sensitive data such as the whitelist, API keys etc. as well as the mod loaders and mods used, please download them yourself from their respective owners.

## Background

PolyCraft V1 officially started in 2016 at Minecraft version 1.10 (Java), but has had numerous predecessors dating back to 2010. With the codebase for PolyCraft V1 becoming 5 years old, I thought I'd be a good idea to make a V2 from scratch in preperation for Minecraft version 1.18. 

## How to use 

This repo is provided without the server .jar file and plugin .jar files, please download them from their respective creators. To get a working Minecraft server use the next steps: 
1. Download [Fabric](https://fabricmc.net/use/) and run the .jar (or .exe) file to get the fabric .jar and vanilla .jar files.
2. Download all the mods and put them into /mods
3. Download the datapacks and put them into /world/datapacks
4. Start the server once and then shut it down
5. Adjust the configs in /config to your liking. The most important ones are config/disfabric.json5 and config/textile_backup.json5

And you're done! Now you (should) have a fully working server.

### Mod loader

In this release (v1.0.0) [Fabric Loader v0.11.6](https://fabricmc.net/use/) is used for Minecraft 1.18-pre1.

### Mods

Below is a list of the mods used for this release (v1.0.0) with their respective versions. However, if there is a newer version available I suggest using that instead. Click on the mod name for the CurseForge page, and click on the version number to go directly to the version download.

| Mods        | Download  |
| ------------- | :-----:|
| [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) | [0.44.0](https://www.curseforge.com/minecraft/mc-mods/fabric-api/download/3546679/file) |
| [Fabric Language Kotlin](https://www.curseforge.com/minecraft/mc-mods/fabric-api) | [1.7.0](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin/download/3531998/file) |
| [LengthyLadders](https://www.curseforge.com/minecraft/mc-mods/lengthy-ladders) | [1.0.5](https://www.curseforge.com/minecraft/mc-mods/lengthy-ladders/download/3522416/file) |
| [LapisReserve](https://www.curseforge.com/minecraft/mc-mods/lapis-reserve) | [1.0.8](https://www.curseforge.com/minecraft/mc-mods/lapis-reserve/download/3345208/file) |
| [WanderingCollector](https://modrinth.com/mod/wandering-collector) | [1.0.2](https://cdn.modrinth.com/data/enYiOcBu/versions/1.0.2+mc1.17/wanderingcollector-1.0.2+mc1.17.jar) |
| [Notchify](https://www.curseforge.com/minecraft/mc-mods/notchify) | [0.4.1](https://www.curseforge.com/minecraft/mc-mods/notchify/download/3346344/file) |
| [Ledger](https://github.com/QuiltServerTools/Ledger/) | [1.2.0](https://github.com/QuiltServerTools/Ledger/releases/download/v1.2.0/ledger-1.2.0.jar) |
| [Textile Backup](https://github.com/QuiltServerTools/Ledger/) | [2.3.0](https://www.curseforge.com/minecraft/mc-mods/textile-backup/download/3542373/file) |
| [DisFabric](https://github.com/QuiltServerTools/Ledger/) | [1.3.5](https://www.curseforge.com/minecraft/mc-mods/disfabric/download/3546329/file) |
| [Lithium](https://github.com/QuiltServerTools/Ledger/) | [0.7.6](https://www.curseforge.com/minecraft/mc-mods/lithium/download/3565566/file) |
| [TimeOutOut](https://www.curseforge.com/minecraft/mc-mods/timeoutout-fabric) | [1.0.0](https://www.curseforge.com/minecraft/mc-mods/timeoutout-fabric/download/3569025/file) |
| [Starlight (Fabric)](https://modrinth.com/mod/starlight) | [1.0.0](https://cdn.modrinth.com/data/H8CaAYZC/versions/Starlight%201.0.0%201.18.x/starlight-1.0.0+fabric.d0a3220.jar) |
| [Krypton](https://github.com/astei/krypton/) | [0.1.6](https://github.com/astei/krypton/releases/download/v0.1.6/krypton-0.1.6.jar) |



### Datapacks

- [Vanilla Tweaks Player Head Drops & More Mob Heads](https://vanillatweaks.net/share#ctCn0s)