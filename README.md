# VolCtrl
A small AutoHotKey script to enable control of system volume without needing explorer.exe running in the background to process volume requests


## Usage
Run the VolCtrl.ahk AutoHotKey script or download a compiled executable from the Releases section


## How It Works
This script utilises the SoundSet functionality of AutoHotKey to adjust the volume while explorer.exe is not running.  AutoHotKey listens for a special key (VolUp, VolDown, or Mute) and sends a command to SoundSet to adjust the Master Volume Up or Down by 2, or to Mute the output.

The special key codes utilised are:
* SC130 - Volume Up
* SC12E - Volume Down
* SC120 - Mute

(These are the general Volume Up / Volume Down / Mute keys, but may vary if an OEM has decided to use different keys alongside a system driver.)
