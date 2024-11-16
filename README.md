# PRODIGY_DS_05
## Analyising the traffic Accident
Overview

This project explores a comprehensive dataset on accidents across the United States to uncover trends, patterns, and actionable insights. The analysis focuses on identifying factors contributing to accidents, highlighting high-severity hotspots, and proposing data-driven solutions to improve road safety.
### Dataset Description
This is a countrywide traffic accident dataset, which covers 49 states of the United States. The data is continuously being collected from February 2016, using several data providers, including multiple APIs that provide streaming traffic event data. These APIs broadcast traffic events captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. Currently, there are about 1.5 million accident records in this dataset. Check the below descriptions for more detailed information.
for more information https://smoosavi.org/datasets/us_accidents
- Source of data set: https://www.kaggle.com/datasets/sasikumarg/us-accidents
### Key Insights

    High-Severity States: States like VA, PA, NC, NY, and FL report the highest number of Severity Level 4 accidents.
    Peak Accident Times: Accidents are most frequent during rush hours, emphasizing the role of traffic congestion.
    Weather Influence: Adverse weather conditions such as rain and snow significantly increase accident risk.

Features

    Exploratory Data Analysis (EDA): Examining trends by time, location, and severity.
    Geospatial Analysis: Mapping accident density and identifying high-risk zones using folium and geopandas.
    Severity Analysis: Investigating factors influencing accident severity levels.
    Data Visualization: Creating impactful visuals using Matplotlib and Seaborn.

Skills Developed

    Data Cleaning: Managing large, messy datasets and handling missing values.
    Data Analysis: Extracting insights using Python libraries like pandas and numpy.
    Geospatial Mapping: Visualizing accident density with geospatial tools.
    Statistical Analysis: Understanding the relationship between variables affecting accidents.
    Communication: Presenting findings through clear, actionable insights.

Tools & Technologies

    Python: pandas, numpy, matplotlib, seaborn, folium, geopandas
    Jupyter Notebook: For interactive analysis and visualization

How to Run

    Clone the repository:

git clone https://github.com/your-username/us-accident-analysis.git
cd us-accident-analysis

Install required packages:

pip install -r requirements.txt

Run the analysis notebook:

    jupyter notebook US_Accident_Analysis.ipynb

Future Work

    Incorporating machine learning models to predict accident severity.
    Exploring temporal trends to improve traffic management strategies.
    Extending analysis to include more detailed socio-economic and infrastructure data.

Contribution

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.
License

This project is licensed under the MIT License.


