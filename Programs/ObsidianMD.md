# Obsidian Markdown

## FrameWorks
Electron; therefore Chromium

## Details

A program that allows you to write files in markdown live, can work as a locally stored wiki and also has a very nice graphing feature

## Website
https://obsidian.md/


## Tests

|*i*  |Operating System   | Version   | Bits | Test Date      | Extenders      | Installs | Runs | Runs w/ WorkArounds/Patches | Rating     | Bugs                 | Tester        |
|-----|-------------------|-----------|------|----------------|----------------|----------|------|-----------------------------|------------|----------------------|---------------|
|0    |Windows 7 SP1 x64  | v1.2.8    | x64  | May 23, 2023   | None           | Yes      | No   | Yes                         | Perfect    | No                   | Johnny-Freedom|

## Bugs
#### Occurs in Test [0]
Packaged electron version wont run on Windows 7

## Work-arounds, patches, ET CETERA
#### Works in Test [0]
Download the last version of electron that runs on 7 v22.3.9 (https://github.com/electron/electron/releases/download/v22.3.9/electron-v22.3.9-win32-x64.zip)

In Obsidian's install directory, C:\Users\%user%\AppData\Local\Obsidian, delete everything but the resources subdirectory and uninstall_obsidian.exe

extract everything out of the afordownloaded zip into here, except for the resources folder

(Optional) Create a shortcut from electron.exe and call it Obsidian, and, right click, and click properties, click change icon and browse to unistall_obsidian.exe and use its icon

Pin that shortcut to your startmenu, taskbar, desktop,etc where ever you want to run obsidian from.
