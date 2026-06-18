## S-band

### 🔍 QA 
```
qa_standard: SRDP Wave 3
qa_status: Pass 
These data were processed using CASA 6.6.6.

qa_comments:

- Issues noted by staff:

-- For Calibration:

- There is gain compression from RFI. 

- The calibrated amplitude vs. frequency for the complex gain calibrator shows a systematic oscillation in amplitude as a function of frequency.
This is a few percent effect (~4% for this observation), and we don't think it should cause serious harm for continuum imaging.

No additional flagging was needed in order to pass the QA standard.
```
\
Note: Data for EB 26A-214.sb50156844.eb50534865.61122.933381215276_targets_cont.ms, field IRAS00342+6347, spw 10 is completely flagged. 

### 📋 LISTOBS
Fields & SPWs:
```
Fields: 3
  ID   Code Name                RA               Decl           Epoch   SrcId      nRows
  0    NONE 3C48                01:37:41.299431 +33.09.35.13299 J2000   0        1773200
  1    NONE J0217+7349          02:17:30.813363 +73.49.32.62175 J2000   1        2818400
  2    NONE IRAS00342+6347      00:37:13.258000 +64.04.15.01999 J2000   2       18699200
Spectral Windows:  (16 unique spectral windows and 1 unique polarization setups)
  SpwID  Name           #Chans   Frame   Ch0(MHz)  ChanWid(kHz)  TotBW(kHz) CtrFreq(MHz) BBC Num  Corrs  
  0      EVLA_S#A0C0#0     128   TOPO    2988.000      1000.000    128000.0   3051.5000       12  RR  LL
  1      EVLA_S#A0C0#1     128   TOPO    3116.000      1000.000    128000.0   3179.5000       12  RR  LL
  2      EVLA_S#A0C0#2     128   TOPO    3244.000      1000.000    128000.0   3307.5000       12  RR  LL
  3      EVLA_S#A0C0#3     128   TOPO    3372.000      1000.000    128000.0   3435.5000       12  RR  LL
  4      EVLA_S#A0C0#4     128   TOPO    3500.000      1000.000    128000.0   3563.5000       12  RR  LL
  5      EVLA_S#A0C0#5     128   TOPO    3628.000      1000.000    128000.0   3691.5000       12  RR  LL
  6      EVLA_S#A0C0#6     128   TOPO    3756.000      1000.000    128000.0   3819.5000       12  RR  LL
  7      EVLA_S#A0C0#7     128   TOPO    3884.000      1000.000    128000.0   3947.5000       12  RR  LL
  8      EVLA_S#B0D0#8     128   TOPO    1988.000      1000.000    128000.0   2051.5000       15  RR  LL
  9      EVLA_S#B0D0#9     128   TOPO    2116.000      1000.000    128000.0   2179.5000       15  RR  LL
  10     EVLA_S#B0D0#10    128   TOPO    2244.000      1000.000    128000.0   2307.5000       15  RR  LL
  11     EVLA_S#B0D0#11    128   TOPO    2372.000      1000.000    128000.0   2435.5000       15  RR  LL
  12     EVLA_S#B0D0#12    128   TOPO    2500.000      1000.000    128000.0   2563.5000       15  RR  LL
  13     EVLA_S#B0D0#13    128   TOPO    2628.000      1000.000    128000.0   2691.5000       15  RR  LL
  14     EVLA_S#B0D0#14    128   TOPO    2756.000      1000.000    128000.0   2819.5000       15  RR  LL
  15     EVLA_S#B0D0#15    128   TOPO    2884.000      1000.000    128000.0   2947.5000       15  RR  LL
Sources: 48
```

### 📈 SOLUTIONS
Reference antenna: ea28
\
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/8a1d851d-447b-4cdc-a4b6-00fddaefaa96" />
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/37115297-37ab-4bf9-8389-8b2509c1ffa0" />
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/6451521c-0839-4d90-aca4-80953b0066fe" />
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/7695f6b0-4d80-45a8-b249-5db1fe663352" />


### 📊 CALTABLES
Examples ea28:
\
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/82f030cc-4ff0-4b67-8c70-91a0c58c729a" />
<img width="377" height="252" alt="image" src="https://github.com/user-attachments/assets/2411c0d9-a90d-4917-994f-6b030ef1817f" />

\
* Inspection:
```
spw='9' antenna='ea06,ea07,ea13,ea19,ea22, ea25'
spw='8' antenna='ea04'
antenna='ea21' scan='10~12'
```
