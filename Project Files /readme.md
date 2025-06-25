project Executable files
♻️ Cleantech: Transforming Waste Management with Transfer Learning

This project is developed as part of an AI/ML internship focused on solving real-world problems through intelligent automation. The system uses Transfer Learning with VGG16 to classify waste into categories like biodegradable, recyclable, and trash, helping promote sustainable waste management practices.

🚀 Features

🌿 Classify waste images into categories
🧠 Powered by VGG16 Transfer Learning
📷 Upload your image and get instant predictions
💻 Flask-based interactive web application
🎨 Clean and responsive UI with multiple pages (Home, Predict, Contact, About)
🛠️ Technologies Used

Python
TensorFlow & Keras
Flask
HTML, CSS
Bootstrap (for design elements)
Git & GitHub
📁 Folder Structure ├── app.py ├── split_data.py ├── train_model.py ├── vgg16.h5 ├── static/ │ └── assets/ │ ├── bg.png │ ├── logo.png │ └── other images ├── templates/ │ ├── index.html │ ├── predict.html │ ├── result.html │ ├── blog.html │ └── blog-single.html

📷 Sample Usage

Run app.py
Open browser and visit http://127.0.0.1:5000/
Navigate to Predict page
Upload an image of waste (like banana peel or plastic bottle)
Get classification result instantly
📌 Note

The dataset used is from Kaggle: Municipal Solid Waste Dataset
Ensure vgg16.h5 (trained model) is in the root directory before running the app.
