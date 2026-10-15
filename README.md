markdown
# IBM AI Racing League - TORCS Driver

Autonomous AI driver for the Corkscrew track in TORCS.

## Results
- Original parameters: car crashed immediately (0 laps, extreme damage)
- Improved version (with IBM Bob): complete lap in ~03:19 with **0 damage**

## Files
- `torcs_jm_par.py` (or the uploaded file): final improved driver

## Improvements
- Reduced TARGET_SPEED and STEER_GAIN for stability
- Adjusted centering and braking to avoid barriers
- Achieved zero-damage laps
