# Tiktok Classification Project

**Background**

TikTok users have the ability to report videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. This process generates a large number of user reports that are difficult to address quickly. TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently. 

**Business Goal**

The purpose of the project is to create a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.

**Tools**

  1. Python
  2. Scipy
  3. scikit-learn
  4. statsmodel
  5. Tableau

**Project Deliverables**

  1. Prep work for next stage of EDA
  2. Complete Exploratory Data Analysis and Visualizations
  3. Statistical Analysis
  4. Regression Model
  5. Machine Learning Model
    
    
**Understanding the data**

The data used in this project was provided by the TikTok team for the Google Advanced Data Analytics Professional Certificate Course. A copy of the dataset can be found along with the other files in this repository. It contains 19382 rows and 12 columns with each video representing each row and various features such as numerous user engagement metrics (views, likes, comments, etc) or transcription texts representing each video. There were 298 rows that contained missing values in the dataset and these affected rows were dropped as they only constituted a minor fraction of the data available. There were no duplicated rows and the class balance of videos containing claims or opinions was approximately 51% to 49% so neither up nor down-sampling was required to balance the dataset. 

**Conclusion**

After numerous prepocessing steps were implemented on the data, a Random Forest model and XGBoost model was used to classify the dataset using the most predictive features associated with each video. Statistical and regression analysis was also performed in earlier stages of the project, which can be viewed in the respective files. To evaluate the models, a confusion matrix as well as classification report was created to get a more accurate visual of each models' performance. The results show that both models performed extremely well at accurate classifying whether a video contains a claim or opinion.

<img width="581" alt="Screen Shot 2024-04-05 at 1 09 44 PM" src="https://github.com/Natsu1579/Tiktok-Classification-Claims-Project/assets/150382759/4b8fcb84-1b6a-4ad1-a52d-dc53e48e39e4">

<img width="588" alt="Screen Shot 2024-04-05 at 1 08 57 PM" src="https://github.com/Natsu1579/Tiktok-Classification-Claims-Project/assets/150382759/5cd41727-8bf9-4f9b-964b-b3bc24a82d12">


