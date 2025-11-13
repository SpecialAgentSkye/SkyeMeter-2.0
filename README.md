# SkyeMeter 2.0 - Custom Dalamud Repository

A modern DPS meter plugin for FFXIV that connects to IINACT to display real-time combat statistics.

## Features

- **Real-time DPS & HPS Tracking**: Live combat data with customizable refresh rates
- **IINACT Integration**: Seamless connection to IINACT for ACT data
- **Dual Tables**: Separate scrollable DPS and HPS meters
- **Pet Damage Merging**: Combine pet damage with owners
- **History Tracking**: Save and review past encounters
- **Accurate Healing**: Calculates actual healing done (excluding overhealing)
- **Customizable Interface**: Extensive visual customization options
- **Job Icons & Colors**: Distinctive visual styling for each job
- **Test Mode**: Preview with dummy data

## Installation

### Step 1: Add Custom Repository

1. Open Dalamud Settings in-game (`/xlsettings`)
2. Navigate to the **Experimental** tab
3. Scroll down to **Custom Plugin Repositories**
4. Paste this URL:
   ```
   https://raw.githubusercontent.com/SpecialAgentSkye/SkyeMeter-2.0/main/pluginmaster.json
   ```
5. Click the **+** button to add the repository
6. Click **Save and Close**

### Step 2: Install Plugin

1. Open the Plugin Installer (`/xlplugins`)
2. Search for **SkyeMeter 2.0** in the **Available Plugins** list
3. Click **Install**

### Step 3: Setup IINACT (Required)

SkyeMeter requires [IINACT](https://github.com/marzent/IINACT) to be running:

1. Download and install IINACT
2. Start IINACT before launching FFXIV
3. SkyeMeter will automatically connect when you log in

## Usage

- `/skye` - Toggle main window
- `/skye config` - Open configuration window
- `/skye connect` - Manually connect to IINACT
- `/skye disconnect` - Manually disconnect from IINACT

## Configuration

Access the configuration window with `/skye config` to customize:

- **Appearance**: Window size, opacity, colors, fonts
- **Tables**: Column visibility, DPS/HPS table settings
- **Bars**: Height, spacing, opacity, font size
- **Behavior**: Auto-hide, merge pets, refresh rate
- **Rows**: Maximum rows before scrolling (auto or manual)

## Requirements

- **FFXIV with Dalamud**: Make sure you're running the game with Dalamud
- **IINACT**: Must be running for combat data
- **Dalamud API Level**: 13

## Support

For issues, feature requests, or contributions:
- GitHub: [SkyeMeter-2.0](https://github.com/SpecialAgentSkye/SkyeMeter-2.0)

## License

AGPL-3.0-or-later
