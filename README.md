# Fruit-Quality-Detection-using-CNN
Fruit Quality Detection using CNN
A web application that classifies and assesses the quality of fruits based on image analysis using deep learning. This tool evaluates ripeness and detects defects in fruits, providing a comprehensive report on each fruit's condition. The project uses computer vision and deep learning models to automate fruit quality checks for apples, oranges, and bananas.

Features
Fruit Classification: Identifies the type of fruit (apple, orange, or banana) in the uploaded image.
Quality Detection: Detects ripeness and potential defects in the fruit.
Deep Learning Models: Utilizes YOLOv5, DenseNet, and VGG16 for image classification and quality assessment.
User-Friendly Interface: Simple, intuitive design for easy image uploads and result visualization.
Data Storage and Sharing: Enables users to save and share assessment results.
Technology Stack
Frontend: HTML, CSS, JavaScript, Streamlit (for easy deployment of the app).
Backend: Python (TensorFlow, OpenCV) for deep learning and image processing.
Models: YOLOv5, DenseNet, VGG16 for fruit classification and quality analysis.
Setup and Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/fruit-quality-detection.git
cd fruit-quality-detection
Install Required Packages: Install dependencies listed in requirements.txt.

bash
Copy code
pip install -r requirements.txt
Run the Application: Start the Streamlit app.

bash
Copy code
streamlit run app.py
Usage
Upload an image of a fruit (apple, orange, or banana).
Click on the "Analyze" button to classify the fruit type and assess its quality.
View the results, which include the fruit type, ripeness level, and any detected defects.
Models Used
YOLOv5: For object detection to locate and classify the fruit in the image.
DenseNet and VGG16: Used for quality assessment, including ripeness and defect detection.
Demo
Here's a quick demo showing how to use the Fruit Classification and Quality Detection tool:


Contributing
Fork the repository.
Create your feature branch: git checkout -b feature-name
Commit your changes: git commit -m 'Add feature'
Push to the branch: git push origin feature-name
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions or suggestions, please contact:

Arshika Mishra
Email: arshikamishra1205@gmail.com
This project is designed to streamline and automate the fruit quality assessment process, enhancing accuracy and reliability compared to manual inspection methods.







