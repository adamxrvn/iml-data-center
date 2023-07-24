<div align="center"> <img src="images/header.png"> </div>


# Industrial Machine Learning: Data Center Air Cooling
This project is a part of the Industrial Machine Learning course at Harbour.Space.  


## Project Description
The main goal of this project is to optimize energy consumption and cooling efficiency in a data center. It aims to reduce overall energy usage while ensuring effective cooling for the data center's equipment, thereby lowering operational costs associated with data processing and storage operations.

We will construct a predictive model that considers various factors such as server utilization, workload distribution, cooling efficiency, and energy management systems. By analyzing these parameters, the model will generate energy consumption forecasts for the data center.

Data Source Link: [Data Source](https://researchdata.ntu.edu.sg/dataset.xhtml?persistentId=doi%3A10.21979%2FN9%2FR1KU6R&version=&q=&fileTypeGroupFacet=%22Tabular+Data%22&fileAccess=&fileSortField=size)


**Model Validation**:
To validate the predictive model, we will compare its energy consumption forecasts with actual energy usage data from the data center. By evaluating the model's accuracy and effectiveness in optimizing energy consumption, we can determine its practical applicability.

**Modeling Technique**:
Given the temporal nature of energy consumption patterns, we will utilize Time Series analysis to develop the predictive model. Time Series models are well-suited for forecasting future values based on past data, making them appropriate for predicting energy consumption in a data center, especially during peak loads when cooling requirements are higher.


## Dataset Description
This dataset includes sensor measurements collected from an air free-cooled data center testbed. The dataset can be divided into two categories: energy and environmental data which are measured by instrumented hardware and software sensors during tests on the testbed. The energy data include power measurements of IT racks, cooling coils, heater, fans, and other supporting facilities. The environmental data include the conditions of outside weather, test rooms and IT racks. The condition includes temperature and RH measured at monitoring points at three heights on the front and back sides of IT racks, air volume flow rate and differential pressure across the IT racks, and concentrations of corrosive gases and particulate contaminations. The controlled tests folder includes 13 subfolders, each of which includes the sensor measurements under a specific supply temperature setpoint from 25°C to 37°C. Each data point is indexed by a timestamp corresponding to when the sensor measurement is sampled. Contents of sensor measurement files in each sub-folders are follows:

| File                                       | Description                                          |
|--------------------------------------------|------------------------------------------------------|
| Energy_PUE.csv                             | Instantaneous PUE                                    |
| Energy_Fan.csv                             | Powers of supply and exhaust fans                    |
| Energy_Heater.csv                          | Power of heater                                      |
| Energy_Rack.csv                            | Powers of four IT racks                              |
| Energy_AirCon.csv                          | Powers of cooling coils and supporting facilities    |
| Airflow_Control.csv                        | Supply air flow rate setpoint and measurement        |
| Chemical.csv                               | Concentrations (ppb) of NOz, H2S and SO2             |
| PM2.5.csv                                  | Concentrations (ug/m^3) of PM2.5                     |
| DP Rack 1.csv and DP _Rack 2.csv           | Differential pressure across IT racks                |
| Outside_Temp_RH.csv                        | Outside air temperature, RH and dewpoint             |
| RH_Cold_Rack_1.cs, RH_Cold_Rack_2.csv      | Supply air RH in front of four IT racks              |
| RH_Hot_Rack_1.cs, RH_Hot_Rack_2.csv        | Hot air RH in back of four IT racks                  |
| Temp_Cold_Rack_1.csv, Temp_Cold_Rack_2.csv | Supply air temperature in front of four IT racks     |
| Temp_Hot_Rack_1.csv, Temp_Hot_Rack_2.csv   | Hot air temperature in back of four IT racks         |
| Temp_Control.csv                           | Supply air temperature setpoint and measurement      |
| Temp_Room.csv                              | Temperature at mixing, cold, hold and buffer spaces  |
| RH_Room.csv                                | RH at mixing, cold, hold and buffer spaces           |



## Directory layout

    .
    ├── data                    # Main data directory
    │   └── controlled_tests     
    │       └── 25
    │       └── ...
    │       └── 37
    ├── images                  # Directory for pictures and graphs
    ├── ...                     # 
    ├── ...                     # 
    ├── ...                     # 
    ├── 
    └── README.md



## Getting Started

 TO BE EDITED

1. Clone this repo 
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)