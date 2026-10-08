![Top Image](https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/top_image.png)


# 🌱 Plant Treatment App: Plant Disease Detection App
---

**Plant Treatment App** is a Flutter-based mobile application designed to help users identify plant diseases, gain plant care insights, and access a comprehensive library of common plant diseases. Powered by a **quantized PyTorch model (EfficientNet-B0)**, the app provides fast, accurate, and offline plant disease detection without the need for server-based predictions. Additional features include secure user authentication via **Firebase**, a **plant care tips** section to help users maintain healthy plants, a vast **disease library** for exploring plant conditions, and **community feedback** for users to share experiences and improve the app. The app is designed with a **responsive interface** that adapts seamlessly to different screen sizes for an optimal user experience.

---

## 📱 Features

- **Plant Disease Detection**: Quickly identify plant diseases by uploading or capturing plant images. The app uses a **quantized EfficientNet-B0 model** optimized for mobile to provide fast and accurate results.
- **Firebase Authentication**: Secure user login and signup powered by Firebase.
- **Plant Care Tips**: Discover tips for maintaining healthy plants and preventing disease.
- **Disease Library**: Access a comprehensive library of common plant diseases, including images, symptoms, and treatments.
- **Community Feedback**: Users can share their experiences and provide feedback to improve the plant disease detection system and overall app functionality.
- **Responsive Design**: A user-friendly interface that adapts to various screen sizes for an optimal experience.

---

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) installed on your machine.
- Firebase project with Authentication enabled.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Salman-Farid/planty.git
   cd planty
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Set up Firebase:

    - Go to the [Firebase Console](https://console.firebase.google.com/), create a new project, and enable Firebase Authentication.
    - Download the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) files and place them in the appropriate directories:
        - `android/app/` for `google-services.json`
        - `ios/Runner/` for `GoogleService-Info.plist`

5. Run the app:

   ```bash
   flutter run
   ```

---

## 🌿 Screenshots

<p align="center">
  <!-- Row 1 -->
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/1.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/2.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/3.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/4.png" width="150" style="margin: 10px;">
  <br>

  <!-- Row 2 -->
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/5.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/6.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/7.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/8.png" width="150" style="margin: 10px;">
  <br>

  <!-- Row 3 -->
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/9.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/10.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/12.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/13.png" width="150" style="margin: 10px;">
  <br>

  <!-- Row 4 -->
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/14.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/15.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/16.png" width="150" style="margin: 10px;">
  <img src="https://github.com/Salman-Farid/planty/blob/main/app_screen_shots/17.png" width="150" style="margin: 10px;">
</p>




## 🔥 Technical Details

- **Flutter Framework**: A cross-platform UI toolkit for building high-performance Android and iOS applications.
- **Firebase Authentication**: Ensures secure user authentication.
- **PyTorch (EfficientNet-B0)**: A quantized deep learning model optimized for on-device plant disease detection, ensuring low latency and offline functionality.
- **Dart**: The primary programming language used for Flutter development.

### ⚙️ ML Model Details

- **Model Name**: EfficientNet-B0 (Quantized)  
- **Total Classes**: 66  
- **Supported Plants**: 13

#### 🏷️ Plant Names
```plaintext
Bitter gourd, Corn, Cucumber, Eggplant, Lentil, Paddy, Potato, Sugarcane, Tomato, Wheat, Soybean, Pepper, Pumpkin.

```





#### 🏷️Diseases
```plaintext
Bitter gourd - Downy Mildew, Bitter gourd - Healthy, Bitter gourd - Jassid, Bitter gourd - Leaf Spot, Bitter gourd - Nitrogen Deficiency, Bitter gourd - Nitrogen and Magnesium Deficiency, Bitter gourd - Nitrogen and Potassium Deficiency, Bitter gourd - Potassium Deficiency, Bitter gourd - Potassium and Magnesium Deficiency, Corn - Blight, Corn - Common Rust, Corn - Gray Leaf Spot, Corn - Healthy, Cucumber - Anthracnose, Cucumber - Bacterial Wilt, Cucumber - Downy Mildew, Cucumber - Fresh Leaf, Cucumber - Gummy Stem Blight, Eggplant - Epilachna Beetle, Eggplant - Flea Beetle, Eggplant - Healthy, Eggplant - Jassid, Eggplant - Mite, Eggplant - Mite and Epilachna Beetle, Eggplant - Nitrogen Deficiency, Eggplant - Nitrogen and Potassium Deficiency, Eggplant - Potassium Deficiency, Lentil - Ascochyta Blight, Lentil - Normal, Lentil - Powdery Mildew, Lentil - Rust, Paddy - Bacterial Leaf Blight, Paddy - Bacterial Leaf Streak, Paddy - Bacterial Panicle Blight, Paddy - Blast, Paddy - Brown Spot, Paddy - Dead Heart, Paddy - Downy Mildew, Paddy - Hispa, Paddy - Normal, Paddy - Tungro, Potato - Early Blight, Potato - Late Blight, Potato - Healthy, Sugarcane - Healthy, Sugarcane - Mosaic, Sugarcane - Red Rot, Sugarcane - Rust, Sugarcane - Yellow, Tomato - Bacterial Spot, Tomato - Early Blight, Tomato - Late Blight, Tomato - Leaf Mold, Tomato - Septoria Leaf Spot, Tomato - Spider Mites - Two Spotted Spider Mite, Tomato - Target Spot, Tomato - Tomato Yellow Leaf Curl Virus, Tomato - Tomato Mosaic Virus, Tomato - Healthy, Wheat - Brown Rust, Wheat - Healthy, Wheat - Loose Smut, Wheat - Mildew, Wheat - Septoria, Wheat - Stem Rust, Wheat - Yellow Rust.
```
---

## 🌟 Future Improvements

✅ **Offline Disease Library** – Enable users to access disease details without an internet connection.  
✅ **Expanded Plant Care Tips** – Enhance the database with more plant care insights.  
✅ **Community Contributions** – Allow users to submit new diseases and share their experiences.  

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---


## ✨Technology Used:

- 🚀 **[PyTorch](https://pytorch.org/)** – For providing efficient tools to deploy ML models.  
- 📖 **[Flutter Documentation](https://flutter.dev/docs)** – For comprehensive development resources.  
- 🔐 **[Firebase](https://firebase.google.com/)** – For secure authentication and backend support.  
- ⚡ **[FastAPI](https://fastapi.tiangolo.com/)** – For serving the ML model efficiently.  
- 🌐 **[Render](https://render.com/)** – For deploying the model API server.  
---

## 🔗 Useful Links

- 📡 **API Documentation** – [Click here](https://plant-disease-detection-2-aa5x.onrender.com/docs#/default/predict_predict__post) to access the API endpoints.  
- 🧠 **ML Model & FastAPI Repository** – [View on GitHub](https://github.com/Salman-Farid/plant_disease_detection.git).  
- 📱 **Planty App Repository** – [Explore on GitHub](https://github.com/Salman-Farid/planty.git).  

---
