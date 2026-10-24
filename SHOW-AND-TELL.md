# MotionPad v1.0 — Android motion steering on a real PS2 over USB tethering

Hey everyone!

I've recently developed **MotionPad v1.0**, a project that turns an Android smartphone into a motion-steering wheel and full controller for a **real PlayStation 2**, with support for **Windows and PCSX2** through a separate Receiver.

What started as an experiment has become three working v1.0 components:

- **Android app:** tilt steering, touchscreen throttle/braking, and full on-screen controller layouts.
- **PS2 ELF:** a Free McBoot-compatible program based on Open PS2 Loader (OPL), communicating with the phone via USB tethering.
- **Windows Receiver:** virtual controller input for Windows games and PCSX2, with a dedicated installer.

On a real PS2 I've confirmed working controls in **Gran Turismo 3**, **Gran Turismo 4**, **Gran Turismo 4 Spec II**, **Tourist Trophy**, and **Need for Speed: Carbon**.

I've recorded a demo showing the phone controlling the game on actual hardware—**no emulator** in the PS2 footage.

**Demo:** https://pub-5acd44ee2d36470481e5e0bc8d19c58d.r2.dev/VID_20261023_223106.mp4

**Project:** https://motionpad.pages.dev/

The PS2 ELF and Windows Receiver are free. I'm looking for PS2 owners and PCSX2 users to help test additional games and report compatibility problems. What would you like to see supported next?
