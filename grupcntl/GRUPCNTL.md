# GRUPCNTL - Group Control Case Test Documentation

Case Name   | Case Description                           | Model    | Results<br />Match | Comments |
----------- | ------------------------------------------ | ---------| ------- | ------------------------------------- |
GRUPCNTL-01 | 0A1_GRCTRL_LRAT_ORAT_BASE_MODEL2_MSW       | MODEL02  |  Yes    | Good match with commercial simulator.            
GRUPCNTL-02 | 0A1_GRCTRL_LRAT_ORAT_BASE_MODEL2_STW       | MODEL02  |  Yes    | Good match with commercial simulator.                                      
GRUPCNTL-03 | 0A2_GRCTRL_LRAT_ORAT_GGR_BASE_MODEL2_MSW   | MODEL02  |  Yes    | Good match with commercial simulator.                                  
GRUPCNTL-04 | 0A2_GRCTRL_LRAT_ORAT_GGR_BASE_MODEL2_STW   | MODEL02  |  Yes    | Good match with commercial simulator.                                      
GRUPCNTL-05 | 0A3_GRCTRL_LRAT_LRAT_BASE_MODEL2_MSW       | MODEL02  |  Yes    | Good match with commercial simulator.                                      
GRUPCNTL-06 | 0A3_GRCTRL_LRAT_LRAT_BASE_MODEL2_STW       | MODEL02  |  Yes    | Good match with commercial simulator.                                      
GRUPCNTL-07 | 0A4_GRCTRL_LRAT_LRAT_GGR_BASE_MODEL2_MSW   | MODEL02  |  Yes    | Good match with commercial simulator.                                      
GRUPCNTL-08 | 0A4_GRCTRL_LRAT_LRAT_GGR_BASE_MODEL2_STW   | MODEL02  |  Yes    | Good match with commercial simulator.                                      
GRUPCNTL-09 | 9_1A_DEPL_MAX_RATE_MIN_BHP_MSW             | MODEL02A |  Yes    | Perfect match with commercial simulator.                                      
GRUPCNTL-10 | 9_1A_DEPL_MAX_RATE_MIN_BHP_STW             | MODEL02A |  Yes    | Perfect match with commercial simulator.                                      
GRUPCNTL-11 | 9_1B_DEPL_MAX_RATE_MIN_THP_MSW             | MODEL02A |  Yes    | Perfect match with commercial simulator.                                      
GRUPCNTL-12 | 9_1B_DEPL_MAX_RATE_MIN_THP_STW             | MODEL02A |  Yes    | Perfect match with commercial simulator.                                      
GRUPCNTL-13 | 9_2A_DEPL_GCONPROD_1L_MSW                  | MODEL02A |  Yes    | Perfect match with commercial simulator, except for well control mode.                                       
GRUPCNTL-14 | 9_2A_DEPL_GCONPROD_1l_STW                  | MODEL02A |  Yes    | Perfect match with commercial simulator, except for well control mode.
GRUPCNTL-15 | 9_2B_DEPL_GCONPROD_2L_MSW                  | MODEL02A |  Yes    | Perfect match with commercial simulator, except for well control mode.
GRUPCNTL-16 | 9_2B_DEPL_GCONPROD_2L_MSW                  | MODEL02A |  Yes    | Perfect match with commercial simulator, except for well control mode.
GRUPCNTL-17 | 9_3A_GINJ_REIN-G_MSW                       | MODEL02A |  Yes    | Perfect match with commercial simulator, but no Sales Gas or Gas Consumption volumes.                                    
GRUPCNTL-18 | 9_3A_GINJ_REIN-G_STW                       | MODEL02A |  Yes    | Perfect match with commercial simulator, but no Sales Gas or Gas Consumption volumes.                                     
GRUPCNTL-19 | 9_3B_GINJ_GAS_EXPORT_MSW                   | MODEL02A |  Yes    | Perfect match with commercial simulator, but no Sales Gas or Gas Consumption volumes.                                   
GRUPCNTL-20 | 9_3B_GINJ_GAS_EXPORT_STW                   | MODEL02A |  Yes    | Perfect match with commercial simulator, but no Sales Gas or Gas Consumption volumes.
GRUPCNTL-21 | 9_3C_GINJ_GAS_GCONSUMP_MSW                 | MODEL02A |  Yes    | Perfect match with commercial simulator, but no Sales Gas or Gas Consumption volumes.                                   
GRUPCNTL-22 | 9_3C_GINJ_GAS_GCONSUMP_STW                 | MODEL02A |  Yes    | Perfect match with commercial simulator, but no Sales Gas or Gas Consumption volumes.                                     
GRUPCNTL-23 | 9_3D_GINJ_GAS_MAX_EXPORT_MSW               | MODEL02A |  Yes    | Very good match, except for gas volumes after 2019-06-01. Reference case matches commercial simulator.                                
GRUPCNTL-24 | 9_3D_GINJ_GAS_MAX_EXPORT_STW               | MODEL02A |  Yes    | Very good match, except for gas volumes after 2019-06-01. Reference case matches commercial simulator.                                    
GRUPCNTL-25 | 9_3E_GAS_MIN_EXPORT_MSW                    | MODEL02A |  Yes    | Perfect match with commercial simulator, but no Sales Gas or Gas Consumption volumes.                                       
GRUPCNTL-26 | 9_3E_GAS_MIN_EXPORT_MSW                    | MODEL02A |  Yes    | Perfect match with commercial simulator, but no Sales Gas or Gas Consumption volumes.                                      
GRUPCNTL-27 | 9_4A_WINJ_MAXWRATES_MAXBHP_GCONPROD_1L_MSW | MODEL02A |  Yes    | Perfect match with commercial simulator, but there appears to be time step issue with OPM Flow and the results are slightly different after 250 days.                                     
GRUPCNTL-28 | 9_4A_WINJ_MAXWRATES_MAXBHP_GCONPROD_1L_STW | MODEL02A |  Yes    | Perfect match with commercial simulator, but there appears to be time step issue with OPM Flow and the results are slightly different after 250 days.                                     
GRUPCNTL-29 | 9_4B_WINJ_VREP-W_MSW                       | MODEL02A |  Yes    | Perfect match with commercial simulator, but there appears to be time step issue with OPM Flow and the results are slightly different after 250 days.                                      
GRUPCNTL-30 | 9_4B_WINJ_VREP-W_STW                       | MODEL02A |  Yes    | Perfect match with commercial simulator, but there appears to be time step issue with OPM Flow and the results are slightly different after 250 days.                                      
GRUPCNTL-31 | 9_4C_WINJ_GINJ_VREP-W_REIN-G_MSW           | MODEL02A |  Yes    | Perfect match with commercial simulator.                                       
GRUPCNTL-32 | 9_4C_WINJ_GINJ_VREP-W_REIN-G_STW           | MODEL02A |  Yes    | Perfect match with commercial simulator.                                      
GRUPCNTL-33 | 9_4D_WINJ_GINJ_GAS_EXPORT_MSW              | MODEL02A | Yes/No  | Perfect match with commercial simulator up to gas sales, than diverges - OPM Flow looks correct.                                     
GRUPCNTL-34 | 9_4D_WINJ_GINJ_GAS_EXPORT_STW              | MODEL02A | Yes/No  | Perfect match with commercial simulator up to gas sales, than diverges - OPM Flow looks correct.  
GRUPCNTL-35 | 9_4E_WINJ_GINJ_GUIDERATE_MSW               | MODEL02A |         | Perfect match with commercial simulator up to gas sales, than diverges - no OPM Flow reference results.                                      
GRUPCNTL-36 | 9_4E_WINJ_GINJ_GUIDERATE_STW               | MODEL02A |         | Perfect match with commercial simulator up to gas sales, than diverges - no OPM Flow reference results.

