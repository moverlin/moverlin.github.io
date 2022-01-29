---
layout: custom
---

# Power Systems Simulation
---

### Relevant Publications

<!-- HPEC Supercloud, High-performance computing techniques in power systems -->
\item[\bullet] **Matthew Overlin**, Christopher Smith.  "High Performance Computing Techniques with Power Systems Simulations," in \textit{IEEE High Performance and Extreme Computing (HPEC)}.  2018.

<!-- FPGA Load flow -->
\item[\bullet] **Matthew Overlin**, Colm O'Rourke, Po-Hsu Huang, James Kirtley Jr., "A Timing Comparison of Different FPGA-Accelerated Load Flow Solvers," \textit{IEEE Innovative Smart Grid Technologies (ISGT) Brazil}.  2019.

<!-- SM, network, DAE's, WECC 9-bus network. -->
* **Matthew Overlin**, Marc Barbar, Krishnan Kant, Christopher Smith, James Kirtley Jr., "An Enhanced Time-Domain Simulator of Transient Stability in Power Systems," \textit{IEEE PowerAfrica Conference}.  2019.

<!-- Geometric DQ0 transformations, Colm O'Rourke -->
* Colm O'Rourke, Mohammad M. Qasim, **Matthew Overlin**, James Kirtley Jr., "A Geometric Interpretation of Reference Frames and Transformations: dq0, Clarke and Park," \textit{IEEE Transactions on Energy Conversion}.  2019.


# Parameter Estimation with Devices in Microgrids
---

<img align="right" width="255" src="./pictures/CPL_MG_annotated.png">
<img align="right" width="245" src="./pictures/experimental_Set_Up_right_half.png">
<img align="right" width="250" src="./pictures/prog_load_connected_outside.png">
<img align="right" width="250" src="./pictures/MEP_802A_5k_TQG.png">

### Relevant Publications

<!-- IEEE Transactions on Industrial Electronics, Load Identification -->
* **Matthew Overlin**, Christopher Smith, James L. Kirtley Jr.  "A Hybrid Algorithm for Parameter Estimation (HAPE) for Dynamic Constant Power Loads," in _IEEE Transactions on Industrial Electronics_.  2020.

<!-- IEEE Transactions on Energy Conversion, TQG diesel genset parameter estimation. -->
* [Accepted] **Matthew Overlin**, James Macomber, Christopher Smith, Luca Daniel, Edward Corbett, James L. Kirtley Jr.  "A Hybrid Algorithm for Parameter Estimation (HAPE) for Diesel Generator Sets," in _IEEE Transactions on Energy Conversion_.  2022.


# Reconfigurability and System Stability in Microgrids
---

### Relevant Publications

<!-- Paper from Xia, SM PHiL work -->
* Xia Miao, Marija Ilic, Christopher Smith, **Matthew Overlin**, Ryan Wiechens.  "Toward Distributed Control for Reconfigurable Robust Microgrids," in _IEEE Energy Conversion Congress and Exposition (ECCE)_.  2020.

<!-- IEEE Transactions on Power Delivery, Solar APF paper. -->
* [Submitted] **Matthew Overlin**, James Macomber, Christopher Smith, Luca Daniel, Edward Corbett, James L. Kirtley Jr.  "Parameter Selection for Harmonic Mitigation in Rooftop Photovoltaic Systems," in _IEEE Transactions on Power Delivery_.  2021.


# Power Electronics
---

### Relevant Publications

<!-- APEC Load Identification -->
* **Matthew Overlin**, Christopher Smith, Marija Ilic, James L. Kirtley Jr.  "A Workflow for Non-linear Load Parameter Estimation using a Power-Hardware-in-the-Loop Experimental Testbed," in \textit{Applied Power Electronics Conference (APEC)}.  2020.

<!-- APEC multi-functional AC-AC converter -->
* Krishan Kant, **Matthew Overlin**, Lukasz Huchel, Mohammad Qasim, James L. Kirtley Jr..  "Self Synchronizing Controller for a Multifunctional Single Phase AC-DC-AC Converter," in _Applied Power Electronics Conference (APEC)_.  2020.


## Parameter Estimation for Dynamic Constant Power Loads
---

<img align="right" width="255" src="./pictures/CPL_MG_annotated.png">
<img align="right" width="245" src="./pictures/experimental_Set_Up_right_half.png">

<br/><br/>

Low-inertia microgrids may easily have a single load that can make up most of the total load, thereby greatly affecting stability and power quality. Instead of a static load model, a dynamic constant power load (DCPL) model is considered here. Next, a hybrid algorithm for parameter estimation (HAPE) is introduced. In order to verify the load model and the HAPE, two experiments are conducted with different DCPLs using a power-hardware-in-the-loop (PHiL) testbed. The PHiL testbed consists of a real-time computer working with a programmable power amplifier in order to perturb the input voltage's amplitude and frequency. Each connected DCPL in two separate experiments serves as the device under test. Using the captured experimental data as a reference, the HAPE is then invoked. The resulting parameter estimates are used to define simulation models. Both resulting DCPL models are simulated to produce waveforms that closely resemble experimental waveforms. Finally, the HAPE's resulting parameter estimates are presented, and the performance of the HAPE is discussed.

## Parameter Estimation for Diesel Generator Sets
---

<img align="right" width="250" src="./pictures/prog_load_connected_outside.png">
<img align="right" width="250" src="./pictures/MEP_802A_5k_TQG.png">

<br/><br/>

In order to simulate the dynamic phenomena of devices within a microgrid, suitable simulation models are needed.  Historically, parameterization approaches have been explored for large generator sets rather than for smaller generator sets, which would be more suitable in a microgrid.  Additionally, non-invasive experimental methods are often preferred over invasive methods when collecting data.  Further, if there are many uncertain parameters, then it is more imperative to employ a larger computing platform.  In this work, a hybrid algorithm for parameter estimation (HAPE) is utilized to find a fitting simulation model for a diesel genset.  A Sobol parameter sensitivity analysis is conducted to inform the HAPE of the more influential parameters.  Finally, the HAPE is developed for a supercomputing platform so that the HAPE can be executed in a massively parallel fashion.

[Home](./)
