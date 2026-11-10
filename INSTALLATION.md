# GREENIX — Windows Installation Guide

This guide covers the general setup flow. Always follow any additional instructions included with the specific GREENIX release you downloaded.

## 1. Before you begin

Make sure you have:
- A Windows PC.
- A PS5 console connected to your network.
- **Chiaki-NG** installed and configured to connect to your PS5.
- The official GREENIX installer downloaded from the [GREENIX Releases page](https://github.com/BRKENZI/GREENIX-Downloads/releases).

Only use installer files attached to official releases in this repository.

## 2. Install GREENIX

1. Close GREENIX and Chiaki-NG if either is running.
2. Run the official GREENIX setup file.
3. Follow the installer prompts.
4. Launch GREENIX from the installed shortcut.

If Windows displays a security warning, verify that the file came from the official GREENIX release before deciding whether to continue. Do not bypass warnings for files from unknown sources.

## 3. Configure Chiaki-NG

1. Install and open Chiaki-NG.
2. Complete Chiaki-NG's normal PS5 pairing and connection setup.
3. Confirm that Chiaki-NG can connect to your PS5 before troubleshooting GREENIX.

Chiaki-NG is a separate application; it is not replaced by GREENIX.

## 4. DualSense and HidHide configuration

If your setup uses HidHide, the following configuration is important:

1. Close GREENIX and Chiaki-NG.
2. Open **HidHide Configuration Client**.
3. Under **Applications**, add the installed `GREENIX.exe`.
4. Under **Devices**, hide only the physical Sony DualSense controller.
5. Do **not** hide the Virtual DS4 device.
6. Enable device hiding.
7. Start GREENIX first.
8. Start Chiaki-NG after GREENIX is running.

The intended input path is:

**Physical DualSense → GREENIX → Virtual DS4 → Chiaki-NG → PS5**

Do not hide every controller device. Hiding the virtual device can prevent the controller input from reaching Chiaki-NG.

## 5. Troubleshooting

### Controller is not detected
- Close GREENIX and Chiaki-NG.
- Recheck that the physical DualSense is the device hidden in HidHide.
- Confirm that GREENIX.exe is listed under HidHide Applications.
- Confirm that Virtual DS4 is not hidden.
- Start GREENIX before Chiaki-NG.

### Chiaki-NG does not connect
- Confirm that Chiaki-NG can connect to the PS5 without GREENIX.
- Check your network connection and PS5 remote-play settings.
- Consult the official Chiaki-NG documentation for pairing and connection issues.

### Still having problems?
Open an issue in the [GREENIX-Downloads repository](https://github.com/BRKENZI/GREENIX-Downloads/issues). Include your GREENIX version, Windows version, and a description of the issue. Do not include passwords, license keys, or account credentials.

---

*This guide is general documentation. Driver requirements and installer behavior can vary by release; check the release notes for the exact version you installed.*
