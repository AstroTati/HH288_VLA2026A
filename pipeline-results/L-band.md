## L-band

### 🔍 QA 
```
qa_standard: SRDP Wave 3
qa_status: Pass 
These data were processed using CASA 6.6.6.

qa_comments:

- Issues noted by staff:

-- For Calibration:

- No additional flagging was needed in order to pass the QA standard.

- There was gain compression in a few antennas from RFI. 

- 6s short solint

-- For Imaging:

- The pipeline limits the products created based on total product size. As a result, the image size may be smaller than ideal and the cell size may be larger than ideal.
```

### 📋 LISTOBS
Fields & SPWs:
```
Fields: 3
  ID   Code Name                RA               Decl           Epoch   SrcId      nRows
  0    NONE 3C48                01:37:41.299431 +33.09.35.13299 J2000   0        1915056
  1    NONE J0110+5632          01:10:57.560999 +56.32.16.93199 J2000   1        3723408
  2    NONE IRAS00342+6347      00:37:13.258000 +64.04.15.01999 J2000   2       24536304
Spectral Windows:  (16 unique spectral windows and 1 unique polarization setups)
  SpwID  Name           #Chans   Frame   Ch0(MHz)  ChanWid(kHz)  TotBW(kHz) CtrFreq(MHz) BBC Num  Corrs  
  0      EVLA_L#A0C0#0     128   TOPO    1520.000       500.000     64000.0   1551.7500       12  RR  LL
  1      EVLA_L#A0C0#1     128   TOPO    1584.000       500.000     64000.0   1615.7500       12  RR  LL
  2      EVLA_L#A0C0#2     128   TOPO    1648.000       500.000     64000.0   1679.7500       12  RR  LL
  3      EVLA_L#A0C0#3     128   TOPO    1712.000       500.000     64000.0   1743.7500       12  RR  LL
  4      EVLA_L#A0C0#4     128   TOPO    1776.000       500.000     64000.0   1807.7500       12  RR  LL
  5      EVLA_L#A0C0#5     128   TOPO    1840.000       500.000     64000.0   1871.7500       12  RR  LL
  6      EVLA_L#A0C0#6     128   TOPO    1904.000       500.000     64000.0   1935.7500       12  RR  LL
  7      EVLA_L#A0C0#7     128   TOPO    1968.000       500.000     64000.0   1999.7500       12  RR  LL
  8      EVLA_L#B0D0#8     128   TOPO    1008.000       500.000     64000.0   1039.7500       15  RR  LL
  9      EVLA_L#B0D0#9     128   TOPO    1072.000       500.000     64000.0   1103.7500       15  RR  LL
  10     EVLA_L#B0D0#10    128   TOPO    1136.000       500.000     64000.0   1167.7500       15  RR  LL
  11     EVLA_L#B0D0#11    128   TOPO    1200.000       500.000     64000.0   1231.7500       15  RR  LL
  12     EVLA_L#B0D0#12    128   TOPO    1264.000       500.000     64000.0   1295.7500       15  RR  LL
  13     EVLA_L#B0D0#13    128   TOPO    1328.000       500.000     64000.0   1359.7500       15  RR  LL
  14     EVLA_L#B0D0#14    128   TOPO    1392.000       500.000     64000.0   1423.7500       15  RR  LL
  15     EVLA_L#B0D0#15    128   TOPO    1456.000       500.000     64000.0   1487.7500       15  RR  LL
```

### 📈 SOLUTIONS
Reference antenna: ea11

<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/64a25c70-ea2f-4ecd-9e99-5a07dde3971e" />
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/e02c79ea-0ed0-4bcd-85de-0eb39b14e6a1" />
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/e64b3062-66f3-4abb-a3d6-b8d6fb3ba8ee" />
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/fd812993-0d50-4f40-8fe6-e870c69af2a0" />




### 📊 CALTABLES
```
Warning! Antenna ea06, spws: 2 have a flagging fraction of 1.0.
Warning! Antenna ea13, spws: 6 have a flagging fraction of 1.0.
Warning! Antenna ea23, spws: 6 have a flagging fraction of 1.0.
Warning! Antenna ea28, spws: 6 have a flagging fraction of 1.0.
```

* Examples:

<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/98b5b851-5cd8-416d-a52f-973e473dfc5e" />
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/7de996c1-5925-4a6c-b6c7-cb5ffab359f7" />


* Inspection:
```
spw='0' antenna='ea23'
scan='22~24' spw='0,10~12' corr='LL'
antenna='ea17' scan='2~4'
antenna='ea16' spw='8~15' correlation='LL'
```


