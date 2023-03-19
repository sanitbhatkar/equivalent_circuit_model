# Equivalent Circuit Model



The repository has Battery Equivalent Circuit model coded explained in the lecture notes. The code is written in Python. The battery data is also provided by the Professor.

__Ref : Dr.Gregory L. Plett, UCCS, ECE4710/5710: Modeling, Simulation, and Identification of Battery Dynamics__

## Nomenclature
#### Open Circuit Voltage
Cell deliver this voltage at its terminal. The voltage reduces as we draw current out of the cell and increases as we charge the cell. We cannot directly measure open circuit voltage (OCV) as it is present in equilibrium condition.

#### State of Charge
State of charge (SOC) is 100% when cell is fully charged and 0% when it is fully discharged. Every cell has fixed amount of charge capacity or Total capacity Q (A-h) which is unique to the cell. When cell is charged, SOC increased and when discharged SOC decreases. Total capacity is not a function of temperature or current. It decreases gradually due to parasitic reactions occurring in the cell. The SOC can be expressed by the equation below.
</br>$\frac{dz}{dt}=-\frac{\eta(t)i(t)}{Q}$
