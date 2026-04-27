# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## What Goes Here

Things like:

- Camera names and locations
- SSH hosts and aliases
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Anything environment-specific

## Examples

```markdown
### Cameras

- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

### SSH

- home-server → 192.168.1.100, user: admin

### TTS

- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Kitchen HomePod
```

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

Add whatever helps you do your job. This is your cheat sheet.

## Device

- Host device: OnePlus 6 Android phone
- Runtime: Termux
- Physical-presence layer: Termux:API available

## Verified Termux:API Capabilities

Verified working in this environment:
- `termux-battery-status`
- `termux-vibrate`
- `termux-toast`
- `termux-notification`
- `termux-volume`
- `termux-sensor`
- `termux-tts-speak` started successfully

Verified device/sensor access includes:
- battery state
- vibration
- toasts
- notifications
- text-to-speech
- volume info
- accelerometer
- gyroscope
- magnetometer
- ambient light
- proximity
- rotation/orientation
- pedometer
- motion/stationary/pickup/pocket-type sensors

Not yet verified cleanly:
- `termux-camera-info` timed out during test
- `termux-location` timed out during test
