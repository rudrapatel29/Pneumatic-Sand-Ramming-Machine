Here is the updated README file with the additional details, including the positive correlation results, a table of force and mold hardness values, and the specific result for the optimal mold hardness:

---

# Pneumatic Sand Ramming Machine with Sensors

## Overview
This project focuses on developing a pneumatic sand ramming machine integrated with sensors for real-time feedback and control. The machine aims to streamline the sand compaction process in foundries, ensuring uniformity, precision, and enhanced productivity. The integration of load and moisture sensors allows for real-time monitoring and adjustments to maintain optimal compaction conditions, thereby improving the quality of castings and molded products.

## Project Goals
- **Automation**: Utilize load and moisture sensors to automate the sand compaction process.
- **Quality Improvement**: Enhance the quality of castings and molded products by maintaining consistent density and moisture levels.
- **Real-time Monitoring**: Provide real-time monitoring and feedback for adjustments to optimize compaction conditions.
- **Defect Minimization**: Minimize defects in the final products through sensor-guided processes.

## Hardware Requirements
- Load Sensors
- Moisture Sensors
- Compressor
- Pneumatic Ramming Machine
- Arduino Board

## Software Requirements
- Arduino IDE 1.8.19

## Methodology
1. **Design Phase**:
    - Conduct initial research and gather requirements.
    - Select and integrate load sensors and moisture sensors into the system.

2. **Sensor Calibration and Testing**:
    - Calibrate load sensors and moisture sensors to accurately measure force exerted during sand compaction and moisture content.
    - Conduct rigorous testing to validate sensor accuracy and reliability.

3. **Integration and Optimization**:
    - Integrate the control system with the pneumatic sand ramming machine.
    - Optimize system parameters for efficiency, precision, and reliability through iterative testing and refinement.

4. **Validation and Performance Testing**:
    - Conduct comprehensive validation tests in real-world foundry environments to evaluate system performance.
    - Iteratively refine the design based on testing feedback to ensure optimal functionality.

5. **Documentation and Reporting**:
    - Document the design process, development iterations, and testing results.
    - Generate comprehensive reports detailing the methodology, findings, and recommendations.
    - Present the project outcomes to stakeholders for feedback and further refinement.

## Python Analysis

The Python analysis in this project involves plotting relationships between force, hardness, and moisture levels. This analysis helps in understanding how different factors influence the sand compaction process. The data is collected through sensor readings and processed using Python libraries like `pandas`, `numpy`, `matplotlib`, and `seaborn`.

### Analysis Highlights
- **Data Collection**: User inputs for force, hardness, and moisture values are collected.
- **Relationship Plots**: Visualizations showing the relationship between:
    - Force and Hardness
    - Moisture Level and Hardness
- **Correlation Analysis**: A heatmap to show the correlation between force, hardness, and moisture levels.

### Results
The analysis indicates a positive correlation between the applied force and mold hardness. As shown in the attached plot:

![)

The table below presents the observed force and mold hardness values:

| Force (Newtons) | Mold Hardness (Shore A) |
|-----------------|-------------------------|
| 200             | 55.68                   |
| 225             | 62.12                   |
| 250             | 68.74                   |
| 275             | 71.80                   |
| 300             | 74.14                   |

The optimal mold hardness of 65 Shore A requires an applied force of 235 Newtons.

### Libraries Used
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For plotting and visualization.
- `seaborn`: For advanced visualizations.

## Repository Contents
- **Code**: Python scripts for data processing and visualization.
