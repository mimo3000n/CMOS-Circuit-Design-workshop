# CMOS-Circuit-Design-workshop
CMOS Circuit Design workshop 25.8-3.9.2025


<img width="1194" height="581" alt="image" src="https://github.com/user-attachments/assets/81c972d8-d197-4d79-9f97-9cfbf1eb22f7" />

## Overview

This workshop is designed to provide a deep understanding of CMOS design fundamentals through SPICE simulations. Over five days, participants will explore the behavior of NMOS and CMOS inverters in different operating regions, evaluate switching thresholds, noise margins, and analyze robustness against supply and device variations. Each session includes hands-on SPICE simulations backed by strong theoretical foundations, making it ideal for learners who wish to master transistor-level circuit behavior.

The global semiconductor resurgence – fueled by sovereign CHIPS initiatives, a surging demand for edge‑AI silicon, and an acute shortage of analog‑mixed‑signal talent – has made open, mature‑node platforms like SKY130 the fastest on‑ramp from idea to tape‑out. This ten‑day, cloud based online workshop positions you at the heart of that movement, translating industry‑grade CMOS theory into actionable design insight while leveraging the very PDK that start‑ups, national fabs, and university shuttle programs now rely on for first‑silicon success.

Across 10-days, you will dissect device physics, construct parameter‑swept SPICE decks, and benchmark inverter robustness under real‑world process and voltage variation. Each module pairs concise lectures with guided labs – covering velocity‑saturation, noise‑margin optimisation, dynamic power analysis, and script‑driven verification – so every concept is cemented by plots you generate yourself. Exclusive toolchains, reference designs, and daily design clinics ensure you leave with reusable IP blocks and a repeatable simulation workflow that dovetails directly into open‑source RTL‑to‑GDS flows such as OpenLane and VSDFlow.

Graduates emerge ready to contribute immediately to low‑power IoT nodes, automotive safety ICs, and chiplet‑based heterogenous packages – all markets leaning heavily on 130 nm for cost‑balanced innovation. Whether you aim to upskill a design team, strengthen research credentials, or fast‑track a prototype toward fabrication, this program delivers the simulation mastery and process‑aware mindset demanded by today’s accelerated semiconductor landscape.

------------------------------------------------------------

## NgspiceSky130 - Day 1 - Basics of NMOS Drain current (Id) vs Drain-to-source Voltage (Vds)
------------------------------------------------------------
<details>
<summary>Introduction to Circuit Design and SPICE simulations</summary>
  
### Introduction to Circuit Design and SPICE simulations ###
    
- L1 Why do we need SPICE simulations?

  <img width="1005" height="694" alt="image" src="https://github.com/user-attachments/assets/9e6f5f1d-acd9-41bb-b17b-2ab56a2c7949" />


  <img width="1425" height="940" alt="image" src="https://github.com/user-attachments/assets/7b2639e7-5e85-4db1-923e-881f9306c85f" />


  <img width="1809" height="934" alt="image" src="https://github.com/user-attachments/assets/fa2b335c-e986-491f-b35c-4c90a9b946f0" />
  

  <img width="1783" height="854" alt="image" src="https://github.com/user-attachments/assets/045d766e-ffd6-4603-814c-e72da1b8e97d" />

  
- L2 Introduction to basic element in Circuit design – NMOS

<img width="1640" height="693" alt="image" src="https://github.com/user-attachments/assets/504dc4ac-501d-46bc-bcdf-b4803ce765f1" />


<img width="1796" height="843" alt="image" src="https://github.com/user-attachments/assets/4a2b07d5-41fa-4d0f-8ab0-1e1bdc3087cd" />


<img width="1792" height="842" alt="image" src="https://github.com/user-attachments/assets/ae94c9b3-623f-49a1-bf57-3cbc145b2dd8" />


- L3 Strong inversion and threshold voltage

<img width="1792" height="842" alt="image" src="https://github.com/user-attachments/assets/161f760f-5bfe-48a1-90e5-63f95d3bd903" />


<img width="1962" height="751" alt="image" src="https://github.com/user-attachments/assets/e42d18c3-4e4c-4ed4-bc7c-5a69278058dd" />


<img width="1962" height="751" alt="image" src="https://github.com/user-attachments/assets/bb97050c-5569-494c-9e8f-78d3ace27b85" />


<img width="1837" height="843" alt="image" src="https://github.com/user-attachments/assets/04355acb-8a45-4a56-b9b5-b12e9e0c87a3" />


