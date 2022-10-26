# Food-Dishes-Image-Classification-with-Transfer-Learning
In a multi-class classification framework, a Convolution Neural Network (CNN) model based on food image classification is designed to predict the name of the food.
For this, the TensorFlow dataset's food 101 dataset is utilised.
As a feature extraction model, the EfficientNetB0 model from the TensorFlow hub is utilised, which was pre-trained on the ImageNet Dataset.
To increase accuracy, some of the top layers of the efficientnetb0 base model are unfrozen as part of the model's fine-tuning process.
The GPU is utilised to speed up computing by employing a mixed precision and prefetch method.
TensorBoard is used to assess the model training logs, and confusion matrices are created for the evaluation of the predictions.
