# Fitboy

![Preview](github/alpha.png)

## Description
A clock face for Fitbit Sense, modeled after the legendary Pipboy from the Fallout Series by Fallout Series by Bethesda. Built using the Fitbit Studio and Fitbit OS Simulator.

## Target Devices:
- Fitbit Sense
- (Fitbit Versa 3)

## Requested Permissions:
- heart rate access (live bpm)
- activity (today's stats)
- user profile (weight)
- location (GPS)

## Features
- Vault Boy with limb health bars for the proper pipboy feel

### Clock
- Supports both 12 and 24 hour format

### Date and Day Format
- YYYY-MM-DD [N/7], N ∈ <1, 7>, where 1 = Monday and 7 = Sunday
    
### Stats
- Distance in kilometers
- Active zone in minutes
- Calories burn in kcal
- Elevation in floors
- Steps in... well... steps
- Heart rate in bpm
- Resting heart rate in the bottom left-hand corner, marked as HP
- Weight in the bottom right-hand corner, in kilograms
- Battery charge displayed instead of the LEVEL progress bar

### Color Schemes
- Fallout 4 green (#16FF42)

### "Console"
- Displays "> CHARGING ..." when charging
- Displays "> USER NOT DETECTED" when not on wrist
    - Also hides the vault boy and name
    
### WIP
- [ ] Customizable name
- [ ] More color schemes
- [ ] AM/PM for the 12h clock format
- [ ] Support Sunday as the first day
- [ ] Use the limb health bars as goal bars
  - [ ] Active Zone Minutes
  - [ ] Calories Burn
  - [ ] Elevation
  - [ ] Distance
  - [ ] Steps
  - [ ] ? Use the bottom bar as total progress
- [ ] Change picture based on the active zone and other factors
    - [ ] Make the vault boy animated
- [ ] Time till sunrise / sunset
- [ ] GPS
    - [ ] Latitude
    - [ ] Longitude
    - [ ] Heading