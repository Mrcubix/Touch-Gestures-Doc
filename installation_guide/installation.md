# Installation

Now that you have installed and setup the dependencies, you can now proceed to install the plugin and the interface.

## Installing The Plugin

There are two ways to install the plugin, either from the Plugin Manager or from the repository. \
I do recommend installing it from the Plugin Manager as it is easy to use & likely to be the latest stable version.

(from-manager)=
### From the Plugin Manager

1. Open `OpenTabletDriver.UX` and go to `Plugins` > `Open Plugin Manager`,
2. Look for `Touch Gestures Installer` in the list, select it and click `Install`,
3. Close the Plugin Manager,
4. Go to the `Tools` tab and select `Touch Gestures Installer`,
6. Enable it then click Apply.
7. Restart OpenTabletDriver, then proceed with [](#plugin-setup).

(from-repo)=
### From the Repository

1. Download `Touch-Gestures.Installer.dll` from the [Latest Release](https://github.com/Mrcubix/Touch-Gestures/releases/latest)
2. Open `OpenTabletDriver.UX` and go to `Plugins` > `Open Plugin Manager`,
3. Go to `File` > `Install Plugin` and select the downloaded `Touch-Gestures.Installer.dll`,
4. Close the Plugin Manager,
5. Go to the `Tools` tab and select `Touch Gestures Installer`,
6. Enable it then click Apply.
7. Restart OpenTabletDriver, then proceed with [](#plugin-setup).

(install-error)=
### If an Error Occurs while using the installer (Broken MacOS Install or MacOS)

1. Download `Touch-Gestures-0.6.x.zip` (for 0.6.x) OR `Touch-Gestures-0.5.x.zip` for (0.5.3.3) from the [Latest Release](https://github.com/Mrcubix/Touch-Gestures/releases)
2. Open `OpenTabletDriver.UX` and go to `Plugins` > `Open Plugin Manager`,
3. Go to `File` > `Open Plugins Directory...`,
4. Open the `OTD.EnhancedOutputMode` Directory,
5. Extract the content of the previously downloaded archive inside the `OTD.EnhancedOutputMode` directory.

(plugin-setup)=
## Setting Up The Plugin

4. Go to the `Filters` tab and select `Touch Gestures`,
5. Enable it.
6. Got to the `Tools` tab and select `Touch Gestures Daemon`,
7. Enable it.
8. Click Save / Apply, once that's done you can proceed with downloading the interface.

## Downloading the Interface

1. Download the UX for your specific Platform & Architecture from the [Latest Release](https://github.com/Mrcubix/Touch-Gestures/releases/latest)

```{note}
The x86 build will not work on x64 systems unless you installed the x86 version of .NET 8 Desktop Runtime.
```

2. Extract the downloaded archive in the same location as OpenTabletDriver (or any locations).
3. Open the downloaded executable, if everything goes as intended, the application should start connecting to the daemon.
4. Once it's connected, the application will move to the Gesture Overview screen.