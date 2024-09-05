# Pore-pressure-Prediction-Using-the-Smectite-Illite-Workflow
This repository automates the pore pressure prediction using the smectite-illite workflow
- The smectite-illite workflow incorporates the effects of mineralization due to diagenesis in abnormal pressure generation, which if not properly accounted for, could lead to underprediction of pore pressure. 

Required inputs:
Basic logs: Depth reference (True Vertical Depth, preferably), Sonic/Velocity wireline, GR (For mud filtering), RHOB (For overburden stress)

CODE OUTPUT:
1. Normal Compaction Trend plot: The code outputs the normal compaction trend (NCT) for the smectite- and illite-rick rock, and an NCT for the transition from smectite to illite-rich rocks at a specific depth range. 
2. The transition function plot
3. Pressure plot - Hydrostatic pressure, Predicted pore pressure, mud weight, overburden stress. The plot is made interactive to vary the Illite fitting parameter, and the mud weight is used as a calibration reference. The output of the smectite illite function might not display properly when viewed as a raw file on GitHub due to the fact the plot was made interactive to vary the illite fitting parameter but the GitHub interface does not support the widget.


#NOTE: The data used for this project are real oil field data in the Gulf of Mexico and can't be released on GitHub due to proprietary reasons. However, the workflow employed in the notebook can be applied to other data.
