# Analysing-the-Wine-Quality-Dataset-with-Python
Analysing the Wine Quality Dataset with Python
## Introduction:

The Wine Quality dataset, which includes the physical and chemical characteristics of several red and white wine varieties as well as quality rankings based on sensory assessments, has been examined in this research. Paulo Cortez and his team generated the dataset in 2009 [Cortez et al., 2009]. The analysis's objectives are to comprehend the distribution of wine quality scores, investigate the connections between various aspects and wine quality, and pinpoint the key variables affecting wine quality.

## Dataset Overview:

Source: The dataset was created by Paulo Cortez and his team in 2009 [Cortez et al., 2009].
Available Dataset: https://archive.ics.uci.edu/ml/datasets/wine+quality
Number of Instances: Red wine - 1599; White wine - 4898.
Number of Attributes: 11 physicochemical attributes + 1 output attribute (quality).

## Attributes:
The dataset contains 11 input variables based on physicochemical tests and 1 output variable based on sensory data. The attributes are as follows:

Fixed Acidity
Volatile Acidity
Citric Acid
Residual Sugar
Chlorides
Free Sulfur Dioxide
Total Sulfur Dioxide
Density
pH
Sulphates
Alcohol
Quality (output variable, a score between 0 and 10)


## Data Preparation:
The dataset was loaded into a Python environment, and no missing attribute values were found, simplifying the data preparation process. It was decided to analyze red and white wines separately.


# Exploratory Data Analysis (EDA)
## Wine Quality Distribution:

The wine quality scores were visualized to understand their distribution. The results showed that the scores are not evenly distributed; there are more normal wines than excellent or poor ones.

## Relationships Between Features and Wine Quality:

Fixed Acidity vs. Wine Quality: A scatter plot revealed a weak relationship between fixed acidity and wine quality.
Volatile Acidity vs. Alcohol Content: A scatter plot indicated a weak relationship between volatile acidity and alcohol content.
Citric Acid vs. Quality: A bar plot showed a minor impact of citric acid on wine quality.
Correlation Heatmap: A heatmap displayed correlations between different features. Strong correlations were observed between fixed acidity and citric acid, free sulfur dioxide, and total sulfur dioxide, as well as alcohol and quality.

## Most Important Factors:

To identify the most important factors influencing wine quality, Based on the analysis, alcohol was identified as the most crucial factor in determining the quality of wine, as it exhibited the most significant relationship with wine quality.

## Identifying Important Factors:

We can easily identify which items have a strong relationship to one another and which items are related to one another on a weekly basis from the correlation plot shown above for the dataset used to estimate the quality of the wine. For instance,
The strongly correlated items are :
1.fixed acidity and citric acid. 2.free sulphur dioxide and total sulphor dioxide. 3.fixed acidity and density. 4. alcohol and quality.
Therefore, it is evident from the information above that alcohol is the most crucial factor in determining the quality of wine.
The weekly correlated items are :
1.citric acid and volatile acidity. 2.fixed acidity and ph. 3.density and alcohol.
These relationships don't rely on one another at all.

## Conclusion:

This investigation of the Wine Quality dataset offers insightful information on the variables affecting wine quality. In addition to providing visualisations and relationships that make the dataset easier to grasp, it emphasises how important alcohol content is in determining wine quality.

The majority of the wines in the sample had mid-quality scores, with the distribution of wine quality scores being right-skewed.
While there is a complex relationship between several physical and chemical properties and wine quality, some characteristics have a noticeable impact on quality.
The most important elements influencing wine quality can be found via feature importance analysis.

## Recommendations:

Further analysis, including regression modeling, could be conducted to predict wine quality based on the identified important factors.
Additional data, such as grape types, wine brand, and selling price, could be collected and analyzed to gain a more comprehensive understanding of wine quality determinants.

## Available Dataset: https://archive.ics.uci.edu/ml/datasets/wine+quality

