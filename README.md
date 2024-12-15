# Optimizing-Biodiversity
# **Wildlife Conservation Optimization Model**

### MGSC 662: Decision Analytics 

---

## **Project Overview**  
This repository contains the implementation of an **optimization framework for wildlife conservation planning**, developed as part of our *MGSC 662 Decision Analytics* course. The project focuses on **maximizing biodiversity impact** under real-world constraints such as financial budgets and operational limitations.  

The framework integrates techniques like **stochastic optimization**, **scenario reduction**, and **Pareto front analysis** to identify cost-effective conservation strategies.

---

## **Project Files**  

- **[OptimizingBiodiversity.ipynb](OptimizingBiodiversity.ipynb)**  
   Jupyter Notebook containing the full implementation, including:  
   - Data retrieval (GBIF API).  
   - Biodiversity score calculations.  
   - Stochastic and deterministic optimization models.  
   - Scenario reduction using **K-Means clustering**.  
   - Visualizations: Pareto fronts, cost-impact trade-offs, and sensitivity analysis.  

- **[OptimizingBiodiversity_Report.pdf](OptimizingBiodiversity_Report.pdf)**  
   The final project report detailing:  
   - Problem formulation.  
   - Mathematical models.  
   - Methodology and implementation.  
   - Results and key insights.  

- **[OptimizingBiodiversity_Presentation.pdf](OptimizingBiodiversity_Presentation.pdf)**  
   A summary presentation of the project, highlighting the methodology, key findings, and visualizations.  

---

## **Problem Statement**  
Wildlife habitats are under increasing threats from biodiversity loss and climate change. Conservation organizations must strategically allocate resources to achieve the greatest **biodiversity impact** under limited budgets.

**Objective**:  
To develop a systematic optimization framework that identifies strategies balancing **cost** and **biodiversity impact** over multiple years.

---

## **Key Features**  

1. **Data Collection**  
   - Species occurrence data retrieved using the **GBIF API**.  

2. **Biodiversity Impact Calculations**  
   - Calculated biodiversity scores based on species richness and observation counts.  

3. **Optimization Models**  
   - **Deterministic Model**: Solves for fixed costs and impacts.  
   - **Stochastic Model**: Incorporates uncertainty by simulating multiple scenarios.  
   - **Scenario Reduction**: K-Means clustering reduces 500 scenarios for computational efficiency.  

4. **Pareto Front Analysis**  
   - Visualizes the trade-offs between **cost** and **biodiversity impact**.  

5. **Sensitivity Analysis**  
   - Analyzes model behavior under varying parameters (e.g., budgets, variability, and cluster sizes).  

---

## **Results**  

1. **Optimal Conservation Strategies**  
   - Identified cost-effective strategies that maximize biodiversity impact while adhering to yearly budgets.

2. **Pareto Front Visualization**  
   - Highlights optimal trade-offs between cost and impact.

3. **Sensitivity Analysis**  
   - Explores robustness of the solution under different variability and resource constraints.

---

## **Technologies and Tools**  

- **Python**: Core implementation.  
- **Gurobi Optimizer**: Solves the optimization models.  
- **Pandas, NumPy**: Data processing and numerical operations.  
- **Matplotlib**: Visualization of results (e.g., Pareto fronts).  
- **Scikit-learn**: K-Means clustering for scenario reduction.  
- **Jupyter Notebook**: Code organization and execution.  

---

## **Team Members**  
*This project was a collaborative effort by:*  

- **Alexandra Guion**  
- **Nandini Sankarabukta**  
- **Berly Brigith Biju**  
- **Tehreem Nasir**  

---

## **Conclusion**  
This project demonstrates how **optimization techniques** and **data-driven decision-making** can address real-world wildlife conservation challenges. By balancing **costs** and **biodiversity impact**, our framework provides actionable insights to guide resource allocation effectively.  

Key highlights include:  
- Development of **stochastic optimization models** to simulate uncertain costs and impacts.  
- Reduction of computational complexity using **K-Means clustering** for scenario reduction.  
- Visualization of **Pareto fronts** to identify optimal trade-offs between cost and biodiversity outcomes.  
- **Sensitivity analysis** to test model robustness across various input parameters.  

For further details on the methodology, implementation, and results, please refer to:  
- **[OptimizingBiodiversity_Report.pdf](OptimizingBiodiversity_Report.pdf)**  
- **[OptimizingBiodiversity_Presentation.pdf](OptimizingBiodiversity_Presentation.pdf)**  

---

## **Acknowledgments**  
I would like to express my gratitude to **Professor Rob Glew** for his invaluable guidance and support throughout the project and this course.  

---

