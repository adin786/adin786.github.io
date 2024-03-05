---
title: "Azam Din"
layout: splash
permalink: /
projects_1:
  - image_path:    /assets/images/energy-teaser2.jpg
    title:         "Energy Forecasting"
    excerpt:       "<span class='project-text'>
    Built a serverless ML pipeline for timeseries forecasting + CI/CD.
    <br>
    `Terraform` `AWS` `Lambda` `sktime` `mlflow` `dvc` `streamlit` `Docker` `pytest` `github-actions`</span>"
    # url:           "/projects/energy-forecast"
    url:           "https://github.com/adin786/energy_forecast"
    btn_label:     "Read More"
    btn_class:     "btn--primary"

  - image_path:    /assets/images/tado-teaser.jpg
    title:         "Smart Home ELT pipeline"
    excerpt:       "<span class='project-text'>
    Built an ELT pipeline to ingest smart home JSON data from Tado API, into Postgres.
    <br>
    `airflow` `DockerOperator` `Postgres` `SQLAlchemy` `pytest` `JSON` `Makefile`</span>"
    # url:           "/projects/energy-forecast"
    url:           "https://github.com/adin786/house_climate"
    btn_label:     "Read More"
    btn_class:     "btn--primary"

  - image_path:    /assets/images/auto-trader-teaser.jpg
    title:         "Used Car Values"
    excerpt:       "<span class='project-text'>
    Web scraped auto trader adverts and predicted valuation of my own car.
    <br>
    `python` `pandas` `numpy` `requests` `BeautifulSoup4` `matplotlib` `seaborn` `sklearn`</span>"
    url:           "https://github.com/adin786/autotrader-analysis"
    btn_label:     "Read More"
    btn_class:     "btn--primary"

projects_2:
  - image_path:    /assets/images/jobs.jpg
    title:         "Job Description NLP"
    excerpt:       "<span class='project-text'>
    Interactive job ad classifier for data jobs. Web scraping and NLP.
    <br>
    `requests` `BeautifulSoup4` `pandas` `nltk` `spacy` `seaborn` `sklearn` `streamlit`</span>"
    url:           "https://github.com/adin786/jobs-analysis"
    btn_label:     "Read More"
    btn_class:     "btn--primary"

  - image_path:    /assets/images/mot-teaser.jpg
    title:         "MOT data analysis"
    excerpt:       "<span class='project-text'>
    Analysed 30mil MOT tests from GOV.uk for trends in vehicle ownership, pass/fail rates etc.
    <br>
    `sqlite` `pandas` `seaborn` `sklearn`</span>"
    url:           "https://github.com/adin786/mot-data"
    btn_label:     "Read More"
    btn_class:     "btn--primary"

---
<br>
![image-center](assets/images/bio-circle.png){: .bio-image}

<h1>Azam Din</h1>{: .text-center .text-h1}
<p>ML Engineer, MLOps, Leadership</p>{: .text-center .text-h2}

Experienced ML Engineer, currently leading the MLOps team at a national supermarket bank. I've specialised in Python, Docker and AWS, including the Sagemaker ecosystem. I am passionate about engineering robust machine learning and data pipelines, architecting and building out cloud infrastructure, including tooling & processes for MLOps.
{: .bio-text}

My current role involves being responsible for the bank's ML platform, devveloping frameworks for contract-based ETL pipelines, ML batch inference, Data Science dev environments, CI/CD, model training pipelines and much more...
{: .bio-text}

Prior to this I was a Research Data Scientist for a SaaS offering in the Sales Enablement space where I built NLP pipelines, voice feature engineering and content recommenders. As an experienced Python developer, I have mentored my teams to instill engineering quality and standardisation, especially in code quality with efforts in unit testing, abstraction layers, CI/CD.
{: .bio-text}

With my MEng degree in Mechanical & Aerospace Engineering I specialised in instrumentation and data acquisition systems.  I have led a wide range of analytical projects across various industries including automotive, oil & gas and IT. I am passionate about automating complex processes and building novel machine learning solutions.
{: .bio-text}

<b>Skip to:</b> <a href="#personal-projects">Projects</a> \| <a href="#experience">Experience</a> \| <a href="#skills">Skills</a>
{: .bio-text .bio-padding}

---

# Personal projects
{: .section-heading}

{% include feature_row id="projects_1" %}

{% include feature_row id="projects_2" %}

---

# Experience
{: .section-heading}

<div class="experience-table">

<div class="experience-row">
    <div class="experience-left">
<img src="/assets/images/sainsburys_bank_logo.png" class="experience-logo2">
    </div>
    <div class="experience-right">
        <span class="experience-heading-bold">
