# Diabetic Retionpathy - Capstone Project 

## Diabetic Retinopathy 

Diabetic retinopathy is a diabetes-related eye disease that affects the blood vessels in the retina. It is a leading cause of blindeness amoung individuals with diabetes. Over time, high blood sugar levels can damage blood vessels in the retina, leading to swelling, leakage, and the growth of abnormal new blood vessels. Diabetic retinopathy often progresses without noticeable symptoms, making early detection crucial for effective treatment. 

## Project Goal

The goal of this capstone project is to develop an image classification model that can accurately classify the presence of diabetic retinopathy based on retinal images. Early detection can facilitate timely medical intervention to prevent vision loss. Traditional methods of diabetic retinopathy diagnosis involve manual examination of retinal images by trained ophthalmologists. However, this process can be time-consuming and may be subject to inter-observer variability. Machine learning-based image analysis offers a more efficient and consistent approach to diabetic retinopathy screening. 

## Project Outline 

1. Data Exploration
* Exploring the dataset from: https://www.kaggle.com/c/diabetic-retinopathy-detection/overview.
* Understand the distribution of severity scores, and gain insights into the characteristics of retinal images.

2. Preprocessing
* Check for any inverted images and correct them to ensure consisten analysis.
* Standardize the sizes of all images to a common resolution for model compatibility.
* Ensure that each image has a corresponding severity score label for supervised learning.

3. Model Development
* Choose suitable image classification model architecture. (CNNs)
* Apply data augmentation techniques to enhance model generalization
* Train the model on the preprocessed dataset, using a portion for training and a separate portion for validation.
* Compare and evaluate other deep neural networks like ResNet50. 

4. Model evaluation
* Evaluate the model's performance using accuracy, precision, recall and F1 score.
* Analyze the confusion matrix to understand the model's strengths and weaknesses in different severity classifications.

5. Model Interpretation
* Use Class Activation Maps (CAM) to visualize which regions of the retinal images are important for the model's predictions.
* Explore methods for explaining the model's decisions to enhance interpretability.

6. Conclusion and Future
* Summarize the project findings, including the model's performance and comparison to other models previously created.
* Discuss potential enhancements or extentions to the project. 


## Project Progression and Next Steps

* Multi-class classification turned into binary classification due to small dataset and low computational resources
* Baseline CNN model created, need fine tuning and regularization to avoid over fitting on training. 
* Tune parameters for higher recall, especially in lower severity scores
* Explore ResNet50 and evaluate results
* Compare scores to other publications with regards to retinal image classification 
