# Food Nutrition Estimator

## Abstract
This project is a research-based approach to estimating the nutritional values of food using the food’s image as input. The primary focus was to deepen our understanding of machine learning, especially deep learning techniques. We collected image-based food data from various sources and trained a Convolutional Neural Network (CNN) based image classification model to achieve the best possible accuracy. 

To make the model accessible to users, we developed a web application using the Streamlit and Flask frameworks. The web app allows users to easily drag and drop an image of food, and then extracts and displays its nutritional information.

## Features
- Image-based food classification using CNN
- High accuracy with MobileNetV2 architecture
- User-friendly web interface for easy image upload
- Instant nutritional value estimation

## Technologies Used
- Deep Learning: Convolutional Neural Network (CNN)
- Pretrained Model: MobileNetV2
- Web Frameworks: Streamlit, Flask
- Programming Language: Python

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/food-nutrition-estimator.git
    cd food-nutrition-estimator
    ```

2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

- Run the web application:
    ```bash
    streamlit run app.py
    ```
- Open the displayed URL in your browser.
- Drag and drop your food image to get the nutritional values.

## Dataset
We used image datasets collected from various publicly available sources, covering a wide variety of food items to train our CNN model.

## Model Details
- Model Architecture: MobileNetV2
- Training: Transfer learning with fine-tuning
- Performance: Achieved peak accuracy on test data

## Future Work
- Expand food categories
- Improve accuracy with larger datasets
- Integrate with a nutritional database for detailed micronutrient info

## Keywords
Food Image Classification, CNN, MobileNetV2, Deep Learning, Nutrition Estimation, Streamlit, Flask

---

Feel free to contribute or raise issues!

