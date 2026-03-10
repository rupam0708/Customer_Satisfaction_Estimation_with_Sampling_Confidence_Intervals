Customer Satisfaction Estimation with Sampling & Confidence Intervals
---------------------------------------------------------------------

This repository contains a comprehensive data science project that explores the relationship between **sample size** and **statistical precision**. Using a dataset of 38,000+ customer feedback entries, I simulated the **Central Limit Theorem (CLT)** and visualized how **Confidence Intervals (CI)** behave as we scale our data collection efforts.

### 📊 Project Overview

In real-world analytics, we rarely have access to a full population. We rely on samples to make decisions. This project serves as a technical proof of how larger sample sizes reduce the "window of uncertainty" (Margin of Error) and provide a more stable foundation for business intelligence.

**Key Technical Concepts Explored:**

*   **Central Limit Theorem (CLT):** Proving that the distribution of sample means follows a normal curve.
    
*   **Confidence Intervals (CI):** Calculating the range where the true population mean is likely to reside.
    
*   **Sampling Error & Volatility:** Visualizing how small samples ($n=50$) lead to wild swings compared to large samples ($n=500$).
    
*   **Coverage Rate Analysis:** Validating the mathematical formula by checking how often the true mean falls within our calculated CI.
    

### 🛠️ Tech Stack

*   **Language:** Python
    
*   **Libraries:** Pandas (Data Manipulation), NumPy (Numerical Simulation), Matplotlib/Seaborn (Statistical Plotting)
    
*   **Visualization:** Tableau Public (Advanced Visual Storytelling)
    
*   **Environment:** Google Colab
    

### 📈 Key Visualizations (Tableau)

I exported the simulation results to Tableau to create a series of high-impact charts:

1.  **The "Squeeze" (Area Chart):** Demonstrates the exponential decrease in the Confidence Interval Range as sample size increases.
    
2.  **Sampling Distribution Hierarchy:** A binned histogram showing the 10,000 simulated means converging on the population mean.
    
3.  **Path Convergence:** A line chart tracking the volatility of individual sample means across different size cohorts.
    
4.  **Stability Plot:** Mapping the relationship between sample means and their corresponding Lower Bounds to visualize the "safety net" of our estimations.
    

### 🚀 Getting Started

#### Running the Simulation

1.  Bashgit clone https://github.com/rupam0708/Customer\_Satisfaction\_Estimation\_with\_Sampling\_Confidence\_Intervals.git
    
2.  Open the .ipynb file in Google Colab or Jupyter Notebook.
    
3.  Download the dataset from [Kaggle](https://www.kaggle.com/datasets/jahnavipaliwal/customer-feedback-and-satisfaction) and upload it to your environment.
    
4.  Execute the cells to generate the 10,000-iteration simulation and export the sampling\_results\_tableau.csv file.
    

### 🔗 Project Links

*   **Live Dashboard:** [Tableau Public Interactive Viz](https://public.tableau.com/views/CustomerSatisfactionEstimationwithSamplingConfidenceIntervals/Sheet1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
    
*   **Deep Dive Article:** [Medium Blog Post](https://medium.com/@rupamkarmakar1238/from-uncertainty-to-insights-a-technical-deep-dive-into-sampling-confidence-intervals-6566d1c3ac16)
    
*   **Dataset Source:** [Kaggle - Customer Feedback & Satisfaction](https://www.kaggle.com/datasets/jahnavipaliwal/customer-feedback-and-satisfaction)
    

### 🤝 Connect with Me

**Rupam Karmakar**

*   **LinkedIn:** [in/rupam0708](https://www.linkedin.com/in/rupam0708/)
    
*   **Portfolio:** Flutter Developer & Full-Stack Mobile Developer

