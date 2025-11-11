## 📂 Project Resources

All large project files — including datasets and the demo video — are hosted on Google Drive for easy access due to GitHub size limitations.

**Access the Complete Folder Here:**  
➡️ [Click to Open Google Drive Folder](https://drive.google.com/drive/folders/1_YbkaMPxjC8b6VBrw6UPNfthtd5AXW0_?usp=drive_link)

### 📊 Contents of the Folder
| File Name | Description |
|------------|-------------|
| **TMDB_5000_movies.csv** | Dataset containing metadata for 5000+ movies including budget, revenue, popularity, and votes |
| **IMDB_Dataset.csv** | Dataset containing 50,000 audience reviews labeled as positive/negative for sentiment analysis |
| **Project_Demo_Video.mp4** | 10-minute project demo explaining problem statement, methodology, implementation, and results |

> *Note:* Datasets and video are hosted externally because they exceed GitHub’s upload size limit.  
>

## ***🎬 Big Data Capstone Project – Media & Entertainment Industry***

**Platform:** Databricks (PySpark, MLlib, SQL, Visualization)
**Objective:** Analyze, predict, and optimize various aspects of movie performance and audience behavior using Big Data analytics.

***Project Overview***

This Big Data project explores how analytics and machine learning can transform the media and entertainment industry.
By leveraging the TMDB 5000 Movies Dataset and IMDB Reviews, we implemented five real-world use cases — from predicting box-office success to optimizing recommendation systems.

The workflow integrates Databricks, PySpark, Spark SQL, and MLlib to perform scalable data processing, model training, and visualization.

***Use Cases Summary***
| No.   | Use Case Title                                   | Goal                                                                               | Technique / Model                 | Key Result                                                                             |
| ----- | ------------------------------------------------ | ---------------------------------------------------------------------------------- | --------------------------------- | -------------------------------------------------------------------------------------- |
| **1** | **Box Office / Streaming Success Prediction** | Predict whether a movie will be successful based on budget, votes, and popularity. | Logistic Regression (Spark MLlib) | Accuracy **74%**, AUC **0.85**. *Vote count* & *popularity* were strongest predictors. |
| **2** |  **Audience Sentiment Analysis**               | Classify IMDB reviews as positive or negative using text analytics.                | TF-IDF + Logistic Regression      | Accuracy **88%**, AUC **0.95**. Positive terms: “great”, “story”, “film”.              |
| **3** | **Trend Forecasting**                         | Analyze and forecast how movie popularity changes over time.                       | Polynomial Regression             | R² **0.67**. Popularity rising steadily post-2010 due to streaming.                    |
| **4** | **Viewer Engagement Prediction**              | Predict audience engagement using votes, ratings, and budget data.                 | Decision Tree Classifier          | Accuracy **95.2%**. *Vote count (0.987)* dominates engagement prediction.              |
| **5** |  **Content Recommendation Optimization**       | Cluster similar movies to power personalized recommendations.                      | K-Means Clustering (Unsupervised) | Movies grouped into 4 clusters — blockbusters, average, niche, acclaimed.              |

***Overall Insights***

1. Popularity and audience votes are the most influential features for predicting engagement.
2. Sentiment polarity correlates strongly with movie ratings.
3. Popularity trends show rapid growth in the streaming era.
4. Unsupervised clustering helps segment content for targeted recommendation.
5. The Big Data pipeline (PySpark + SQL + MLlib) enables large-scale, efficient computation and modeling.

***Tech Stack***
| Category            | Tools / Libraries                                |
| ------------------- | ------------------------------------------------ |
| Data Platform       | Databricks                                       |
| Big Data Processing | PySpark, Spark SQL                               |
| Machine Learning    | Spark MLlib (Regression, Decision Tree, K-Means) |
| Visualization       | Matplotlib, Databricks Display, SQL Dashboards   |
| Data Sources        | TMDB 5000 Movies, IMDB Reviews (Kaggle)          |

***Key Visuals***

Feature Influence on Movie Success

Top 20 Important Words in Reviews (TF-IDF)

Popularity Trend (1970–2030)

Decision Tree Feature Importance

K-Means Movie Clusters by Popularity & Rating

***Final Outcome***

This project demonstrates how Big Data and Machine Learning can be integrated to analyze entertainment data at scale.
Each use case provides valuable insights — from predicting success to automating recommendations.
📄 Author & Credits

Project Author:Yashika

Course: Big Data Analytics – Capstone Project

Instructor: Ms. Sree Laxmi

Dataset Sources: Kaggle (TMDB 5000 Movies, IMDB Reviews)
