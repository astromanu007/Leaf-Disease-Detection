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

## 🚪 Setup Instructions

### 🚀 Requirements
- 🧪 Node.js (v14 or above)
- 📅 NPM (v6 or above)
- 🛋️ MongoDB
- 🤖 TensorFlow.js

### 📜 Step-by-step Guide:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/astromanu007/Leaf-Disease-Detection.git
    cd leaf-disease-prediction
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up environment variables**:
    Create a `.env` file in the root directory with the following variables:
    ```
    MONGO_URI=your_mongodb_connection_string
    CLOUDINARY_URL=your_cloudinary_url
    ```

4. **Run the development server**:
    ```bash
    npm start
    ```

5. **Run the backend server**:
    In a separate terminal, navigate to the `backend` directory and start the backend:
    ```bash
    cd backend
    npm install
    npm run server
    ```

6. **Access the app**: Open your browser and go to `http://localhost:3000`

## 🎯 How to Use

1. **Upload a Leaf Image**: 🖼️ Take a clear photo of the leaf and upload it using the "Upload Image" button.
2. **View Predictions**: 🤖 The app will display the detected disease along with confidence levels.
3. **Get Cure Suggestions**: 🧪 Based on the prediction, the app will suggest potential treatments or remedies.
4. **Save History**: 📂 You can view and manage previous predictions through the app's history feature.

## 🤝 Contributing

We welcome contributions from the open-source community! Feel free to submit issues and pull requests.

### 📑 How to Contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

## 📜 License

This project is licensed under the MIT License.

## 📧 Contact

- **GitHub**: [Your GitHub Profile](https://github.com/astromanu007)
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/manish-dhatrak-b759171aa/)
- **Email**: astromanu007@example.com

