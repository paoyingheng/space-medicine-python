# Phase 2: Python Problem Solving for Space Medicine

This phase focuses on applying Python programming to solve real-world operational and biomedical challenges encountered in space missions.  
Each project reflects a specific use case relevant to astronaut health, performance, or life support systems, with emphasis on data logic, thresholds, and early detection.

---

## Mini-Projects

### [Project 1: Fever Alert System](./project1_fever_alert/fever_alert.ipynb)
Detects elevated body temperatures using medical logs. Flags possible fever events above 37.8°C and summarizes frequency by crew member.

📁 `project1_fever_alert/`  
📄 Data: `temp_log.csv`

---

### [Project 2: Circadian Rhythm Drift Tracker](./project2_circadian_drift/circadian_drift.ipynb)
Monitors astronaut sleep start times over a multi-day mission. Flags significant circadian misalignment if sleep shifts by more than 2.0 hours from baseline.

📁 `project2_circadian_drift/`  
📄 Data: `sleep_log.csv`

---

### [Project 3: CO₂ Exposure Tracker](./project3_co2_tracker/co2_tracker.ipynb)
Analyzes daily CO₂ levels for each crew member. Flags elevated levels above 1000 ppm (mild risk) and 2500 ppm (cognitive impairment risk). Plots trends and cumulative exposure.

📁 `project3_co2_tracker/`  
📄 Data: `co2_log.csv`

---

### [Project 4: Caloric Balance Tracker](./project4_caloric_balance_tracker/caloric_balance.ipynb)
Calculates daily energy balance (calories in vs. calories out) for each astronaut. Flags prolonged deficits and summarizes net caloric status over time.

📁 `project4_caloric_balance_tracker/`  
📄 Data: `caloric_balance_log.csv`

---

### [Project 5: Contagion Risk Mapper](./project5_contagion_risk_mapper/contagion_risk_mapper.ipynb)
Simulates infectious disease spread using daily contact logs and symptom onset. Identifies at-risk crew members based on contact in the 3 days prior to a symptomatic case.

📁 `project5_contagion_risk_mapper/`  
📄 Data: `contagion_log.csv`

---

## 💡 Key Skills Developed

- Data filtering, grouping, and aggregation using pandas
- Conditional logic and threshold-based flagging
- Time-series trend analysis
- Plotting with matplotlib
- Thinking critically about data in a mission operations context

---

## 🧭 What’s Next?

Head to [Phase 3: Modeling & Simulation](../phase3_modeling_applications/)  
to turn these insights into full dynamic models and mission tools.

