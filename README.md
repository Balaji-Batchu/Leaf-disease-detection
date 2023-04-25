# Leaf-disease-detection

Here's an updated readme.md file for the leaf disease detection project that uses Streamlit instead of Flask:

Leaf Disease Detection Project
This project is a machine learning-based solution for detecting five types of leafs for inividual leaf disease detection, including corn and maize, potato, tomato, grape, and cotton. The project uses a deep learning-based approach for image classification, where a convolutional neural network (CNN) is trained on a large dataset of healthy and diseased leaves.

Requirements
To run this project, you need to have the following software installed:

Python 3.x
TensorFlow 2.x
Keras 2.x
Streamlit 1.x

You can install these packages using pip, by running the following command:


pip install tensorflow keras streamlit pillow
Usage
To use the leaf disease detection model, you can run the Streamlit application by running the following command:

streamlit run app.py
This will start a local web server on port 8501. You can then open your web browser and go to http://localhost:8501 to access the web application.

Alternatively, you can use localtunnel to create a public URL for your application. To do this, run the following command:

streamlit run app.py & npx localtunnel --port 8501 --subdomain leafdetector
This will create a public URL that you can share with others.

To test the model, you can upload an image of a leaf, and the model will predict whether the leaf is healthy or diseased and which type of disease it belongs to.

Dataset
The dataset used for training the model is publicly available and can be downloaded from the following source:

License
This project is licensed under the MIT License. You are free to use, modify, and distribute this project under the terms of the MIT License.

Contributing
If you want to contribute to this project, please feel free to submit pull requests or open issues. You can also contact the project owner for more information.
