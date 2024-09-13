# Multi-User Enabler Magisk Module

This Magisk module enables Android's multi-user UI and sets the maximum number of users to 10.

## Features

- Enables the multi-user interface on Android devices.
- Sets the maximum number of users to 10.
- Appends properties to `/system/build.prop` without replacing existing content.

## Requirements

- Rooted Android device with Magisk installed.
- Compatible with Android versions that support multi-user features.

## Installation

1. Download the module from the [Releases](https://github.com/unreliablecode/multiuser-enabler/releases) section or clone the repository.
2. Open the Magisk Manager app.
3. Tap on the "Modules" section.
4. Select "Install from storage" and choose the downloaded zip file.
5. Reboot your device.

## Usage

After installation, the following properties are appended to your `/system/build.prop`:

```
fw.show_multiuserui=1
fw.max_users=10
```

This enables the multi-user feature and sets the maximum number of users to 10.
## Developer

- **Owner:** unreliablecode
- **GitHub:** [unreliablecode](https://github.com/unreliablecode)
