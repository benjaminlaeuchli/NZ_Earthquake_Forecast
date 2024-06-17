![pulsar_star_wp](https://gssc.esa.int/navipedia/images/a/a9/Example.jpg)

# New Zealand's ten most earthquake prone cities and their earthquake event forecast.  

### Project Overview
Objective: This project aims to analyse a 24 year spanning earthquake dataset (2020-01-01 to 2024-06-16) obtained from geonet.org.nz/
and create a model to identify the 10 most earthquake towns / cities in New Zealand and predict the timing of the next earthquake eventy for these population centers. 

Context: Explain the challenges or complexities involved in the domain or field of study. Mention any common obstacles or issues that make the task difficult.

Significance: Highlight the importance of achieving accurate predictions and how it benefits further research, analysis, or practical applications in the field.

Goal: State the ultimate aim of the project, such as identifying specific phenomena, improving detection accuracy, or prioritizing certain areas for more detailed investigation.
## Team Members

- Dr. Benjamin Läuchli: [GitHub](https://github.com/benjaminlaeuchli)

## Jupyter Notebooks

This project consists of 3 Jupyter Notebooks that serve different purposes:

1. **Prep_Mod_MergeFile.ipynb**: 

This notebook focuses on preparing, modifying, and merging the used data sets to one compound dataset that is used for the EDA and machine learning approaches in notebooks 2 and 3.
The dataframe preparation includes a cKD-driven (scipy.spatial) cluster analysis to group the earthquakes time series by their recorded coordinates (latitude / longitude) and depth with respect to the nearest population center. This includes calculating the distance between the nearest town and respective earthquake under consideration of lateral distance and depth of the event.    

2. **EDA_Data_Visualisation.ipynb**: 
This notebook focuses on Exploratory Data Analysis (EDA) and visualisation of key aspects of the compiled dataset. It includes (i) Investigating number of NZ MMI type occurrences, (ii) Count number of quakes (NZ MMI grouped) as line plots, (iii) Exploring Earthquake Magnitude vs Depth, (iv) grouping the data by year and magnitude type and count the number of Earthquakes, (v) a interactive scatter plot of spatial-temporally clustered earthquake data with dropdown menu function, (vi) an interactive tempo-spatial graph with earthquake frequency per cluster plotted against measured magnitudes controlled by a dropdown menu. 


4. **Quake_Predict.ipynb**:
This notebook focuses on establishing a top 10 list of cities most likely to experience a major earthquake event uisng an isolation forest prediction model. Based on the outcome of the forecast year to next likely earth quake event are calculated. These results are set into context of the geographical distribution of populations centers, major earthquakes, and average population desnity on the North- and South Island.

...

## Installation and Setup

To set up the project locally, follow these steps:

1. Clone the repository:
```
git clone https://github.com/daistmarco/PredictingPulsarStar.git
```
2. Navigate to the project directory:
```
cd your-repository
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```
4. Download the modified dataset and place it in the project directory. The original dataset can be acquired from the link [xxx](link here).

5. ...

**Note:** If any of the above files are missing, the corresponding functionality may not work as expected.

Once the setup is complete, you can use the provided functions, such as `ann_prediction(csv_file)`, to make predictions on new data using the pre-trained models.


## Dataset

Descibe where you got the Data from. Did you get it from different sources? Provide Download links only if publicly available. 

## Attribute Information

The dataset contains the following attributes:

1. ...
2. ...
3. ...
4. ...

The dataset contains a total of xxx examples, with xxx positive examples and xxx negative examples.


## EDA/Cleaning

...

## Model Choices

What models did you test against each other and why? How did you optimize them? 

## Results

What metric did you use and why? How did you final model perform? 

## Prediction Function

What happens when a prediction is made using the final function? What scripts are run? 

## Final Remarks

