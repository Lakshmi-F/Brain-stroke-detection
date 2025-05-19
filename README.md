# Brain-stroke-detection

This project consists of an advanced stroke detection system using brain CT images, powered by a combination of a pre-trained CNN, Genetic Algorithm and a BiLSTM (Bidirectional Long Short-Term Memory) network. The model first extracts relevant features using InceptionV3 CNN model, selects the most important and relevant image features using a Genetic Algorithm, and trains the BiLSTM model based on these features for prediction. We have also added a Gradio interface where the user can upload a CT image and obtain prediction.

This project is inspired from an IEEE published journal paper- M. A. Saleem et al., "Innovations in Stroke Identification: A Machine Learning-Based Diagnostic Model Using Neuroimages," in IEEE Access, vol. 12, pp. 35754-35764, 2024, doi: 10.1109/ACCESS.2024.3369673.

The dataset used is obtained from Kaggle- https://www.kaggle.com/datasets/afridirahman/brain-stroke-ct-image-dataset
