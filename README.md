# VLA/26A-214: Calibration, reduction & imaging
This repository contains the calibration, reduction and imaging workflow for VLA-A observations of HH288. 
The data were initially processed with the standard NRAO pipeline and subsequently refined through manual flagging, calibration, and imaging procedures.

### Structure
```
├── data-collection/          # Details on the SBs
│   ├── L-band.md   
│   ├── S-band.md     
│   ├── C-X-band.md    
│
├── pipeline-calibration/     # Pipeline results & further calibration
│
├── imaging/                  # tclean details
│
└── outputs/
    ├── images/               # Figures as png
    └── reports/              # Core positions, statistics, etc.
```
