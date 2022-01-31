---
layout: custom
---

# Research
---

## Power Systems Simulation
---

<img align="right" width="250" src="./pictures/Enhanced_Sim_PowerAfrica.png">
<img align="right" width="250" src="./pictures/Colm_dq0_geometric.png">
<img align="right" width="500" src="./pictures/HPEC_diagram.png">


<br />
I have explored different methods for the numerical simulation of power systems.  Some of the work includes high performance computing techniques in large power systems, simulations on certain hardware platforms with FPGAs, and adjustments to a numerical integration method to achieve faster simulation times.  Finally, in order to clarify some key concepts, I have co-authored a paper which considers a geomettric interpretation for reference frames and the transformations between them.

### Relevant Publications

<!-- HPEC Supercloud, High-performance computing techniques in power systems -->
* **Matthew Overlin**, Christopher Smith.  "High Performance Computing Techniques with Power Systems Simulations," in _IEEE High Performance and Extreme Computing (HPEC)_.  2018.

<!-- FPGA Load flow -->
* **Matthew Overlin**, Colm O'Rourke, Po-Hsu Huang, James Kirtley Jr., "A Timing Comparison of Different FPGA-Accelerated Load Flow Solvers," _IEEE Innovative Smart Grid Technologies (ISGT) Brazil_.  2019.

<!-- SM, network, DAE's, WECC 9-bus network. -->
* **Matthew Overlin**, Marc Barbar, Krishnan Kant, Christopher Smith, James Kirtley Jr., "An Enhanced Time-Domain Simulator of Transient Stability in Power Systems," _IEEE PowerAfrica Conference_.  2019.

<!-- Geometric DQ0 transformations, Colm O'Rourke -->
* Colm O'Rourke, Mohammad M. Qasim, **Matthew Overlin**, James Kirtley Jr., "A Geometric Interpretation of Reference Frames and Transformations: dq0, Clarke and Park," _IEEE Transactions on Energy Conversion_.  2019.


## Parameter Estimation with Devices in Microgrids
---

<img align="right" width="255" src="./pictures/CPL_MG_annotated.png">
<img align="right" width="245" src="./pictures/experimental_Set_Up_right_half.png">
<!-- <img align="right" width="250" src="./pictures/prog_load_connected_outside.png"> -->
<!-- <img align="right" width="250" src="./pictures/MEP_802A_5k_TQG.png"> -->

<br />
<br />
As part of my PhD research, I developed a hybrid algorithm for parameter estimation (HAPE) which is used to estimate the parameters in simulaiton models for dynamic constant power loads (DCPLs) and diesel generator sets.  In each piece of work, the HAPE considers non-invasive measurement waveforms (voltage and current).  These measurement waveforms are to be matched with corresponding waveforms from a similar simulation.  The HAPE is executed in a massively parallel fashion on a supercomputing platform maintained by the Lincoln Laboratory Supercomputing Center (LLSC).

### Relevant Publications

<!-- IEEE Transactions on Industrial Electronics, Load Identification -->
* **Matthew Overlin**, Christopher Smith, James L. Kirtley Jr.  "A Hybrid Algorithm for Parameter Estimation (HAPE) for Dynamic Constant Power Loads," in _IEEE Transactions on Industrial Electronics_.  2020.

<!-- IEEE Transactions on Energy Conversion, TQG diesel genset parameter estimation. -->
* [Accepted] **Matthew Overlin**, James Macomber, Christopher Smith, Luca Daniel, Edward Corbett, James L. Kirtley Jr.  "A Hybrid Algorithm for Parameter Estimation (HAPE) for Diesel Generator Sets," in _IEEE Transactions on Energy Conversion_.  2022.


## Reconfigurability and System Stability in Microgrids
---

<img align="right" width="500" src="./pictures/Reconfigurable_microgrids_Xia_ECCE.png">

I am interested in the operation of low voltage microgrids.  In some of my research I have investigated stable operational states which are reconfigurable and robust.  More specifically, I am interested in a single-family home as a case study- one which includes 1 or 2 electric vehicles, a rooftop solar system, and perhaps other sub-systems which may be installed inside a modern all-electric home.

### Relevant Publications

<!-- Paper from Xia, SM PHiL work -->
* Xia Miao, Marija Ilic, Christopher Smith, **Matthew Overlin**, Ryan Wiechens.  "Toward Distributed Control for Reconfigurable Robust Microgrids," in _IEEE Energy Conversion Congress and Exposition (ECCE)_.  2020.

<!-- IEEE Transactions on Power Delivery, Solar APF paper. -->
* [Submitted] **Matthew Overlin**, James Macomber, Christopher Smith, Luca Daniel, Edward Corbett, James L. Kirtley Jr.  "Parameter Selection for Harmonic Mitigation in Rooftop Photovoltaic Systems," in _IEEE Transactions on Power Delivery_.  2021.


## Power Electronics
---

<img align="right" width="500" src="./pictures/AC_AC_converter_Kant_APEC.png">

In order to enable flexible grid topologies for single phase systems, the design, operation, and control of microgrids
both globally and locally become important. Bi-directional power flow, seamless operational transitions in the midst of disturbances
and the integration of new technologies are all relevant in modern power systems. To enable such important functionality, we may explore new additions to the rectifier and inverter controllers
in an AC-AC converter with a topology containing few switches.  
In addition to some of these modifications, I am also interested in some of the enhancements to conventional control methods which can allow for versatile operation in power systems.


### Relevant Publications

<!-- APEC Load Identification -->
* **Matthew Overlin**, Christopher Smith, Marija Ilic, James L. Kirtley Jr.  "A Workflow for Non-linear Load Parameter Estimation using a Power-Hardware-in-the-Loop Experimental Testbed," in _Applied Power Electronics Conference (APEC)_.  2020.

<!-- APEC multi-functional AC-AC converter -->
* Krishan Kant, **Matthew Overlin**, Lukasz Huchel, Mohammad Qasim, James L. Kirtley Jr..  "Self Synchronizing Controller for a Multifunctional Single Phase AC-DC-AC Converter," in _Applied Power Electronics Conference (APEC)_.  2020.


[Home](./)
