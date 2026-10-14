# Agenda-Rec: User's Guide

> Agenda-Rec is **on hold**: it is an old project (2008), published as found.



## Downloads & Runtimes

Download the latest release from the [Releases page](https://github.com/RemusRigo/Agenda-Rec-Delphi/releases).

|Folder|Architecture|Required Runtime|
|-|-|-|
|`Win32`|32-bit|none (native Windows app)|



## Install

Agenda-Rec is portable: there is no installer.

1. Copy `Agenda.exe` (and the `Language` folder, if the release has one) to a folder where you have write access,
   for example `D:\My Apps\Agenda\`.
2. Double-click `Agenda.exe`. It creates the `Contacts`, `Language` and `Temp` folders next to itself.



## Usage

* The main window lists the contacts. Use the toolbar to add a contact, edit the selected one, delete it, or open the **Alarm**.
* **Options** → **Language**: choose the language of the user interface.

|Folder (next to `Agenda.exe`)|Content|
|-|-|
|`Contacts\`|One compressed `.pk` file per contact|
|`Language\`|Language files (`.ini`)|
|`Temp\`|Used while a contact is read; emptied automatically|



## Uninstall

Delete the folder (copy the `Contacts` folder first if you want to keep your contacts).
