# Inclusive Sign Language Translator

This project aims to develop an accessible, real-time system for translating American Sign Language (ASL) gestures into text. The goal is to create an intuitive tool that allows ASL users to communicate effectively with non-signers, reducing the communication barrier and promoting inclusivity. By employing Convolutional Neural Networks (CNNs), the system achieves high accuracy in gesture recognition, offering a reliable and efficient solution for everyday interactions. 

This project focuses on using affordable and commonly available hardware, ensuring that ASL recognition technology is accessible to a wide range of users. With real-time performance and robust functionality, the system is poised to improve communication for ASL users in various scenarios, including education, healthcare, and professional settings.

## Objective

The primary objective of this project is to build a real-time ASL detection system that converts sign language gestures into text, enabling smooth communication between ASL users and non-signers. The system leverages deep learning techniques to recognize and translate a wide range of ASL signs with high accuracy, making it a practical tool for everyday use.

## Key Features

- **High Accuracy**: The model achieved an accuracy rate of **92%** on the test dataset, demonstrating robust gesture recognition capabilities across diverse ASL gestures.
- **Precision & Recall**: The system achieved an average precision of **90%** and recall of **88%** for each gesture class, ensuring both specificity (correct identification of true positives) and sensitivity (detecting relevant instances).
- **Real-Time Processing**: The system performs at a frame rate of **25 fps** on standard CPU resources within Google Colab, with minimal latency (below 0.2 seconds). With GPU acceleration, the frame rate increases to **35+ fps**, ensuring smooth real-time translation for practical applications.
- **User-Friendly Interface**: Designed to be intuitive and accessible, the system is easy to use for both ASL users and non-signers, making it suitable for various settings such as classrooms, public spaces, and healthcare environments.

## Technologies Used

- **Python**: The primary programming language used for the development of the model.
- **TensorFlow** & **Keras**: Libraries used to build and train the Convolutional Neural Network (CNN) model.
- **OpenCV**: Used for real-time image and video processing to capture and analyze hand gestures.
- **Google Colab**: Platform used for training the model with GPU acceleration, providing a cost-effective environment for development.
- **NumPy** & **Pandas**: Used for data manipulation and preprocessing.

## Model Development

The system uses a **Convolutional Neural Network (CNN)**, a deep learning model well-suited for image classification tasks. The model was trained on a dataset of ASL gestures, with the following key steps in its development:

1. **Data Collection & Preprocessing**: The dataset was preprocessed to ensure consistency and high quality. Hand gesture images were standardized, normalized, and augmented to increase model generalization.
2. **Model Architecture**: A CNN model was designed with multiple layers of convolution, pooling, and fully connected layers to detect and classify ASL gestures.
3. **Training & Evaluation**: The model was trained on a labeled ASL dataset, achieving an accuracy of **92%**. Various performance metrics like precision, recall, and confusion matrix were used to evaluate the model.
4. **Real-Time Performance**: The model was optimized to run in real-time, processing frames at a rate of **25 fps** on standard hardware and **35+ fps** with GPU acceleration.

## Conclusion
The Inclusive Sign Language Translator project addresses the communication challenges faced by ASL users, offering a real-time, accurate, and efficient tool for translating sign language gestures into text. By incorporating deep learning techniques and leveraging commonly available hardware, this project helps bridge the communication gap, promoting inclusivity and independence for ASL users in a variety of contexts.

## Future Improvements
**Multi-language Support**: Expanding the model to recognize and translate gestures from other sign languages (e.g., British Sign Language, French Sign Language).
**Mobile Application**: Developing a mobile app for real-time ASL translation on smartphones and other portable devices.
