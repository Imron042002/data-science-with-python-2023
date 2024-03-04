# Data Science with Python 2023
---
## Car Sale

### Overview

This is a life cycle project using CRISP-DM as the process. The objective of this project is to gather statistics about car brands and predict car prices.

---

* Tool
    * Anaconda
    * Jupyter lab

* Installation
    * Python v.3
    * Python libraries:
        * sklearn.
        * Pandas.
        * numpy.
        * seaborn
        * matplotlib.

## Methodology

### 1. Business Understanding
---
To gather various statistics about the habits of customers who buy cars and predict car prices.

### 2. Data Understanding
---
Information taken from [Car Sales Report.kaggle](https://www.kaggle.com/datasets/missionjee/car-sales-report) as a CSV file.

![Car Sales Report](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/Screenshot%202024-02-28%20173657.png?raw=true)

### 3. Data Preparation
---
- Check data missing in table.
![Data Missing](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/2.png?raw=true)

- Drop columns:
  - Phone
  - Car_id
  - Customer Name
  - Dealer Name
  - Dealer_No

![Drop Columns](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/3.png?raw=true)

- Data Visualization and Interpretation:
  - Graphs Plot Relational Graphs
  - Univariate and Bivariate Analysis

![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/4.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/5.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/6.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/7.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/8.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/9.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/10.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/11.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/12.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/13.png?raw=true)
![Graphs](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/14.png?raw=true)

Conclusion:
- Top 5 Companies: Chevrolet, Dodge, Ford, Volkswagen, Mitsubishi
- Preferred Engine: Double Overhead Camshaft
- Preferred Transmission: Auto
- Most Liked Color of Cars: Pale White
- Most Cars Sold in Price Range: $15,000 to $40,000
- Highest Sales Regions: Austin, Janesville, Scottsdale
- People's Favorite Body Style: SUV and HatchBack

### 4. Modeling
---
- Set Date Time
![Date Time](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/15.png?raw=true)
- Set Annual Income
![Annual Income](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/16.png?raw=true)
- Set Encoder
![Encoder](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/17.png?raw=true)
![Encoder](https://github.com/Imron042002/data-science-with-python-2023/blob/main/image/18.png?raw=true)
- Set Model (X, Y Train Model) using DecisionTreeClassifier


### 5. Evaluation
---
- Predict

