# US Road Accidents — Exploratory Data Analysis (2022) [Colab Link](https://colab.research.google.com/drive/1Kgj791323uqTARBXaaUSB1EorEt2Wh2o?usp=sharing)

This project presents an exploratory data analysis (EDA) of the **US Accidents Dataset**, focusing on the year **2022** to ensure completeness and consistency. The dataset compiles nationwide traffic incident reports from multiple real-time sources, including state DOTs, law enforcement feeds, traffic cameras, and road sensors.

The analysis explores **when, where, and why** accidents occur by examining temporal patterns, geographic distribution, environmental conditions, severity drivers, and infrastructure-related factors.

---

## Project Objectives

- Analyze accident trends across **time of day, weekdays, and months**
- Compare accident frequency using **raw counts vs. per-capita rates**
- Identify **high-risk cities and states** after adjusting for population
- Examine impacts of **temperature, visibility, and weather**
- Study whether **traffic signals, crossings, and junctions** correlate with accidents
- Understand conditions associated with **higher accident severity**

---

## Key Insights

- **Rush-hour patterns dominate**, with peaks at **7–8 AM** and **3–5 PM**, and the highest weekday counts on **Fridays**.
- **Temperature and visibility** show limited correlation with severity; most accidents occur under **moderate** conditions.
- **Night-time accidents**, although fewer, make up a **disproportionately higher share of severe crashes**.
- Accidents cluster heavily around **junctions and crossings**, while roundabouts and bumps have minimal involvement.
- **Per-capita accident rates** reveal hidden high-risk cities such as **Miami, Orlando, Baton Rouge, Richmond (CA)** that do not stand out in raw counts.
- State-wise concentration is highest in **California, Arizona, and Florida**, reflecting dense networks and high travel volumes.

---

## Data Source -> 

[US Accidents Dataset (Kaggle)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)


---

## Limitations & Future Work

- **Uneven dataset coverage** across states may bias geographic comparisons.
- Missing **crash-level details** (fatalities, vehicle type, speed, driver behavior) limit severity interpretation.
- Some **weather and visibility** values are missing or inconsistent.
- **Population data merged manually**, and may not perfectly align with 2022 accident counts.
- Future work could integrate **traffic volume (VMT)**, richer crash data, and **predictive modeling** for risk assessment.

---

## Environment & Tools

- Python, Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Jupyter/Google Colab  



