# ReaCustomMenu

**Create persistent custom menus in REAPER's main menu bar.**

> **Windows only**

ReaCustomMenu is a native REAPER extension that allows you to create one or more custom menus directly in REAPER's main menu bar.

Menus are defined in a simple XML configuration file.

## Features

* Create multiple top-level menus
* Create nested submenus
* Add native REAPER actions
* Add ReaScripts
* Add SWS commands
* Add separators
* Assign custom display names to commands and scripts
* No dependency on REAPER's Customize Menus/Toolbars system

## Installation

1. Copy `reaper_ReaCustomMenu.dll` to REAPER's `UserPlugins` folder.
2. Copy `ReaCustomMenu.xml` to REAPER's resource folder.
3. Restart REAPER.

The supplied XML file is intentionally minimal:

```xml
<?xml version="1.0" encoding="utf-8"?>
<menus></menus>
```

The user can then add their own menus and commands.

## Download

The latest version is available on the [Releases](../../releases) page.

## Documentation

See the included user manuals for detailed installation and configuration instructions:

* French manual
* English manual

## Requirements

* REAPER
* Windows
* 64-bit Windows version

## License

See the `LICENSE` file.
