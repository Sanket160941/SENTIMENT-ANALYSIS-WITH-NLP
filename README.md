# SENTIMENT-ANALYSIS-WITH-NLP

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SANKET MITHBAVKAR

*INTERN ID*: CTIS6838

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION ABOUT THIS TASK*:
In this task, we performed sentiment analysis on a dataset of customer reviews using Natural Language Processing techniques. The dataset consisted of textual reviews along with corresponding sentiment labels, which indicate whether a review expresses a positive or negative opinion. Initially, the dataset required cleaning because real-world text data often contains inconsistencies such as missing values, special characters, extra spaces, and formatting issues. We handled these challenges by removing null values, eliminating unwanted symbols, and standardizing the text by converting it to lowercase. This preprocessing step ensured that the data was clean, structured, and ready for further analysis.

After preparing the dataset, we moved to the core step of transforming textual data into numerical form. Since machine learning models cannot directly understand raw text, we used TF-IDF (Term Frequency–Inverse Document Frequency) vectorization. This technique converts each review into a numerical vector based on the importance of words. Words that appear frequently in a specific review but are not common across all reviews receive higher importance scores. This helps the model focus on meaningful words like “excellent,” “worst,” or “disappointed” rather than common words like “the” or “is.” By applying TF-IDF, we effectively captured the significance of each word in the context of sentiment.

Once the data was transformed into numerical features, we used Logistic Regression as our classification model. Logistic Regression is a simple yet powerful algorithm widely used for binary classification problems. In this task, it learned to distinguish between positive and negative sentiments by identifying patterns in the TF-IDF vectors. The model assigns weights to different words, allowing it to predict sentiment based on the presence and importance of those words. For example, words with positive connotations receive higher positive weights, while negative words receive lower or negative weights. This makes the model both efficient and interpretable. The entire implementation was carried out using a Jupyter Notebook within Visual Studio Code (VS Code). This environment allowed us to write, execute, and document code in an organized manner. Each step of the workflow, including data loading, preprocessing, vectorization, model training, and evaluation, was separated into individual cells for clarity and readability. This structured approach makes it easier to understand the process and also helps in debugging and future modifications.

In addition to the basic implementation, we performed several extra tasks to enhance the quality and depth of the project. We experimented with different TF-IDF configurations such as adjusting the maximum number of features. We also explored Logistic Regression with different regularization techniques and hyperparameters to improve model performance. Further analysis included identifying the most important words influencing predictions, visualizing them, and evaluating model confidence using probability scores. Additionally, we tested the model with custom input reviews to simulate real-world usage.

The final model was evaluated using metrics such as accuracy, classification report, and confusion matrix. These evaluation methods provided insights into how well the model performs in predicting sentiments and helped identify areas for improvement. By analyzing misclassified examples, we gained a better understanding of the limitations of the model and the complexity of human language.

This task has practical applications in many real-world scenarios. Sentiment analysis is widely used by companies to analyze customer feedback, improve products and services, and monitor brand reputation. It is also used in social media analysis, product reviews, and recommendation systems. Through this task, we gained hands-on experience in handling textual data, applying machine learning techniques, and building a complete sentiment analysis pipeline from scratch.

*OUTPUTS*:
<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/d2f602a0-6709-4303-a288-1c8e92246b75" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/e13c4d21-6124-4a61-9dd9-3acfc240d459" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/74c54b52-52ff-42fe-b733-1962e2f99e96" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/a678574f-e981-46b3-bb85-6424fbc8cc01" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/c6df081d-6b1c-4085-856b-cf486eca599b" />

<img width="2551" height="1103" alt="Image" src="https://github.com/user-attachments/assets/560f828f-a3d4-47b6-9ed9-18e1420d5ade" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/5bf71258-7672-472f-8c55-5c2936b4624b" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/de69eb4a-5f15-42f9-8dba-f114e2725587" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/4722c55c-ae59-4554-9f7a-5ca0f9def24d" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/3cc488c3-b05c-490d-a188-010663b42a7d" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/de52ec61-891d-4245-b6c5-f2dafa2d2926" />