Lead MLOps Engineer
        </span>
        <br>
        <span class="experience-heading-small">
Sainsburys Bank - May/2023 to today
        </span>
        <br>
        <span class="experience-text">
Led the ML-platform team (AWS, SageMaker, Terraform, CDK, Gitlab CI, Step Funcs, Lambda, CodePipeline). I led the MLOps strategy for the team, evaluating and deploying PoCs for Mlflow, Sagemaker Studio, FastAPI and Streamlit. Developed the bank's first NLP workflows including a topic modelling solution for analysing customer feedback. Built automated model evaluation pipelines. Established containerisation practises and standardised the team's python dev tooling (poetry, ruff, pre-commit, Gitlab CI, cookiecutter templating). Developed a self-service ETL framework for deploying pipelines using JSON contracts (Python, CDK and AWS Step Functions).
        </span>
    </div>
</div>

<div class="experience-row">
    <div class="experience-left">
<img src="/assets/images/btc-logo-50.png" class="experience-logo2">
    </div>
    <div class="experience-right">
        <span class="experience-heading-bold">
R&D Data Scientist
        </span>
        <br>
        <span class="experience-heading-small">
Bigtincan, Sales Enablement - Jan/2022 to Apr/2023
        </span>
        <br>
        <span class="experience-text">
I primarily worked on NLP pipelines, text classification, online topic-modelling, embeddings, voice analytics. 
I built and deployed an interactive sales call analytics system using EC2, Docker & spaCy. 
With my engineering focus I established standardised MLOps tooling like Mlflow and DVC, managed a Prodigy annotation server and was responsible for data engineering and ingestion workflows.
         </span>
    </div>
</div>


<div class="experience-row">
    <div class="experience-left">
<img src="/assets/images/doosan-logo-50.png" class="experience-logo2">
    </div>
    <div class="experience-right">
        <span class="experience-heading-bold">
Project Engineer
        </span>
        <br>
        <span class="experience-heading-small">
Doosan Babcock - May/2019 to Dec/2021
        </span>
        <br>
        <span class="experience-text">
I served in a technical consultancy as the lead engineer and client-facing project manager for a €1.6 million test-engineering contract. 
I reported to both client and senior management and explained technical topics to a diverse audience. 
I used pandas to build a data extraction pipeline and automated visualisation and report generation, doubling documentation throughput. 
I established the team's Git version control and authored 20+ technical reports.
         </span>
    </div>
</div>


<div class="experience-row">
    <div class="experience-left">
<img src="/assets/images/jlr-logo-50.png" class="experience-logo2">
    </div>
    <div class="experience-right">
        <span class="experience-heading-bold">
Technical Strategy Analyst
        </span>
        <br>
        <span class="experience-heading-small">
Jaguar Land Rover - Apr/2017 to Apr/2019
        </span>
        <br>
        <span class="experience-text">
As an analyst, I presented competitor and market intelligence to Directors and built forecasts for early electric vehicle adoption. 
I proposed and developed a new EV fleet telematics data pipeline and created a regression model to predict EV battery failures, which helped the business to assess a potential warranty risk of over £10 million. 
I was also the lead engineer in a technology partnership that delivered a prototype robotic EV charger.
         </span>
    </div>
</div>


<div class="experience-row">
    <div class="experience-left">
<img src="/assets/images/jlr-logo-50.png" class="experience-logo2">
    </div>
    <div class="experience-right">
        <span class="experience-heading-bold">
Vehicle Dynamics Engineer
        </span>
        <br>
        <span class="experience-heading-small">
Jaguar Land Rover - Sep/2015 to Mar/2017
        </span>
        <br>
        <span class="experience-text">
I was responsible for conducting **objective** testing and subjective assessment, as well as developing data processing automation tooling and data validation tools using MATLAB. I also developed new vehicle assessment metrics and supported CAE-based tuning using a driving simulator.
         </span>
    </div>
</div>

</div>

---

# Skills
{: .section-heading}

| Languages & Technologies | `Python` `SQL` `Docker` `Devcontainers` `AWS` `Sagemaker` `GCP` `Databricks` `Terraform` `Linux` `Git` `Bash` `Jupyter` `Matlab` `CI/CD`|
| Python libraries | `sklearn` `tensorFlow` `pytorch` `mlflow` `dvc` `wandb` `airflow` `matplotlib` `plotly` `seaborn` `scipy` `pandas` `numpy` `sktime` `spaCy` `Prodigy` `nltk` `librosa` `dask` `pyspark` `transformers` `BERTopic` `pre-commit` `BeautifulSoup4`|
