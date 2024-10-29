# 🌱🌿 Leaf Disease Prediction with Cure 🌿🌱

![Leaf Disease Detection Banner](link_to_your_banner_image_or_gif)

## 🚀 Overview

Leaf Disease Prediction with Cure is an 🤖 AI-powered application designed to detect plant leaf diseases and suggest appropriate treatments. Using deep learning models, the app helps farmers and gardeners 🌾 identify diseases from images of leaves and provides solutions to address these problems.

This project is developed using React for the frontend, TensorFlow.js for machine learning, and Node.js for backend services.

## 💡 Features
- 🔮 **AI-based Leaf Disease Detection**: Upload a leaf image, and the app will predict the disease.
- 👩‍🌾 **Cure Suggestions**: Provides appropriate remedies for the detected diseases.
- 🌐 **User-friendly Interface**: Simple, clean, and responsive UI.
- ⏱️ **Real-time Performance**: Quick and efficient predictions.
- 🛠️ **Cross-platform Support**: Works on web and mobile browsers.

## 🚀 Live Demo

[Click here to try the live demo](link_to_live_demo)

## 📝 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Live Demo](#-live-demo)
- [Screenshots](#-screenshots)
- [Technologies Used](#-technologies-used)
- [Setup Instructions](#-setup-instructions)
- [How to Use](#-how-to-use)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)



Technologies:
Frontend: React.js with Tailwind CSS for UI.
Backend: Node.js with Express.js for APIs.
Machine Learning: TensorFlow.js for leaf disease prediction.
Let’s start building:


#### Step 1: Setup the Project Structure
1. **Frontend Folder Structure:**
   ```
   leaf-disease-prediction/
     ├── public/
     ├── src/
     │    ├── components/
     │    ├── assets/
     │    ├── App.js
     │    └── index.js
     ├── package.json
     └── .env
   ```
2. **Backend Folder Structure:**
   ```
   backend/
     ├── controllers/
     ├── models/
     ├── routes/
     ├── app.js
     ├── package.json
     └── .env
   ```

#### Step 2: Backend Development
- **Setting up Node.js with Express:**

   1. Create a new directory called `backend`, and initiate it with:
      ```bash
      mkdir backend
      cd backend
      npm init -y
      npm install express mongoose dotenv cors
      ```

   2. **Models and Routes:**
      - Create a `disease.model.js` under `models/` for MongoDB schema.
      - Create a `diseaseRoutes.js` under `routes/` to define API endpoints.

#### Step 3: Frontend Development
1. **Set up React:**
   - Navigate to your project root and create a React app:
     ```bash
     npx create-react-app leaf-disease-prediction
     cd leaf-disease-prediction
     npm install tailwindcss @tensorflow/tfjs axios
     ```

   - **Tailwind CSS Setup:**
     Follow [Tailwind CSS official setup guide](https://tailwindcss.com/docs/guides/create-react-app) for React apps.

  
## 🖼️ Screenshots
![Leaf Detection Animation](link_to_screenshot_or_animation_gif)

## 🛠️ Technologies Used

- 🛡️ **Frontend**: React.js, Tailwind CSS
- 💻 **Backend**: Node.js, Express.js
- 🔗 **Machine Learning**: TensorFlow.js
- 📄 **Database**: MongoDB
- 🤖 **Others**: Cloudinary (for image hosting), Axios (for API calls)

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
   - Get `plant_disease_model_1.pt` from [this link](https://drive.google.com/drive/folders/1ewJWAiduGuld_9oGSrTuLumg9y62qS6A?usp=share_link)
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

## 📚 Learn More
<a href="https://medium.com/analytics-vidhya/plant-disease-detection-using-convolutional-neural-networks-and-pytorch-87c00c54c88f" target = "_blank">Discover Our CNN Implementation with PyTorch</a><br>

## 🌐 Live Demo
<a href="https://plant-disease-detection-ai.herokuapp.com/" target = "_blank">Try Our AI-Powered Detection Tool</a><br>

## 📸 Application Preview:
#### Homepage
<img src = "demo_images/1.PNG" > <br>
#### Image Upload Interface
<img src = "demo_images/2.PNG"> <br>
#### Analysis Results
<img src = "demo_images/3.PNG"> <br>
#### Connect With Us
<img src = "demo_images/4.PNG"> <br>

### Created by Manish Dhatrak 🌱 

## 📜 License

This project is licensed under the MIT License.

## 📧 Contact

- **GitHub**: [Your GitHub Profile](https://github.com/astromanu007)
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/manish-dhatrak-b759171aa/)
- **Email**: astromanu007@example.com

