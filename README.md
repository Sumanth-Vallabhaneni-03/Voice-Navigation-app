# 📱 Voice-Navigation-app
A voice based navigation app
**Seamless Navigation with Ease Interface**  

---

## 📚 **Project Overview**  
**Voice-Navigation** is an intuitive and accessible Android application designed to assist visually impaired individuals by providing seamless navigation using voice commands and audio guidance. The app allows users to:  

- Reaching destination using voice commands.  
- Select the Destination point by tapping anywhere on the screen.  
- Receive real-time step-by-step audio navigation cues for safe mobility.  

---

## 🎯 **Key Features**  

✅ **Voice-to-Text Input**  
- Allows users to input source and destination through voice commands.  
- Utilizes `SpeechRecognizer` API for accurate speech recognition.  

✅ **Audio Navigation Cues**  
- Provides clear and concise step-by-step voice instructions.  
- Guides users safely to their destination using Google Maps.  

---

## 🛠️ **Technologies Used**  

- **Android Studio** – Development environment for building the app.  
- **Java** – Primary programming language for application logic.  
- **XML** – For designing the user interface.  
- **SpeechRecognizer API** – Converts voice input to text.  
- **Google Maps API** – Provides real-time navigation and route guidance.  

---

## 📂 **Project Structure**  

```
/VoiceNavigationApp
├── /app
│   ├── /src
│   │   ├── /main
│   │   │   ├── /java/com/example/voicenavigationapp
│   │   │   │   ├── MainActivity.java
│   │   │   └── /res
│   │   │       ├── /layout
│   │   │       │   └── activity_main.xml
│   │   │       └── /mipmap
│   │   │           └── App icons and launcher images
│   │   └── AndroidManifest.xml
└── /gradle
    └── Build configuration files
```

---

## 🚀 **Installation and Setup**  

### **Step 1: Clone the Repository**  
```bash
git clone https://github.com/Sumanth-Vallabhaneni-03/Voice-Navigation-app.git
```

### **Step 2: Open in Android Studio**  
- Open **Android Studio**.  
- Select **Open an Existing Project** and choose the `VoiceNavigationApp` folder.  

### **Step 3: Configure API Keys**  
- Get your API key from [Google Cloud Console](https://console.cloud.google.com/).  
- Add the API key in the `AndroidManifest.xml` file.  

```xml
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_API_KEY_HERE" />
```

### **Step 4: Build and Run**  
- Connect your Android device or use an emulator.  
- Click **Run** to install and launch the application.  

---

## 🎙️ **How to Use**  

1. **Launch the App:** Open the app then **Tap Anywhere to Start**.  
2. **Voice Input:** Speak the destination point.  
3. **Audio Cues:** Follow the step-by-step audio instructions to reach your destination safely.  

---

## 🔒 **Permissions Required**  

- **Microphone Access:** To capture and process voice input.  
- **Internet Access:** To fetch route data using Google Maps API.  


---

✅ **Voice-Navigation** is committed to enhancing mobility & empowering seamless interface with less Complexity🌟

---

## 📱 Mobile Application Screenshots  
Below are the screenshots showcasing the working of our mobile application. 🚀  

<p>
  <img src="https://github.com/user-attachments/assets/791ad337-aee3-4fc8-9c1f-d06712b86906" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/1e929868-d2c5-4c41-8aa3-f56c219ba01c" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/785dd713-1cf3-4e25-8c07-c68124f50174" width="200">
    <br><br>
  <img src="https://github.com/user-attachments/assets/bdeaea00-f0d7-479b-9dee-39bea05acb39" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/b04d0791-d892-4ea7-bdeb-1bed85e0cc68" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/79d8d513-8d9f-4ae1-aa9b-4c9481432a74" width="200">
</p>

---
