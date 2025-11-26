# Project Background
Daikibo is a multinational manufacturing company operating factories across Tokyo, Osaka, Berlin, and Shenzhen. Each location operates 9 types of machines, which send telemetry messages every 10 minutes.


The data analyzed covers one month (May 2021) and was collected to answer the following business questions:


1. In which location did machines break the most?
2. What are the machines that broke most often in that location?


Insights and recommendations are provided on the following key areas:

- **Category 1:** Down Time per Factory
- **Category 2:** Down Time per Device Type 




An interactive Tableau dashboard used to report and explore machine down time trends can be found here [[link](https://public.tableau.com/views/Book1_17442576765920/Dashboard13?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)].


# Data Structure & Initial Checks

The company's main telemetry data was collected from 4 factories, each with 9 types of machines, recorded every 10 minutes for one month (May 2021). The data was provided in a single JSON file and imported into Tableau.

The raw telemetry dataset for this project can be downloaded here:  
[daikibo-telemetry-data.json.zip](./data/daikibo-telemetry-data.json.zip)




# Executive Summary

### Overview of Findings

After analyzing the telemetry data for May 2021, the factory with the highest machine down time was identified, and the machine types contributing most to this down time were determined. These insights allow Daikibo to prioritize maintenance efforts and improve operational efficiency.


[Visualization: Screenshot of the dashboard showing Down Time per Factory and Down Time per Device Type]

![Dashboard](https://raw.githubusercontent.com/DataandUXgirl/Daikibo-Telemetry-Analysis/main/image/Dashboard%201%20(3).png)

# Insights Deep Dive
### Category 1: Down Time per Factory

Main insight 1:
Factory Seiko had the highest total down time (480 minutes) in May 2021, indicating significant maintenance issues or repeated failures in specific machine types.

Main insight 2:
Daikibo Factory Berlin had the lowest down time (20 minutes), showing the most stable operations across all four locations.

Main insight 3:
The large gap between Seiko (480) and Meiyo (110) suggests location-specific operational or environmental factors influencing machine reliability.

Main insight 4:
Total factory down time directly reflects the severity of device type breakdowns, especially in factories where high-failure machines (like laser welders and laser cutters) dominate.

[Visualization specific to category 1]
![Dashboard](https://github.com/DataandUXgirl/Daikibo-Telemetry-Analysis/blob/main/image/Dashboard%201%20(3).png)


### Category 2:

Main insight 1:
In Seiko, the Laser Welder (480 mins) contributed the most to overall down time, making it the primary risk point in the factory.

Main insight 2:
Device Types AirWrench and Metal Press had zero down time, showing strong reliability and minimal maintenance needs.

Main insight 3:
Both Laser Cutter (430 mins) and Laser Welder (480 mins) show extremely high failure patterns, suggesting possible design flaws or insufficient preventive maintenance for laser-based machine types.

Main insight 4:
Down time patterns clearly show which machines require immediate maintenance prioritization, supporting targeted operational decisions.

[Visualization specific to category 2]
![Dashboard](https://github.com/DataandUXgirl/Daikibo-Telemetry-Analysis/blob/main/image/Dashboard%201%20(3).png)



### Category 3: Device Type Comparisons


Main insight 1: Laser-based machines (Laser Cutter & Laser Welder) consistently had the highest down time across factories compared to mechanical devices like AirWrench or Metal Press.

Main insight 2: Heat-intensive devices (e.g., Furnace) show moderate down time, suggesting environmental sensitivity.

Main insight 3: Lightweight devices (CNC, Conveyor Bolt) show low down time, indicating stable performance.

Main insight 4: Comparing device categories helps identify which machines are most cost-intensive to maintain.

[Visualization specific to category 3]




# Recommendations:

Based on the insights and findings above, i would recommend the operations team to consider the following: 

- Prioritize maintenance at Seiko, which had the highest down time (480 mins).

- Immediately address Laser Welders and Laser Cutters, the top contributors to down time.

- Use daily down time patterns to schedule preventive maintenance, especially for laser-based machines.

- Replicate Berlin’s operational strategies, since it demonstrated exceptionally low down time.

- Investigate location specific environmental or operational factors (temperature, humidity, workload) that may worsen failures.

# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1: Each “Unhealthy” status = 10 minutes of down time (based on task instructions).
  
* Assumption 2: Data is assumed to be complete for May 2021; missing telemetry is not considered.
  
* Assumption 3: All machines of the same type are treated as equivalent for down time calculations.
