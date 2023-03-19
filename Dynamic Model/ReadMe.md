# Dynamic Model

* Dynamic model inlcude effect of voltage and current hysterisis. Effect of diffusion voltage can also be considered.
* The code solves state-spcace equations to estimate all the model parameters.

__Ref : Dr.Gregory L. Plett, UCCS, ECE4710/5710: Modeling, Simulation, and Identification of Battery Dynamics__

## Dynamic Prameter Test

### Test Script 1 (At Test Temperature)
* Soak the fully charged cell at the test temperature for at least 2h to ensure a uniform temperature throughout the cell.
* Discharge the cell using a constant current at a C/1 rate long enough to deplete about 10% of capacity (helping ensure we avoid over-voltage conditions during random charging portions of the dynamic profile).
* Execute dynamic profiles over the SOC range of interest, nominally from 90% SOC down to 10% SOC.

### Test Script 2 (At 25°C)
* Soak the fully charged cell at the 25°C for at least 2h to ensure a uniform temperature throughout the cell.
* If the cell voltage is below Vmin, then charge the cell at a C/30 rate until the voltage is equal to Vmin. If the cell voltage is above Vmin then discharge the cell at a C/30 rate until the voltage is equal to Vmin, Follow-on dither profile(s) can be used to eliminate hysteresis to the greatest degree possible.

### Test Script 3 (At 25°C)
* Charge the cell using a constant current at a C/1 rate until voltage is equal to Vmax. Then, maintain voltage constant at Vmax until current drops below C/30. Follow-on dither profile(s) at the end can be used to help eliminate hysteresis.


