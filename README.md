# -Powerful-Flashlight
 Powerful Flashlight simulations, PCBs and etc.

 WARNING: The files are simulations only. No real field tests have been conducted. AI has been used to support the models of components for which manufacturer models are not available.
 I recommend contacting the component manufacturers for accurate data and support. Please do not use these simulations for any circuits other than FlashLight.

 *12/26/2025 added LTSpice LT3477 adj Led Driver with XHP708 LED simulation
 
 *12/28/2025 added LTSpice S-82B2A/B 2S BMS IC Over Current Protection Simulation

 *12/28/2025 added LTSpice S-82B2A/B 2S BMS IC Low Voltage Protection Simulation

 *12/29/2025 added LTspice S82B2A/B 2S BMS IC Over Voltage Protection Simulation
 Changed * S-82B2AAA Behavioral Model (2-Cell Protection)
 *BCO CO_int 0 V=IF((V(Vc1)>VCU | V(Vc2)>VCU), 0, 1)
 BCO CO_int 0 V=IF(V(Vc1) > VCU | V(Vc2) > VCU, 0, IF(V(Vc1) < VCL & V(Vc2) < VCL, 1, IF(V(CO_dly) > 0.5, 1, 0)))
 Not: reconsider later for other simulations.
