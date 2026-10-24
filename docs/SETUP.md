# MotionPad setup (v1.0)

## Real PlayStation 2

1. Use a PS2 configured to launch homebrew with Free McBoot.
2. Connect the Android phone with a **USB data cable**.
3. Enable **USB tethering** in Android settings (not ordinary file-transfer mode).
4. Start `MotionPad.elf` via the PS2 homebrew launcher before launching a supported game.
5. For the currently tested setup, keep a physical PS2 controller connected to **controller Port 1**, not Port 2.
6. Select the desired controls in MotionPad Android and test steering, throttle, and braking in-game.

The current hardware-confirmed game list is in [COMPATIBILITY.md](COMPATIBILITY.md). Different consoles, games, regions, and input settings may behave differently; please report any failures.

## Windows / PCSX2

1. Install the **MotionPad Windows Receiver** from the project website.
2. Connect your Android phone to the PC using a USB data cable.
3. Enable **USB tethering** in Android settings.
4. Open MotionPad Receiver and then MotionPad Android.
5. Bind the Receiver's virtual controller through your game's or PCSX2's controller configuration.

If a game does not detect the virtual controller, report the game version, controller backend, Windows version, and whether Windows detects the virtual device.

**Official downloads and updates:** https://motionpad.pages.dev/
