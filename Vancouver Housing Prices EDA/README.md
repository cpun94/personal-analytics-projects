# Vancouver Housing Prices Analysis

This project explores metropolitan Vancouver housing prices over a 20-year period (2004–2024). As a new homeowner and lifelong Vancouverite, this topic is personally meaningful as housing affordability and market trends have become increasingly important both locally and across Canada.

The analysis will focus on the Exploratory-Data-Analysis (EDA) process, including cleaning and transforming raw real estate sales data, generating numerical summaries, exploring statistical patterns, and visualizing long-term price trends using Python (Pandas, Matplotlib, and Seaborn libraries).

By the end of this analysis, the goal is to answer:   
  - How have average housing prices in Vancouver changed between 2004 to 2024?  
  - Which cities have experienced the most significant growth?  
  - What external factors might explain observed trends?  
  - Have real estate prices been consistent across the city or have a few, select cities experienced high volumes of real estate activity in their local communities?
  
This dataset is a publicly available on [Kaggle](https://www.kaggle.com/datasets/jennyzzhu/vancouver-house-prices-for-past-20-years).  

## Dataset Description
The dataset contains over 3,000 synthetic real estate transactions from 10 cities in the metropolitan Vancouver area from 2004 to 2024.  

Key columns include: ``Neighborhood``, ``City``, ``Year``, ``Season``, ``Property Type``, ``Bedrooms``, ``Bathrooms``, ``Year Built``, ``Square Footage (Land)``, and ``Price``.

A separate reference table containing over 40 neighbourhoods in metropolitan Vancouver along with the cities they belong to is also provided. Relevant details will be joined to the primary real estate transactions dataset during the data preparation phase.  

## Project Structure
```
Vancouver-Housing-Prices-EDA/
│
├── data/
│ ├── vancouver_neighborhoods.csv
│ └── vancouver_synthetic_house_prices_2004_2024.csv
│
├── notebooks/
│ └── vancouver_house_prices_EDA_notebook.ipynb
│
├── README.md
├── vancouver_house_prices_2004_to_2024_notebook.ipynb
```

## Key Insights
- Total sales volume and average home prices more than doubled over the 20-year period.
- Real estate activity peaked during 2020-2022, a period largely influenced by the COVID-19 pandemic and low interest rates.  
- Vancouver was the most popular city for real estate, with Downtown Vancouver & Downtown New Westminster ranking as the top neighbourhoods.     
- Spring & Summer consisntely showed the highest sales activity within the year with clear seasonal peaks observed across multiple years  
<!--- Properties built after 2010 commanded a higher premium than older homes-->
<!--Key findings and visualizations will be summarized here once analysis is complete.-->

## Next Steps
- Incorporate external datasets (interest rates, immigration data, construction activity) to integrate, analyse and draw further conclusions   
- Create interactive dashboards in Power BI or Tableau to visualize predictions, seasonal trends, factors that may influence real estate sales   
- Apply predictive analytics techniques such as linear regression or time-series forecasting to predict potential future selling price and understand the relationship between different independent variables

<!--## Project Structure-->

<!--## Tools-->

<!--## Key Insights-->

<!-- This text is hidden in the rendered Markdown. -->