**Notes:** 

1. _Results Match_ column indicate if the OPM Flow results match the commercial simulator, see below for comparisons.
2. If Yes is in **bold** under the _Results Match_ column, then the case is part of the regression testing.
3. Under comments, _Complete_ means that the test case is completed, it does not mean that the runs are necessarily comparable to the commercial simulator.
4. All cases run with one day time steps for comparison purposes.

**Version: 11 October 2022**

### GRUPCNT MODEL02 Model (Regular Corner-Point)
![](plots/GRUPCNTL-MODEL02.jpg)

This case is based on MODEL02 and is intended to verify various aspects of group and well control inter-actions. The  model is 
is a (13, 22, 11) model with Regular Corner-Point grid. This is a three-phase model using MODEL02 PVT based on the Norne model.
The model has several groups as shown below:
```                                                        
                                                        FIELD                                                                  
                                                          |                                                                    
                                                     --------------
                                                      |           |
                                                    INJE        PROD  
                                                     |            |
                                                   INJE1      -------- 
                                                              |        |
                                                             WGRP1    WGRP2   
                                                               |       |    
                                                           --------  PROD2 
                                                           |      | 
                                                        PROD1   PROD3       
                                                               
                                                                                                                           
```
### GRUPCNT MODEL02A Model (Regular Corner-Point)
![](plots/GRUPCNTL-MODEL02A.jpg) 

This case is based on MODEL02 and is intended to verify various aspects of group and well control inter-actions. The  model is 
is a (13, 22, 11) model with Regular Corner-Point grid. This is a three-phase model using MODEL02 PVT based on the Norne model.
The static data for this model is different to the standard MODEL02, due to fault and NNC modifications, as well as, activating
the hysteresis and end-point scaling option. 

The model has several groups as shown below:
```                                      
                                                          FIELD
                                                            |
                                                          PROD
                                               +-------+-------+-------+   
                                               |       |       |       |    
                                             PROD1   PROD2   PROD3   PROD4  
```

## RESULTS

### GRUPCNTL-01 Description and Results
1) The case has three producers (no VFP) and one water injector.
2) Producers and injectors are **multi-segment wells**.
3) Group PROD: GCONPROD(TARGET) set to LRAT control and GCONPROD(OIL) limit set to 2,500.   
4) Group WGRP1: GCONPROD(GUIPHASE) set to 1* (well level).
5) Group WGRP1: GCONPROD(GUIPHASE) set to 1* (well level).

Note multi-well segment case has maximum time step size of 3.0 days.

