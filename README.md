Recommend jar file for installation. Click -> [**here**](https://github.com/LunarMoonDLCT/GalaxyClientInstaller/releases/latest) <- to download the latest version.
---
# ✨ Galaxy Client Installer

This is a simple Java-based installer for the Galaxy Client Minecraft.  
It downloads the Galaxy Client from GitHub and installs it directly into your minecraft directory.

---
- Recommend jar file for installation.
 Click here -> [**here**](https://github.com/LunarMoonDLCT/GalaxyClientInstaller/releases/latest) <- to download the latest version.
---
If you use Windows to run exe files, download [**JRE 8**](https://www.java.com/en/download/manual.jsp) to run the application.
if you use linux or mac os to run, open Terminal, then type the following: 
(linux)
```bash
sudo apt install default-jre
```
(mac Os)
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install oracle-jdk --cask
```
When the installation is complete, type this command:
```bash
cd your-dir
java -jar GalaxyClient-Installer-0.2.4-Universal.jar
```
---
## ❗ If linux error sound in game

If you are a Linux user and the game has sound errors or no sound in game, please use the [fabric](https://fabricmc.net/) version in game to fix the error.

---

## ✅ Features

- Easy to use
- Install Galaxy Client Minecraft for you
- GUI-based, built with Java Swing
- Added automatic deletion of junk files after installation is complete
- FlatDarkLaf Theme

---

## 🧱 Requirements

- **[JRE 8](https://www.java.com/en/download/manual.jsp) or higher**
- Internet connection to download client from GitHub

---

## 🚀 How to Build

1.Requirements to build

-  JDK 8 or higher
-  Gradlew

---
2.Build commands

```bash
# 1. Clone the repository
git clone https://github.com/LunarMoonDLCT/GalaxyClientInstaller.git
cd your-repo

# 2. Run the Gradle wrapper to build the installer
# Linux/macOS:
./gradlew build

# Windows:
gradlew.bat build

#After the build is complete, check the output in the path: build/libs/Galaxy-Client-Installer.jar
