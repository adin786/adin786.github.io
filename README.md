# Azam Din (adin786)
I'm an MEng Mechanical Engineer with a software and data analytics specialism.  I'm learning Data Science and machine learning skills to maximise my value as a numerical and analytical problem solver.  This Github is my place to document a few of my projects, develop good software development practises and hopefully build some stories around data!

## 🔭 Project summary
|Project name|Links|
|------------|-----|
|MOT data analysis|([More detail](#mot-data-analysis)) / ([Link to repo](https://github.com/adin786/mot-data))|
|Used car pricing analysis|([More detail](#used-car-pricing-analysis)) / ([Link to repo](https://github.com/adin786/autotrader-analysis))
|Titanic survivor prediction|([More detail](#titanic-survivor-prediction)) / ([Link to repo](https://github.com/adin786/ad-titanic))|
|DIC strain mapping|([More detail](#dic-strain-mapping-data-processing)) / (private repo)|

### MOT data analysis 
<img src="images/mot-2.jpg" height=50><img src="https://github.com/adin786/mot-data/raw/main/images/testmileage_histplot.png" height=50><img src="https://github.com/adin786/mot-data/raw/main/images/pairplot_bymake.png" height=50>

Analysing 30 million MOT test records from GOV.uk, trying to extract some insights and pick out trends about failure rates.  Tools I'm using: 
- SQLite and Pandas for ETL, loading and sorting large dataset
- Seaborn and Matplotlib for data visualisation and exploration
- Scikit-learn for model training, classification
- Libraries: SQLite, Pandas, Seaborn, Scikit-Learn

### Used car pricing analysis
<img src="images/used_cars2.jpg" height=50><img src="https://github.com/adin786/autotrader-analysis/raw/main/images/modelrev.png" height=50><img src="https://github.com/adin786/autotrader-analysis/raw/main/images/svr.png" height=50>

Modelled car pricing on Autotrader.co.uk to help decide on a selling price for my own Audi A6.
- Wrote a webscraper to extract 1000+ adverts
- Analysed trends and extracted 11 features about the cars from each advert
- Tuned a Support Vector Regression model which achieved r^2 of 0.97 and MAE of £961
- Most important features were `age` and `mileage`
- libraries: BeautifulSoup4, Pandas, Seaborn, Scikit-Learn

### Titanic survivor prediction
<img src="images/Titanic2.jpg" height=50 alt="abc"><img src="https://github.com/adin786/ad-titanic/raw/main/images/titanic_ticketfreq_vs_survived.png" height=50><img src="https://github.com/adin786/ad-titanic/raw/main/images/titanic_deck_vs_survived.png" height=50><img src="https://github.com/adin786/ad-titanic/raw/main/images/titanic_logreg2_charts.png" height=50>

Predicted survival status for passengers onboard the Titanic cruise ship.  Dataset from www.kaggle.com
- Pandas and Seaborn for exploratory analysis
- Engineered features from text data like title and deck number. Engineered numerical features like family_size, ticket_frequency
- Trained, tuned and compared classifier models based on Logistic Regression, Decision Tree, and Random Forest
- Best model gave cross validation accuracy of 0.83 and AUC of 0.88.
- Libraries: Pandas, Seaborn, Scikit-Learn

### DIC strain mapping data processing
Commercial project. I've written a toolkit of python scripts and modules to take multi-million row point-cloud data files, aligns them all to a global coordinate system and exports the data into formatted csv files for a commercial client.  The data comes from a DIC (digital image correlation) image based inspection system for measuring mechanical behaviour of deforming structures in large scale bending tests.  Inluded creating a GUI for data filtering and extraction

### Other software projects in MatLab and Python
- Matlab GUI tool for data processing, visualisation and automation of Automotive ECU tuning

### 🌱 I’m currently learning ...
Data science, python, SQL, machine learning models, data transformation, mining and visualisation

## 📫 How to reach me:
[Github](https://github.com/adin786/)   /   [Linkedin](https://www.linkedin.com/in/azam-din/)   /   [Kaggle](https://www.kaggle.com/azamdin)







<!--
**adin786/adin786** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