[GRUPCNTL-01 ECL Results](plots/GRUPCNTL-01-ECL.md) 

[GRUPCNTL-01 REF Results](plots/GRUPCNTL-01-REF.md) 

---

### GRUPCNTL-02 Description and Results
1) The case has three producers (no VFP) and one water injector.
2) Producers and injectors are **standard wells**.
3) Group PROD: GCONPROD(TARGET) set to LRAT control and GCONPROD(OIL) limit set to 2,500.   
4) Group WGRP1: GCONPROD(GUIPHASE) set to 1* (well level).
5) Group WGRP1: GCONPROD(GUIPHASE) set to 1* (well level).

[GRUPCNTL-02 ECL Results](plots/GRUPCNTL-02-ECL.md) 

[GRUPCNTL-02 REF Results](plots/GRUPCNTL-02-REF.md)    

---

### GRUPCNTL-03 Description and Results
1) The case has three producers (no VFP) and one water injector.
2) Producers and injectors are **multi-segment wells**.
3) Group PROD: GCONPROD(TARGET) set to LRAT control and GCONPROD(OIL) limit set to 2,500.   
4) Group WGRP1: GCONPROD(GUIPHASE) set to **FORM**.
5) Group WGRP2: GCONPROD(GUIPHASE) set to **FORM**.

Note multi-well segment case has maximum time step size of 3.0 days.

```
Warning: Problem with GCONPROD
In GRUPCNTL-03.DATA line 397
The supplied guide rate will be ignored

Warning: Problem with GCONPROD
In GRUPCNTL-03.DATA line 397
The supplied guide rate will be ignored
```
[GRUPCNTL-03 ECL Results](plots/GRUPCNTL-03-ECL.md) 

[GRUPCNTL-03 REF Results](plots/GRUPCNTL-03-REF.md) 

---

### GRUPCNTL-04 Description and Results
1) The case has three producers (no VFP) and one water injector.
2) Producers and injectors are **standard wells**.
3) Group PROD: GCONPROD(TARGET) set to LRAT control and GCONPROD(OIL) limit set to 2,500.   
4) Group WGRP1: GCONPROD(GUIPHASE) set to **FORM**.
5) Group WGRP2: GCONPROD(GUIPHASE) set to **FORM**.
```
Warning: Problem with GCONPROD
In GRUPCNTL-03.DATA line 397
The supplied guide rate will be ignored

Warning: Problem with GCONPROD
In GRUPCNTL-03.DATA line 397
The supplied guide rate will be ignored
```
[GRUPCNTL-04 ECL Results](plots/GRUPCNTL-04-ECL.md)

[GRUPCNTL-04 REF Results](plots/GRUPCNTL-04-REF.md) 

---

### GRUPCNTL-05 Description and Results
1) The case has three producers (no VFP) and one water injector.
2) Producers and injectors are **multi-segment wells**.
3) Group PROD: GCONPROD(TARGET) set to LRAT control and GCONPROD(OIL) limit set to **900**.   
4) Group WGRP1: GCONPROD(GUIPHASE) set to 1* (well level).
5) Group WGRP1: GCONPROD(GUIPHASE) set to 1* (well level).

Note multi-well segment case has maximum time step size of 3.0 days.

[GRUPCNTL-05 ECL Results](plots/GRUPCNTL-05-ECL.md) 

[GRUPCNTL-05 REF Results](plots/GRUPCNTL-05-REF.md) 

---

### GRUPCNTL-06 Description and Results
1) The case has three producers (no VFP) and one water injector.
2) Producers and injectors are **standard wells**.
3) Group PROD: GCONPROD(TARGET) set to LRAT control and GCONPROD(OIL) limit set to **900**.   
4) Group WGRP1: GCONPROD(GUIPHASE) set to 1* (well level).
5) Group WGRP1: GCONPROD(GUIPHASE) set to 1* (well level).

[GRUPCNTL-06 ECL Results](plots/GRUPCNTL-06-ECL.md) 

[GRUPCNTL-06 REF Results](plots/GRUPCNTL-06-REF.md)

---

### GRUPCNTL-07 Description and Results
1) The case has three producers (no VFP) and one water injector.
2) Producers and injectors are **multi-segment wells**.
3) Group PROD: GCONPROD(TARGET) set to LRAT control and GCONPROD(OIL) limit set to **900**.
4) Group WGRP1: GCONPROD(GUIPHASE) set to **FORM**.
5) Group WGRP2: GCONPROD(GUIPHASE) set to **FORM**.

Note multi-well segment case has maximum time step size of 3.0 days.

```
Warning: Problem with GCONPROD
In GRUPCNTL-07.DATA line 397
The supplied guide rate will be ignored

Warning: Problem with GCONPROD
In GRUPCNTL-07.DATA line 397
```
[GRUPCNTL-07 ECL Results](plots/GRUPCNTL-07-ECL.md) 

[GRUPCNTL-07 REF Results](plots/GRUPCNTL-07-REF.md)   

---

