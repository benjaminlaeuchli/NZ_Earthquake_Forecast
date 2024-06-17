![pulsar_star_wp](https://gssc.esa.int/navipedia/images/a/a9/Example.jpg)

# Prediction on the ten most earth quake prone cities in New Zealand

### Project Overview
Objective: Describe the main goal of the project, which is to use machine learning techniques to predict a specific outcome based on the given dataset.

Context: Explain the challenges or complexities involved in the domain or field of study. Mention any common obstacles or issues that make the task difficult.

Significance: Highlight the importance of achieving accurate predictions and how it benefits further research, analysis, or practical applications in the field.

Goal: State the ultimate aim of the project, such as identifying specific phenomena, improving detection accuracy, or prioritizing certain areas for more detailed investigation.
## Team Members

- Team Member 1: [GitHub](https://github.com/benjaminlaeuchli)


## Jupyter Notebooks

This project consists of 3 Jupyter Notebooks that serve different purposes:

1. **Prep_Mod_MergeFile.ipynb**: 

This notebook focuses on preparing, modifying, and merging the used data sets to one compound dataset that is used for the EDA and machine learning approaches in notebooks 2 and 3.
The dataframe preparation includes a cKD-driven (scipy.spatial) cluster analysis to group the earthquakes time series by their recorded coordinates (latitude / longitude) and depth with respect to the nearest population center. This includes calculating the distance between the nearest town and respective earthquake under consideration of lateral distance and depth of the event.    

2. **EDA_Data_Visualisation.ipynb**: 
This notebook focuses on Exploratory Data Analysis (EDA) and visualisation of key aspects of the compiled dataset. It includes (i) Investigating number of NZ MMI type occurrences, (ii) Count number of quakes (NZ MMI grouped) as line plots, (iii) Exploring Earthquake Magnitude vs Depth, (iv) Grouping the data by year and magnitude type and count the number of Earthquakes, (v) a interactive scatter plot of spatial-temporally clustered earthquake data with dropdown menu function, (vi) an interactive tempo-spatial graph with earthquake frequency per cluster plotted against measured magnitudes controlled by a dropdown menu. 


4. **Quake_Predict.ipynb**: 
 throughout the studied time frame
data preprocessing, feature engineering, model training, and evaluation... etc. 
...
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

