README File

# Predicting Crop Yields using a Machine Learning Model

### File Info
> **Author:** Leah Nicholson<br/>
**Date:** June 22nd, 2025<br/>
**Dataset:** Crop Yield Prediction Dataset<br/>
**Algorithm:**  Decision Tree<br/>
**ML Libraries:** Pandas, Numpy, Seaborn, Matplotlib, Scikit learn <br/>

### Project Description 

> **Context:**<br/>
Machine learning in agriculture is increasingly valuable, particularly in predicting crop yields. As a fundamental part of the global economy, agriculture sustains the human population, making accurate yield forecasting essential for addressing food security concerns and combating unpredictable weather. Crop yield prediction plays a crucial role in agricultural planning, which is what this machine learning model is trained to assist with. Key factors such as weather conditions (rainfall, temperature, etc.), pesticide usage, and historical yield data provides us with the necessary insights for training this model, allowing stakeholders to manage agricultural risks and make informed decisions to optimize future harvests. <br/>

> **Task:**<br/>
Develop a machine learning model to predict crop yields using historical data. Since this data is nonlinear, a model suited for nonlinearity will be used: Decision Tree. <br/>

### Data Notes

> **Data Source**: <br/>This dataset is from the FAO (Food and Agriculture Organization) and World Data Bank, sourced through the Crop Yield Prediction Dataset through Kaggle. <br/>

> **Link to Dataset:** <br/>[Crop Yield Dataset](https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset?resource=download)<br/>

> **Dataset Shape:** <br/>
The dataset contains 28241 Rows (crop-years) x 7 columns (features) = 197,687 data points<br/>
This excludes the provided indexing column. <br/>

> **Column Descriptions:** <br/>
    Unnamed: 0 | Contains an indexing number for the data <br/>
    Area | Contains the Country name<br/>
    Item | Contains the crop type (eg: Maize)<br/>
    Year | The given year<br/>
    hg/ha_yield | The yield obtained (our target variable)<br/>
    average_rain_fall_mm_per_year | Average rainfall in millimeters per year experienced in the given Area (Country)<br/>
    pesticides_tonnes | Pesticide use in tons<br/>
    avg_temp | The yearly average temperature experienced in the Area (Country)<br/>