### GRUPCNTL-08 Description and Results
1) The case has three producers (no VFP) and one water injector.
2) Producers and injectors are **standard wells**.
3) Group PROD: GCONPROD(TARGET) set to LRAT control and GCONPROD(OIL) limit set to **900**.
4) Group WGRP1: GCONPROD(GUIPHASE) set to **FORM**.
5) Group WGRP2: GCONPROD(GUIPHASE) set to **FORM**.
```
Warning: Problem with GCONPROD
In GRUPCNTL-08.DATA line 397
The supplied guide rate will be ignored

Warning: Problem with GCONPROD
In GRUPCNTL-08.DATA line 397
The supplied guide rate will be ignored
```
[GRUPCNTL-08 ECL Results](plots/GRUPCNTL-08-ECL.md) 

[GRUPCNTL-08 REF Results](plots/GRUPCNTL-08-REF.md) 

---

### GRUPCNTL-09 Description and Results (MODEL02A)

1) The case has **four producers** (no VFP) and no water injectors (depletion case).
2) Producers are multi-segment wells
3) No Group control.
4) WCONPROD(OIL) = 4E3, WCONPROD(GAS) = 4E6, WCONPROD(LIQ) = 8E3, and WCONPROD(BHP) = 60.0, same for all wells. 

[GRUPCNTL-09 ECL Results](plots/GRUPCNTL-09-ECL.md) 

[GRUPCNTL-09 REF Results](plots/GRUPCNTL-09-REF.md) 

---

### GRUPCNTL-10 Description and Results (MODEL02A)

1) The case has four producers (no VFP) and no water injectors (depletion case).
2) Producers are **standard wells**.
3) No Group control.
4) WCONPROD(OIL) = 4E3, WCONPROD(GAS) = 4E6, WCONPROD(LIQ) = 8E3, and WCONPROD(BHP) = 60.0, same for all wells. 

[GRUPCNTL-10 ECL Results](plots/GRUPCNTL-10-ECL.md)

[GRUPCNTL-10 REF Results](plots/GRUPCNTL-10-REF.md) 

---

### GRUPCNTL-11 Description and Results

1) The case has four producers with VFP tables, and no water injectors (depletion case).
2) Producers are multi-segment wells.
3) No Group control.
4) WCONPROD(OIL) = 4E3, WCONPROD(GAS) = 4E6, WCONPROD(LIQ) = 8E3, and WCONPROD(BHP) = 60.0, same for all wells.
5) **WCONPROD(THP) = 30.0 and VFP tables.**

[GRUPCNTL-11 ECL Results](plots/GRUPCNTL-11-ECL.md)

[GRUPCNTL-11 REF Results](plots/GRUPCNTL-11-REF.md)

---

### GRUPCNTL-12 Description and Results

1) The case has four producers with VFP tables, and no water injectors (depletion case).
2) Producers are **standard wells**.
3) No Group control.
4) WCONPROD(OIL) = 4E3, WCONPROD(GAS) = 4E6, WCONPROD(LIQ) = 8E3, and WCONPROD(BHP) = 60.0, same for all wells.
5) **WCONPROD(THP) = 30.0 and VFP tables**.

[GRUPCNTL-12 ECL Results](plots/GRUPCNTL-12-ECL.md)

[GRUPCNTL-12 REF Results](plots/GRUPCNTL-12-REF.md) 

---

### GRUPCNTL-13 Description and Results

1) The case has four producers with VFP tables, and no water injectors (depletion case).
2) Producers are multi-segment wells.
3) Group control.
4) WCONPROD(OIL)= 4E3, WCONPROD(GAS)= 4E6, WCONPROD(LIQ) = 8E3, and WCONPROD(BHP) = 60.0, same for all wells. 
5) WCONPROD(THP) = 30.0 and VFP tables.
6) **Group PROD: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.**
7) **Group PROD: GCONPROD(GRPCNTL)=NO**

[GRUPCNTL-13 ECL Results](plots/GRUPCNTL-13-ECL.md) 

[GRUPCNTL-13 REF Results](plots/GRUPCNTL-13-REF.md)  

---

### GRUPCNTL-14 Description and Results

1) The case has four producers with VFP tables, and no water injectors (depletion case).
2) Producers are **standard wells**.
3) Group control.
4) WCONPROD(OIL)= 4E3, WCONPROD(GAS)= 4E6, WCONPROD(LIQ) = 8E3, and WCONPROD(BHP) = 60.0, same for all wells. 
5) WCONPROD(THP) = 30.0 and VFP tables.
6) **Group PROD: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.**
7) **Group PROD: GCONPROD(GRPCNTL)=NO**

[GRUPCNTL-14 ECL Results](plots/GRUPCNTL-14-ECL.md)

[GRUPCNTL-14 REF Results](plots/GRUPCNTL-14-REF.md)

---

### GRUPCNTL-15 Description and Results

```                                      
                                                   FIELD
                                                     |
                                                   PROD
                                           ----------+------------
                                          |                      |        
                                       MANI-A                 MANI-B      
                                    +-----+------+          +-----+------+
                                    |            |          |            |   
                                  PROD1       PROD2       PROD3        PROD4  
```
 1) The case has four producers with VFP tables, and no water injectors (depletion case).
 2) Producers are multi-segment wells.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group PROD: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3. 
 7) Group PROD: GCONPROD(GRPCNTL)=NO
 8) **Group MANI-A: GCONPROD(TARGET)=FLD, GCONPROD(OIL)=6E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.** 
 9) **Group MANI-A: GCONPROD(GRPCNTL)=YES**
 10) **Group MANi-B: Same as MANI-A**

