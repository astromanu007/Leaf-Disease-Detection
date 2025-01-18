#  🌿 Anjaneya Plant Disease Detection & Cure

* Welcome to our innovative Plant Disease Detection system, a vital tool for modern agriculture. We've developed an advanced solution using Deep Learning technology that enables farmers to identify plant diseases quickly and accurately. Our system leverages Convolutional Neural Networks built with PyTorch to classify plant leaf images into 39 distinct disease categories. The model was trained on the comprehensive Plant Village dataset, which you can find linked in our Blog section.

## 🚀 Getting Started

### Prerequisites
1. Make sure you have **Python 3.8** installed on your system
   - You can download it from [Python's official website](https://www.python.org/downloads/)
   - Verify installation by running `python --version` in terminal

### Installation Steps
1. Clone this repository
   ```
   git clone https://github.com/astromanu007/Leaf-Disease-Detection.git
   cd Leaf-Disease-Detection
   ```

2. Set up Python Virtual Environment
   ```
   python -m venv venv
   ```
   - For Windows: `venv\Scripts\activate`
   - For Linux/Mac: `source venv/bin/activate`

3. Install Required Dependencies
   ```
   pip install -r requirements.txt
   ```

4. Download Pre-trained Model
   - Get `plant_disease_model_1.pt` from [this link](https://drive.google.com/file/d/1JsUW38lrsyAYG0ORjqwQxQiRZpPIoc0c/view?usp=sharing)
   - Place it in the `Flask Deployed App` directory

5. Run the Application
   ```
   cd Flask\ Deployed\ App
   python app.py
   ```

6. Access the Application
   - Open your web browser
   - Go to `http://localhost:5000`
   - You're ready to start detecting plant diseases!

### Optional: Explore in Jupyter Notebook
- Navigate to the `Model` directory
- Launch Jupyter Notebook to explore the model implementation

## 🤝 Join Our Community
* We welcome contributions from the developer community!
* Help us enhance the UI, improve the Deep Learning model, or add informative documentation
* When modifying the Deep Learning components, please update related documentation (.md, .pdf, .ipynb)
* Ensure your code is error-free and thoroughly tested
* Follow the standard fork and pull request workflow
* Learn about creating pull requests: https://opensource.com/article/19/7/create-pull-request-github

## 🔍 Test Image Library
* Access our curated test images in the test_images folder
* Each image is labeled with its corresponding disease for easy verification
* Perfect for validating the model's accuracy

## 🌐 Live Demo
<a href="https://plant-disease-detection-ai.herokuapp.com/" target = "_blank">Try Our AI-Powered Detection Tool</a><br>

## 📸 Application Preview:
#### Homepage
<img src="https://github.com/astromanu007/Leaf-Disease-Detection/blob/main/demo_images/1.png"> <br>
#### Image Upload Interface
<img src = "https://github.com/astromanu007/Leaf-Disease-Detection/blob/main/demo_images/2.png"> <br>
#### Analysis Results
<img src = "https://github.com/astromanu007/Leaf-Disease-Detection/blob/main/demo_images/3.png"> <br>
#### Connect With Us
<img src = "https://github.com/astromanu007/Leaf-Disease-Detection/blob/main/demo_images/4.png"> <br>

### Created by Manish Dhatrak 🌱 
