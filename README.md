# Drays Aion 2 Meter

A heal meter for Aion 2 (EU client). For every boss fight it shows each party member's healing
(actual heal, overheal, HPS, heal per skill), shields and damage, in a small overlay over the game.

It only reads the game's network traffic, the way Wireshark does. It never touches the game, its files
or its memory, and never sends anything to the game server.

## Install

1. Install **Npcap** from [npcap.com](https://npcap.com/#download). In its installer, leave
   "Restrict Npcap driver's access to Administrators only" **unchecked**.
2. Download `DraysAion2Meter_<version>_setup.exe` from the
   [latest release](https://github.com/DraysGR/drays-aion2-meter/releases/latest) and run it.
   Windows may say "Windows protected your PC": click **More info**, then **Run anyway**.
3. Play Aion 2 in **borderless** or **windowed** mode (an overlay can't draw over exclusive fullscreen),
   and start **Drays Aion 2 Meter** from the Start menu.

The meter checks for updates when it starts. You can also check in **Settings > Updates**.

## Use

- The meter starts at the first hit on a boss. Trash fights are not recorded.
- **Insert** turns click-through on and off, so the overlay never takes your clicks during a fight.
  You can change the keys in Settings.
- **History** has your last 50 runs; **Export image** saves a fight's stats as a picture.

Not affiliated with NCSOFT. Third-party tools may be against the game's terms; use it at your own risk.
