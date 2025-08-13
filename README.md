#  Top Spotify Songs by Country – Data Analysis & Machine Learning

##  Project Overview
This project explores **Spotify's top songs by country** to uncover:
- Regional music preferences
- Genre and artist popularity trends
- Predictive insights using Machine Learning

We combined **Exploratory Data Analysis (EDA)** with **multiple ML classification models** to build a system capable of predicting song popularity based on various features.


##  Dataset
The dataset contains:
- **spotify_track_uri**
- **ts**
- **platform**
- **ms_played**
- **track_name**
- **artist_name**
- **artist_name**
- **album_name**
- **reason_start**
- **reason_end**
- **shuffle**
- **skipped**



## Tech Stack
- **Python** – Data processing & analysis
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – Machine Learning
- **Plotly** – Interactive charts


##  Analysis Highlights
- **EDA** to identify global & regional trends
- Top 10 most played tracks
- Top 10 Most Played Artists
- Listening Activity Over Time
- Top Listening Platforms


##  Machine Learning Models Used
We tested multiple classification algorithms:
1. **Logistic Regression**
2. **Decision Tree**
3. **Random Forest**
4. **Naive Bayes**
5. **Support Vector Machine (SVM)**
6. **K-Nearest Neighbors (KNN)**



## Model Accuracy Comparison


| Model                  | Accuracy (%) |
|------------------------|--------------|
| Logistic Regression    | 94.78        |
| Decision Tree          | 93.46        |
| Random Forest          | 93.44        |
| Naive Bayes            | 94.78        |
| Support Vector Machine | 94.78        |
| K-Nearest Neighbors    | **94.97**    |

**Best Model:** `K-Nearest Neighbors (KNN)` with **94.97% accuracy**.
