# Transit or Trails? A Decision Framework for Reducing Congestion and Emissions in Halifax

## Decision Statement

Should the Halifax Regional Municipality (HRM) transportation planning director prioritize investment in public transit expansion or active transportation infrastructure (bike lanes and pedestrian networks) to reduce urban congestion and greenhouse gas emissions by 2030, given budgetary and land-use constraints?

## Primary Objective (KPI)

The primary objective of this analysis is to evaluate which investment pathway — public transit expansion or active transportation infrastructure — is more likely to reduce traffic volumes and congestion pressure within Halifax by 2030.

Traffic volume (AADT) is used as a measurable proxy for congestion pressure and private vehicle dependence within the Halifax transportation network.

## Executive Summary

Halifax Regional Municipality is experiencing sustained population growth alongside increasing pressure on its transportation system. Rising congestion, longer commute times, and transportation-related greenhouse gas emissions pose significant challenges to economic productivity, environmental sustainability, and quality of life. As HRM works toward climate targets and long-term urban development goals, transportation investment decisions have become increasingly consequential.

The transportation planning director faces a strategic allocation decision under constrained budgets and limited urban space. Two leading investment pathways dominate current policy discussions: expanding public transit services—such as increasing route coverage, frequency, and reliability—or prioritizing active transportation infrastructure, including protected bike lanes and pedestrian-oriented streets. While both strategies aim to reduce reliance on private vehicles, they differ in cost structures, adoption timelines, equity implications, and system-wide impacts.

This project frames the decision as a system dynamics problem rather than a narrow infrastructure comparison. Transportation outcomes emerge from interconnected feedback loops involving congestion, mode choice, emissions, land use, and public support. By integrating background research, exploratory data analysis, and causal loop modeling, this project seeks to identify which investment pathway offers the greatest leverage for achieving HRM’s congestion and emissions reduction objectives by 2030, while acknowledging uncertainty and tradeoffs inherent in urban transportation systems.


[Read more](Background.md)


## Initial Causal Loop Diagram (Draft)
![Draft Causal Loop Diagram](img/cld-draft.png)

### Key Feedback Loops (Draft)
- **Reinforcing Loop (R1 – Transit Quality Loop):** Increased transit investment improves service quality, which raises ridership. Higher ridership increases political and financial support for transit, enabling further investment.
- **Reinforcing Loop (R2 – Active Transportation Adoption Loop):** Expanded active transportation infrastructure improves perceived safety and accessibility, increasing walking and cycling rates and generating demand for additional infrastructure.
- **Balancing Loop (B1 – Congestion Pressure / Induced Demand Loop):** Reduced car usage lowers congestion, but improved traffic conditions can induce additional driving, partially offsetting congestion reductions.

## Evidence Supporting Key Causal Links

1. The increasing or sustained AADT trend (Figure 1) supports the positive relationship between private vehicle use and traffic volume.

2. The concentration of traffic in specific corridors (Figure 2) supports the link between infrastructure capacity and congestion pressure.

3. The distribution and variation in traffic intensity (Figures 3 and 4) reinforce the reinforcing feedback loop between vehicle dependence and road utilization.

## Exploratory Visualizations

### Figure 1: Traffic Volume Trend Over Time

![Viz 1](img/viz1.png)

**Interpretation:**  
Figure 1 shows the trend in Annual Average Daily Traffic (AADT) across Halifax-area highway segments. The observed pattern indicates sustained vehicle reliance, reinforcing the system’s dependence on private automobile use. Increasing traffic volumes strengthen congestion pressure and support the reinforcing loop identified in the causal model.

---

### Figure 2: Concentration of Traffic Volume by Highway Segment

![Viz 2](img/viz2.png)

**Interpretation:**  
Figure 2 highlights the highway corridors with the highest traffic volumes. Traffic concentration across specific segments suggests that congestion pressure is spatially clustered. This supports the causal link between infrastructure capacity and vehicle flow intensity.

---

### Figure 3: Distribution of AADT Across Provincial Highway Segments

![Viz 3](img/viz3.png)

**Interpretation:**  
Figure 3 illustrates the distribution of AADT values across highway segments. The distribution indicates that while many segments carry moderate traffic, a smaller subset carries disproportionately high volumes. This imbalance supports the system dynamics framing of concentrated congestion pressure.

---

### Figure 4: Variation in Traffic Volume Across Highway Segments

![Viz 4](img/viz4.png)

**Interpretation:**  
Figure 4 explores variation in traffic volume across segments (or over time, depending on your scatterplot). The observed relationship suggests that certain structural or temporal factors influence traffic intensity, reinforcing feedback mechanisms in the refined causal loop diagram.
