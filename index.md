---
title:          About me
permalink:      /
layout:         archive
classes:        wide
author_profile: true
feature_row:
  - image_path:    /assets/images/used-cars-teaser.jpg
    alt:           "Cars at auction"
    title:         "Used car pricing analysis"
    excerpt:       "<ul style='padding-inline-start:20px'>
    <li>Built a used car valuation model to optimise the selling price for my own car.</li>
    <li>Web-scraped 1000+ adverts from Autotrader and analysed price trends against features like age, mileage, engine size etc.</li>  
    <li>With an SVR Regression model I achieved R^2: 0.97 and MAE: £961.  The most influential features on price were age and mileage.</li>
    <li>The final result valued my car within £200 of Autotrader's own recommended selling price.</li>
    </ul>
    **Tools:** `Python` `Pandas` `NumPy` `Requests` `BeautifulSoup4` `Matplotlib` `Seaborn` `Scikit-learn`"
    url:           "/projects/used-cars"
    btn_label:     "Read More"
    btn_class:     "btn--inverse"

  - image_path:    /assets/images/jobs.jpg
    alt:           "Job market"
    title:         "Job market analysis (NLP)"
    excerpt:       "<ul style='padding-inline-start:20px'>
    <li>Created an NLP job title classifier with data scraped from indeed.com.</li>
    <li>Automation of job titling could boost recruitment efficiency and better reach the most suitable candidates.</li>
    <li>Extracted 'skill tags' for each role (Python, Cloud, Machine Learning etc).</li>
    <li><a href='https://share.streamlit.io/adin786/jobs-analysis/main/app/app_deploy.py'>Deployed a web-app</a> using Streamlit, allowing anyone to classify a job as 'Data Scientist', 'Data Analyst', or 'Data Engineer'.</li>
    </ul>
    **Libraries:** `Requests` `BeautifulSoup4` `Pandas` `NTLK` `Seaborn` `Scikit-learn` `Streamlit`"
    url:           "/projects/jobs"
    btn_label:     "Read More"
    btn_class:     "btn--inverse"

  - image_path:    /assets/images/mot-teaser.jpg
    alt:           "mot inspection"
    title:         "MOT data analysis"
    excerpt:       "<ul style='padding-inline-start:20px'><li>Analysed 30mi MOT tests from GOV.uk for trends in vehicle ownership, pass/fail rates etc.</li></ul>
**Libraries:** `SQLite` `Pandas` `Seaborn` `Scikit-Learn`"
    url:           "/projects/mot"
    btn_label:     "Read More"
    btn_class:     "btn--inverse"

  - image_path:    /assets/images/titanic-teaser.jpg
    title:         "Energy Demand Forecasting"
    excerpt:       "<ul style='padding-inline-start:20px'>
    <li>Predicted survival probability for passengers onboard the Titanic cruise ship.</li>
    </ul>
**Libraries:** ..."
    url:           "/projects/energy_forecast"
    btn_label:     "Read More"
    btn_class:     "btn--inverse"
