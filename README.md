# marlin-to-klipper
Marlin to Klipper or Klipper to Marlin converter
---
## Concept, do not use!
---
# What it converts:

- Steps/mm → rotation_distance (with proper calculation)
- Max feedrates and acceleration
- Bed size and travel limits
- Kinematics detection (Cartesian, CoreXY, Delta)
- Thermistor types
- PID values for hotend and bed
- Probe offsets (if BLTouch or fixed probe enabled)
- Generates bed mesh and safe_z_home sections

# What you'll need to manually configure:

- MCU serial path
- Pin assignments (these are board-specific)
- TMC driver settings if used