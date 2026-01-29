# Spatial and Temporal Analysis of Assists in Football  
### Case Study: Lorenzo Insigne → José Callejón (2017/18 Season)

## Introduction

In recent years, data analysis has become a central component of professional football, enabling a deeper understanding of tactical behaviors, player interactions, and offensive efficiency.

This project fits within the field of **football analytics**, aiming to analyze assist and finishing dynamics through a spatial representation of match events.

The case study focuses on the **2017/18 season**, analyzing the offensive connection between **Lorenzo Insigne** and **José Callejón**, two key players in Napoli’s attacking system.

---

## Objective of the Analysis

The main objectives of this analysis are:

- Study the spatial distribution of assists provided by Insigne to Callejón  
- Distinguish between action outcomes (goals vs non-goal shots)  
- Identify recurring patterns in creation and finishing zones  
- Evaluate the effectiveness of the Insigne–Callejón partnership in offensive production  

The analysis goes beyond simple event counting and aims to provide a **qualitative tactical interpretation** through data-driven insights.

---

## Dataset and Methodology

The dataset includes offensive events from the **2017/18 season**, with a specific focus on actions where:

- Insigne is the final passer  
- Callejón is the shooter  

For each event, the following information was considered:

- Assist origin coordinates  
- Shot location coordinates  
- Shot outcome (goal or non-goal)  

All spatial data were **normalized according to standard football pitch dimensions**, ensuring a consistent and comparable representation of events.

---

## Visualization and Spatial Analysis

The analysis is based on a pitch-based spatial visualization of the actions:

- **Assists** are represented as passing trajectories from Insigne to Callejón  
- **Goals** are highlighted separately from non-converted shots  
- **Non-goal shots** are used to analyze inefficiencies and missed opportunities  

The visualization highlights a **strong concentration of actions on the right side of the opponent’s penalty area**, which aligns with Callejón’s typical attacking movement, often aimed at exploiting space at the far post.

---

## Results

Overall, the analysis shows:

- **15 total assists** from Insigne to Callejón  
- **3 goals** scored following these assists  
- A prevalence of assists originating from the **left half-space**  
- A high repetition of offensive patterns, indicating **well-established tactical automatisms**

The assist-to-goal ratio suggests a strong offensive output, with room for improvement in terms of shot conversion.

---

## Tactical Interpretation

From a tactical perspective, the results confirm:

- Insigne’s role as an **advanced playmaker**  
- The importance of Callejón’s **off-ball movements**  
- The effectiveness of attacking rotations within the adopted playing system  

The repeated passing trajectories clearly indicate a **structured and rehearsed attacking pattern**, consistently exploited throughout the season.

---

## Conclusions

This study demonstrates how **spatial data analysis** can provide valuable insights into a team’s offensive behavior and player relationships.

The proposed approach is easily extendable to other contexts, such as:

- Comparisons across seasons  
- Comparisons between teams  
- Analysis of different player pairs  

This makes the methodology a useful tool for **analysts, coaches, and technical staff**.

---

## Future Work

Potential future developments include:

- Integration of **Expected Goals (xG)** metrics  
- Temporal analysis of actions (match minute)  
- Comparison with other wide attackers from the same season  
- Application of predictive models to estimate goal probability  

---

## Notes

This project represents my **first structured approach to data science applied to football**, developed as a personal study and learning exercise after completing my exam session.
