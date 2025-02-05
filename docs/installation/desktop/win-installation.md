---
title: Windows Installation
linktitle: Windows
weight: 20
---

Headlamp is available for Windows as a direct download from its [releases page](https://github.com/kinvolk/headlamp/releases) on Github (.exe file) and from the [Chocolatey](https://chocolatey.org/) package registry.

## Install via Chocolatey

To install Headlamp from the Chocolatey registry, first install the choco command by following
its [official instructions](https://chocolatey.org/install#generic).
After `choco` is available, [install Headlamp](https://community.chocolatey.org/packages/headlamp#install) by running the following command:
```powershell
choco install headlamp
```

### Upgrading

To upgrade Headlamp when its installed with Chocolatey, run the command:
```powershell
choco upgrade headlamp
```

## Install via Github Releases

To install Headlamp from its official installer, first download the _.exe_ file for the [latest release](https://github.com/headlamp-k8s/headlamp/releases/latest)'s assets section (located at the bottom of the section). Then double click the file and follow the installer's instructions.

### Upgrading

Until we have an automatic update, to upgrade Headlamp when it's installed directly from its
installer, you have to download the new version of the installer and re-install it.