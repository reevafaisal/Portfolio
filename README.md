## Introduction

- Working as a Data Integration Analyst at the University of Wisconsin-Madison.
- Data Science (B.S.) graduate from the University of Michigan-Ann Arbor.

---

## Publications and Presentations

- Ahmed KS, **Faisal R**, Ali MM, Virani SS, Marcinak CT, Zafar SN. *Predicting Post-discharge Infection: A Machine Learning-driven Composite Outcome Model for Patients Undergoing Pancreatectomy*. Accepted for e-poster presentation at the American College of Surgeons’ Clinical Congress 2025.
- **Faisal R**, Yan F, Omar C. *From Holes To Whole: Building A Guided Onboarding Experience for Functional Programming in Hazel.*
[Poster presentation](https://drive.google.com/file/d/161VTlf0VTTH99A6JV_RWtrAfuYqzRfBO/view?usp=sharing) at the University of Michigan Explore Computer Science Research Poster Session 2025.


---

## Projects

### Weather Patterns Time-Series Forecasting and Anomaly Detection
#### [Report](https://reevafaisal.github.io/weather_predictions/index.html) | 01/2025

- Conducted comprehensive analysis of the [Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/data) dataset containing over 46,000 rows of meteorological data, including temperature, precipitation, and air quality indicators.
- Designed and implemented advanced anomaly detection techniques (Z-Score, IQR, Isolation Forest) to identify statistical and environmental outliers.
- Developed and compared time-series forecasting models (SARIMA, Random Forest, Stacked Ensemble) to predict temperature and precipitation trends with a focus on anomaly scenarios.
- Explored geographical and spatial analysis through choropleth maps, highlighting regional variations in weather conditions and anomalies.
- Evaluated feature importance using SHAP values, identifying wind speed and humidity as key drivers of air quality.

Technologies: Python, Scikit-learn, Pandas, NumPy, Plotly, Graphviz

### Search Engine
#### [Demo](https://reevafaisal.github.io/SearchEngine/) | 12/2024

- Built a scalable search engine similar to Google or Bing, for EECS 485.
- Includes information retrieval concepts like text analysis (tf-idf) and link analysis (PageRank), and parallel data processing with MapReduce.
- Uses a Service-Oriented Architecture to scale dynamic pages and web search.
- Creates a segmented inverted index of web pages using a pipeline of MapReduce programs.
- Built an Index server, a REST API app that returns search results in JSON format.
- Built a Search server, a user interface that returns search results just like Google or Bing.
    
Technologies: Python, SQL, Flask, HTML and CSS, JSON

### Mortality Outcome Prediction in TB and HIV  
#### [Report](https://reevafaisal.github.io/Performance-Predictions-in-TB-HIV/index.html) | 11/2024 
- This project leverages logistic regression to measure the predictive performance of Case Detection Rate (CDR) in country-specific mortality outcomes for patients with a dual burden of Tuberculosis (TB) and Human Immunodeficiency Viruses (HIV). 
- Using data from the [Tuberculosis Burden by Country](https://public.tableau.com/app/sample-data/TB_Burden_Country.csv?_gl=1*jep8cy*_ga*MTk5ODg2MTIzMi4xNzMxOTM4NzQx*_ga_8YLN0SNXVS*MTczMjU0MjY2OS42LjEuMTczMjU0MjgyNC4wLjAuMA..) dataset, it evaluates the role of CDR in determining mortality-to-incidence ratios (MIRs).
- Feature engineering techniques such as logarithmic scaling and quantile transformation were applied to the baseline model to address data skewness and improve model performance.
- The final model demonstrated an improvement in AUC for dual-burden mortality predictions, emphasizing the importance of early case detection in mitigating public health challenges.

Technologies: Python, Scikit-learn, Pandas, NumPy, Plotly 

### MapReduce Framework
#### [Demo](https://reevafaisal.github.io/MapReduce/) | 10/2024

- MapReduce framework in Python inspired by Google’s original [MapReduce paper](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf) for EECS 485.
- Executes MapReduce programs with distributed processing on a cluster of computers like AWS EMR, Google Dataproc, or Microsoft MapReduce.
- Includes program execution, distributed systems, fault tolerance, OS-provided concurrency facilities (threads and processes), and networking (sockets).
- Consists of a Manager which listens for user-submitted MapReduce jobs and distributes the work among Workers, and multiple Worker instances that receive instructions from the Manager and execute map and reduce tasks that combine to form a MapReduce program.

Technologies: Python, Madoop (Custom version of Hadoop)

### Insta485 Client-Side Web Application
#### [Demo](https://reevafaisal.github.io/Insta485/) | 10/2024  
- Developed an Instagram clone as part of a three-project sequence for EECS 485, focusing on building client-side dynamic pages using JavaScript, React, and AJAX.
- Refactored the server-side logic from Flask into a REST API to handle asynchronous data requests, enabling real-time updates for user interactions such as likes, comments, and infinite scrolling without page reloads.

Technologies: Python, SQL, HTML, CSS, JavaScript, React, Flask, AWS 
