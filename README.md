Ground Truth Report App - Readme Documentation

Introduction:
Welcome to the Ground Truth Report App! This Android application allows users to capture pictures of plastic waste using their device's camera and then employs a backend Machine Learning (ML) model based on the Inceptionv3 architecture to identify the presence of plastic waste in the image. Additionally, the ML model provides a confidence score for the prediction. Users can also provide feedback and rate the app, which will be sent to a designated email address.

Table of Contents:
1. Features
2. Installation
3. Usage
4. Backend ML Model
5. Dataset
6. Feedback and Ratings
7. Contributing
8. License

Features:
1. Camera Integration: The app integrates with the device's camera, allowing users to take pictures directly from the application.
2. Plastic Waste Identification: Utilizing the backend ML API based on the Inceptionv3 model, the app can predict whether the image contains plastic waste and provides a confidence score for the prediction.
3. Feedback and Ratings: Users can provide feedback about the app and rate it on a scale of 1 to 5 stars. The feedback will be sent to a designated email address for further evaluation.
4. User-friendly Interface: The app is designed with a user-friendly interface, making it easy for users to navigate and utilize its features.

Installation:
To run the Ground Truth Report App, follow these steps:
1. Clone the GitHub repository to your local machine using the following command:
git clone https://github.com/Harshsharma2602/Accenture_Ground_Truth_Application.git
2. Open the project in Android Studio by selecting the root directory of the cloned repository.
3. Connect your Android device to your computer or set up an Android Virtual Device (AVD) using Android Studio.
4. Build and run the app on your Android device or AVD.

Usage:
1. Capture an Image: Open the app and click on the camera button to take a picture of the object you want to identify.
2. Confirm Selection: After capturing the image, confirm the selection to proceed with the plastic waste identification.
3. Prediction and Confidence Score: The app will use the backend ML API to make predictions on the image. It will then display whether the image contains plastic waste and the confidence score for the prediction.
4. Feedback and Ratings: To provide feedback and rate the app, click on the feedback button and find the option for feedback and ratings.

Backend ML Model:
The backend ML model used in the app is based on the Inceptionv3 architecture. Inceptionv3 is a deep convolutional neural network (CNN) that is widely used for image classification tasks. The model was trained using a custom dataset of plastic waste images. The ML API is hosted on a remote server and is accessed by the app to make predictions on captured images.

Dataset:
The dataset used for training the backend ML model is sourced from "https://universe.roboflow.com/hamdi-ali/plastic-pollution-ugslg". The images in the dataset were not annotated initially. To create annotated data, a CSV file was provided along with the images. The images were annotated using a custom script. The annotated dataset was then used for training the ML model.

Feedback and Ratings:
We value user feedback and would love to hear your thoughts on the app. If you encounter any issues or have suggestions for improvement, please provide your feedback and rate the app on a scale of 1 to 5 stars. Your feedback will help us enhance the app and make it even better!
To submit your feedback, click on the feedback button in the app and find the feedback and ratings option. Enter your comments and select the star rating before submitting. Your feedback will be sent to our team for review.

Contributing:
We welcome contributions to improve the Ground Truth Report App. If you'd like to contribute, follow these steps:
1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Make your changes in the new branch.
4. Test your changes thoroughly.
5. Commit your changes and push them to your fork.
6. Create a pull request to merge your changes into the main repository.
7. We will review your contribution and, if it meets the project's guidelines, merge it into the main branch.

License:
This project is licensed to be used solely by Accenture. 

-----
Thank you for your interest in the Ground Truth Report App! If you have any questions or need further assistance, please feel free to reach out to us or open an issue in the GitHub repository. Happy classifying and contributing!
