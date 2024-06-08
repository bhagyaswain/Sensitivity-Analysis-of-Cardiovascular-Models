# Zero-Dimensional Cardiovascular Modeling: A Personalized Approach to Non-Invasive Measurement and Stability Analysis
## Project Description
This project explores the use of zero-dimensional (0D) modeling techniques to analyze cardiovascular responses. It aims to understand how different physiological parameters affect cardiovascular function, providing a personalized approach to non-invasive measurement and stability analysis.

## Implementation Details
### 1. Model Replication
Two separate 0D models were developed to depict the cardiovascular system:
Model 1: Single Ventricle Model
Simplified representation combining all heart components into a single pumping unit.
Includes factors such as venous capacitance, arterial compliance, and peripheral resistance.
Model 2: Four-Chamber Model
More intricate representation explicitly depicting the right atrium, right ventricle, left atrium, and left ventricle.
Each chamber designed as an individual compartment with unique pressure-volume characteristics and valve behavior.
### 2. Sensitivity Analysis
Methods: Sobol and Morris methods were used for sensitivity analysis.
Objective: Identify crucial factors impacting cardiovascular dynamics by manipulating parameters within the normal range of physiological values.
### 3. Model Extension
Model 3: Developed from Model 2 by fixing unimportant parameters identified from sensitivity analysis, making the model simpler without significantly affecting accuracy.
### 4. Rationality of Input Parameter Values
Justification for input parameter values was based on literature to ensure reasonableness and logical consistency.
Results
Both 0D models produced expected hemodynamic responses under simulated conditions.
Significant differences in sensitivity analysis between four-chamber and single ventricle models emphasize the importance of model complexity matching the research question.
Model 3 achieved a balance between simplicity and accuracy.

## Conclusion
This study highlights the impact of model detail on sensitivity to specific physiological parameters.
Simplified models can achieve comparable results to complex models while being more computationally efficient.
Future simulations and sensitivity analysis would benefit from adding more physiological parameters.

## Future Research
Incorporating additional physiological parameters like heart rate, blood viscosity, and neurohumoral regulation.
Developing other streamlined models based on findings from the four-chamber model.
Validating models with experimental data to enhance accuracy and reliability.
