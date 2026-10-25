# Bladeglass Meter

A combat meter for Aion 2 (EU client). For every boss fight it shows each party member's damage, healing
(actual heal, overheal, HPS, heal per skill), shields, damage taken, dodges and deaths, in a small overlay
over the game. It also reminds you of the Shugo event and of field boss respawns, with live boss timers.

Bladeglass was called *Drays Aion 2 Meter* until 0.5.0. Installed copies update to the new name by themselves,
and keep their history and settings.

It only reads the game's network traffic, the way Wireshark does. It never touches the game, its files
or its memory, and never sends anything to the game server.

## Install

1. Install **Npcap** from [npcap.com](https://npcap.com/#download). In its installer, leave
   "Restrict Npcap driver's access to Administrators only" **unchecked**.
2. Download `BladeglassMeter_<version>_setup.exe` from the
   [latest release](https://github.com/DraysGR/bladeglass-meter/releases/latest) and run it.
   Windows may say "Windows protected your PC": click **More info**, then **Run anyway**.
3. Play Aion 2 in **borderless** or **windowed** mode (an overlay can't draw over exclusive fullscreen),
   and start **Bladeglass Meter** from the Start menu.

The meter checks for updates when it starts. You can also check in **Settings > Updates**.

## Use

- The meter starts at the first hit on a boss. Trash fights are not recorded.
- **Insert** turns click-through on and off, so the overlay never takes your clicks during a fight.
  **Page Down** (or the clock button) shows the boss timers. You can change the keys in Settings.
- **Field boss reminders:** open the game's Field Boss panel once (Exploration > Field Boss), then tick the
  bosses you want in **Settings > Field bosses**. Times are shared between meters on the same server, so one
  player opening the panel is enough for everyone.
- **History** has your last 50 runs; **Export image** saves a fight's stats as a picture.

Not affiliated with NCSOFT. Third-party tools may be against the game's terms; use it at your own risk.
