# XJack Mod - M5StickC Plus2

A specialized screensaver project featuring **10 psychological hacker scenarios**, including the classic XJack "The Shining" typewriter effect, plus custom programmer-themed modes, the **Xtreme Hack** psychological thriller scenes, and the revolutionary **Crash Grammar** system failure generator.

## Features

### Mode 1: Original XJack
- Classic "All work and no play makes Jack a dull boy" typewriter effect
- Authentic glitch effects and psychological tension
- Red screen flickers for atmosphere
- Typewriter key strike animations

### Mode 2: Back Room (Custom)
- Programming-themed phrases with poetic darkness
- Different visual style with green/blue glitches
- Matrix-style code rain effects
- Custom phrases include:
  - "The stench of death is all around me."
  - "Been beaten and bitten by memories unkind."
  - Lyrics from Jesus Hooligan on Youtube "Back Room"


### Mode 3: Dogs & Motorbikes
 -Lyrics from Jesus Hooligan on Youtube "I like dogs motorbikes and 3 people"
 -You should check him out. 
 

### Mode 4: System Error
- Cascading system failure simulation
- Multi-phase error progression (Warning → Critical → Cascade → Meltdown)
- Color-coded error levels with visual effects
- Authentic system crash sequence

### Mode 5: Symbol Storm
- ASCII art chaos with symbol flooding
- Multiple character sets (Greek, mathematical, box-drawing)
- Typing effect builds to full screen
- Symbol cycling and randomization

### Mode 6: Terminal Hacker
- Realistic hacker session simulation
- Authentic terminal commands and code compilation
- Matrix rain execution phase
- Progressive typing with syntax highlighting

### Mode 7: Hacked Terminal
- Cyber intrusion scenario
- Multi-phase hack progression
- Security breach simulation with visual corruption
- Escalating system compromise effects

### Mode 8: **XTREME HACK** ⭐
**7 Psychological Hacker Scenarios:**

1. **Filesystem Autopsy** - System analyzing corruption with creeping data loss
2. **Code Patch Disaster** - Live backdoor injection gone horribly wrong  
3. **Encryption Trap** - Files locked forever, keys destroyed remotely
4. **Mind Leak** - System consciousness bleeding through, questioning reality
5. **Reality Glitch** - Documentation rewriting itself in real-time
6. **Screensaver Debug** - Meta self-awareness horror, trapped in display loop
7. **Build From Hell** - Recursive compiler nightmare that won't stop

Each scene features:
- **Authentic terminal typography** and realistic command sequences
- **Psychological tension building** through typing speed and content
- **Color-coded warnings** (green → yellow → red → magenta)
- **Visual corruption effects** matching scene intensity
- **30-second cycles** with automatic scene progression

### Mode 9: Kernel Panic
- Humanized system failure with dramatic pacing
- Recovery attempts that ultimately fail
- Psychological transition from technical to human
- Screen freeze simulation with blinking cursor

### Mode 10: **CRASH GRAMMAR** ⭐ (NEW!)
**Procedural System Failure Generator** - The most sophisticated screensaver yet!

**Core Features:**
- **7 Distinct Roles**: SYS, KERNEL, SEC, IO, WATCHER, HUMAN, PANIC
- **6 Phase Progression**: BOOT → NORMAL → WARNING → FAILURE → PANIC → SILENCE
- **Infinite Variation** through finite-state machine with weighted text generation
- **Escalation Rules** prevent immersion-breaking randomness
- **Memory Decay Effects** create haunting word repetition
- **4 Silence Modes**: Freeze, Hard Stop, Reboot Loop, Corruption

**The Intelligence:**
- Templates dynamically filled from parameter pools (services, resources, locations)
- HUMAN role only appears after WARNING phase (psychological authenticity)
- PANIC role only triggers after sufficient FAILURE events
- Memory decay makes earlier words "leak" back into later messages
- Role-based color coding with flickering effects for psychological roles

**Example Progression:**
```
SYS: initializing watchdog
KERNEL: heap allocated  
SYS: monitoring scheduler
IO: retrying inode table
WATCHER: anomaly in display
HUMAN: who started this
KERNEL: fault in watchdog
PANIC: cannot continue
PANIC: watchdog watchdog watchdog
[SILENCE - cursor blinking forever]
```

This creates **believable system consciousness losing narrative control** - the holy grail of psychological screensavers!

## Hardware

- **Board**: M5StickC Plus2
- **Display**: 240x135 LCD
- **Platform**: ESP32
- **Memory**: 8.1% RAM, 36.5% Flash (very efficient!)

## Controls

- **M5 Button**: Switch between 10 modes (cycles through all modes)
- **Button B**: Toggle auto-scroll on/off (15 seconds per mode when enabled)
- **Power Button**: Toggle titles

## Quick Start

1. **Flash firmware**: Use `M5releases/XjackMod-XTREME-HACK-v1.0.bin`
2. **Power on**: Starts with Original XJack mode
3. **Press Button A**: Cycle through all 8 modes
4. **Press Button B**: Enable auto-scroll for hands-free demo
5. **Enjoy**: Watch the psychological hacker scenarios unfold!

## Build & Flash

```bash
# Using PlatformIO
pio run --target upload

# Using pre-built binary
# Flash M5releases/XjackMod-XTREME-HACK-v1.0.bin to M5StickC Plus2
```

## Customization

To add your own custom phrases, edit the appropriate arrays in `src/main.cpp`:

```cpp
// For Back Room mode
const char* backRoomPhrases[] = {
  "Your custom atmospheric phrase here.",
  // Add more phrases...
};

// For Xtreme Hack - add new scenes
const char* xtremeHackScenes[][20] = {
  // Your custom psychological hacker scenario
  {
    "Custom command sequence...",
    "Building tension...",
    "DRAMATIC CLIMAX",
    NULL  // Always end with NULL
  }
};
```

## Project Structure

```
XjackMod/
├── src/
│   └── main.cpp              # Main application (1,600+ lines)
├── M5releases/               # Pre-built binaries
│   └── XjackMod-XTREME-HACK-v1.0.bin
├── platformio.ini            # ESP32 configuration
├── README.md                 # This file
└── XJackBackups/            # Development backups
```

## Technical Details

- **10 Screensaver modes** with seamless switching
- **Psychological progression** in each scene including **procedural generation**
- **Memory efficient** - optimized for M5StickC Plus2
- **Authentic terminal effects** with proper timing
- **Color-coded threat levels** and role-based visual language
- **Visual corruption effects** matching scene intensity
- **Finite-state machine** for intelligent failure progression
- **60 FPS rendering** with smooth animations

## Based On

This project extracts and heavily extends the XJack screensaver concept, adding:
- 8 additional psychological hacker scenarios beyond the original
- **Xtreme Hack mode** with 7 unique thriller scenes
- **Crash Grammar system** - procedural system failure with finite-state machine
- Authentic terminal simulation and command sequences
- Multi-phase progression systems with escalation rules
- Visual effects synchronized to content intensity
- Role-based dialogue generation with memory decay effects

## License

Lyrics owned by Jesus Hooligan

This project ports XJack.c originally from XScreensaver by Jamie Zawinski and contributors. The XScreensaver license permits modification and distribution for non-Windows platforms.

Original XScreensaver: https://www.jwz.org/xscreensaver/
License: MIT-compatible (no Windows restriction clause applies)

Open source - feel free to modify and extend with your own custom psychological thriller themes!
