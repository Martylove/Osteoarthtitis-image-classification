# Osteoarthritis Image Classification

This project aims to classify X-ray images of knee joints as either normal or having osteoarthritis. Osteoarthritis is a degenerative joint disease that affects millions of people worldwide. The dataset used in this project is the [Osteoarthritis Initiative (OAI)](https://nda.nih.gov/oai/) dataset, which contains knee X-ray images of participants with and without osteoarthritis. The dataset contains images of both knees of each participant, taken either at the baseline or follow-up visit. The dataset has a total of 4 visits with a 4-year interval between each visit, providing a rich source of data for analysis and training of the model.

The dataset consist of three folders of images: 

1.Test

2.Train

3.Validation

and there are two sub-class folders as Normal and Osteoarthritis 

The model used for this project is a convolutional neural network (CNN) with 4 convolutional layers and 2 fully connected layers. CNNs have been used extensively for image classification tasks and have shown great promise in the medical field. The model was trained on a subset of the OAI dataset and achieved 92% accuracy on the test set, demonstrating its effectiveness in classifying knee X-ray images.

To use this project, first download the OAI dataset from the /Kaggle.com. Then, preprocess the data and train the model using the `train.py` script. The model can be fine-tuned by adjusting hyperparameters or adding more layers to the network. Finally, use the `predict.py` script to classify new X-ray images.

In conclusion, this project demonstrates the use of a CNN for classifying X-ray images of knee joints as either normal or having osteoarthritis. With further development, this model could potentially aid in the diagnosis of osteoarthritis and improve patient outcomes. Future work could involve expanding the dataset to include more diverse populations and exploring the use of other deep learning techniques such as transfer learning.
