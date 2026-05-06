# Development Standards
 
## Commit Convention
 
```
type: short description
```
 
| Type | Use |
|------|-----|
| `feat` | new feature |
| `fix` | bug fix |
| `setup` | initial configuration |
| `docs` | documentation |
| `refactor` | code improvement |
| `test` | testing changes |
 
**Examples:**
 
```bash
feat: add person detection trigger
fix: prevent duplicate image capture
setup: configure raspberry pi camera
docs: add hardware setup instructions
```
 
---
 
## Issue Naming
 
Clear and action-based.
 
**Examples:**
 
```
Setup Raspberry Pi + Camera
Define Data Collection Locations
Implement Person Detection
Document Development Standards
```
 
---
 
## Issue Structure
 
```md
## Objective
## Context
## Tasks
- [ ] Task 1
## Output
## Acceptance Criteria
- [ ] Behavior completed
- [ ] Tested
- [ ] Committed
```
 
**Example — real issue:**
 
```md
## Objective
Deploy the first data collection module in Tío Gus workshop.
 
## Context
We need real welding images to build the dataset. Tío Gus workshop
is the first confirmed location. No WiFi available, so storage must be local.
 
## Tasks
- [ ] Confirm permission with Tío Gus
- [ ] Purchase Raspberry Pi Zero 2W + AI Camera + MicroSD
- [ ] Set up local storage on the device
- [ ] Define camera placement at the welding station
- [ ] Run first capture test
 
## Output
A working data collection module deployed at Tío Gus workshop,
capturing and storing welding images locally on the SD card.
 
## Acceptance Criteria
- [ ] Device captures images without internet connection
- [ ] Images are stored correctly on the SD card
- [ ] Camera angle covers the welding area
- [ ] Collection can run unattended
```
 
---
 
## Definition of Done
 
- [ ] Acceptance criteria met
- [ ] Solution tested
- [ ] Commit follows convention
- [ ] Docs updated if needed