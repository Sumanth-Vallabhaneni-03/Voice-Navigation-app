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
  <img src="https://github.com/user-attachments/assets/0d40f9ac-1f1a-44d3-9985-c009896f61cf" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/491e1664-6310-4aee-8088-8d5a2418804d" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/8a296f5b-1a07-4c4d-8890-44a900c22323" width="200">
    <br><br>
  <img src="https://github.com/user-attachments/assets/fddc60d1-6158-4e71-aaf7-44237de875f6" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/27b34c10-aed4-4641-865d-2ce1c5f296c3" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/e27e9e78-3d2b-44f4-940d-d333d853701c" width="200">
</p>







