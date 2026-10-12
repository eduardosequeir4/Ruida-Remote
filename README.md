# Ruida Remote

**Android remote control for Ruida laser controllers**

Developed by Eduardo Sequeira.

Ruida Remote is an Android application for operating compatible Ruida laser controllers over a local Wi-Fi connection. It provides manual X/Y jogging and a press-and-hold laser pulse control.

## Features
- Connect to a compatible Ruida controller over UDP.
- Manual X+ / X− / Y+ / Y− movements, active only while pressing the button.
- Press-and-hold laser pulse, stopping when the button is released.
- Connection status and an optional technical log.
- Configurable controller IP, remote UDP port and connection timeout.

## Download and installation
1. Open the [Releases](https://github.com/eduardosequeir4/Ruida-Remote/releases) page.
2. Download the APK attached to the latest release (once published).
3. On your Android device, open the APK and allow installation from this source if Android requests permission.
4. Open **Ruida Remote**.

> No APK has been published here yet. A release will appear once a compiled APK has been uploaded.

## Connecting
1. Connect your Android device to the Wi-Fi network used by the Ruida controller.
2. In the app, confirm the controller IP (commonly `192.168.1.100` for the tested setup).
3. Confirm the UDP destination port (the tested setup uses `50207`).
4. Tap **Connect** and wait for the connection status.
5. Use the X/Y buttons only after verifying that the work area is clear.

The tested configuration uses local UDP source port `40207` and remote port `50207`. Other controllers and network setups may differ.

## Compatibility
Developed and tested with a Ruida RDC6442-series setup. Compatibility with other controllers, firmware versions and Android devices is not guaranteed.

## Safety
**Read [SAFETY.md](SAFETY.md) before operating the machine.** This app does not replace the physical emergency stop, safety interlocks, operator supervision or the manufacturer's operating procedures.

## Source code
This is a **binary distribution repository**. The application source code is not included or publicly licensed here. The absence of a source license does not grant permission to copy, modify or redistribute the source.

## Disclaimer
Independent project; not an official Ruida application and not affiliated with or endorsed by Ruida. Provided without warranty. Operate only with appropriate training and precautions.

**Developed by Eduardo Sequeira**
