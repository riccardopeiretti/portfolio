# portfolio
Welcome to my portfolio of university projects. Here you will find a collection of work completed during my bachelor’s and master’s studies. 

## cycling related projects

### Calorie Estimation for Cyclists 
- *Objective:* Propose a machine learning approach to estimate a cyclist's caloric needs during training, using body metrics, historical ride data, and training plans.  

- *Achievements:* Designed the concept of a Random Forest regression model using a simulated dataset, outlining validation strategies with MAE and RMSE; the proposed system envisions integration with wearable devices and platforms such as Strava/Garmin, with accuracy requirements of ≥85% and full GDPR compliance.  

### Predictive Model for Cycling
- **Objective:** Develop a supervised machine learning model to predict riders' results in each stage of the Tour de France 2023, using historical Grand Tour data (2017–2022) and stage/rider characteristics.  

- **Achievements:** Implemented and evaluated two predictive models with XGBoost:  
  - *Time prediction model* (R² ≈ 0.90) accurately estimated stage completion times.  
  - *Position prediction model* (R² ≈ 0.26) partially predicted rankings, highlighting the complexity of rider-specific outcomes. 

  The thesis identified major challenges (data quality, tactics, injuries, weather) and proposed improvements through richer feature integration. 

### Product Development for Safety in Cycling 
- **Objective:** Design and prototype an innovative smart helmet (E-Helmet) and companion mobile app to enhance cyclists’ road safety.  

- **Achievements:** Conducted user research through surveys, interviews, and field observations; defined personas and scenarios; developed and evaluated low- and medium-fidelity prototypes. Key features include brain–computer interface for automatic turn signals, accident detection, head-up display, and integration with fitness apps. Usability testing showed strong results (SUS ≈ 85, ~94% task completion).

## other modeling projects

### AIS-Based Predictive Modeling of Vessel Trajectories 
- **Objective:** Predict the future positions of vessels up to five days ahead using Automatic Identification System (AIS) data, integrating vessel characteristics, navigation status, and port information.  

- **Achievements:** Conducted exploratory data analysis and feature engineering (lags, time differences, distance and bearing to port); implemented predictive models with Random Forest, XGBoost, and LightGBM. The best-performing models leveraged temporal and spatial features (latitude/longitude lags, moving averages) to improve trajectory forecasting accuracy, highlighting both the potential and limitations of AIS data for maritime traffic prediction.

### Knowledge Graphs and Transportation Optimization 
- **Objective:** Build a Knowledge Graph (KG) to integrate public transportation data (urban, extra-urban, trains, buses) with educational facilities in Trentino, aiming to optimize students’ and professors’ commutes from regional and national locations.  

- **Achievements:** Collected and integrated heterogeneous datasets (GTFS, open data, PDFs, scraped sources); formalized the purpose with personas, competency questions, and ER models; designed and implemented a teleontology aligned with existing ontologies (GTFS, Schema.org, Datascientia LiveKnowledge); produced and evaluated a reusable KG enabling queries about optimal transportation routes for different user profiles.

### On Recommendation Systems in Logistics 
- **Objective:** Explore the application of recommendation systems within the logistics domain, focusing on optimizing drivers’ route choices through data mining and machine learning techniques.  

- **Achievements:** Designed and tested different approaches including collaborative filtering (user-user, item-item), content-based filtering, and hybrid systems. Leveraged Locality Sensitive Hashing (LSH) and clustering (K-means) to improve performance and scalability. The work demonstrated the feasibility of personalized and system-wide route recommendations, significantly outperforming baseline heuristics in both quality and efficiency.
