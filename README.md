# LuckPermsPlaceholders Fabric 1.20.1
Provides LuckPerms placeholders for modded Fabric 1.20.1 server.

Tips : Use [Styled Player List](https://modrinth.com/mod/styledplayerlist) and [Styled Chat](https://modrinth.com/mod/styled-chat).

This project is a fork of [LuckPermsPlaceholders](https://github.com/LuckPerms/placeholders) by [lucko](https://github.com/lucko).

## Downloads
You can get the official latest versions [here](https://ci.lucko.me/job/LuckPermsPlaceholders/).

## Build

To build LuckPermsPlaceholders:

1. Clone the repository:
```BASH
git clone https://github.com/lucko/LuckPermsPlaceholders.git
cd LuckPermsPlaceholders
```

2. Build the project using Gradle:
```BASH
./gradlew build
```

On Windows, use `gradlew.bat build` instead.

3. The build process will compile all subprojects, including common and fabric-placeholderapi.

4. After a successful build, you can find the compiled JAR files in their respective `build/libs` directories:
- Fabric PlaceholderAPI: `fabric-placeholderapi/build/libs/LuckPerms-Fabric-PlaceholderAPI-Hook.jar`

Note: Make sure you have JDK 17 or later installed on your system before building.

## Installation

### PlaceholderAPI Fabric
You need to place `LuckPerms-Fabric-PlaceholderAPI-Hook.jar` from `fabric-placeholderapi/build/libs` folder in the server mods folder, located at `/mods/`.
