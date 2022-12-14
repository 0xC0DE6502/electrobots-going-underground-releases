# Electrobots Going Underground

Electrobots Going Underground by [0xC0DE](https://twitter.com/0xC0DE6502), an 8-bit game for Acorn Electron, BBC Micro and BBC Master. Can also be played on a PC (Windows or Linux+Wine) with the self-contained EXE.

Download and play for free. Please donate to support me: [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6S33YYQ7)

![Electrobots Going Underground - Screenshot 1](https://github.com/0xC0DE6502/electrobots-going-underground-releases/blob/main/res/screenshot1.png?raw=true)
![Electrobots Going Underground - Screenshot 2](https://github.com/0xC0DE6502/electrobots-going-underground-releases/blob/main/res/screenshot2.png?raw=true)

## Aim of the game
Electrobots are sent down the mines of Terranova to find diamonds. Collect all diamonds to finish a level. If you get stuck, press `ESCAPE` for the Pause Menu and then `R` to restart the level. Watch out for enemies and spikes; they will quickly drain your energy (and lives). Collect batteries to replenish your energy and find hearts for extra lives. Use crates wisely to find your way across some levels. Can you safely guide our little robot friends through all 16 levels?

## How to play
There are 3 main ways to play the game:
1. Use the [tape image](https://github.com/0xC0DE6502/electrobots-going-underground-releases/raw/main/electrobots-going-underground.uef) on real hardware or an emulator
2. Use the [disk image](https://github.com/0xC0DE6502/electrobots-going-underground-releases/raw/main/electrobots-going-underground.ssd) on real hardware or an emulator
3. Play the [self-contained EXE](https://github.com/0xC0DE6502/electrobots-going-underground-releases/raw/main/electrobots-going-underground.exe) on a PC

### Linux+Wine
The self-contained Windows EXE works on Linux as well if you use Wine: `wine electrobots-going-underground.exe`. You need a 64-bit `WINEPREFIX` and enough video memory configured (`winetricks videomemorysize=1024`). I have played the game successfully on Ubuntu 22.04 using Wine 7.18. Known issue: toggling full-screen play (`ALT+ENTER`) may cause the game to lose keyboard focus. Fix: use `ALT+TAB` to select the game window again.

## Controls

```
Z      - Left
X      - Right
:      - Take Crate
/      - Drop Crate
RETURN - Jump
```

### Alternate controls

```
C      - Left
V      - Right
K      - Take Crate
M      - Drop Crate
L      - Jump
```

### Other keys

```
Q      - Toggle Sound
ESCAPE - Pause Menu
```

Keys in the Pause Menu:

```
ESCAPE - Continue Game
R      - Restart Level
Q      - Quit Game
```

Tip: skip scrolling text messages by pressing `SPACE`, `L` or `RETURN`.

---

Electrobots Going Underground - Copyright (C) 2022 [0xC0DE](https://twitter.com/0xC0DE6502)
