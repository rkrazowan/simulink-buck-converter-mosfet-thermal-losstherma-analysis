# simulink-buck-converter-mosfet-thermal-losstherma-analysis
"MATLAB/Simulink and Simscape model for a Buck Converter to analyze MOSFET junction temperature and dynamic power dissipation. Includes a custom MATLAB function for quick statistics logging."


# Buck Converter Thermal Analysis & Power Loss Simulation

This repository contains a MATLAB/Simulink (Simscape) model of a Buck Converter designed to evaluate MOSFET power losses (switching and conduction) and monitor real-time junction temperature variations under high-frequency switching.

## Features
- Full Simscape thermal network integration.
- Transient and steady-state junction temperature tracking.
- Custom MATLAB function for instant data logging directly from the Command Window.

## How to Use
1. Download both the `.slx` and `.m` files into the same MATLAB directory.
2. Run the Simulink model (`buck_converter_model.slx`).
3. Open the MATLAB Command Window and run the custom function to see the temperature and power loss summary instantly:
   ```matlab
   check_mosfet_stats('MOSFET_Ideal_Switching')