[GRUPCNTL-15 ECL Results](plots/GRUPCNTL-15-ECL.md)

[GRUPCNTL-15 REF Results](plots/GRUPCNTL-15-REF.md)

---

### GRUPCNTL-16 Description and Results
 1) The case has four producers with VFP tables, and no water injectors (depletion case).
 2) Producers are standard wells.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group PROD: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3. 
 7) Group PROD: GCONPROD(GRPCNTL)=NO
 8) **Group MANI-A: GCONPROD(TARGET)=FLD, GCONPROD(OIL)=6E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.** 
 9) **Group MANI-A: GCONPROD(GRPCNTL)=YES**
 10) **Group MANI-B: Same as MANI-A**

[GRUPCNTL-16 ECL Results](plots/GRUPCNTL-16-ECL.md) 

[GRUPCNTL-16 REF Results](plots/GRUPCNTL-16-REF.md)

---

### GRUPCNTL-17 Description and Results

```                                      
                                             FIELD
                                               |
                                              RES
                                 --------------+------------
                                 |                         |        
                               PROD                      INJE      
                       +-----+-----+-----+           +-----+-----+
                       |     |     |     |           |           |
                    PROD1  PROD2  PROD3  PROD4      INJE1      INJE2
```                                      
 1) The case has four producers with VFP tables, and **two gas injectors**.
 2) Producers and injectors are multi-segment wells.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3. 
 7) Group RES: GCONPROD(GRPCNTL)=NO
 8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
 9) Well INJ1 re-completed 2019-03-01.
 10) Group RES: GCONPROD(GAS)=2.1E6 at 2019-06-01.

[GRUPCNTL-17 ECL Results](plots/GRUPCNTL-17-ECL.md)

[GRUPCNTL-17 REF Results](plots/GRUPCNTL-17-REF.md)  

---

### GRUPCNTL-18 Description and Results
 1) The case has four producers with VFP tables, and two gas injectors.
 2) Producers and injectors are **standard wells**.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3. 
 7) Group RES: GCONPROD(GRPCNTL)=NO
 8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
 9) Well INJ1 re-completed 2019-03-01.
 10) Group RES: GCONPROD(GAS)=2.1E6 at 2019-06-01.

[GRUPCNTL-18 ECL Results](plots/GRUPCNTL-18-ECL.md)

[GRUPCNTL-18 REF Results](plots/GRUPCNTL-18-REF.md)

---

### GRUPCNTL-19 Description and Results
1) The case has four producers with VFP tables, and two gas injectors.
2) Producers and injectors are multi-segment wells.
3) Group control.
4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
5) WCONPROD(THP)=30.0 and VFP tables.
6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.  
7) Group RES: GCONPROD(GRPCNTL)=NO
8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
9) Well INJ1 re-completed 2019-03-01.
10) Group RES: GCONPROD(GAS)=2.1E6 at 2019-06-01.
11) Group RES: GCONSALE(GSALE)=0.75E6, GCONSALE(GSALEMAX=0.80E6), GCONSALE(GSALEMIN)=0.50E6, and  GCONSALE(ACTION)=RATE

[GRUPCNTL-19 ECL Results](plots/GRUPCNTL-19-ECL.md) 

[GRUPCNTL-19 REF Results](plots/GRUPCNTL-19-REF.md)

---

### GRUPCNTL-20 Description and Results
 1) The case has four producers with VFP tables, and two gas injectors.
 2) Producers and injectors are **standard wells**.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.  
 7) Group RES: GCONPROD(GRPCNTL)=NO
 8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
 9) Well INJ1 re-completed 2019-03-01.
 10) Group RES: GCONPROD(GAS)=2.1E6 at 2019-06-01.
 11) Group RES: GCONSALE(GSALE)=0.75E6, GCONSALE(GSALEMAX=0.80E6), GCONSALE(GSALEMIN)=0.50E6, and  GCONSALE(ACTION)=RATE

[GRUPCNTL-20 ECL Results](plots/GRUPCNTL-20-ECL.md)

[GRUPCNTL-20 REF Results](plots/GRUPCNTL-20-REF.md) 

---

### GRUPCNTL-21 Description and Results
 1) The case has four producers with VFP tables, and two gas injectors.
 2) Producers and injectors are multi-segment wells.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.  
 7) Group RES: GCONPROD(GRPCNTL)=NO
 8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
 9) Well INJ1 re-completed 2019-03-01.
 10) Group RES: GCONPROD(GAS)=2.1E6 at 2019-06-01.
 11) Group RES: GCONSALE(GSALE)=0.75E6, GCONSALE(GSALEMAX=0.80E6), GCONSALE(GSALEMIN)=0.50E6, and  GCONSALE(ACTION)=RATE
 12) Group RES: GCONSUMP(GASFUEL)=0.25E6

[GRUPCNTL-21 ECL Results](plots/GRUPCNTL-21-ECL.md)

