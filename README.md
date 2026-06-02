# Mods Guide

This repository is the shared mod pack for our server. The goal is simple: everyone uses the same mod files, and when we update them here, you can pull the latest changes instead of hunting down and installing mods one by one.

If you are new to modded Minecraft, don't worry. Follow the steps below and you should be fine.

## What this repo is for

- Keeps all of our mod `.jar` files in one place.
- Makes updates easier by letting you download the newest version with a `git pull`.
- Helps everyone stay on the same mod list so the game works the same for all players.

## What you need before starting

- Minecraft installed.
- The Fabric mod loader installed.
- A launcher you are comfortable with, such as the official Minecraft Launcher, Prism Launcher, or Modrinth App.
- This repository downloaded to your computer.

## First-time setup

1. Download this repo or clone it with Git.
2. Open the folder that contains the mod files.
3. Find your Minecraft instance or `.minecraft` folder.
4. Open the `mods` folder inside that instance.
5. Copy all of the `.jar` files from this repo into that `mods` folder.
6. Launch Minecraft using the Fabric profile.

If you are using a launcher with separate instances, make sure you copy the files into the correct instance, not into a random folder.

## How to update mods later

When we add, remove, or update mods in this repository, updating on your side should be easy.

If you cloned the repo with Git:

1. Open a terminal in this folder.
2. Run `git pull`.
3. Copy any changed `.jar` files into your Minecraft `mods` folder again.
4. Start the game.

If you downloaded the repo as a ZIP:

1. Download the newest version of the repo.
2. Replace the old mod files with the new ones.
3. Start the game.

## Important notes

- Do not mix old and new mod files if a mod was updated or removed.
- If the game crashes after an update, remove the old mod file first and then try again.
- Everyone joining the server should use the same mod pack version.
- Some mods may require the same Minecraft version and the same Fabric version as the server.

## Simple troubleshooting

- Game will not launch: check that Fabric is installed and that you copied the files into the correct `mods` folder.
- Game says a mod is missing: make sure you pulled the latest repo changes and copied every updated file.
- Game crashes on startup: one mod may not match your Minecraft version, or an old file may still be in the folder.
- Server connection fails: your mod list may be different from the server's mod list.

## For the least experienced users

If this feels confusing, just remember this one rule: whenever the repo changes, pull the latest version and replace the old mod files with the new ones.

That is the whole idea behind this repo.

## File location

All mod files live in the root of this repository as `.jar` files. That is the set you copy into your Minecraft `mods` folder.
