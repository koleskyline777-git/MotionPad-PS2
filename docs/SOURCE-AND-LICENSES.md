# MotionPad source-code and license notes

MotionPad consists of separate components with different code ownership and distribution plans:

| Component | Source publication |
| --- | --- |
| MotionPad PS2 ELF | Planned public source, derived in part from Open PS2 Loader (OPL) |
| MotionPad Android | Private / proprietary source |
| MotionPad Windows Receiver | Private / proprietary source |
| Website | Hosted separately on Cloudflare Pages |

## Open PS2 Loader attribution

Open PS2 Loader (OPL): https://github.com/ps2homebrew/Open-PS2-Loader

The upstream project states that OPL is licensed under the **Academic Free License version 3.0 (AFL-3.0)**. It includes its own `LICENSE` and `CREDITS` files. When the actual MotionPad ELF source is added, include the applicable upstream copyright notices, credit files, modification notices, and all licenses for third-party components present in that fork.

**Do not treat this documentation-only starter repository as an audited source distribution.** Neither a complete source tree nor a final license manifest for MotionPad's custom PS2 changes has been supplied here. Before publishing the PS2 sources, review which upstream code and other dependencies they contain.

No source for the Android app or Windows Receiver should be committed to this public PS2 repository.
