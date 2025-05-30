---
layout: default
title: Vortex
nav_order: 2
---

# Vortex Installation Guide

## Pre-Installation Cleanup
**If you've never modded Cyberpunk before, skip to Installation.**

### 1. Clean Vortex
1. Go to Settings → V2077 Settings
2. Ensure "Automatically convert old style 'archive' mods to REDmods on install" is OFF
3. Go to Settings → Mods  
4. Set deployment method to "Hardlink Deployment"
5. Remove ALL old mods from the Mods section
6. Check ALL Cyberpunk profiles for leftover mods

### 2. Clean Game Files
1. Navigate to %appdata%
2. Delete "CD Projekt Red" folder
3. Delete "Red Engine" folder
4. In your Cyberpunk 2077 directory, delete all folders EXCEPT "archive"
5. In "Cyberpunk 2077/archive/pc/" delete the "mod" folder
6. Verify game files through Steam/GOG/Epic

## Installation

### 1. Install Vortex (if necessary)
Download and install Vortex from Nexus Mods.

### 2. Configure Cyberpunk 2077 in Vortex
1. Open Vortex and click "Select a game to manage"
2. Find Cyberpunk 2077 and click "Manage"
3. Click "Download" when prompted
4. After restart, click "Continue" on the "Game not discovered" popup
5. Select your Cyberpunk 2077 installation directory
6. Click "Ignore" on the "REDmod DLC missing" popup
7. Go to Settings → V2077 Settings
8. Ensure "Automatically convert old style 'archive' mods to REDmods on install" is OFF
9. Go to Settings → Mods
10. Set deployment method to "Hardlink Deployment"

### 3. Install Collection
1. Click "Add to Vortex" on the collection page
2. Click "Install Now" when prompted
3. For Premium users: Installation is automatic
4. For non-Premium users: Click "Download" then "Slow Download" for each mod
5. Once complete, click the Play button in top left of Vortex

## Notes
- System Requirements: Same as base Cyberpunk 2077
- If hardlink deployment fails, your drive may need reformatting (FAT/exFAT drives don't support hardlinks)
