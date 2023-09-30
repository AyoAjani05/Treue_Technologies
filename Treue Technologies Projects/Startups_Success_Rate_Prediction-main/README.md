# Startups_Success_Rate_Prediction

This project was completed as part of Treue Technologies Internship.
## Introduction
> In recent years, startups have played a pivotal role in shaping the business landscape, driving innovation, and reshaping industries. However, the journey from inception to success is riddled with challenges and uncertainties. To gain insights into the dynamics of startup success rates, we turn to data analysis and artificial intelligence as potent tools for understanding and potentially predicting these outcomes.<br>
Startups, by nature, are characterized by high-risk and high-reward scenarios. Many factors influence their trajectories, including market conditions, funding availability, leadership, and product-market fit. To comprehend these intricate dynamics, we leverage advanced data analytics and AI algorithms to navigate the startup landscape.
In this endeavor, our primary goal is to develop a highly accurate model for forecasting startup success rates. By delving into historical data encompassing critical parameters such as industry, funding rounds, team composition, geographic location, and market trends, we seek to unearth valuable insights and key determinants of startup success.<br>
Our predictive model aspires to serve as a compass for entrepreneurs, investors, and policymakers. With its insights, stakeholders can make informed decisions, allocate resources strategically, and increase the odds of success in the volatile startup ecosystem.Over the years, house prices have displayed significant fluctuations and trends. However, with the utilization of advanced data analytics and artificial intelligence, there is a potent tool to understand and potentially predict these price movements. Startup success prediction, powered by data-driven insights and AI algorithms, offers a proactive approach to grasp the dynamics of real estate markets.<br>
In this project, our primary objective is to develop a highly accurate model for forecasting Startup success. This predictive model will enable stakeholders, such as buyers, sellers, and investors, to make informed decisions, optimize investments, and navigate the real startup market with confidence.<br>

# Column Description

| Variable              | Definition                                                                                                         |
|-----------------------|--------------------------------------------------------------------------------------------------------------------|
| state_code            | The state code of the state in which the start-up is located.                                                      |
| latitude              | The latitude of the start-up.                                                                                      |
| longitude             | The longitude of the start-up.                                                                                     |
| zip_code              | The zip code of the start-up.                                                                                      |
| id                    | A unique Identifier.                                                                                               |
| city                  | The city in which the start-up is located.                                                                         |
| name                  | The name of the start-up.                                                                                          |
| labels                | Labels or categories associated with the start-up.                                                                 |
| founded_at            | The date when the start-up was founded.                                                                            |
| closed_at             | The date when the start-up closed or ceased operations.                                                            |
| first_funding_at      | The date of the first funding round for the start-up.                                                              |
| last_funding_at       | The date of the most recent funding round for the start-up.                                                        |
| age_first_funding_year| The number of years between founding and first funding.                                                            |
| age_last_funding_year | The number of years between founding and last funding.                                                             |
| age_first_milestone_year | The number of years between founding and the first significant milestone.                                       |
| age_last_milestone_year  | The number of years between founding and the most recent significant milestone.                                 |
| relationships         | The number of relationships or connections associated with the start-up.                                           |
| funding_rounds        | The total number of funding rounds the start-up has gone through.                                                  |
| funding_total_usd     | The total amount of funding in USD received by the start-up.                                                       |
| milestones            | The total number of significant milestones achieved by the start-up.                                               |
| state_code.1          | The state code of the state where the start-up is located.                                                         |
| is_CA                 | A binary indicator (0 or 1) representing whether the start-up is located in California (CA).                       |
| is_NY                 | A binary indicator (0 or 1) representing whether the start-up is located in New York (NY).                         |
| is_MA                 | A binary indicator (0 or 1) representing whether the start-up is located in Massachusetts (MA).                    |
| is_TX                 | A binary indicator (0 or 1) representing whether the start-up is located in Texas (TX).                            |
| is_otherstate         | A binary indicator (0 or 1) representing whether the start-up is located in a state other than CA, NY, MA, or TX.  |
| category_code         | The category or industry code associated with the start-up.                                                        |
| is_software           | A binary indicator (0 or 1) representing whether the start-up is in the software industry.                         |
| is_web                | A binary indicator (0 or 1) representing whether the start-up is in the web industry.                              |
| is_mobile             | A binary indicator (0 or 1) representing whether the start-up is in the mobile industry.                           |
| is_enterprise         | A binary indicator (0 or 1) representing whether the start-up operates in the enterprise sector.                   |
| is_advertising        | A binary indicator (0 or 1) representing whether the start-up is in the advertising industry.                      |
| is_gamesvideo         | A binary indicator (0 or 1) representing whether the start-up is in the games and video industry.                  |
| is_ecommerce          | A binary indicator (0 or 1) representing whether the start-up is in the e-commerce industry.                       |
| is_biotech            | A binary indicator (0 or 1) representing whether the start-up is in the biotech industry.                          |
| is_consulting         | A binary indicator (0 or 1) representing whether the start-up is in the consulting industry.                       |
| is_othercategory      | A binary indicator (0 or 1) representing whether the start-up falls into a category other than those listed above. |
| object_id             | A unique identifier for the start-up.                                                                              |
| has_VC                | A binary indicator (0 or 1) representing whether the start-up has received venture capital (VC) funding.           |
| has_angel             | A binary indicator (0 or 1) representing whether the start-up has received angel funding.                          |
| has_roundA            | A binary indicator (0 or 1) representing whether the start-up has completed a round A funding.                     |
| has_roundB            | A binary indicator (0 or 1) representing whether the start-up has completed a round B funding.                     |
| has_roundC            | A binary indicator (0 or 1) representing whether the start-up has completed a round C funding.                     |
| has_roundD            | A binary indicator (0 or 1) representing whether the start-up has completed a round D funding.                     |
| avg_participants      | The average number of participants in funding rounds for the start-up.                                             |
| is_top500             | A binary indicator (0 or 1) representing whether the start-up is ranked among the top 500.                         |
| status                | The current status or condition of the start-up.                                                                   |


# Table of Contents
- `data:` the folder containing the original and the cleaned datasets.
- `model:` the folder containing the trained Model.
- `Startups Success Rate Data Analysis and Visualization Notebook.ipynb:` the Jupyter Notebook containing the cleaning and analytical techniques used.
- `Startups Success Rate_Prediction.ipynb`: the Jupyter Notebook containing the techniques used in creating the model.
- `Requirements.txt`: the required python libraries.

# Installation and Configuration
Download Anaconda at https://www.anaconda.com/download/ and install the libraries in the requirement.txt file using PIP

Install Jupyter Notebook by running the following command:
```
conda install jupyter notebook
```
or
```
pip install jupyter notebook
```

Then launch the Jupyter Notebook to view the .ipynb file.

