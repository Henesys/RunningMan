# Running Man
Analysis, science and visualization of data collected from the South Korean variety show "Running Man" (런닝맨).

## Goals & Overview
- The initial goal of this project is to create a dataset that encompasses a wide variety of Running Man's facets as a show.
- Upon the creation of the dataset itself, I want to use the data at hand to ask questions such as whether the theme of the episode affected the ratings and the impact that guests have on the show, among others.
- In addition to creating the dataset itself, I intend to use it for additional projects intended to serve as portfolio material to showcase my data analysis, science and visualization skills.
- Depending on how I choose to create the dataset, SQL may or may not be used to combine tables and query the dataset as a simple form of EDA.

## Project Ideas
1. Predictive Model for TV Ratings
    - Use machine learning algorithms (e.g. XGBoost) to predict episode ratings.
    - Conducting feature engineering on the dataset to create additional meaningful variables.
    - Showcase use of Python (scikit-learn) by performing cross validation operations and hyperparametrization (tuning) to further optimize model performance.

2. Time Series Analysis of Viewer Engagement
    - Using ARIMA to forecast viewer ratings (Seoul, domestic & foreign) and gauge viewer engagement.
    - Observe the creation of Running Man's YouTube channel for additional reference/ research areas.
    - Potentially compare models created in project #1 and observe differences in performance.

3. Network Analysis of Guests
    - Observe frequency and impact of guest appearances.
    - Model relationships between guests and the main cast to create a graph database using Python (NetworkX).
    - Potentially implement centrality measures to identify important and influencial guests.

4. Episode Theme Clustering & Analysis
    - Depending on how the dataset is structured, use the themes of the episodes and cluster them.
    - Conduct dimensionality reduction on the themes for visualization.

5. Rating Fluctuation Detection
    - Identify abnormal fluctuations in ratings.
    - Given that Running Man has been running for almost 15 years, it has gone through numerous changes and events such as time slot changes, COVID, delayed for Olympics broadcasting etc.
    - If a fluctuation is detected, attempt to find a cause.
    - Use of isolation forests or autoencoders for these detections?
    - Study and demonstrate the use of Python (PyOD) for detection techniques as a segue into future anomaly detection related projects on Kaggle etc.

6. Recommendation Systems
    - Some episodes are bound to similar to others as popular themes are often brought back due to popular demand.
    - A collaborative filtering system designed to recommend viewers who viewed a certain episode and redirect them to another episode.
    - Toss-up between Python (Surprise) and R (recommenderlab @ CRAN).

7. A/B Testing
    - Pinpointing partial segments of the show to determine their effects on the ratings (if at all).
    - Difference-in-differences (DiD) analysis & propensity score matching implementation.
    - Python (CausalInference) could be used, I also want to try out R (MatchIt).

8. Dashboards
    - Direct interaction of the dataset to allow users to manipulate Running Man statistics themselves.
    - Could use Python (Dash) in conjunction with Heroku as a cloud platform to host the dashboard.
    - A map of South Korea to show filming locations with additional filters for time (year of film broadcast date).
    - Ideally, I want to create the *same* dashboard across multiple platforms (Dash, Shiny, Tableau, PowerBI) to demonstrate mastery.
    - Individual profiles for each cast member could also be made into visualizations as well.

9. Multi-armed Bandit (MAB) for Showrunner Simulation
    - A common criticism of the most recent iteration of episodes I've seen by the current showrunner (a.k.a. PD in Korea) is that the games are boring or structured poorly. 
    - I want to see if there is a way to create an "ideal" episode that satisfies viewers by simulating "optimal" games/ segments within each episode. 