<img width="1701" height="844" alt="image" src="https://github.com/user-attachments/assets/2af88005-3543-4eb4-9897-2590d7876ddd" />

<img width="1710" height="828" alt="image" src="https://github.com/user-attachments/assets/70f222c4-c63b-400e-aa56-241fab6c61e4" />

<img width="1704" height="824" alt="image" src="https://github.com/user-attachments/assets/d6b89001-627d-4c45-bf0f-50bd8a733792" />

<img width="1796" height="844" alt="image" src="https://github.com/user-attachments/assets/6e5e4d55-4706-4c58-a9d3-0bbd0d570e05" />


<img width="1914" height="926" alt="image" src="https://github.com/user-attachments/assets/bf9a9287-dc70-484c-afda-51883b5d8687" />

- L4 Threshold voltage with positive substrate potential

<img width="1826" height="874" alt="image" src="https://github.com/user-attachments/assets/e2225b29-23c5-44ab-b755-1ca8b1f3f0df" />
 
 </details>  

<details>			
<summary>NMOS resistive region and saturation region of operation</summary>

### NMOS resistive region and saturation region of operation

- L1 Resistive region of operation with small drain-source voltage

<img width="1870" height="839" alt="image" src="https://github.com/user-attachments/assets/dd7b9b01-34bf-4b4d-87e4-a09fdd3ecf95" />

  
- L2 Drift current theory

  <img width="1846" height="844" alt="image" src="https://github.com/user-attachments/assets/1084f4e9-1165-4e0b-9911-5ac06fd62210" />

  <img width="1897" height="842" alt="image" src="https://github.com/user-attachments/assets/c3b5b71e-9384-421c-835f-6a3bc39689aa" />

  <img width="1793" height="924" alt="image" src="https://github.com/user-attachments/assets/4a8c0e54-123c-4c55-9798-b72ccb6f872d" />

  



  
- L3 Drain current model for linear region of operation
  
- L4 SPICE conclusion to resistive operation
   
- L5 Pinch-off region condition
    
- L6 Drain current model for saturation region of operation
  
</details>		

<details>		
<summary>Introduction to SPICE</summary>

### Introduction to SPICE
    
- L1 Basic SPICE setup
     
- L2 Circuit description in SPICE syntax
    
- L3 Define technology parameters
     
- L4 First SPICE simulation

enter following command to clone repository:

git clone https://github.com/kunalg123/sky130CircuitDesignWorkshop.git
 
 <img width="893" height="218" alt="image" src="https://github.com/user-attachments/assets/3daa0f57-a4b8-4e61-8dab-8fadbf1c1eb8" />

goto "~/sky130CircuitDesignWorkshop/design"

<img width="1068" height="277" alt="image" src="https://github.com/user-attachments/assets/98a0d853-f0ba-4808-b7f7-3db1cea335b0" />

cell definition which wer use in our workshop are in "~/sky130CircuitDesignWorkshop/design/sky130_fd_pr/cells".

nfet_01v8 - NMOS
pfet_01v8 - PMOS

<img width="741" height="142" alt="image" src="https://github.com/user-attachments/assets/6c827099-482c-4f19-a0b1-bb63989c3b00" />

if we go to "nfet_01v8" and do an ls we have all lib files for different corners.

<img width="1250" height="171" alt="image" src="https://github.com/user-attachments/assets/6e6ce39e-adc8-48ac-bd4e-24a4246fa7a8" />

file "sky130_fd_pr__nfet_01v8__tt.pm3.spice" contain different model parameters.

