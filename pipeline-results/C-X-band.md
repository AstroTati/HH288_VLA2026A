## C-band

### 🔍 QA 
```
These data were processed using CASA 6.6.6.

qa_comments:
- Issues noted by staff:

-- For Calibration:
- No additional flagging was needed in order to pass the QA standard.
- This observation failed due to not all antennas being included at the start of the observation. As a result, no target scans were observed for X band. However, the data are still archived in the hopes they may be useful in the future.

C
- There was gain compression in a few antennas from RFI.

-- For Imaging:

C
- The pipeline limits the products created based on total product size. As a result, the image size may be smaller than ideal and the cell size may be larger than ideal. 

- The imaging pipeline will have attempted self calibration on each of the target sources if possible.
```

### 📋 listobs
Extract:
```
Fields: 3
  ID   Code Name                RA               Decl           Epoch   SrcId      nRows
  0    NONE 3C48                01:37:41.299431 +33.09.35.13299 J2000   0        1728496
  1    NONE J0102+5824          01:02:45.762384 +58.24.11.13662 J2000   1         720544
  2    NONE HH288_SE            00:37:11.153001 +64.03.39.85999 J2000   2        2210208
Spectral Windows:  (32 unique spectral windows and 1 unique polarization setups)
  SpwID  Name           #Chans   Frame   Ch0(MHz)  ChanWid(kHz)  TotBW(kHz) CtrFreq(MHz) BBC Num  Corrs
  0      EVLA_X#A0C0#0     128   TOPO    9488.000      1000.000    128000.0   9551.5000       12  RR  LL
  1      EVLA_X#A0C0#1     128   TOPO    9616.000      1000.000    128000.0   9679.5000       12  RR  LL
  2      EVLA_X#A0C0#2     128   TOPO    9744.000      1000.000    128000.0   9807.5000       12  RR  LL
  3      EVLA_X#A0C0#3     128   TOPO    9872.000      1000.000    128000.0   9935.5000       12  RR  LL
  4      EVLA_X#A0C0#4     128   TOPO   10000.000      1000.000    128000.0  10063.5000       12  RR  LL
  5      EVLA_X#A0C0#5     128   TOPO   10128.000      1000.000    128000.0  10191.5000       12  RR  LL
  6      EVLA_X#A0C0#6     128   TOPO   10256.000      1000.000    128000.0  10319.5000       12  RR  LL
  7      EVLA_X#A0C0#7     128   TOPO   10384.000      1000.000    128000.0  10447.5000       12  RR  LL
  8      EVLA_X#B0D0#8     128   TOPO    8488.000      1000.000    128000.0   8551.5000       15  RR  LL
  9      EVLA_X#B0D0#9     128   TOPO    8616.000      1000.000    128000.0   8679.5000       15  RR  LL
  10     EVLA_X#B0D0#10    128   TOPO    8744.000      1000.000    128000.0   8807.5000       15  RR  LL
  11     EVLA_X#B0D0#11    128   TOPO    8872.000      1000.000    128000.0   8935.5000       15  RR  LL
  12     EVLA_X#B0D0#12    128   TOPO    9000.000      1000.000    128000.0   9063.5000       15  RR  LL
  13     EVLA_X#B0D0#13    128   TOPO    9128.000      1000.000    128000.0   9191.5000       15  RR  LL
  14     EVLA_X#B0D0#14    128   TOPO    9256.000      1000.000    128000.0   9319.5000       15  RR  LL
  15     EVLA_X#B0D0#15    128   TOPO    9384.000      1000.000    128000.0   9447.5000       15  RR  LL
  16     EVLA_C#A0C0#16    128   TOPO    5988.000      1000.000    128000.0   6051.5000       12  RR  LL
  17     EVLA_C#A0C0#17    128   TOPO    6116.000      1000.000    128000.0   6179.5000       12  RR  LL
  18     EVLA_C#A0C0#18    128   TOPO    6244.000      1000.000    128000.0   6307.5000       12  RR  LL
  19     EVLA_C#A0C0#19    128   TOPO    6372.000      1000.000    128000.0   6435.5000       12  RR  LL
  20     EVLA_C#A0C0#20    128   TOPO    6500.000      1000.000    128000.0   6563.5000       12  RR  LL
  21     EVLA_C#A0C0#21    128   TOPO    6628.000      1000.000    128000.0   6691.5000       12  RR  LL
  22     EVLA_C#A0C0#22    128   TOPO    6756.000      1000.000    128000.0   6819.5000       12  RR  LL
  23     EVLA_C#A0C0#23    128   TOPO    6884.000      1000.000    128000.0   6947.5000       12  RR  LL
  24     EVLA_C#B0D0#24    128   TOPO    4988.000      1000.000    128000.0   5051.5000       15  RR  LL
  25     EVLA_C#B0D0#25    128   TOPO    5116.000      1000.000    128000.0   5179.5000       15  RR  LL
  26     EVLA_C#B0D0#26    128   TOPO    5244.000      1000.000    128000.0   5307.5000       15  RR  LL
  27     EVLA_C#B0D0#27    128   TOPO    5372.000      1000.000    128000.0   5435.5000       15  RR  LL
  28     EVLA_C#B0D0#28    128   TOPO    5500.000      1000.000    128000.0   5563.5000       15  RR  LL
  29     EVLA_C#B0D0#29    128   TOPO    5628.000      1000.000    128000.0   5691.5000       15  RR  LL
  30     EVLA_C#B0D0#30    128   TOPO    5756.000      1000.000    128000.0   5819.5000       15  RR  LL
  31     EVLA_C#B0D0#31    128   TOPO    5884.000      1000.000    128000.0   5947.5000       15  RR  LL
Sources: 64
```

* 3C48 & J0102+5824: SPW 0~31
* HH288: SPW 16~31

### 📈 Analysis
#### Amp vs Freq
J0102+5824 corrected, spw 16~31, avg time = 1e9, avg scan, avg antenna, colorize by baseline
<img width="1574" height="969" alt="image" src="https://github.com/user-attachments/assets/4f31930d-cfef-4c96-a955-dcc3591cd096" />


---

## C-X-band
