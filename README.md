# Student-Performence-Prediction
This project aims to develop a model that predicts the weak topics of students based on their performance in various subjects. The model utilizes machine learning algorithms, such as Random Forest Classifier (RFC), Decision Tree Classifier (DTree), and K-Nearest Neighbors (KNN), to analyze student data and provide insights on the topics that require more focus and improvement.

The project follows the following steps:

Data Generation: Simulated data is created to mimic student performance on different topics within a subject. The data includes information such as the number of correct answers and total questions attempted for each topic.

Data Preprocessing: The data is processed to ensure consistency and compatibility with the machine learning algorithms. The necessary features are extracted, including the performance on each topic and the weak topic labels.

Model Training: The generated data is split into training and testing sets. The RFC, DTree, and KNN models are trained using the training set, allowing them to learn the patterns and relationships between the input features (performance on each topic) and the weak topic labels.

Model Evaluation: The trained models are evaluated using various evaluation metrics, including accuracy, precision, recall, and F1-score. These metrics provide insights into the performance of each model in predicting weak topics.

Prediction and Recommendation: The trained RFC model is utilized to predict weak topics for new students or data. The model takes the performance on each topic as input and outputs the predicted weak topic labels. Based on these predictions, students can be advised to focus on the identified weak topics to improve their performance.

The project utilizes Python and popular libraries such as pandas, scikit-learn, and seaborn for data manipulation, model training, evaluation, and visualization. The code is structured and well-documented, making it easy to understand and replicate the workflow.

I used FAKE DATA!
