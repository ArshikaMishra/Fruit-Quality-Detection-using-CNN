

# Fruit Classification and Quality Detection 
## Description
A web application built with computer vision and deep learning to classify fruits (apple, orange, banana) and assess quality based on ripeness and defect detection through image analysis. This project is intended to automate fruit quality checks, providing detailed evaluation results.

## Features
- **Fruit Classification**: Detects and classifies fruit types from images.
- **Quality Assessment**: Evaluates ripeness levels and identifies any defects.
- **Model Integration**: Uses **YOLOv5**, **DenseNet**, and **VGG16** for robust analysis.
- **User-Friendly Interface**: Simple and interactive, allowing easy uploads and result visualization.

## Technology Stack
- **Frontend**: HTML, CSS, JavaScript, Streamlit for deployment.
- **Backend**: Python (using TensorFlow, OpenCV).
- **Models**: YOLOv5, DenseNet, VGG16.

## Installation
1. Clone the repository to your local machine.
    ```bash
    git clone <repo-link>
    cd <repo-folder>
    ```
2. Install all dependencies from the requirements file.
    ```bash
    pip install -r requirements.txt
    ```
3. Run the app locally.
    ```bash
    streamlit run app.py
    ```

## Usage
1. Upload an image of a fruit.
2. Click "Analyze" to classify and assess the fruit's quality.
3. View results showing fruit type, ripeness level, and any detected defects.

## Demo
> Add a GIF or image that illustrates the tool's functionality.

## Contributing
To contribute to the project:
1. Fork the repo.
2. Create a new feature branch.
3. Commit changes and open a pull request.

## License
Licensed under the MIT License. See `LICENSE` for more details.