---
[Click here to go direct to my Github profile](https://github.com/adin786)

Hi, I'm a Data Scientist with an Product Development and Strategic analysis background.  I hold a Masters degree in Mechanical Engineering and Aeronautics with a focus in numerical analysis and simulation.  I have extensive experience in the automotive and energy sectors in product development, testing and strategic insight functions.  

My commercial projects have included: 
- **Fleet telematics:** Deployment of a vehicle fleet telematics system including ETL pipeline, data processing, visualisation and dashboarding. 
- **Battery health forecasting:** Regression model to forecast EV battery failure, and add data-driven insight to support >£10mil warranty analysis.
- **Pipe inspection tools:** Developed data processing and reporting tools for 2x cutting edge subsea pipe test inspection products, laser bore scanning and 3D strain imaging.

My technical expertise is in data mining, visualisation and software development (Python, Matlab etc).  I work on Data analytics and machine learning projects in my free time.  Some personal projects include:

# Projects
{% include feature_row type="left" %}

<!-- # Professional Experience
**Testing Project Engineer - Doosan Babcock, Glasgow** *(05/2019 - Present)*
- Lead engineer and project manager for a €1.6mil. subsea client pipe reeling test programme.
- Reported and presented weekly on technical status to client senior management.
- Developed 2x new data processing pipelines for cutting-edge pipe 3D inspection products: laser scanning and stereo strain imaging.
- Wrote automated plotting tools, doubling the team’s report writing throughput and drastically improving quality.
- Established the team’s use of Git for version control, for developing robust and extensible data processing tools.
- Completed 20+ technical reports issued to clients including data processing and visualisation.

**Technical Strategy Analyst - Jaguar Land Rover, Warwickshire** *(04/2015 - 04/2019)*
-	Supported Exec Leadership with business intelligence, competitor benchmarking and auto-industry trend analysis.
-	Used regression to combine multiple EV sales projections into an aggregated forecast model.  This work proved essential in winning support for investment in UK-based EV manufacturing.
-	Identified a gap in EV usage data and led the deployment of a streaming data pipeline for a fleet of electric taxis. This resulted in 500k+ miles of strategic EV data.  Stored in the Google cloud datalake to make available across corporate silos.
-	Was a central contact for all stakeholders including Legal (GDPR), BI team (dashboards) as well as Exec Leadership.
-	Developed an EV range prediction model for rapid benchmarking.
-	Produced an Internal Comms video to show the company’s long-range vision of an autonomous, connected and electrified future.
-	Delivered a prototype robotic premium EV charger in partnership with a start-up.

**Vehicle Dynamics Engineer - Jaguar Land Rover, Warwickshire** *(09/2015 to 03/2017)*
-	Steering control system development, test data-acquisition and analysis for products including XE, Evoque, I-PACE. 
-	Responsible for maintaining and extending the functionality of a business critical Matlab code library for time-series analysis of vehicle test data, including automated processing, visualisation and metrics.
-	Built a suite of Matlab-based graphical tools for automation, increasing team productivity and driving quality and consistency of steering feel across all product lines. -->

# Data science tools
- Languages: `Python` `SQL` `Matlab`
- Databases: `SQLite` `BigQuery`
- Machine learning: `sklearn`
- Tex analytics: `nltk` `spaCy`
- Data manipulation: `pandas` `numpy` `dask` `scipy`
- Visualisation: `matplotlib` `seaborn` `plotly` `Tableau` `streamlit`

# Other skills and tools
- Google Cloud: `BigQuery` `Datastudio`
- Web scraping: `BeatifulSoup4`
- Other: `pptk` (point cloud visualisation)

# Currently learning
- `tensorflow/keras`
- `Databricks` `spark`
- `Airflow`


<!--
## Project summary
#
|Project name|Links|
|------------|-----|
|MOT data analysis|([More detail](#mot-data-analysis)) / ([Link to repo](https://github.com/adin786/mot-data))|
|Used car pricing analysis|([More detail](#used-car-pricing-analysis)) / ([Link to repo](https://github.com/adin786/autotrader-analysis))
|Titanic survivor prediction|([More detail](#titanic-survivor-prediction)) / ([Link to repo](https://github.com/adin786/ad-titanic))|
|DIC strain mapping|([More detail](#dic-strain-mapping-data-processing)) / (private repo)|
#
#
### MOT data analysis 
<img src="https://github.com/adin786/adin786/raw/main/images/mot-2.jpg" height=50><img src="https://github.com/adin786/mot-data/raw/main/images/testmileage_histplot.png" height=50><img src="https://github.com/adin786/mot-data/raw/main/images/pairplot_bymake.png" height=50>
#
Analysing 30 million MOT test records from GOV.uk, trying to extract some insights and pick out trends about failure rates.  Tools I'm using: 
- SQLite and Pandas for ETL, loading and sorting large dataset
- Seaborn and Matplotlib for data visualisation and exploration
- Scikit-learn for model training, classification
- Libraries: SQLite, Pandas, Seaborn, Scikit-Learn
#
### Used car pricing analysis
<img src="https://github.com/adin786/adin786/raw/main/images/used_cars2.jpg" height=50><img src="https://github.com/adin786/autotrader-analysis/raw/main/images/modelrev.png" height=50><img src="https://github.com/adin786/autotrader-analysis/raw/main/images/svr.png" height=50>
#
Modelled car pricing on Autotrader.co.uk to help decide on a selling price for my own Audi A6.
- Wrote a webscraper to extract 1000+ adverts
- Analysed trends and extracted 11 features about the cars from each advert
- Tuned a Support Vector Regression model which achieved r^2 of 0.97 and MAE of £961
- Most important features were `age` and `mileage`
- libraries: BeautifulSoup4, Pandas, Seaborn, Scikit-Learn
#
### Titanic survivor prediction
<img src="https://github.com/adin786/adin786/raw/main/images/Titanic2.jpg" height=50 alt="abc"><img src="https://github.com/adin786/ad-titanic/raw/main/images/titanic_ticketfreq_vs_survived.png" height=50><img src="https://github.com/adin786/ad-titanic/raw/main/images/titanic_deck_vs_survived.png" height=50><img src="https://github.com/adin786/ad-titanic/raw/main/images/titanic_logreg2_charts.png" height=50>
#
Predicted survival status for passengers onboard the Titanic cruise ship.  Dataset from www.kaggle.com
- Pandas and Seaborn for exploratory analysis
- Engineered features from text data like title and deck number. Engineered numerical features like family_size, ticket_frequency
- Trained, tuned and compared classifier models based on Logistic Regression, Decision Tree, and Random Forest
- Best model gave cross validation accuracy of 0.83 and AUC of 0.88.
- Libraries: Pandas, Seaborn, Scikit-Learn
#
### DIC strain mapping data processing
Commercial project. I've written a toolkit of python scripts and modules to take multi-million row point-cloud data files, aligns them all to a global coordinate system and exports the data into formatted csv files for a commercial client.  The data comes from a DIC (digital image correlation) image based inspection system for measuring mechanical behaviour of deforming structures in large scale bending tests.  Inluded creating a GUI for data filtering and extraction
#
### Other software projects in MatLab and Python
- Matlab GUI tool for data processing, visualisation and automation of Automotive ECU tuning
#
#
### I'm currently learning ...
Data science, python, SQL, machine learning models, data transformation, mining and visualisation
#
## How to reach me:
[Github](https://github.com/adin786/)   /   [Linkedin](https://www.linkedin.com/in/azam-din/)   /   [Kaggle](https://www.kaggle.com/azamdin)
-->
<!-- Site structure and layout inspired by https://shravan-kuchkula.github.io/ -->
