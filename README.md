# Fintech Lending Analysis Project

Welcome to the Fintech Lending Analysis Project! This project focuses on conducting an in-depth analysis of user reviews from popular fintech lending apps. By processing structured data for simple visualization and applying sentiment analysis to unstructured data, I aim to provide actionable insights for the fintech lending industry.

## Objectives and Benefits:

**Objective**: The main objective of this research is to analyze user sentiments towards Indonesia's popular fintech lending applications and provide valuable insights for the industry.

**Benefits**:

- **Application Performance Evaluation**:
   Provides an assessment of the performance and services offered by fintech lending applications for the companies involved. Analyzing user sentiment can offer valuable insights regarding positive, neutral, or potential concerns that can be addressed by the company.

- **Reference for the Community**:
   Offers information based on research on fintech lending applications, assisting the community in selecting applications that align with their needs and preferences.

- **Source of Reference for Further Research**:
   Provides studies and references that can serve as a foundation for further research in the field of user sentiment analysis toward fintech lending applications.

## Libraries Used:

- pandas
- numpy
- matplotlib
- scikit-learn
- regex
- nltk
- sastrawi
- swifter
- seaborn
- wordcloud
- PIL
- pickle
- googletrans
- google-play-scraper

## Methodology: SEMMA

In this project, I follow the SEMMA methodology, which stands for Simple, Explore, Modify, Model, and Assess. Here's a brief overview of each step:

- **Sample**: Data is collected by extracting user comments from Google Play Store related to popular fintech lending applications. A random sample is taken, adjusting for a margin of error (+/- 4%) and a confidence level of 99%. The labeling process includes categorizing comments into positive, negative, and neutral sentiments based on the criteria below:
   - Positive Sentiment: Praise, gratitude, enthusiasm, and recommendations to others.
   - Negative Sentiment: Complaints, criticisms, sarcasm, and threats.
   - Neutral Sentiment: General inquiries, and comments with minimal emotional content.

- **Explore**: Information about the data is gathered, including attributes, data quantity, presence of missing values, and data types. Basic visualizations, such as bar charts, are utilized to analyze sentiment label distribution.

- **Modify**: The datasets from three different fintech lending apps are integrated, unnecessary attributes are removed, and data is pre-processed. This involves tasks like case folding, cleaning noise, tokenizing, normalizing, filtering stopwords, stemming, and applying TF-IDF (Term Frequency-Inverse Document Frequency) for numerical representation of words.

- **Model**: Classification models are created using Support Vector Machine (SVM) with various settings. Grid search CV is employed to find the optimal kernel and parameters. The models are evaluated based on performance metrics.

- **Assess**: Model performance is assessed using confusion matrix. The best-performing models are saved in pickle format for future use.

## Findings:

- Dominant sentiment across all three popular fintech lending apps (September 2022) is positive.

- SVM Performance:
  - **AdaKami**: (Accuracy: 94%, Precision: 93%, Recall: 98%, F1-Score: 96%)
  - **EasyCash**: (Accuracy: 89%, Precision: 95%, Recall: 87%, F1-Score: 96%)
  - **Kredit Pintar**: (Accuracy: 85%, Precision: 89%, Recall: 94%, F1-Score: 96%)

- Word Cloud Findings:
  - **Positive**: Commonly mentioned topics include praise, gratitude, and satisfaction expressed by users towards the fintech lending apps.
  - **Negative**: Users often discuss issues related to loan rejection and payment problems.
  - **Neutral**: Comments in this category may focus on process approval, app rating, and other less emotionally charged topics.

## Challenges:

One of the primary challenges faced during this project was the extensive data extraction from Google Play Store. This process required a stable and uninterrupted internet connection, often spanning over several hours. Additionally, the manual labeling process demanded meticulous attention to detail to ensure accuracy in sentiment analysis.

## How to Use:

To explore this project, download the zip file and run the Fintech_Lending_Analysist.ipynb notebook. The project includes datasets, models, and assets for analysis.

## Note:

To obtain results consistent with the presented findings, avoid running the program from the sampling stage. Sampling random data will alter the dataset, affecting the analysis. The provided labeled sample data is sufficient for exploring the project.

**Disclaimer**: This project involves extensive data extraction from Google Play Store, which may require stable and uninterrupted internet connectivity. The labeling process was conducted meticulously to ensure accuracy.

## Acknowledgements

I would like to express my sincere gratitude to Mr. Apriade Voutama, M.Kom., and Ms. Nina Sulistiyowati, S.T., M.T., for their invaluable guidance and support throughout the duration of this research project. Their expertise and insights greatly contributed to the success of this analysis.



If you have any suggestions or feedback for this project, kindly fill out this [feedback form](https://forms.gle/AnBTciPWuZV9YhYK8) and feel free to contribute!

Thank you for exploring this Fintech Lending Analysis Project :)
