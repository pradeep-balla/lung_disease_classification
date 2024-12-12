# lung_disease_classification
The project was focused on creating a lung disease classification system using chest X-ray images. The goal was to develop an automated solution capable of accurately diagnosing different lung conditions, including COVID-19, lung opacity, normal lungs, and pneumonia, through the application of deep learning techniques

Problem Statement: The challenge addressed in this project was the need for a fast and accurate method to classify lung diseases from chest X-rays. Traditional diagnostic methods are time-consuming and can be subject to human error, particularly in high-stress environments like hospitals. With the rise of COVID-19, the demand for an efficient, automated system to assist in the diagnosis of lung conditions became even more critical.

My Approach: To solve this problem, I started by assembling a dataset of chest X-ray images, with 1300 images for each of the four classes. The dataset was preprocessed and split into training, validation, and test sets to ensure robust model evaluation.

I trained several state-of-the-art deep learning models, including ResNet50, Xception, MobileNetV2, VGG16, VGG19, and InceptionV3, on the dataset. These models were fine-tuned to improve their performance on the specific task of lung disease classification.

To further enhance accuracy, I developed an ensemble model that combined the strengths of the ResNet50, Xception, and VGG16 models. I also explored different ensemble techniques like stacking, boosting, and voting to find the most effective approach. Hyperparameter tuning was performed using Grid Search, and data augmentation techniques were employed to increase the diversity and robustness of the training data.
![image](https://github.com/user-attachments/assets/1f802bbd-c644-4f5f-8a49-4078978b808a)
![image](https://github.com/user-attachments/assets/a257cac7-9d19-40f5-8569-a848f7c04129)
