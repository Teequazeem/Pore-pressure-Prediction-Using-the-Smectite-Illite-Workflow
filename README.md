# Pore-pressure-Prediction-Using-the-Smectite-Illite-Workflow
This repository automates the pore pressure prediction using the smectite-illite workflow
- The smecitite-illite workflow incorporates the effects of mineralizationa dn diagenesis in abnormal pressure generation.
- If not properly accounted for, it can lead to underprediction of pore pressure

INPUTS:
Basic logs: Depth reference, Sonic wireline, Velocity, GR (For mud filtering), RHOB (For overburden stress)

CODE OUTPUT:
1. Normal Compaction Trend plot
2. The transition function plot
3. Pressure plot - Hydrostatic pressure, Predicted pore pressure, mud weight, overburden stress. Plot is made interactive to vary the Illite fitting parameter, and MW used as a calibration reference. 
