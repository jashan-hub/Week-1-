# The wildfire Detection Project Week-1
The Wildfire Detection project aims to build an AI-based image classification system that automatically detects the presence of wildfire in images. Using deep learning and computer vision techniques, the model learns to distinguish between “fire” and “no fire” scenes from a dataset of real-world wildfire and non-fire images.

🎯 Objective:
To develop a simple yet effective wildfire detection model capable of classifying images as fire or no fire, demonstrating the potential of AI for environmental monitoring and early warning systems

## 🌱 Week 1: Understanding, Planning & Designing the Solution

The first week laid the foundation for the entire project. I began by exploring the *Easy Wildfire Detection* notebook on Kaggle to understand its purpose — building a deep learning model capable of distinguishing between **fire** and **no-fire** images.

I started with **requirement gathering**, identifying the project goal: *to create a reliable AI model for wildfire image detection that can assist in early environmental hazard monitoring.*

Next, I moved on to **dataset exploration**. I examined the wildfire image dataset, analyzed the class distribution, and visualized random samples to get a feel for the data. This step helped me understand challenges like **class imbalance**, **image variation**, and **lighting differences**, which could affect model accuracy.

Finally, I focused on the **design phase**. I mapped out the end-to-end pipeline — from preprocessing and model architecture to evaluation metrics. The plan was to implement a **Convolutional Neural Network (CNN)**, use image augmentation to improve generalization, and evaluate the model using accuracy, precision, recall, and confusion matrix.

By the end of Week 1, I had a **clear project roadmap** and a well-defined vision for implementation.


## ⚙️**Week 2: Building, Training & Testing the Model**

Week 2 was all about turning the design into a working prototype. I implemented the **data pipeline**, ensuring smooth loading, resizing, normalization, and augmentation of images. Consistent preprocessing was crucial to achieving stable model training.

Next came the **model building phase**. I constructed and trained a CNN using **TensorFlow/Keras**, experimenting with parameters like learning rate, batch size, and number of epochs. Throughout training, I closely monitored **loss and accuracy curves** to identify signs of overfitting and applied regularization techniques such as **dropout** and **early stopping**.

After several iterations, the model began to show promising results. I then evaluated it on the test set, generating a **confusion matrix** and performance metrics. The model achieved strong accuracy in identifying wildfire images while maintaining low false negatives — an essential goal for real-world application.

Finally, I documented the results, reviewed the code for clarity, and ensured reproducibility for future improvements.

By the end of Week 2, the wildfire detection model was not just running — it was **learning**, **predicting**.
