# The Impact of Greenhouse Gases in Transports on Global Warming

## Project Overview
In this project, I will analyze how transportation-related greenhouse gas emissions contribute to global warming and climate change. The greenhouse gas impact in European countries where public transport is widespread and in the United States where private car use is widespread will be compared. My goal is to better understand the environmental impact of vehicles such as cars, planes, trains, public transportations and raise awareness that could help reduce emissions.


---


## Objectives
 The goal of this project is to analyze the impact of greenhouse gas emissions from different modes of transportation on global warming by correlating data on transportation emissions and climate change indicators. This project aims to provide insights into how transportation choices contribute to greenhouse gas emissions and may suggest sustainable alternatives to reduce their environmental impact.

1. **Understand Environmental Impact:**
Explore the relationship between transportation emissions, greenhouse gas emissions, and global warming, identifying how different transportation modes contribute to atmospheric pollution.

2. **Identify Main Contributors:** Pinpoint which transportation sectors and fuel types have the highest carbon footprint and assess their role in climate change acceleration.

3. **Sustainable Alternatives:** Analyze eco-friendly transportation options and their potential to reduce greenhouse gas emissions, providing insights into more sustainable consumer and policy choices.

4. **Apply Data Science Skills:** Utilize data science techniques to analyze emissions data, climate trends, and industry reports, applying the concepts learned in DSA 210 to a real-world environmental issue.


---


## **Description of Dataset**

The dataset for this project consists of transportation-related greenhouse gas emissions data collected over multiple years. The dataset provides insights into different transportation methods and their environmental impact, focusing on regional comparisons.

The main columns in the dataset include:

**Date:** The specific day of the recorded emissions data

**Greenhouse Gas Emissions:** Total CO₂, CH₄, and other greenhouse gas emissions (measured in metric tons) from different transportation modes

**Transportation Mode:** Type of transport (e.g., private cars, buses, trains, airplanes, public transit systems)

**Fuel Type:** Gasoline, diesel, electric, or alternative fuels used in transportation

**Vehicle Usage Frequency:** The number of trips and distances traveled for different transportation methods

**Sustainability Rating:** Eco-friendliness score of transportation modes based on sustainability reports (scale of 1–10)

**Country of Data Collection:** Regional differences in transportation emissions (e.g., EU vs. USA comparison)

**Global Temperature Trends:** Historical temperature data corresponding to emission records

**Regulatory Impact:** Presence of government policies or industry regulations affecting emission levels

