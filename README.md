# Packet Tool

Client-side packet tracker for **Minecraft 1.21.1 (Fabric)**.

Packet Tool adds a simple in-game UI that lists inbound/outbound packets in real time so you can see what your client is sending and receiving.

## Features

- Live packet list with timestamps
- Inbound/Outbound filters
- Search by packet class name
- Clear button
- Mod Menu support (opens the Packet Tool screen)

## How To Use

- Press `R` in-game to open/close Packet Tool.
- Use the search bar and filters to narrow results.
- Click **Clear** to reset the log.

## Install

1. Install **Fabric Loader** for 1.21.1.
2. Install **Fabric API**.
3. Drop the jar into your `mods` folder.

## Build From Source

```powershell
$env:JAVA_HOME="C:\Program Files\Java\jdk-21.0.10"
$env:PATH="$env:JAVA_HOME\bin;$env:PATH"
$env:GRADLE_OPTS="-Dorg.gradle.native=false"
$env:GRADLE_USER_HOME="$PWD\.gradle"
.\gradle-8.14\bin\gradle.bat build
```

Output jar:

```
C:\Users\Zayn Shabhi\Documents\other\minecraftmod\build\libs\packettool-0.1.0+mc1.21.1.jar
```

## Screenshots

Place screenshots here (for example: `marketing/packettool-screenshot-clean.png`).

## License

All Rights Reserved
