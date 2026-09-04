# Key Findings:
- The best GPUs (looking at 3DMARK & VRAM) are expensive
- 2022 had the highest average price (both retail and used) of GPUs
- 2024 sold the most GPUs
- The GPU specs are so similar to each other they're almost identical (Multicollinearity)
- The dataset is not normally distributed
</br>

# Author/s: 
[Imaan](https://github.com/Imaan14)
</br>

# Table of Contents
- [Business Problem](#Business-Problem)
- [Data Source](#Data-Source)
- [Methods](#Methods)
- [Tech Stack](#Tech-Stack)
- [Quick glance at the results](#Quick-glance-at-the-results)
- [Lessons learned and recommendation](#Lessons-learned-and-recommendation])
- [Limitations and what can be improved](#Limitations-and-what-can-be-improved)
- [Explore the notebook](#Explore-the-notebook)
</br>

# Business Problem
During planning, I brainstormed a few questions that I wanted answers to based on the data. These questions guides the analysis methods and visualizations.</br>

My Questions:
- What is the prices of the best GPUs? (price vs performance)
- What is the average cost of GPUs?
- What period of time did most people buy a GPU?
- Does retail price affect second hand price?
- What would future prices of the best GPU look like?
</br>

# Data Source
Free Dataset from Kaggle, published by Mann Acharya.

https://www.kaggle.com/datasets/mannacharya/historical-gpu-prices-nvidia-and-amd/data
</br>

# Methods
## Data Cleaning Pipeline
- Remove duplicates
- Standardize the data
- Deal with null or blank values
- Change format of Date column
</br>

## Statistical Methods
- Correlation
- Descriptive Statistics (count, mean, median, mode, std, min, max & percentiles)
- Testing Multicollinearity
    - Variance Inflation Factor
    - Tolerance, Eigenvalues
    - Condition Index
- Testing Normality
    - Shapiro-Wilk Test
    - Skewness and Kurtosis
</br>

# Tech Stack
Pandas, Plotly, Scikit-learn, Numpy, Matplotlib
</br>

# Quick glance at the results
<img width="700" height="360" alt="Image" src="https://github.com/user-attachments/assets/b5096de1-ae10-4483-a1f7-8b5dce408af7" />
<img width="700" height="360" alt="Image" src="https://github.com/user-attachments/assets/476e2661-7858-4ab4-81b1-9f7eeb490cfa" />
<img width="700" height="360" alt="Image" src="https://github.com/user-attachments/assets/0a30b447-4dd6-4038-ae38-526a10cd7a84" />
<img width="700" height="360" alt="Image" src="https://github.com/user-attachments/assets/5f0ad633-2c48-46bf-a11a-62e5c2370f71" />
<img width="700" height="360" alt="Image" src="https://github.com/user-attachments/assets/e7c06ee2-c7ac-4d6c-bb2b-ba45e3af7522" />
</br>

# Lessons learned and recommendation
I learned which library is best for visualizations in jupyter notebook, how to pick different graphs to display certain results and how to execute more advanced statistic techniques using python.

Recommendations: Use ridge regression to combat the multicollinearity problem 
</br>

# Limitations and what can be improved
My lack of knowledge in data science topics limited me on how much of my statistical knowledge that could be used in this project.

*Note: All data science techniques I've used in this project with python is self-taught

Some improvements:
- Using the gpu specifications (3DMARK, VRAM, Wattage) as categorical variables
- Redo the advanced statistics so I can create a forecasting model of future GPUs or comparison model for  prices

</br>

# Explore the notebook
- [Normal Data Analysis](https://github.com/Imaan14/GPU-Analysis/blob/main/GPU_analysis.ipynb)
- [Advanced Statistics](https://github.com/Imaan14/GPU-Analysis/blob/main/gpu_stats.ipynb)

</br>

#	License
This project is under the MIT license. Take a look at the [LICENSE](https://github.com/Imaan14/My-Data-Analysis-Projects/blob/main/LICENSE) file for more details.
<br><br/>