---
![image](https://github.com/user-attachments/assets/bd3d6bfd-3f93-4e6d-92bb-272edf720df4)
![image](https://github.com/user-attachments/assets/8d03c806-4ec0-457e-a486-d8cbe32de4eb)
![image](https://github.com/user-attachments/assets/aa4da4f4-4599-490c-bdc3-c03a8be9e532)
![image](https://github.com/user-attachments/assets/6b86076d-3756-499d-9455-0bb188d078da)
![image](https://github.com/user-attachments/assets/c85f32d8-168d-4867-9289-15172e1ef5ed)
![image](https://github.com/user-attachments/assets/7fe6bb71-7f6b-4f96-af5b-98bac8fed3a1)

**Query Parameters:**

**data_sources:** source_ids[] - view data source id at https://www.climatewatchdata.org/api/v1/data/historical_emissions/data_sources

**gases:** - gas_ids[] - view gas id at https://www.climatewatchdata.org/api/v1/data/historical_emissions/gases

**sectors:** - sector_ids[] - view sector id at https://www.climatewatchdata.org/api/v1/data/historical_emissions/sectors

**regions:** - regions[] - region ISO code 3 (ISO Codes for World and European Union (27) are WORLD and EUU, respectively)

**start_year:** - start_year - Show results from this year onwards

**end_year:** - end_year - Show results up to this year

**sort_col:** - sort_col - column to sort the table by

**sort_dir:** - sort_dir - sort direction (ASC or DESC)



Data Link: [https://ourworldindata.org/co2-emissions-from-transport](https://www.climatewatchdata.org/data-explorer/historical-emissions?historical-emissions-data-sources=climate-watch&historical-emissions-end_year=2021&historical-emissions-gases=co2&historical-emissions-regions=USA%2CEUU&historical-emissions-sectors=%2Ctransportation&historical-emissions-start_year=2016&page=1&sort_col=country&sort_dir=DESC)


---

## **Motivation**

Greenhouse gas emissions from the transportation sector contribute significantly to climate change and global warming. Understanding how different transportation choices impact atmospheric pollution may help in developing more sustainable commuting habits and policies.

By analyzing data from environmental agencies and industry reports, I hope to:
- Understand the relationship between transportation emissions and global warming trends.

- Identify key contributors within the transportation sector that have the highest environmental impact.

- Gain actionable insights into how switching to sustainable transportation could reduce greenhouse gas emissions and mitigate climate change.


---

## Tools and Technologies

I will rely on the following tools for data analysis and visualization in this project:

-**Python:** For data cleaning, preprocessing, and statistical analysis

-**Pandas:** To manipulate and process environmental and transportation emission data

-**Matplotlib and Seaborn:** For visualizing trends in greenhouse gas emissions, temperature changes, and industry impact (scatter plots, heatmaps, time series)

-**SciPy:** For hypothesis testing and correlation analysis between transportation emissions and climate change

-**Scikit-learn:** For implementing regression models and predicting emission trends

-**Jupyter Notebook:** For organizing and presenting analyses in an interactive environment


---

## Analysis Plan


1. **Data Collection**
Import greenhouse gas emissions and transportation industry data into a Pandas DataFrame and preprocess the dataset by handling missing values and standardizing units.



2. **Visualization**
Use scatter plots, heatmaps, and time series plots to explore relationships between greenhouse gas emissions, transportation industry data, and global temperature trends.

**Examples include:**

**Scatter plot** of carbon emissions from different transportation modes vs. global temperature changes

**Heatmap** showing correlations between transportation types and greenhouse gas levels

**Time series plot** comparing historical CO₂ levels and temperature anomalies over time



3. **Hypothesis Testing**

**Test hypotheses like:**
- H₀ (Null Hypothesis): Transportation methods have no significant impact on greenhouse gas emissions.
- H₁ (Alternative Hypothesis): Certain transportation choices significantly contribute to greenhouse gas emissions.

Run regression analysis to determine whether there is a significant relationship between transportation emissions and climate change.



4. **Trend Analysis**
- Investigate patterns in greenhouse gas emissions over time, identifying key contributors from the transportation sector.
- Analyze how sustainability efforts and eco-friendly transportation alternatives impact emissions reduction trends.


**Example Analysis:**

To illustrate, I’ll create a scatter plot to visualize the relationship between greenhouse gas emissions from transportation and global temperature changes. The x-axis will represent carbon emissions (metric tons) from the transportation sector, and the y-axis will show global temperature anomalies (°C). If there is a clear upward trend, it might suggest a strong correlation between transportation-related emissions and climate change.

Another example involves comparing private car usage with public transportation. By analyzing emission levels from these two transport modes, I can determine if shifting to public transit significantly reduces carbon emissions.

Similarly, I’ll examine greenhouse gas emission trends over time to see if regulatory policies or industry sustainability efforts have resulted in a decline in emissions. For example, if emissions from transportation decrease following stricter environmental policies, this could indicate that regulations are effective in reducing climate impact.


---

## **Conclusion**

By the end of this project, I hope to answer the following questions:

- How do transportation emissions contribute to greenhouse gas levels?
- Is there a measurable correlation between the transportation sector and global warming trends?
- Can sustainable alternatives significantly reduce the environmental impact of transportation?
- How can these insights be applied to encourage more eco-friendly commuting and policy changes?

This project isn’t just about analyzing emissions from transportation; it’s about leveraging data science to gain a deeper understanding of environmental sustainability. Whether in public transit, private vehicle use, or air travel, data-driven insights can help shape more responsible transportation choices and mitigate climate change.



---


### Exploratory data analysis 
There are two datasets for emissions as EU27 and USA:

**For EU27:**
1. Filtering data sets for 1.A.3.b - Road Transportation.
2. Handling missing values by elimination.
3. Eliminating unnecessary information.
4. Visualisation of the data.
5. Data enrichs with total vehicle numbers of EU27 in between 1990 and 2022, missing values handle by linear regression.

   
**For USA:**
1. Handling missing values by elimination.
2. Eliminating unnecessary information.
3. Visualisation of the data.
4. Data enrichs with total vehicle numbers of USA in between 1990 and 2022, missing values handle by linear regression.

   
**Emissions by Country Bar Chart**
To show EU27 countries emission distribution between 1990-2022:

   ![image](https://github.com/user-attachments/assets/ed6e6262-df7a-497f-bb91-a600d1215e59)


**Histogram of Gross Total Emissions**
To show frequency of USA's Emissions:

![image](https://github.com/user-attachments/assets/01be07f0-e751-4fd0-9eef-25ae69025a5c)

**EU-27 vs USA Total Transportation Emissions by Line Plot(1990–2022)**
To show USA and EU27 Emission Differences:

![image](https://github.com/user-attachments/assets/c3f6ec07-4f34-4d0d-ba9e-e06c9b7885fe)


**EU27 Scatter Plot**
To show correlation between CO2 Emission and Public Transportation:

![image](https://github.com/user-attachments/assets/2cd53c4d-a54c-43aa-bb7b-f2e48ff616ce)


**USA Scatter Plot**
To show correlation between CO2 Emission and Public Transportation:

![image](https://github.com/user-attachments/assets/754972d8-bb2d-4530-b960-c421059449b4)


### 🧪 Hypothesis Test Report

**Hypothesis:**
- H₀: There is not correlation between public transport ratio and emissions per public vehicle.
- H₁: There is a correlation between public transport ratio and emissions per public vehicle.

**Significance Level:** α = 0.05

---

**USA:**
**Pearson r** = -0.25, p = 0.168 → Fail to Reject H₀
**Spearman ρ** = -0.35, p = 0.048 → Reject H₀

**EU27:**
**Pearson r** = -0.06, p = 0.738 → Fail to Reject H₀
**Spearman ρ** = -0.03, p = 0.849 → Fail to Reject H₀

**Conclusion:** There is a statistically significant negative monotonic relationship between public transport ratio and CO₂ emissions per public vehicle in the USA (Spearman test only). No significant relationship exists for EU27.


  
This project isn’t just about analyzing emissions from cosmetics; it’s about leveraging data science to gain a deeper understanding of environmental sustainability. Whether in the beauty industry or other sectors, data-driven insights can help shape more responsible production and consumption habits to mitigate climate change.