``` spice
* Copyright 2020 The SkyWater PDK Authors
*
* Licensed under the Apache License, Version 2.0 (the "License");
* you may not use this file except in compliance with the License.
* You may obtain a copy of the License at
*
*     https://www.apache.org/licenses/LICENSE-2.0
*
* Unless required by applicable law or agreed to in writing, software
* distributed under the License is distributed on an "AS IS" BASIS,
* WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
* See the License for the specific language governing permissions and
* limitations under the License.

* SKY130 Spice File.
* Number of bins: 63
.param
+ sky130_fd_pr__nfet_01v8__toxe_mult = 1.0
+ sky130_fd_pr__nfet_01v8__rshn_mult = 1.0
+ sky130_fd_pr__nfet_01v8__overlap_mult = 0.9642
+ sky130_fd_pr__nfet_01v8__lint_diff = 0.0
+ sky130_fd_pr__nfet_01v8__wint_diff = 0.0
+ sky130_fd_pr__nfet_01v8__dlc_diff = -.61492e-9
+ sky130_fd_pr__nfet_01v8__dwc_diff = 0.0
*
* sky130_fd_pr__nfet_01v8, Bin 000, W = 1.26, L = 0.15
* -----------------------------------
+ sky130_fd_pr__nfet_01v8__voff_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__kt1_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ub_diff_0 = -1.1675e-19
+ sky130_fd_pr__nfet_01v8__pditsd_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ua_diff_0 = 1.3935e-11
+ sky130_fd_pr__nfet_01v8__vsat_diff_0 = 594.41
+ sky130_fd_pr__nfet_01v8__tvoff_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ags_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__a0_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__b0_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__pclm_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__pdits_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__keta_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__rdsw_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__k2_diff_0 = 0.0031843
+ sky130_fd_pr__nfet_01v8__vth0_diff_0 = -0.024441
+ sky130_fd_pr__nfet_01v8__nfactor_diff_0 = 0.37668
+ sky130_fd_pr__nfet_01v8__u0_diff_0 = -0.0034894
+ sky130_fd_pr__nfet_01v8__eta0_diff_0 = 0.0
........

```

file "sky130_fd_pr__nfet_01v8__tt.corner.spice" contein different L andW parameters

``` spice
* Copyright 2020 The SkyWater PDK Authors
*
* Licensed under the Apache License, Version 2.0 (the "License");
* you may not use this file except in compliance with the License.
* You may obtain a copy of the License at
*
*     https://www.apache.org/licenses/LICENSE-2.0
*
* Unless required by applicable law or agreed to in writing, software
* distributed under the License is distributed on an "AS IS" BASIS,
* WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
* See the License for the specific language governing permissions and
* limitations under the License.

* SKY130 Spice File.
* Number of bins: 63
.param
+ sky130_fd_pr__nfet_01v8__toxe_mult = 1.0
+ sky130_fd_pr__nfet_01v8__rshn_mult = 1.0
+ sky130_fd_pr__nfet_01v8__overlap_mult = 0.9642
+ sky130_fd_pr__nfet_01v8__lint_diff = 0.0
+ sky130_fd_pr__nfet_01v8__wint_diff = 0.0
+ sky130_fd_pr__nfet_01v8__dlc_diff = -.61492e-9
+ sky130_fd_pr__nfet_01v8__dwc_diff = 0.0
*
* sky130_fd_pr__nfet_01v8, Bin 000, W = 1.26, L = 0.15
* -----------------------------------
+ sky130_fd_pr__nfet_01v8__voff_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__kt1_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ub_diff_0 = -1.1675e-19
+ sky130_fd_pr__nfet_01v8__pditsd_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ua_diff_0 = 1.3935e-11
+ sky130_fd_pr__nfet_01v8__vsat_diff_0 = 594.41
+ sky130_fd_pr__nfet_01v8__tvoff_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ags_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__a0_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__b0_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__pclm_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__pdits_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__keta_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__rdsw_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__k2_diff_0 = 0.0031843
+ sky130_fd_pr__nfet_01v8__vth0_diff_0 = -0.024441
+ sky130_fd_pr__nfet_01v8__nfactor_diff_0 = 0.37668
+ sky130_fd_pr__nfet_01v8__u0_diff_0 = -0.0034894
+ sky130_fd_pr__nfet_01v8__eta0_diff_0 = 0.0

* sky130_fd_pr__nfet_01v8, Bin 001, W = 1.68, L = 0.15
* -----------------------------------
+ sky130_fd_pr__nfet_01v8__eta0_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__b1_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__voff_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__kt1_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__ub_diff_1 = -1.6979e-19
+ sky130_fd_pr__nfet_01v8__pditsd_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__ua_diff_1 = 1.0381e-11
+ sky130_fd_pr__nfet_01v8__vsat_diff_1 = 249.83
+ sky130_fd_pr__nfet_01v8__tvoff_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__ags_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__a0_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__b0_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__pclm_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__pdits_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__keta_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__rdsw_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__k2_diff_1 = 0.0047171
+ sky130_fd_pr__nfet_01v8__vth0_diff_1 = 0.0064909
+ sky130_fd_pr__nfet_01v8__nfactor_diff_1 = 0.31936
+ sky130_fd_pr__nfet_01v8__u0_diff_1 = -0.002698
*
* sky130_fd_pr__nfet_01v8, Bin 002, W = 1.0, L = 1.0
* ---------------------------------
+ sky130_fd_pr__nfet_01v8__nfactor_diff_2 = 1.11
+ sky130_fd_pr__nfet_01v8__u0_diff_2 = -9.2293e-5
+ sky130_fd_pr__nfet_01v8__vth0_diff_2 = 0.0065633
+ sky130_fd_pr__nfet_01v8__eta0_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__b1_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__voff_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__ub_diff_2 = 1.6548e-19
+ sky130_fd_pr__nfet_01v8__kt1_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__pditsd_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__ua_diff_2 = 4.5462e-13
+ sky130_fd_pr__nfet_01v8__vsat_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__tvoff_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__ags_diff_2 = -0.052872
+ sky130_fd_pr__nfet_01v8__a0_diff_2 = 0.23412
+ sky130_fd_pr__nfet_01v8__b0_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__pclm_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__pdits_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__keta_diff_2 = 0.0
*
.......

```
 