[GRUPCNTL-21 REF Results](plots/GRUPCNTL-21-REF.md)

---

### GRUPCNTL-22 Description and Results
 1) The case has four producers with VFP tables, and two gas injectors.
 2) Producers and injectors are **standard wells**.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.  
 7) Group RES: GCONPROD(GRPCNTL)=NO
 8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
 9) Well INJ1 re-completed 2019-03-01.
 10) Group RES: GCONPROD(GAS)=2.1E6 at 2019-06-01.
 11) Group RES: GCONSALE(GSALE)=0.75E6, GCONSALE(GSALEMAX=0.80E6), GCONSALE(GSALEMIN)=0.50E6, and  GCONSALE(ACTION)=RATE
 12) Group RES: GCONSUMP(GASFUEL)=0.25E6

[GRUPCNTL-22 ECL Results](plots/GRUPCNTL-22-ECL.md) 

[GRUPCNTL-22 REF Results](plots/GRUPCNTL-22-REF.md)

---

### GRUPCNTL-23 Description and Results
 1) The case has four producers with VFP tables, and two gas injectors.
 2) Producers and injectors are **standard wells**.
 3) Group control.                   
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.  
 7) Group RES: GCONPROD(GRPCNTL)=NO
 8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
 9) Well INJ1 re-completed 2019-03-01, shut-in 2019-05-20.
 10) Group RES: GCONPROD(GAS)=2.3E6 at 2019-06-01.
 11) Group RES: GCONSALE(GSALE)=0.30E6, GCONSALE(GSALEMAX=0.40E6), GCONSALE(GSALEMIN)=0.05E6, and  GCONSALE(ACTION)=RATE
 12) Group RES: GCONSUMP(GASFUEL)=0.25E6
 13) Well INJE2: WCONINJE(BHP)=235.0 

[GRUPCNTL-23 ECL Results](plots/GRUPCNTL-23-ECL.md) 

[GRUPCNTL-23 REF Results](plots/GRUPCNTL-23-REF.md) 

---

### GRUPCNTL-24 Description and Results
 1) The case has four producers with VFP tables, and two gas injectors.
 2) Producers and injectors are multi-segment wells.
 3) Group control.                   
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.  
 7) Group RES: GCONPROD(GRPCNTL)=NO
 8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
 9) Well INJ1 re-completed 2019-03-01, shut-in 2019-05-20.
10) Group RES: GCONPROD(GAS)=2.3E6 at 2019-06-01.
11) Group RES: GCONSALE(GSALE)=0.30E6, GCONSALE(GSALEMAX=0.40E6), GCONSALE(GSALEMIN)=0.05E6, and  GCONSALE(ACTION)=RATE
12) Group RES: GCONSUMP(GASFUEL)=0.25E6
13) Well INJE2: WCONINJE(BHP)=235.0 

[GRUPCNTL-24 ECL Results](plots/GRUPCNTL-24-ECL.md) 

[GRUPCNTL-24 REF Results](plots/GRUPCNTL-24-REF.md)

---

### GRUPCNTL-25 Description and Results

```                                      
                                             FIELD
                                               |
                                              RES
                                 --------------+------------
                                 |                         |        
                               PROD                      INJE      
                       +-----+-----+-----+           +-----+-----+
                       |     |     |               |          
                    PROD1  PROD2  PROD3          INJE1      
``` 
 1) The case has four producers with VFP tables, and two gas injectors.
 2) Producers and injectors are multi-segment wells.
 3) Group control.                   
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) **Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.25E6, GCONPROD(LIQ)=15E3.** 
 7) Group RES: GCONPROD(GRPCNTL)=NO
 8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
 9) **Group RES: GCONSALE(GSALE)=0.60E6, GCONSALE(GSALEMAX=2.50E6), GCONSALE(GSALEMIN)=0.40E6, and  GCONSALE(ACTION)=RATE.**
 10) Group RES: GCONSUMP(GASFUEL)=0.25E6
 11) **Well INJE2: Not active.**
 12) **Well PROD1: Well failure 2019-03-01**.
 13) **Well PROD2: WELTARG(BHP)= 160.0 from 2019-03-01**.
 14) **Well PROD3: WELTARG(BHP)= 160.0 from 2019-03-01**.
 15) **Well PROD4: Not active**.

[GRUPCNTL-25 ECL Results](plots/GRUPCNTL-25-ECL.md)

[GRUPCNTL-25 REF Results](plots/GRUPCNTL-25-REF.md)

---

### GRUPCNTL-26 Description and Results
 1) The case has four producers with VFP tables, and two gas injectors.
 2) Producers and injectors are **standard wells**.
 3) Group control.                   
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.25E6, GCONPROD(LIQ)=15E3. 
 7) Group RES: GCONPROD(GRPCNTL)=NO
 8) Group INJE: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, GCONPROD(REIN)=1.0    
 9) Group RES: GCONSALE(GSALE)=0.60E6, GCONSALE(GSALEMAX=2.50E6), GCONSALE(GSALEMIN)=0.40E6, and  GCONSALE(ACTION)=RATE
 10) Group RES: GCONSUMP(GASFUEL)=0.25E6
 11) Well INJE2: Not active.
 12) Well PROD1: Well failure 2019-03-01.
 13) Well PROD2: WELTARG(BHP)= 160.0 from 2019-03-01.
 14) Well PROD3: WELTARG(BHP)= 160.0 from 2019-03-01.
 15) Well PROD4: Not active.

