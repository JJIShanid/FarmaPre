# 🌾 Farma: Smart Agriculture Assistant

**Farma** is a web and mobile-based application designed to support farmers with intelligent crop management and prediction tools. Built using Angular for the frontend and powered by deep learning models (CNN), this project helps predict suitable crops, estimate yields, and recommend fertilizers based on soil and environmental inputs. The application is also extended to mobile using Flutter, ensuring accessibility for farmers on the go.


https://github.com/user-attachments/assets/cfafffac-aedd-40de-ac89-2e7c6241e3ad


## 🎯 Features

### ✅ Web Dashboard (Angular + Python Backend)
- 🌱 **Crop Prediction** using Convolutional Neural Networks (CNN)
- 💊 **Fertilizer Recommendation** system based on soil health
- 🐛 **Disease Detection** from uploaded crop leaf images (CNN-powered)
- 📊 **Yield Prediction** using historical and live environmental data
- 🛰️ **Weather Integration** (via APIs or mock data)
- 🔍 Input form for entering:
  - Soil pH
  - Rainfall
  - Temperature
  - Humidity
- 📁 Downloadable reports and visual analytics
- 💡 Easy-to-use UI for farmers and agriculture officers

### 📱 Mobile App Extension (Flutter)
- 🔔 Notifications for weather, best crop suggestions, etc.
- 📷 Mobile upload for leaf images for disease detection
- 📍 GPS-enabled location-based suggestions
- 🗣️ Local language support (future extension)
- 🧠 Embedded models for offline use (for simple predictions)

## 🧠 Technologies Used

| Stack        | Tech Details                                      |
|--------------|---------------------------------------------------|
| Frontend     | Angular, HTML5, SCSS, Bootstrap                   |
| Backend      | Flask (Python) with RESTful APIs                  |
| AI/ML Models | TensorFlow / Keras (CNN for predictions)          |
| Mobile App   | Flutter, Dart                                     |
| Data         | Custom-trained datasets + Kaggle (crop data)      |
| Deployment   | Localhost / Flutter Emulator / APK build          |

📸 Demo Preview
🎥 Click here to view the demo video

The video demonstrates the core web functionalities: prediction input, result display, disease detection via image upload, and user navigation.

📂 Folder Structure (Simplified)
bash
Copy
Edit
farma/
├── frontend/                # Angular web UI
├── backend/                 # Flask + AI/ML models
├── farma_flutter/           # Flutter mobile app
├── models/                  # Saved deep learning models (.h5)
├── data/                    # Crop and soil datasets
└── README.md
📌 Future Scope
🌐 Host the app online (e.g., Firebase + Heroku)

🌎 Multilingual Support for regional farmers

📦 Model compression for faster predictions on mobile

🧑‍🌾 Farmer profile management and history tracking

🤝 Integration with government databases for subsidies and schemes

👨‍💻 Author
Developed by [Ishan]
📧 Email: your.ishan96570@gmail.com.com
🛠️ Role: Full Stack Developer, AI Model Trainer, and Mobile App Integrator

📝 License
This project is open source and available under the MIT License.
## 🚀 How to Run

### 💻 Web App (Angular + Flask)

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/farma.git
   cd farma
cd frontend
npm install
ng serve

Run Deep Learning Models

The CNN models are pre-trained and saved as .h5 files.

They will be loaded automatically when Flask starts.

Test Features

Use the Angular form to input data and see results

Upload a crop image to detect disease
