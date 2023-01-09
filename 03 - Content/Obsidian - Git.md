
---
creation date: January 09 2023
last modifed: January 09 2023
aliases: []
---
Primary Categories: [[01 - Administration]]
Secondary Categories:  [[02 - Obsidian]]
Links: [[Obsidian Plugins]] - [[Obsidian - Getting Started]]

# [[Obsidian - Git]]
***
## Overview
Simple plugin that allows you to backup your [Obsidian](https://obsidian.md) vault to a remote git repository (e.g. private repo on GitHub). 

This plugin assumes you have existing git repository initialized locally and credentials are setup. This is the mechanism by which all your notes are sync'd to the Offpipe repository and shared between consultants.

## Installation
Obsidian-Git is a registered Obsidian Community Plugin and can be installed directly from `Settings > Community Plugins > Browse > Obsidian Git`

## Settings
1. Enable `Obsidian Git-` under `Settings > Community Plugins > Obsidian Git`
2. Navigate to `Settings > Obsidian Git`
3. Edit the following settings
	1. *Vault Backup Interval*: 60
	2. *Auto Pull Interval*: 10
	3. *Commit message*: FLast {{date}}
	4. *Date placeholder*: MM-DD-YYYY HH:mm:ss
	5. *Pull changes before push*: Enabled (default)

## Commands
All associated commands specific to Obsidian git can be reviewed from the Command Pallete (**CTRL + P** to open)

![[obsidian-git-cp.png]]
***
These commands can be added to hotkey combinations which greatly simply the addons use.

![[obsidian git settings.png]]

***
## Resources:

| Hyperlink | Info |
| --------- | ---- |
| [Obsidian Git Github Repo](https://github.com/denolehov/obsidian-git) | Git Repo | 

creation date: January 09 2023
last modifed: January 09 2023