[GRUPCNTL-26 ECL Results](plots/GRUPCNTL-26-ECL.md)

[GRUPCNTL-26 REF Results](plots/GRUPCNTL-26-REF.md)

---

### GRUPCNTL-27 Description and Results
1) The case has four producers with VFP tables, and **two water injectors**.
2) Producers and injectors are multi-segment wells.
3) Group control.
4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
5) WCONPROD(THP)=30.0 and VFP tables.
6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, **GCONPROD(GAS)=1.6E6**, GCONPROD(LIQ)=15E3.
7) Group RES: GCONPROD(GRPCNTL)=NO.
8) **WCONJINJE(RATE)=8E3, same for both injectors**.

[GRUPCNTL-27 ECL Results](plots/GRUPCNTL-27-ECL.md) 

[GRUPCNTL-27 REF Results](plots/GRUPCNTL-27-REF.md) 

---

### GRUPCNTL-28 Description and Results
1) The case has four producers with VFP tables, and two water injectors.
2) Producers and injectors are **standard wells**.
3) Group control.
4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
5) WCONPROD(THP)=30.0 and VFP tables.
6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.
7) Group RES: GCONPROD(GRPCNTL)=NO.
8) WCONJINJE(RATE)=8E3, same for both injectors.

[GRUPCNTL-28 ECL Results](plots/GRUPCNTL-28-ECL.md)

[GRUPCNTL-28 REF Results](plots/GRUPCNTL-28-REF.md) 

---

### GRUPCNTL-29 Description and Results
1) The case has four producers with VFP tables, and two water injectors.
2) Producers and injectors are multi-segment wells.
3) Group control.
4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
5) WCONPROD(THP)=30.0 and VFP tables.
6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3. 
7) Group RES: GCONPROD(GRPCNTL)=NO.
8) WCONJINJE(RATE)=8E3, same for both injectors.
9) **Group RES: GCONINJE(TYPE)=WAT, GCONINJE(TARGET)=VREP, and GCONINJE(VREP)=1.0**.  

[GRUPCNTL-29 ECL Results](plots/GRUPCNTL-29-ECL.md) 

[GRUPCNTL-29 REF Results](plots/GRUPCNTL-29-REF.md)

---

### GRUPCNTL-30 Description and Results
1) The case has four producers with VFP tables, and two water injectors.
2) Producers and injectors are **standard wells**.
3) Group control.
4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
5) WCONPROD(THP)=30.0 and VFP tables.
6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3. 
7) Group RES: GCONPROD(GRPCNTL)=NO.
8) WCONJINJE(RATE)=8E3, same for both injectors.
9) Group RES: GCONINJE(TYPE)=WAT, GCONINJE(TARGET)=VREP, and GCONINJE(VREP)=1.0   

[GRUPCNTL-30 ECL Results](plots/GRUPCNTL-30-ECL.md)

[GRUPCNTL-30 REF Results](plots/GRUPCNTL-30-REF.md)

---

### GRUPCNTL-31 Description and Results
 1) The case has four producers with VFP tables, and one gas injector (INJ1) and one water injector (INJ2).
 2) Producers and injectors are multi-segment wells.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3. 
 7) Group RES: GCONPROD(GRPCNTL)=NO.
 8) **WCONJINJE(RATE)=8E3 for water injectors and WCONJINJE(RATE)=1.6E6 for gas injectors**.
 9) **Group RES: GCONINJE(TYPE)=WAT, GCONINJE(TARGET)=VREP, and GCONINJE(VREP)=1.25**  
 10) **Group RES: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, and GCONINJE(VREP)=1.00**   

[GRUPCNTL-31 ECL Results](plots/GRUPCNTL-31-ECL.md) 

[GRUPCNTL-31 REF Results](plots/GRUPCNTL-31-REF.md) 

---

### GRUPCNTL-32 Description and Results
 1) The case has four producers with VFP tables, and one gas injector (INJ1) and one water injector (INJ2).
 2) Producers and injectors are **standard wells**.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3. 
 7) Group RES: GCONPROD(GRPCNTL)=NO.
 8) WCONJINJE(RATE)=8E3 for water injectors and WCONJINJE(RATE)=1.6E6 for gas injectors.
 9) Group RES: GCONINJE(TYPE)=WAT, GCONINJE(TARGET)=VREP, and GCONINJE(VREP)=1.25   
 10) Group RES: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, and GCONINJE(VREP)=1.00   

[GRUPCNTL-32 ECL Results](plots/GRUPCNTL-32-ECL.md)   

[GRUPCNTL-32 REF Results](plots/GRUPCNTL-32-REF.md) 

---

