# Pore-pressure-Prediction-Using-the-Smectite-Illite-Workflow
This repository automates the pore pressure prediction using the smectite-illite workflow
- The smecitite-illite workflow incorporates the effects of mineralization due to diagenesis in abnormal pressure generation.
- If not properly accounted for, it can lead to underprediction of pore pressure

INPUTS:
Basic logs: Depth reference, Sonic wireline, Velocity, GR (For mud filtering), RHOB (For overburden stress)

CODE OUTPUT:
1. Normal Compaction Trend plot
2. The transition function plot
3. Pressure plot - Hydrostatic pressure, Predicted pore pressure, mud weight, overburden stress. The plot is made interactive to vary the Illite fitting parameter, and the mud weight is used as a calibration reference. The output of the smectite illite function might not display properly when viewed as a raw file on GitHub due to the fact the plot was made interactive to vary the illite fitting parameter but the GitHub interface does not support the widget. 
