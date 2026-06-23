# NovariaMC Guide

This guide explains the basic workflow for installing NovariaMC, preparing dependencies, creating a server, and opening it from a PC or Minecraft client.

NovariaMC is still in active development, so some screens may change over time.

## 1. Install The App

1. Download the latest APK from the Releases page:
   https://github.com/ErogamesMC/NovariaMC/releases/latest
2. Install the APK on your Android device.
3. Open NovariaMC.
4. If Android asks for permissions, allow the ones required for file access, network access, and background operation.

## 2. Install Dependencies

Open the dependencies screen from the download button in the top bar.

Recommended setup:

- Install Java 21 for modern Paper, Fabric, NeoForge, and recent Minecraft versions.
- Install Java 8 only when working with older Forge or legacy servers.
- Install Playit if you want friends outside your local network to connect.
- Install Chunker if you plan to import or convert Bedrock `.mcworld` worlds.

If a dependency fails, reinstall it from this screen before creating or starting a server.

## 3. Create A Server

1. Tap the `+` button on the main screen.
2. Choose the server type and Minecraft version.
3. Wait for NovariaMC to download and prepare the server.
4. Open the server console.
5. Start the server.

The first start can take longer because Minecraft generates folders, settings, worlds, and cache files.

## 4. Manage The Server

From the server management screen you can:

- Edit server settings.
- Change RAM, players, view distance, simulation distance, difficulty, PvP, and other options.
- Manage files.
- Manage worlds.
- Import `.mcworld` files.
- Create and restore backups.
- Browse mods or plugins when supported by the server type.

Stop the server before replacing worlds, changing important files, or modifying large mod/plugin setups.

## 5. Use The Local Web Panel

The local web panel lets you manage the server from a PC on the same Wi-Fi network.

1. Open the server console in NovariaMC.
2. Tap `Panel local para PC`.
3. Copy the LAN link.
4. Open that link from your PC browser.

The phone and PC must be connected to the same local network.

## 6. Public Access With Playit

Playit allows people outside your local network to connect.

Basic flow:

1. Install Playit from dependencies.
2. Open a server console.
3. Open the Playit tab.
4. Claim or configure the Playit agent.
5. Start the server and keep Playit active.

If Playit says the agent has no tunnels assigned, open the Playit account page and assign the tunnel to the current agent.

## 7. Import Worlds

For Bedrock `.mcworld` files:

1. Stop the server.
2. Open the server file manager or world tools.
3. Upload the `.mcworld`.
4. NovariaMC will import or convert it when supported.
5. Start the server again.

Large worlds can take several minutes to process.

## 8. Common Issues

### The server does not start

- Check that the correct Java runtime is installed.
- Open the console and read the first error shown.
- Try lowering the assigned RAM.
- Make sure the server version matches the selected runtime.

### Friends cannot connect

- Confirm the server is running.
- Confirm Playit is running if they are outside your Wi-Fi network.
- Check that the tunnel points to the correct local port.
- For Bedrock-compatible setups, verify the correct Bedrock port.

### The app feels slow

- Lower RAM, view distance, and simulation distance.
- Close other apps.
- Keep the phone cool and connected to power for larger servers.
- Prefer lightweight server types when using lower-end devices.

### A modpack does not work

- Confirm it supports the server version and loader.
- Check if it is client-only.
- Make sure required dependencies are installed.
- Read the server console logs for missing mods or incompatible versions.

## 9. Support Development

If NovariaMC helps you, you can support development through Ko-fi:

https://ko-fi.com/uwuzzi

## 10. Disclaimer

NovariaMC is an independent project and is not affiliated with Mojang, Microsoft, Minecraft, PaperMC, GeyserMC, Playit, or other third-party projects used or supported by the app.
