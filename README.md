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

![Dashboard](https://raw.githubusercontent.com/username/repo/main/images/Dashboard%201%20(3).png)


# Insights Deep Dive
### Category 1:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 1]


### Category 2:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 2]


### Category 3:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]


### Category 4:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
