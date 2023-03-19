# Static Model

* Static model includes charging the cell at very low current ~C/10
* This way effect of hysterisis can be avoided. The measured terminal voltage can be used to extract OCV
* Simple OCV and SOC realation for different temperatures can be established and values can be stored in lookup table.

## Static Parameter Estimation Tests

### Test Script 1 (At Test Temperature)
* Soak the fully charged cell at the test temperature for at least 2h to ensure a uniform temperature throughout the cell.
* Discharge the cell at a constant-current rate of C/30 until cell terminal voltage equals manufacturer-specified Vmin.

### Test Script 2 (At 25°C)
* Soak the fully charged cell at the 25°C for at least 2h to ensure a uniform temperature throughout the cell.
* If the cell voltage is below Vmin, then charge the cell at a C/30 rate until the voltage is equal to Vmin. If the cell voltage is above Vmin then discharge the cell at a C/30 rate until the voltage is equal to Vmin

### Test Script 3 (At Test Temperature)
* Soak the fully charged cell at the test temperature for at least 2h to ensure a uniform temperature throughout the cell.
* Charge the cell at a constant-current rate of C/30 until cell terminal voltage equals manufacturer-specified Vmin.

### Test Script 4 (At 25°C)
* Soak the fully charged cell at the 25°C for at least 2h to ensure a uniform temperature throughout the cell.
* If the cell voltage is below Vmax, then charge the cell at a C/30 rate until the voltage is equal to Vmax. If the cell voltage is above Vmax, then discharge the cell at a C/30 rate until the voltage is equal to Vmax.

