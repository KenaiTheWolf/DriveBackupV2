# This is a customized version of DriveBackupV2 by MaxMaeder, please use MaxMaeder's version. https://github.com/MaxMaeder/DriveBackupV2
# I provide no support for this branch. It's for personal use, I just find using github as a storage medium to be conveient.


## What is this?
Have you ever lost your Minecraft world before?

Maybe your hard drive died. Maybe you used a server hosting service that terminated without warning. Maybe you just accidentally deleted it.

DriveBackupV2 is a plugin that aims to provide an extra layer of security to your data by backing it up remotely.

## Features
- Creates and/or uploads backups to Google Drive, OneDrive, or a remote (S)FTP server
- Can create a backup out of any files or folders on your Minecraft server
- Can include files and MySQL databases from external servers (such as a BungeeCord one!)
- Deletes backups locally and remotely if they exceed a specified amount
- Can automatically run backups at an interval or on a schedule
- And **much** more!

## Basic Setup
First, download the plugin [here](https://dev.bukkit.org/projects/drivebackupv2) and copy it to the `plugins` folder on your server. Then, restart your server. Finally, follow the instructions below for the backup method of your choice.

### Google Drive
Simply run `/drivebackup linkaccount googledrive` and follow the on-screen instructions.

### OneDrive
Simply run `/drivebackup linkaccount onedrive` and follow the on-screen instructions.

### Local
> Since **v1.3.0**

Change `local-keep-count` in the `config.yml` to the number of backups to keep locally. Set to `-1` to keep an unlimited amount of backups locally.

Once you've completed the above instructions, backups will run automatically every hour.

## Advanced Setup
Learn how to set up and use more advanced features in the [wiki](https://github.com/MaxMaeder/DriveBackupV2/wiki).

## Privacy Policy
Since we need to access your Google Drive and/or OneDrive data to back up your world, we are required to provide a Privacy Policy.
 
All of the data this plugin uploads and downloads from your Google Drive and/or OneDrive stays on your Minecraft server, so we never have access to it. This plugin physically cannot access any data in your Google Drive and/or OneDrive that is not related to backing up your Minecraft world backups. But don't take our word for it, all of this plugin's source code is available here!
