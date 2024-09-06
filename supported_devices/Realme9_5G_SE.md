# InfinityOneFlash v0.1.0

## Overview
**InfinityOneFlash** is a firmware installer specifically designed for the **Realme 9 5G SE (RMX3461)**. It provides a simple and user-friendly interface to flash different firmware versions, supporting both direct flashing and sideloading. This tool is ideal for both beginners and experienced users.

## Features
- **Multi-Firmware Support:**
  - **RealmeUI 4.0 F.18**
  - **RealmeUI 4.0 F.06**
- **Selective Flashing:**
  - Choose which firmware version to install during the process.
- **User-Friendly Interface:**
  - On-screen prompts and progress indicators guide you throughout the installation.
- **Safety First:**
  - Built-in checks and confirmations to prevent accidental flashing.
- **Multiple Installation Methods:**
  - Supports both direct flashing in custom recovery and ADB/LineageOS recovery sideloading.

## Prerequisites
Before beginning, make sure you have the following:

- **Device Preparation:**
  - Realme 9 5G SE (RMX3461) with an unlocked bootloader.
  - A custom recovery installed.
  - Device battery charged to at least 60%.
  - Backup your data to prevent any loss during flashing.

- **ADB Tools for Sideloading:**
  - A computer with **ADB and Fastboot** installed.
  - A USB cable to connect your phone to the computer.

## Installation Instructions

### Method 1: Direct Flash via Custom Recovery

1. **Download the ZIP File:**
   - Download `InfinityOneFlash_v0.1.0_Realme9_5G_SE_RMX3461.zip` and place it in your device’s external storage.

2. **Boot into Custom Recovery:**
   - Power off your device.
   - Hold **Volume Down + Power** to boot into Fastboot mode.
   - Navigate to **Recovery Mode** using the volume buttons, then press Power to select it.

3. **Install the ZIP File:**
   - In the recovery menu, tap **Install**.
   - Navigate to the downloaded ZIP file and select it.
   - Swipe to confirm the flash and follow the prompts to select your firmware.

4. **Reboot the Device:**
   - After installation, choose **Reboot Recovery**.
   - Optionally, remain in recovery mode to install additional firmware or ROMs.

### Method 2: ADB Sideload via LineageOS Recovery

1. **Download the ZIP File:**
   - Download `InfinityOneFlash_v0.1.0_Realme9_5G_SE_RMX3461.zip` and save it to your computer.

2. **Boot into LineageOS Recovery:**
   - Power off the device.
   - Hold **Volume Down + Power** to boot into Fastboot mode, then navigate to **Recovery Mode**.

3. **Enable ADB Sideload:**
   - In LineageOS Recovery, select **Apply Update** > **ADB Sideload**.

4. **Connect the Device:**
   - Connect your device to the computer with a USB cable.

5. **Open Command Prompt/Terminal:**
   - Open your terminal/command prompt as outlined above.

6. **Verify ADB Connection:**
   - Type:
     ```bash
     adb devices
     ```
   - Confirm that your device appears as **sideload**.

7. **Start Sideloading:**
   - Enter the following command:
     ```bash
     adb sideload /path/to/InfinityOneFlash_v0.1.0_Realme9_5G_SE_RMX3461.zip
     ```

8. **Wait for Completion:**
   - The sideload process will begin, and progress will appear on both your device and computer.

9. **Reboot the Device:**
   - After sideloading, go back and select **Reboot Recovery** in the advanced.
   - After your device boots into custom recovery, it’s advisable to remain in recovery mode to install the ROM or carry out any additional tasks.

## Compatibility
- **Device:** Realme 9 5G SE (RMX3461)
- **Supported Firmware Versions:**
  - RealmeUI 4.0 F.06
  - RealmeUI 4.0 F.18

## Warnings
- **Backup Important Data:**
  - Flashing firmware can result in data loss. Ensure you’ve backed up all important data.
- **Correct Firmware Selection:**
  - Flashing the wrong firmware can brick your device. Double-check your selections during installation.
- **Battery Level:**
  - Ensure your device has sufficient battery (at least 60%) to avoid interruptions.
- **Follow Instructions Carefully:**
  - Carefully follow each step to avoid issues with your device.

## Support and Contact
For updates, support, and community help, reach out via the following platforms:

- **Telegram Channel:** [Lazymeao Projects](https://t.me/LazymeaoProjects)
- **Telegram Community:** [Lazymeao Projects Discussion](https://t.me/LazymeaoProjectsDiscussion)
- **GitHub:** [lazymeao](https://github.com/lazymeao)

---

**Disclaimer:** This software is provided as-is, and the developers are not responsible for any damage caused to your device.

**Credits:**
- Developed by [@lazymeao](https://github.com/lazymeao)
- Tested by [@A-netrunner](https://github.com/A-netrunner)