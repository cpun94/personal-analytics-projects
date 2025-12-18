# Netflix Subscriber Churn

This project applies multiple machine learning classification models to predict subscriber churn using a dataset modeled after Netflix's user base. This analysis emphasizes feature engineering and model interpretability to identify key drivers of churn and support data-driven customer retention strategies in subscription-based businesses. 

Like many others, my Netflix usage surged during the COVID-19 pandemic, highlighting the importance of customer retention for subscription-based platforms. Companies such as Netflix likely rely on churn predicton to inform product and marketing decisions, and this project represents a scaled-down version of how such analytics work in practice. 

## Objectives
- Identify the key factors that influence whether a subscriber is likely to churn.  
- Compare multiple machine learning models, balancing predictive performance with interpretability.  
- Evaluate model results using appropriate classification metrics to support business decision-making  
  
## Dataset Description
The dataset contains over 5,000 synthetic customer records, representing subscriber behaviour for a video-streaming service modeled after Netflix. 

Key columns include: 
  - ``customer_id``
  - ``Churned``
  - Additional behavioural and account-related features

This dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets/abdulwadood11220/netflix-customer-churn-dataset?resource=download&select=netflix_customer_churn.csv).  

## Project Structure
netflix-ml-project/
├── data/
├── notebooks/
├── src/
├── models/
├── visuals/
├── reports/
└── README.md

## Methodology
1. **Data Cleaning & Preprocessing:** Load, clean, and prepare the dataset by handling outliers, filling missing values, and removing duplicates.
2. **Exploratory Data Analysis (EDA):** Explore variable distributions, identify trends, and examine relationships and correlations through visualizations.  
3. **Feature Engineering:** Create new features from existing variables to improve model performance and extract deeper patterns. 
4. **Model Development:** Build, train, test, and tune multiple machine-learning models for comparison. 
5. **Model Evaluation & Interpretation:** Evaluate model accuracy and complexity, compare results across models, and interpret feature importance to understand drivers of churn. 

## Key Insights
*This section is currently in progress and will be updated shortly.*

## Next Steps
Potential future improvements include:
  - Incorporating time-based features to capture churn trends over time
  - Testing additional models or hyperparameter optimization

<!---- Total sales volume and average home prices more than doubled over the 20-year period.-->
<!---- Real estate activity peaked during 2020-2022, a period largely influenced by the COVID-19 pandemic and low interest rates.-->  
<!---- Vancouver was the most popular city for real estate, with Downtown Vancouver & Downtown New Westminster ranking as the top neighbourhoods.-->     
<!---- Spring & Summer consisntely showed the highest sales activity within the year with clear seasonal peaks observed across multiple years-->  
<!--- Properties built after 2010 commanded a higher premium than older homes-->
<!--Key findings and visualizations will be summarized here once analysis is complete.-->

## Next Steps
*This section is currently in progress and will be updated shortly.*
