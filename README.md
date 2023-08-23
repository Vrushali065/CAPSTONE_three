NetflixMovies-TVShowsClustering
🔬 Unsupervised-Clustering-Analysis-on-Netflix-Movies-And-TV Shows.
--------------------------------------------------------------------------------------------

This repository contains the and dataset and the research notbook consisting various aproches for clustering movies and tv shows for netflix dataset. The movies and tv shows are present in the dataset which where released during the period of 1925 to 2021.
--------------------------------------------------------------------------------------------

📋 Abstract
This project aims to analyze the Netflix dataset of movies and TV shows till 2021 and group them into relevant clusters using natural language processing (NLP) techniques. The developed content-based recommendation system, based on cosine similarity matrix, is expected to improve the user experience and reduce subscriber churn for Netflix, which currently has over 220 million subscribers. The project includes handling null values, nested columns, binning the rating attribute, performing EDA, creating clusters using various attributes, reducing dimensionality, and developing a recommender system. The findings provide valuable insights into trends in the rapidly growing world of streaming entertainment and help improve the user experience for subscribers..

--------------------------------------------------------------------------------------------

💾 Project Files Description
This Project includes :-

Google Colab NoteBook
Project Summary (with the GitHub Repo link inside)
Presentation Video
Data Source:
https://drive.google.com/file/d/1xHLohgAITtf5639P9_G9m3vlkSoPNP3H/view?usp=sharing - Dataset taken from AlmaBetter
Output:
https://colab.research.google.com/drive/136HKAeyyEGUcAUppVNQ2kNnB7DC2Gn-N?usp=sharing - All the outputs are visible in the provided colab notebook.

🗺️ Dataset Description
The dataset contains 7,787 records and 11 features, including information about movies and TV shows from 1925 to 2021. The dataset includes two types of content: movies (71.1%) and TV shows (28.3%). The most frequent rating is TV-MA (Mature Audience only) followed by Teen and older. The highest number of content was added in 2019. The highest number of content is available in the months of October, December, and January.

--------------------------------------------------------------------------------------------

🔎 Key Findings
Most of the content is of the type of movie (71.1%).
The highest number of aquitted/created content was added in 2019.
The highest number of content is available in the months of October, December, and January.
The top genres where most of the movies and TV shows are listed are Dramas, International Movies, and Comedies.
The optimal number of clusters for the dataset is four.
The developed recommendation system is expected to improve the user experience and reduce subscriber churn for Netflix, which currently has over 220 million subscribers.
--------------------------------------------------------------------------------------------

🧵 Methodology
The project followed a step-by-step process that included handling null values, nested columns, binning the rating attribute, performing EDA, creating clusters using various attributes, reducing dimensionality, and developing a recommender system using the cosine similarity matrix. Clustering algorithms used include K-Means Clustering, Agglomerative Hierarchical Clustering, and DBSCAN.

--------------------------------------------------------------------------------------------

🛠️ Builds with
Python

NumPy

Pandas

Matplotlib

Seaborn

scikit-learn

SciPy

Plotly

GoogleColab

--------------------------------------------------------------------------------------------

📜 Conclusion
Our dataset contain 7787 rows and 12 columns.There was'nt any duplicates in dataset, and maximum number of null value was present in director column followed by cast.

Most of the content on Netflix is from Movies(~69%) and only 31% tv shows.

Raul Campos, jan suter was most famous director among all

Anupam Kher is most popular actor on Netflix.

Most of the content released on Netflix by the end of current year and starting of new year.

International Movies and Dramas are topmost Genres on Netflix.

Most of the content on Netflix is TV-MA(Mature Audience) rated.

United states has the highest number of content on the netflix ,followed by India.

Most of the movies have duration of 90mimutes.

In title column we got 'Love','Man','World','Story','Life' seems very common word.

We have implemented 5 clustering model to divide the dataset in clusters.

K-means clustering shows that '4' will be optimum no of clusters with the silhoutte score of 0.45. But we selected Optimum cluster number as 5 after Elbow curve cross validation.Thus K-means clustering will be best for this data set.

We have built cosine based recommender system using cosine_similarity, which was wroking nicely. --------------------------------------------------------------------------------------------

💶 Credits
Reach-out to me in following spaces.

Reach-out to me in following spaces.

GitHub

Email

Twitter

LinkedIn

--------------------------------------------------------------------------------------------

📚 References
Python documentation
Pandas documentation
Seaborn documentation
Scikit-Learn documentation
Towards data science
Analytics Vidya
StackoverFlow
wikipedia
Google data analytics professional.
--------------------------------------------------------------------------------------------
