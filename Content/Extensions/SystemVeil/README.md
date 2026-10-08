# System Veil - Hacknet Extension

A mysterious Hacknet extension featuring the enigmatic character **VEIL** and three challenging missions.

## Overview

System Veil introduces a new contractor named **VEIL** who tasks players with three sequential missions:

1. **Data Retrieval** - Download `y33_relay.log` from Y-33 Relay and upload it to VEIL DROPBOX
2. **System Purge** - Connect to F0xtr0t's PC and delete `x-server.sys`
3. **Heart Restart** - Restart the PortHack.Heart server from its remnants

## Installation

1. Copy the `SystemVeil` folder to your Hacknet Extensions directory
2. Launch Hacknet
3. The VEIL contractor will appear in your contractor list
4. Accept missions from VEIL to begin

## Mission Details

### Mission 1: VEIL: Data Retrieval
- **Difficulty**: 2/5
- **Reward**: $5,000 + 100 Rep
- **Objective**: Connect to Y-33 Relay, download `y33_relay.log`, and upload it to VEIL DROPBOX on port 8000
- **Hint**: The upload server doesn't require authentication

### Mission 2: VEIL: System Purge  
- **Difficulty**: 3/5
- **Reward**: $7,500 + 150 Rep
- **Objective**: Connect to F0xtr0t's PC, bypass security, and delete `x-server.sys`
- **Hint**: Check for weaknesses on port 1337

### Mission 3: VEIL: Heart Restart
- **Difficulty**: 4/5
- **Reward**: $10,000 + 200 Rep
- **Objective**: Connect to PortHack.Heart Remnants and restart the server
- **Hint**: Execute `porthack_heart.exe --restart` or run `restart_script.sh`

## Nodes

- **Y-33 Relay** (192.168.1.33) - Relay node with the critical log file
- **VEIL DROPBOX** (10.0.0.1) - Upload server for mission 1
- **F0xtr0t's PC** (172.16.0.40) - Contains x-server.sys to be deleted
- **PortHack.Heart Remnants** (192.168.0.100) - Offline server needing restart

## Credits

Created by Zibby32EXE

## Version

1.0.0 - Initial Release
