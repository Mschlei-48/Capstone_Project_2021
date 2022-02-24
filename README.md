# Capstone_Project_2021

## **Authors**

1. Katlego KGOSI, Sol Plaatje University, South Africa
2. Mishi MAKADE, Sol Plaatje University, South Africa

## **Project Layout**

1. Description
2. Project Content and Results
3. Web Application


### **Description**

Accurate and fast diagnosis of brain tumor is crucial as it involves the selection of the most appropriate treatment method for saving a patient’s life . Previously implemented deep learning models on brain tumor classification like vgg16, Resnet etc are complex and slow . Performing real-time performance with these models requires dedicated hardware . This may result in delayed diagnosis, treatment and therefore may increase the chances of a patient’s death. The models are also difficult and impossible to deploy on mobile devices due to their complexity . This project addressed the problem of complexity by using pre-trained EfficientNetB7 model.
EfficientNetB7 is 8.4 times smaller than the best existing ConvNet. So, this study will implement the model in brain tumor classification along with vgg-16 then compare the results based on accuracy and complexity of the models. 

This project classifies brain tumor images as meningioma, pituitary,no_tumor and glioma tumor.  The best model was chosen with regards to one with the highest accuarcy and less complexity(how many training parameters the model has). The aim of the project was to find a deep learning model that improves the accuracy of brain tumor classification and has reduced complexity to allow the deployment of the model on mobile devices. The model that would give the best accuracy while being less complex would then be deployed on a web app.The training process included the fine tuning of hyperparameters. The hyperparameters that were fine-tuned are optimizers, epochs,batch size and dropout value.

### **Project Content and Results**

1. Data Collection

The data used for this project was obtained from Kaggle and is  publicly available. Navoneel Chakrabarty and Swati Kanchan along with the team members Sartaj Bhuvaji, Ankita Kadam, Prajakta Bhumkar and Sameer Dedge(2020) collected the dataset.

The dataset can be accessed from [Kaggle](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri).

#### **Sample of the dataset**


![Picture1](https://user-images.githubusercontent.com/83508295/155328394-b7416b1d-9fef-4357-a436-2656df964fa3.png)

The images were pre-processed with respect to each model's pre-processing requirements.

#### **Sample of the pre-processed images**

![Picture2](https://user-images.githubusercontent.com/83508295/155329044-5bfc6953-c48a-41bc-8c90-435729ed35eb.png)

2. Results

The models were both first fine-tuned with respect to the hyperparameters optimizers, epochs,batch size and dropout value. The optimum hyperparameters were then used for the main model training.

From the results, EfficientNetB7  gave the highest accuracy and was the less complex model in terms of trainable parameters.
EfficientNetB7 has a total of 66 million trainable parameters while VGG-16 has 138 million trainable parameters, which made EfficientNetB7 the best model to be deployed on the web app. 

#### **Table of Results**



 ![Picture3](https://user-images.githubusercontent.com/83508295/155330703-b207eae2-cf20-4bb2-84dd-3be370f24540.png)

 
 
 ### **Web App Demo**
 
 The EfficientNetB7 was deployed on the web app. Below is a demo of the app. A user can upload an MRI by dragging and dropping or by browsing the local files.
 
 
![Demo_WebApp](https://user-images.githubusercontent.com/83508295/155426072-6c23e532-7331-4eb4-960e-3d1e10917575.png)

### **References**


Tan,M & Le,Q. 2019. EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks. Proceedings of the 36 th International Conference on Machine Learning 7:1-11.

Badza,M & Barjaktarovi´,M.2020. Classification of Brain Tumors from MRI Images Using a Convolutional Neural Network.applied sciences 13:1-13.


Kang,J & Ullah,Z &Gwak,J.2021. MRI-Based Brain Tumor Classification Using Ensemble of Deep Features and Machine Learning Classifiers.applied sciences 13:1-21.

Irmak,E.2021. Multi-Classification of Brain Tumor MRI Images Using Deep Convolutional Neural Network with Fully Optimized Framework. Iranian Journal of Science and Technology, Transactions of Electrical Engineering 22:1-22.

Magadza,T.2021. Deep Learning for Brain Tumor Segmentation : A Survey of State-of-the-Art. Journal of Imaging 22:1-22











