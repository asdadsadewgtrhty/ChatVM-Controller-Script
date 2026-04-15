# UltraBot - YouTube Live Chat Controller

## ⚠️ IMPORTANT NOTICE

This repository does **not** contain the source code.

Only the compiled executable (.exe) is provided. The source code is kept private.

Windows Defender may flag this file as a virus. This is a **false positive** caused by PyArmor obfuscation, which is used to protect the source code.

**If you don't trust the .exe file, just delete the .exe file.**

## How to Use

1. **Extract the RAR file first** (Do not run directly from inside the RAR)

2. Double-click `UltraBot 7.3.2 by Nexora.exe` to run the program.

3. The bot will ask you two questions:
   - Enter YouTube Video ID:  
     Paste the Video ID of your YouTube live stream.
   - Enter VirtualBox VM Name:  
     Type the exact name of your VirtualBox virtual machine.

4. After entering both, press Enter.

✅ The bot will start automatically and connect to your live stream.

## Features

- Control your VM using YouTube chat commands
- Dynamic voting system for restart and revert
- Mouse & keyboard control
- Ban system with voting
- Admin commands via console
- Auto watchdog (auto restart when VM crashes)

## Commands

Most commands are used directly in your YouTube live chat with `!` prefix.

## Admin Commands (Console Only)

- `!startvm`
- `!restart`
- `!revert`
- `!speak <text>`
- `!clearvotes`
- `!exit`

## Note

- Do not close the console window while the bot is running.
- Make sure VirtualBox is installed and your VM name is correct.
- Only the streamer (you) can use admin commands in the console.

## ALL COMMANDS:

🔄 System Control
!restartvm → Requires ALL active users to vote (full majority). Restarts the VM.
Example: !restartvm

!revert → Requires ALL active users to vote (full majority). Restores the latest snapshot.
Example: !revert

⚡ Power & Window
!startvm 
Start the VM (cooldown enforced).
Example: !startvm

🖱️ Mouse Control
!move / !mouse / !mv → Move cursor (dx dy or direction).
Example: !move 50 -20 / !move up

!abs / !cursor / !moveabs → Move cursor absolute (scaled).
Example: !abs 800 400

!drag / !dragrel → Drag relative (optional button).
Example: !drag 100 50

!dragabs / !drag_absolute → Drag absolute (scaled).
Example: !dragabs right 900 500

!click / !lclick → Left click [count].
Example: !click 2

!rclick / !rightclick → Right click [count].
Example: !rclick

!mclick / !middleclick → Middle click [count].
Example: !mclick

!scroll / !wheel → Scroll delta.
Example: !scroll -120

⌨️ Keyboard Control
!type → Type text.
Example: !type hello world

!typeenter / !send → Type then Enter.
Example: !send hello world

!key / !press → Press key [duration].
Example: !key esc

!combo → Press keys together.
Example: !combo ctrl+shift+esc

!hold → Hold key.
Example: !hold tab

!release → Release key.
Example: !release tab

🕒 Timing & Display
!wait → Delay next command.
Example: !wait 1.5

---

**Made with ❤️ by @Nexora-WN**
