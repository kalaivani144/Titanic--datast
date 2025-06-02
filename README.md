### **Task 5: Exploratory Data Analysis (EDA)**

This section presents a detailed Exploratory Data Analysis (EDA) of the experimental results for the optimization of WEDM (Wire Electrical Discharge Machining) process parameters on Inconel 625. The Weighted Entropy Method is used to evaluate and rank the experimental trials based on multiple performance metrics.

---

**Figure 1: Normalized Decision Matrix of WEDM Responses (MRR, SR, KW)**
The experimental response values for Material Removal Rate (MRR), Surface Roughness (SR), and Kerf Width (KW) are normalized to eliminate scale differences. This matrix forms the basis for calculating entropy and weight for each criterion.
*(Screenshot: Screenshot 2025-06-02 223238.png)*

---

**Figure 2: Computed Entropy Values and Criteria Weights for WEDM Optimization**
Entropy values are calculated for each normalized criterion to determine the degree of variation across experimental runs. These values are then used to compute the relative weights for MRR, SR, and KW, reflecting their importance in the multi-objective decision-making process.
![Screenshot 2025-06-02 223238](https://github.com/user-attachments/assets/94f24270-1819-4173-86d2-a2d190841011)


---

**Figure 3: Weighted Normalized Decision Matrix for Multi-Criteria Evaluation**
The normalized decision matrix is multiplied by the corresponding weights of each criterion to obtain a weighted matrix. This allows for the aggregation of different performance metrics into a single evaluative framework.
![Screenshot 2025-06-02 223533](https://github.com/user-attachments/assets/9d01b58e-5a6d-409a-9cbf-0808c66d3822)


---

**Figure 4: Performance Scores and Ranking of Experimental Trials Based on Weighted Entropy Method**
A final performance score is calculated for each experimental run by summing its weighted normalized values. Based on these scores, each trial is ranked to identify the most effective parameter combination.
![Screenshot 2025-06-02 223722](https://github.com/user-attachments/assets/bae74630-ec3c-49d5-ba55-c74f1ed0fd23)


---

**Figure 5: Optimal Parameter Setting Identified from Ranked WEDM Experiments**
The experiment with the highest overall performance score is considered optimal. This figure highlights the top-ranked combination of input parameters (Ton, Toff, SV) for improved machining performance on Inconel 625 using the Weighted Entropy Method.
![Screenshot 2025-06-02 223811](https://github.com/user-attachments/assets/03636722-ea10-495b-a87c-9e60d0c8a74f)
