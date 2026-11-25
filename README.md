# GyroPad

**Motion is your controller.** Turn an Android phone into a customizable, motion-enabled game controller for your Windows PC. The PC sees a virtual Xbox 360 controller, and the phone's gyro can aim for you.

> Early preview (v0.1.0). Source code will be published here later.

## Download

Get both files from the [latest release](../../releases/latest):

| File | For |
|---|---|
| `GyroPad-Setup-0.1.0.exe` | Windows 10/11 PC (64-bit). Installs the PC companion. |
| `GyroPad-0.1.0.apk` | Android 8.0 or newer. The controller app. |

## Set up

1. Install the PC companion and open **GyroPad**. If asked, install the free ViGEmBus driver (it provides the virtual Xbox controller).
2. Put the phone and PC on the same Wi-Fi network.
3. On the PC, press **Pair a new phone**. On the phone, open GyroPad, pick your PC and approve the request on the PC.
4. Tap your PC in the list. The controller appears (landscape).

Everything stays on your own network: no account, no internet connection needed.

## Notes

- The Windows installer is not code-signed yet, so Windows SmartScreen may warn: choose **More info → Run anyway**.
- The installer adds a narrow Windows Firewall rule (this program, UDP port 26760, private networks only) and removes it when you uninstall.
- Licensed under Apache-2.0.
