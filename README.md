# Parkinson-s-disease-
Parkinson’s Disease Detection Using Machine Learning

## Project Overview
This project aims to develop a machine learning model to detect Parkinson's Disease based on a dataset of voice measurements. The dataset includes various attributes related to voice frequency, jitter, shimmer, and other vocal features, which are key indicators for diagnosing Parkinson's Disease. After loading and preprocessing the data, it is split into training and testing sets. Feature scaling is applied using standardization, and a Support Vector Machine (SVM) model is trained on the processed data. The model's performance is evaluated by calculating accuracy scores on the test set.

## Data Set Information:

This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds to one of 195 voice recordings from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to the "status" column which is set to 0 for healthy and 1 for PD.
<br>
<a href="https://github.com/SandaminiW/Parkinson-s-disease-/blob/main/parkinsons.csv">DataSet</a>

## Final Conclusion
The developed model successfully classifies Parkinson's Disease with a high accuracy rate, demonstrating the viability of using voice-based features for early detection. The SVM classifier, when applied to the dataset, achieves a reliable prediction performance, underscoring the importance of selecting key vocal biomarkers in diagnosing neurodegenerative diseases. Despite the promising results, the model's success is contingent on the quality and diversity of the dataset. Future work may explore enhancing the model by incorporating more advanced techniques, such as deep learning or ensemble models, and applying it to larger, more varied datasets. Additionally, real-time voice data collection could further improve the practical applications of the system in medical settings.
