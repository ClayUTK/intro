---
layout: archive
#title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---
 
{% include base_path %}
 
# 1.	Design and Development of PMU Hardware and Software (Real-Time PMU System)
*	Managed and maintained the FNET/GridEye wide-area monitoring system under the supervision of Dr. Yilu Liu, supporting field deployment and system reliability.
*	Gained hands-on experience with PMU and waveform measurement hardware (ADC sampling, GPS/PPS timing, FNET protocol & IEEE Standard C37.118-compliant data transmission). 
*	Implemented and optimized synchrophasor estimation for real-time embedded platforms.
*	Debugged and resolved system-level issues across new PMU hardware, timing, and frequency estimation, such as PCB hardware bring-up challenges, DFT timing shift, and GPS/PPS timing.

# 2.	Design of a New High-Precision Timing Source (FPGA + ADC + PPS)
*	Used a signal generator to emulate pulsar profiles and employed a high-rate ADC for sampling.
*	Developed FPGA firmware to process raw samples in real time and stream high-throughput data to a server over a 10-GbE interface and PF_RING package.
*	Applied polyphase filter bank processing, folding, and period estimation to extract pulsar period and calibrate the local oscillator, generating a highly accurate PPS output synchronized to GPS.

# 3.	Key technologies of digital power grid (edge computing + data compression) 
*	Collaborated with China Southern Power Grid on the design of edge-computing devices for distribution grids, supporting integrated monitoring, protection, control, and PMU capabilities.
*	Worked with container-based embedded infrastructure enabling modular deployment.
*	Designed and implemented real-time PMU data compression algorithms achieving high accuracy and high compression ratio for large-scale data transmission and storage.