### GRUPCNTL-33 Description and Results
 1) The case has four producers with VFP tables, and one gas injector (INJ1) and one water injector (INJ2).
 2) Producers and injectors are multi-segment wells.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.   
 7) Group RES: GCONPROD(GRPCNTL)=NO.
 8) WCONJINJE(RATE)=8E3 for water injectors and WCONJINJE(RATE)=1.6E6 for gas injectors.
 9) Group RES: GCONINJE(TYPE)=WAT, GCONINJE(TARGET)=VREP, and GCONINJE(VREP)=1.25   
 10) Group RES: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, and GCONINJE(VREP)=1.00   
 11) **Group RES: GCONPROD(GAS)=2.1E6 from 2019-06-01.**
 12) **GCONSALE(GSALE)=0.75E6, GCONSALE(GSALEMAX=0.80E6), GCONSALE(GSALEMIN)=0.50E6, and  GCONSALE(ACTION)=RATE, from 2019-06-01.**

[GRUPCNTL-33 ECL Results](plots/GRUPCNTL-33-ECL.md)

[GRUPCNTL-33 REF Results](plots/GRUPCNTL-33-REF.md)  

---

### GRUPCNTL-34 Description and Results
 1) The case has four producers with VFP tables, and one gas injector (INJ1) and one water injector (INJ2).
 2) Producers and injectors are **standard wells**.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.   
 7) Group RES: GCONPROD(GRPCNTL)=NO.
 8) WCONJINJE(RATE)=8E3 for water injectors and WCONJINJE(RATE)=1.6E6 for gas injectors.
 9) Group RES: GCONINJE(TYPE)=WAT, GCONINJE(TARGET)=VREP, and GCONINJE(VREP)=1.25   
 10) Group RES: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, and GCONINJE(VREP)=1.00   
 11) Group RES: GCONPROD(GAS)=2.1E6 from 2019-06-01.
 12) GCONSALE(GSALE)=0.75E6, GCONSALE(GSALEMAX=0.80E6), GCONSALE(GSALEMIN)=0.50E6, and  GCONSALE(ACTION)=RATE, from 2019-06-01.

[GRUPCNTL-34 ECL Results](plots/GRUPCNTL-34-ECL.md) 

[GRUPCNTL-34 REF Results](plots/GRUPCNTL-34-REF.md)  

---

### GRUPCNTL-35 Description and Results (No OPM Flow Reference Results on GitHub)
 1) The case has four producers with VFP tables, and one gas injector (INJ1) and one water injector (INJ2).
 2) Producers and injectors are multi-segment wells.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.   
 7) Group RES: GCONPROD(GRPCNTL)=NO.
 8) WCONJINJE(RATE)=8E3 for water injectors and WCONJINJE(RATE)=1.6E6 for gas injectors.
 9) Group RES: GCONINJE(TYPE)=WAT, GCONINJE(TARGET)=VREP, and GCONINJE(VREP)=1.25   
 10) Group RES: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, and GCONINJE(VREP)=1.00   
 11) Group RES: GCONPROD(GAS)=2.1E6 from 2019-06-01.
 12) GCONSALE(GSALE)=0.75E6, GCONSALE(GSALEMAX=0.80E6), GCONSALE(GSALEMIN)=0.50E6, and  GCONSALE(ACTION)=RATE, from 2019-06-01. 
 13) **GUIDRATE is used to prioritize wells with low GOR.**  

[GRUPCNTL-35 ECL Results](plots/GRUPCNTL-35-ECL.md) 

---

### GRUPCNTL-36 Description and Results (No OPM Flow Reference Results on GitHub)
 1) The case has four producers with VFP tables, and one gas injector (INJ1) and one water injector (INJ2).
 2) Producers and injectors are **standard wells**.
 3) Group control.
 4) WCONPROD(OIL)=4E3, WCONPROD(GAS)=4E6,WCONPROD(LIQ)=8E3, and WCONPROD(BHP)=60.0, same for all wells. 
 5) WCONPROD(THP)=30.0 and VFP tables.
 6) Group RES: GCONPROD(TARGET)=ORAT, GCONPROD(OIL)=10E3, GCONPROD(WAT)=12E3, GCONPROD(GAS)=1.6E6, GCONPROD(LIQ)=15E3.   
 7) Group RES: GCONPROD(GRPCNTL)=NO.
 8) WCONJINJE(RATE)=8E3 for water injectors and WCONJINJE(RATE)=1.6E6 for gas injectors.
 9) Group RES: GCONINJE(TYPE)=WAT, GCONINJE(TARGET)=VREP, and GCONINJE(VREP)=1.25   
 10) Group RES: GCONINJE(TYPE)=GAS, GCONINJE(TARGET)=REIN, and GCONINJE(VREP)=1.00   
 11) Group RES: GCONPROD(GAS)=2.1E6 from 2019-06-01.
 12) GCONSALE(GSALE)=0.75E6, GCONSALE(GSALEMAX=0.80E6), GCONSALE(GSALEMIN)=0.50E6, and  GCONSALE(ACTION)=RATE, from 2019-06-01. 
 13) GUIDRATE is used to prioritize wells with low GOR.  

[GRUPCNTL-36 ECL Results](plots/GRUPCNTL-36-ECL.md) 

---

### Field and Group Control Mode Reference
![](plots/GRUPCNTL-REF01.jpg)

### Field and Group Control Mode Reference
![](plots/GRUPCNTL-REF02.jpg)
