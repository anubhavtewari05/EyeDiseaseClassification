
# Eye Disease Classification Using EfficientNetB3

The EfficientNetB3 model classifies the input image into one of the four classes given in the dataset to identify whether the eye has been infected with a disease or not. The model does this with an accuracy of 88.94%.


## Dataset
The dataset consists of Normal, Diabetic Retinopathy, Cataract and Glaucoma retinal images where each class have approximately 1000 images. These images are collected from various sources like IDRiD, Oculur recognition, HRF etc.

Data Augmentation has been performed on each image in the dataset. This is how the images look after the data Augmentation process.

<img width="359" alt="image" src="https://github.com/anubhavtewari05/EyeDiseaseClassification/assets/58473176/f0f24068-e163-4bae-af49-cb8a1b57660c">


## Model
EfficientNetB3 is a convolutional neural network architecture that belongs to the EfficientNet family, introduced by Google Brain. It represents a balanced trade-off between accuracy and computational efficiency. EfficientNetB3 is designed to achieve state-of-the-art performance on image classification tasks while being computationally efficient, making it suitable for deployment on resource-constrained devices or for large-scale deployment in production environments.EfficientNetB3 is pre-trained on the ImageNet dataset.

<img width="288" alt="image" src="https://github.com/anubhavtewari05/EyeDiseaseClassification/assets/58473176/03b5fcd9-a0da-4baa-b636-dc0170c7432f">

EfficientNetB3 has been integrated with two additional dense layers to make the prediction between 4 classes right. Second last layer has the "relu" activation function and the last layer has the softmax activation function to predict class probabilities and finally predict the correct class finally.


## Output
<img width="320" alt="image" src="https://github.com/anubhavtewari05/EyeDiseaseClassification/assets/58473176/af0efa75-9b4c-46fc-9b41-7c8b299807b9">

The above two images have been classified correctly as normal and diabetic_retinopathy accurately respectively.
