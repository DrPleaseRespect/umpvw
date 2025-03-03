# umpvw

umpvw replicates mpv's macOS single-instance behavior on Windows.

It is a wrapper for mpv that uses the player's JSON IPC capabilities, that are used to replace the currently playing file. 

It also handles selecting multiple items in File Explorer and trying to play them - to handle this, it does IPC with itself. Files are launched in alphabetical order, as there isn't really a way to predict what order things will land in. 

## DrPleaseRespect's Modifications
- Added a config key to specify mpv.exe's path (as seen on my [MPV Config](https://github.com/DrPleaseRespect/DrPleaseRespect-MPV-Config/tree/main/umpmv))

## Requirements

.NET Framework, whatever the latest one is ¯\\\_(ツ)_/¯

## File associations and the compiled executable

Use a fork of the mpv-install script by SilverEzhik: https://github.com/SilverEzhik/mpv-install

A compiled version is also available in my [MPV Config](https://github.com/DrPleaseRespect/DrPleaseRespect-MPV-Config/tree/main/umpmv)

## Fix 15 item selection limit

Follow this guide: https://support.microsoft.com/help/2022295/
