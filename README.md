<div align="center"> <img src="images/header.png"> </div>


# Industrial Machine Learning: Data Center Air Cooling
This project is a part of the Industrial Machine Learning course at Harbour.Space.  


## Project Description
The main goal of this project is to optimize energy consumption and cooling efficiency in a data center. It aims to reduce overall energy usage while ensuring effective cooling for the data center's equipment, thereby lowering operational costs associated with data processing and storage operations.

We will construct a predictive model that considers various factors such as server utilization, workload distribution, cooling efficiency, and energy management systems. By analyzing these parameters, the model will generate energy consumption forecasts for the data center.

Data Source Link: [Data Source](https://ieee-dataport.org/open-access/data-server-energy-consumption-dataset)



**Model Validation**:
To validate the predictive model, we will compare its energy consumption forecasts with actual energy usage data from the data center. By evaluating the model's accuracy and effectiveness in optimizing energy consumption, we can determine its practical applicability.

**Modeling Technique**:
Given the temporal nature of energy consumption patterns, we will utilize Time Series analysis to develop the predictive model. Time Series models are well-suited for forecasting future values based on past data, making them appropriate for predicting energy consumption in a data center, especially during peak loads when cooling requirements are higher.


## Project Tasks
 

✅ Take the dataset you selected for the final project.  
✅ Run experiments to find optimal hyperparameters and feature engineering for your model. While running experiments, use the cross-validation technique for quality estimation and Mlflow tracking.  
✅ Select the best model, load it back to Jupyter/script, and estimate the quality on a hold-out dataset.
- Write a conclusion about the experiment results.  
  
As a result, I expect to receive a link to a GitHub/Gitlab repository, which consists of the following:  
- a well-written read.me, which explains what is stored in this repo and how to reproduce experiments  
✅ script or scripts with experiments and experiment tracking  
✅ any supporting materials like visualization results, scripts, instructions, or links that help understand your case and experiment results better.  


## Dataset Description
This dataset comprises sensor readings obtained from an HP Z440 workstation during a 245-day (35-week) period, with data sampled at a rate of one value per second. The dataset encompasses diverse variables that pertain to the workstation's functioning, power usage, and temperature.

The columns in the dataset correspond to the following variables:

1. Voltage (V)
2. Current (A)
3. Power (W) - measured in Watts (W)
4. Frequency (Hz) - measured in Hertz (Hz)
5. Active Energy - measured in kilowatts per hour (KWh)
6. Power Factor - a dimensionless quantity
7. ESP32 Temperature - measured in Centigrade Degrees (°C)
8. CPU Consumption - measured as a percentage (%)
9. CPU Power Consumption - measured as a percentage (%)
10. CPU Temperature - measured in Centigrade Degrees (°C)
11. GPU Consumption - measured as a percentage (%)
12. GPU Power Consumption - measured as a percentage (%)
13. GPU Temperature - measured in Centigrade Degrees (°C)
14. RAM Memory Consumption - measured as a percentage (%)
15. RAM Memory Power Consumption - measured as a percentage (%)

The dataset was collected from an air free-cooled data center testbed, and it includes measurements from instrumented hardware and software sensors during tests on the testbed. 

Each data point in the dataset is indexed by a timestamp indicating when the sensor measurement was taken.

**Example:**

| Timestamp                | Voltage | Current | Power | Frequency | Active Energy | Power Factor | ESP32 Temp (°C) | CPU (%) | CPU Power (%) | CPU Temp (°C) | GPU (%) | GPU Power (%) | GPU Temp (°C) | RAM (%) | RAM Power (%) |
|--------------------------|---------|---------|-------|-----------|---------------|--------------|-----------------|---------|---------------|---------------|---------|---------------|---------------|---------|---------------|
| 2023-01-01 00:00:00 UTC  | 220     | 1.5     | 330   | 50        | 12.5          | 0.95         | 25              | 60      | 50            | 40            | 70      | 60            | 50            | 80      | 70            |
| 2023-01-01 00:00:01 UTC  | 221     | 1.6     | 355   | 50        | 12.8          | 0.96         | 26              | 58      | 49            | 39            | 71      | 62            | 52            | 81      | 71            |
| ...                      | ...     | ...     | ...   | ...       | ...           | ...          | ...             | ...     | ...           | ...           | ...     | ...           | ...           | ...     | ...           |




## Directory layout

    .
    ├── data                    # Main data directory
    ├── images                  # Directory for pictures and graphs
    ├── notebooks               # Jupyter notebooks
    ├── reports                 # Html reports. Can be viewed via Github Pages
    ├── ...
    ├── .github/workflows       # Github workflow directory
    ├── .gitignore                     # 
    └── README.md


## View reports
[Dataset profiling](https://adamxrvn.github.io/iml-data-center/reports/report.html) (Before preprocessing)  
[Dataset profiling](https://adamxrvn.github.io/iml-data-center/reports/report_eda.html) (After preprocessing)  
[Dataset profiling](https://adamxrvn.github.io/iml-data-center/reports/report_resampling.html) (After resampling)  




## Getting Started

 TO BE EDITED

1. Clone this repo 
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...
5. Follow setup [instructions](Link to file)
