# Capstone_Project_2021

## **Authors**

1. Katlego KGOSI, Sol Plaatje University, South Africa
2. Mishi MAKADE, Sol Plaatje University, South Africa

## **Project Layout**

1. Description
3. Project Content and Results
4. Acknowledgements

### **Description**

This project classifies brain tumor images as meningioma, pituitary,no_tumor and glioma tumor. Two deep learning models were used to classify the images and were compared in terms of accuracy and complexity, namely VGG-16 and EfficientNetB7. The best model was chosen with regards to one with the highest accuarcy and less complexity(how many training parameters the model has). The aim of the project was to find a deep learning model that improves the accuracy of brain tumor classification and has reduced complexity to allow the deployment of the model on mobile devices. The training process included the fine tuning of hyperparameters. The hyperparameters that were fine-tuned are optimizers, epochs,batch size and dropout value.

### **Project Content and Results**

1. Data Collection

The data used for this project was obtained from Kaggle and is  publicly available. Navoneel Chakrabarty and Swati Kanchan along with the team members Sartaj Bhuvaji, Ankita Kadam, Prajakta Bhumkar and Sameer Dedge(2020) collected the dataset.

The link for the dataset:https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri

#### **Sample of the dataset**


![Picture1](https://user-images.githubusercontent.com/83508295/155328394-b7416b1d-9fef-4357-a436-2656df964fa3.png)

The images were pre-processed with respect to each model's pre-processing requirements.

#### **Sample of the pre-processed images**

![Picture2](https://user-images.githubusercontent.com/83508295/155329044-5bfc6953-c48a-41bc-8c90-435729ed35eb.png)

2. Results

The models were both first fine-tuned with repsect to the hyperparameters mentioned above. The hyperparameters that gave the best accuracy were then used for the main model training.

From the results, EfficientNetB7  gave the highest accuracy and was the less complex model in terms of trainable parameters.
EfficientNetB7 has a total of 66 million trainable parameters while VGG-16 has 138 million trainable parameters, and EfficientNetB7 gave the highest accuracy. 

### **Results**



 ![Picture3](https://user-images.githubusercontent.com/83508295/155330703-b207eae2-cf20-4bb2-84dd-3be370f24540.png)
 
 
 3. Conclusions
 
 From the results it was concluded that EfficientNetB7 was the best model compared to VGG-16. It gave the highest accuracy and was also the less complex model.