- L5 SPICE Lab with sky130 models
    
 </details> 

------------------------------------------------------------

## NgspiceSky130 - Day 2 - Velocity saturation and basics of CMOS inverter VTC	
------------------------------------------------------------

<details>
<summary>SPICE simulation for lower nodes and velocity saturation effect</summary>
  
###	SPICE simulation for lower nodes and velocity saturation effect	

- L1 SPICE simulation for lower nodes

- L2 Drain current vs gate voltage for long and short channel device

- L3 Velocity saturation at lower and higher electric fields

- L4 Velocity saturation drain current model

- L5 Labs Sky130 Id-Vgs

- L6 Labs Sky130 Vt
</details>

<details>
<summary>CMOS voltage transfer characteristics (VTC)</summary>

###	CMOS voltage transfer characteristics (VTC)

- L1 MOSFET as a switch

- L2 Introduction to standard MOS voltage current parameters

- L3 PMOS/NMOS drain current v/s drain voltage

- L4 Step1 – Convert PMOS gate-source-voltage to Vin

- L5 Step2 & Step3 – Convert PMOS and NMOS drain-source-voltage to vout

- L6 Step4 – Merge PMOS – NMOS load curves and plot VTC

</details>

----------------------------------------
## NgspiceSky130 - Day 3 - CMOS Switching threshold and dynamic simulations
----------------------------------------

<details>
<summary>Voltage transfer characteristics – SPICE simulations</summary>
  
### Voltage transfer characteristics – SPICE simulations

- L1 SPICE deck creation for CMOS inverter

- L2 SPICE simulation for CMOS inverter

- L3 Labs Sky130 SPICE simulation for CMOS

</details>

<details>
<summary>Static behavior evaluation – CMOS inverter robustness – Switching Threshold</summary>
	
### Static behavior evaluation – CMOS inverter robustness – Switching Threshold
	
- L1 Switching Threshold, Vm

- L2 Analytical expression of Vm as a function of (W/L)p and (W/L)n

- L3 Analytical expression of (W/L)p and (W/L)n as a function of Vm

- L4 Static and dynamic simulation of CMOS inverter

- L5 Static and dynamic simulation of CMOS inverter with increased PMOS width

- L6 Applications of CMOS inverter in clock network and STA

</details>

-------------------------------
## NgspiceSky130 - Day 4 - CMOS Noise Margin robustness evaluation
-------------------------------

<details>
<summary>Static behavior evaluation – CMOS inverter robustness – Noise margin</summary>
	
### Static behavior evaluation – CMOS inverter robustness – Noise margin	

- L1 Introduction to noise margin

- L2 Noise margin voltage parameters

- L3 Noise margin equation and summary

- L4 Noise margin variation with respect to PMOS width

- L5 Sky130 Noise margin labs

</details>

----------------------------------
## NgspiceSky130 - Day 5 - CMOS power supply and device variation robustness evaluation
----------------------------------

<details>
<summary>Static behavior evaluation – CMOS inverter robustness – Power supply variation</summary>
	
### Static behavior evaluation – CMOS inverter robustness – Power supply variation

- L1 Smart SPICE simulation for power supply variations

- L2 Advantages and disadvantages using low supply voltage

- L3 Sky130 Supply Variation Labs

</details>

<details>
<summary>Static behavior evaluation – CMOS inverter robustness – Device variation</summary>
	
### Static behavior evaluation – CMOS inverter robustness – Device variation	

- L1 Sources of variation – Etching process

- L2 Sources of variation – oxide thickness

- L3 Smart SPICE simulation for device variations

- L4 Conclusion

- L5 Sky130 Device Variation Labs

</details>
