# Data-Driven-Comparison-of-Formula-1-Drivers-A-Machine-Learning-Approach

## Overview
The 2023-2024 Spring semester graduation project aims to analyze telemetry and radio data from the Formula 1 2022 and 2023 seasons. The project involves computing driver performance similarity using cosine similarity and exploring hierarchical clustering techniques for driver comparison. Additionally, tanglegrams are employed to visually track changes in driver performance across seasons. Further tests include investigating factors that prompt drivers to communicate with race engineers—such as track conditions versus car telemetry. 

## Data Sources

### Telemetry Data

- **FastF1 Package:**
  - Utilized the FastF1 package for telemetry data analysis.
  - Data accessed from the [FastF1 GitHub repository](https://github.com/theOehrly/Fast-F1).
 
### Team Radio Communications

- **Live Timing Formula 1:**
  - Follow the method described in [this GitHub discussion](https://github.com/theOehrly/Fast-F1/issues/53) to obtain team radio data from live sessions.
  - Convert the obtained links to accessible audio formats for further analysis.

## Example Visualizations from the Project

The visualizations of the 2023 Austrian & Mexico City Grand Prix tracks illustrate key points along with the car’s telemetry information, highlighting areas on the track where team radio conversations occur.
<img src="https://github.com/user-attachments/assets/8132f3cf-12fd-4349-8a21-c56580f1e26a" alt="austtrack" width=600/>
<br>
<img src="https://github.com/user-attachments/assets/8615633e-1e5c-4724-82e5-612647802b08" alt="mexicotrack" width=600/>

Hierarchical clustering of Formula 1 drivers from the 2022 & 2023 Monaco Grand Prix telemetry data.

<img src="https://github.com/user-attachments/assets/b88f1079-d839-40bd-9c40-b37eb0f33fec" alt="22clustering" width=400/>
<img src="https://github.com/user-attachments/assets/293772c3-9d47-4775-8c5e-a89cec62b613" alt="23clustering" width=400/>

Tanglegrams to compare clustering of drivers between the 2022 and 2023 Monaco Grand Prix.

<img src="https://github.com/user-attachments/assets/bc4c4382-b29b-4aff-a749-dde8c0b4c8ca" alt="tanglegram" width=700/>

