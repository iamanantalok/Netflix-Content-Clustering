# Netflix Movies and TV Shows Clustering

![image](https://github.com/iamanantalok/Netflix-Content-Clustering/assets/117917485/1a9b964e-0f99-4c66-835f-482426765e29)


## Introduction
With over 83 million subscribers in more than 190 countries, Netflix is the world's leading Internet television network. Users consume over 125 million hours of content daily, spanning original series, documentaries, and feature films. Netflix offers the freedom to watch on any internet-connected screen, providing a seamless viewing experience without interruptions.

### Problem Statement
As the largest online streaming service provider with over 220 million subscribers, Netflix needs to effectively cluster its hosted shows to enhance user experience and prevent subscriber churn. By creating clusters of similar shows, Netflix can offer personalized recommendations to keep viewers engaged.

### Project Summary
This project utilizes a dataset containing Netflix TV shows and movies available as of 2019, sourced from Flixable, a third-party Netflix search engine. We aim to classify these shows into clusters, ensuring that shows within a cluster are similar while those in different clusters are dissimilar.

## Input Files
- **NETFLIX MOVIES AND TV SHOW CLUSTERING.csv**

## Variables Description
- **show_id**: Unique identifier for each movie/show.
- **type**: Indicates if the entry is a movie or TV show.
- **title**: Name of the movie or TV show.
- **director**: Name of the director(s).
- **cast**: Names of actors and actresses.
- **country**: Country or countries of production.
- **date_added**: Date when added to Netflix.
- **release_year**: Year of release.
- **rating**: TV or movie rating.
- **duration**: Length in minutes or seasons.
- **listed_in**: Categories or genres.
- **description**: Brief synopsis.

## Project Structure
1. **README.md**: This document.
2. **Dataset**: Contains the dataset file.
3. **EDA**: Directory for exploratory data analysis.
   - **Numeric & Categoric Features**: Exploration of data through univariate, bivariate, and multivariate analysis.
4. **Data Cleaning**: Cleaning and preprocessing data.
   - **Duplicated values**
   - **NaN/Missing values**
   - **Treating Skewness**
   - **Treating Outliers**
5. **Textual Data Preprocessing**: Preprocessing of text data for clustering.
   - **Clustering Attributes**
   - **Removing Stopwords**
   - **Lowercasing words**
   - **Removing Punctuation**
   - **Stemming**
   - **Snowball Stemmer**
   - **Word Vectorization**
   - **TF-IDF (Term Frequency - Inverse Document Frequency)**
6. **Dimensionality Reduction**: Applying PCA (Principle Component Analysis) for dimensionality reduction.
7. **Model Building**: Implementing clustering models.
   - **K-Means Clustering**
   - **Elbow Method**
   - **Silhouette Score Analysis**
   - **Agglomerative Hierarchical Clustering**
     - **Dendrogram**
8. **Content-Based Recommendation System**: Building a recommendation system based on content similarity.
9. **Future Work**: Suggestions for further project enhancements.
10. **Conclusion**: Summary of insights from exploratory data analysis and machine learning models.

## Conclusions
The EDA uncovered valuable insights into Netflix's content distribution, production trends, viewer preferences, and global impact. Key takeaways include content diversity, production growth, global influences, regional success stories, viewer engagement, and a focus on quality and collaboration.

The machine learning models successfully clustered Netflix shows, with K-Means suggesting four clusters and Agglomerative Hierarchical Clustering indicating two clusters. Silhouette Score was used as the evaluation metric for its interpretability.

Additionally, a content-based recommendation system was implemented to improve user experience and reduce churn by providing personalized recommendations to users based on similarity scores.

In summary, this project highlights Netflix's commitment to offering diverse, high-quality content to a global audience, positioning it as a leader in the streaming industry. Further work can explore additional features, enhance the recommendation system, and analyze user feedback for continuous improvement.
