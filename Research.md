---
layout: custom
---

## Power Systems Simulation

# Relevant Publications

1.  Item one
1.  Item two
1.  Item three
1.  Item four

## Parameter Estimation with Devices in Microgrids

## Reconfigurability and System Stability in Microgrids

## Power Electronics

# Relevant Publications

1.  Item one
1.  Item two
1.  Item three
1.  Item four



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
