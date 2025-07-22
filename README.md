<h2>Customer Churn Prediction with MLP </h2>

<p>This project focuses on predicting customer churn using a deep learning model built with TensorFlow/Keras.</p>

<h3>Techniques Used:</h3>
<ul>
    <li><strong>Data Loading and Exploration:</strong> Loading the dataset using Kagglehub and exploring its structure, missing values, and target variable distribution.</li>
    <li><strong>Data Cleaning:</strong> Handling missing values and dropping irrelevant columns ('customerID').</li>
    <li><strong>Feature Engineering:</strong> Converting categorical features into numerical representations using one-hot encoding.</li>
    <li><strong>Data Balancing:</strong> Addressing class imbalance by undersampling the majority class.</li>
    <li><strong>Data Splitting:</strong> Dividing the data into training and testing sets for model development and evaluation.</li>
    <li><strong>Feature Scaling:</strong> Standardizing numerical features using <code>StandardScaler</code> to improve model performance.</li>
    <li><strong>Deep Learning Model:</strong> Building a sequential neural network with Dense layers, Dropout, and L2 regularization using TensorFlow/Keras.</li>
    <li><strong>Model Compilation:</strong> Configuring the model with an Adam optimizer, binary cross-entropy loss, and accuracy metric.</li>
    <li><strong>Early Stopping:</strong> Using an EarlyStopping callback to prevent overfitting during training.</li>
    <li><strong>Hyperparameter Tuning:</strong> Employing Keras Tuner (RandomSearch) to find optimal hyperparameters for the model architecture and regularization.</li>
    <li><strong>Model Evaluation:</strong> Assessing the model's performance using accuracy and a classification report on the test set.</li>
    <li><strong>Learning Curve Visualization:</strong> Plotting training and validation loss and accuracy to understand the model's learning process.</li>
</ul>

<h3>Report</h3>
<ol>
    <li>         precision    recall  f1-score   support

           0        0.78      0.76      0.77       425
           1        0.74      0.76      0.75       382

    accuracy                            0.76       807
    macro avg       0.76      0.76      0.76       807
    weighted avg    0.76      0.76      0.76       807
</li>
   
</ol>
