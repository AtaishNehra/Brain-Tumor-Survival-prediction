# Brain-Tumor-Survival-prediction

This project focuses on predicting the survival time of brain tumor patients using deep learning techniques. By leveraging MRI imaging data and advanced neural network architectures, the goal is to provide accurate survival time estimations, aiding in clinical decision-making processes.​

Overview
The repository encompasses a complete pipeline:​

Data Preparation: Utilizes preprocessed MRI scans and associated survival data.

Modeling: Implements 3D V-Net architectures for tumor segmentation and survival prediction.

Evaluation: Includes both regression and classification approaches to assess model performance.​

Repository Structure
3d_vnet_results.ipynb: Presents the outcomes of the 3D V-Net model applied to the dataset.

surv_pred_classification.ipynb: Contains the classification model predicting survival categories.

surv_pred_regression.ipynb: Houses the regression model estimating exact survival times.

surv_pred_evaluate.ipynb: Evaluates the performance metrics of the classification model.

surv_pred_evaluate_regression.ipynb: Assesses the regression model's accuracy and error metrics.

survival_data.csv: Dataset comprising patient IDs, MRI scan references, and survival times.​

Prerequisites
Ensure the following libraries are installed:

Python 3.x

NumPy

Pandas

TensorFlow

Keras

scikit-learn

Matplotlib​
GitHub
+10
Jait
+10
Wiley Online Library
+10

Install dependencies using pip:

bash
Copy
Edit
pip install numpy pandas tensorflow keras scikit-learn matplotlib
Usage
Data Preparation:

Place the survival_data.csv file in the working directory.​

Model Training:

Run surv_pred_classification.ipynb to train the classification model.

Run surv_pred_regression.ipynb to train the regression model.​

Evaluation:

Use surv_pred_evaluate.ipynb to evaluate the classification model's performance.

Use surv_pred_evaluate_regression.ipynb to assess the regression model's accuracy.​

Results Visualization:

Refer to 3d_vnet_results.ipynb for visual representations of model predictions and performance metrics.​

Results
The models demonstrate promising capabilities in predicting patient survival times based on MRI data. Detailed performance metrics and visualizations are available in the respective evaluation notebooks.​
Nature

Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.​
GitHub

License
This project is licensed under the MIT License.
