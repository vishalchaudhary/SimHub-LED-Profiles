# SimHub LED Profiles

Custom SimHub LED profiles for sim racing.

## Profiles

### Any_Game - Vishal ACC RGB Enhanced

An 8x8 RGB LED profile designed for Assetto Corsa Competizione and compatible with other sim racing titles.

**Features:**
- Gear display (R, N, 1–7) with per-gear halo animations
- Race flags: Yellow, Blue, White, Green, Black
- Spotter overlay (car left/right)
- Fuel level indicator (5 bands: 8/8, 6/8, 4/8, 3/8, 2/8)
- ABS Active indicator
- TC (Traction Control) Active indicator
- DRS Available / DRS Enabled indicators
- Pit Lane detection
- Pit Limiter indicator
- Low Fuel Alert
- Idle cinematic animation when no game is running

**Versions:**
- `v11` – Original release
- `v12` – Fixed: boolean conditions now use `isnull(..., 0) = 1` for cross-game compatibility (ABS, TC, DRS, Pit Limiter, Pit Lane, Low Fuel Alert)

## Installation

1. Open SimHub
2. Go to **LED Output** → **Profiles**
3. Click **Import** and select the `.ledsprofile` file
