# 📱 Voice-Navigation-app
A voice based navigation app
**Empowering the Visually Impaired with Seamless Navigation**  

---

## 📚 **Project Overview**  
**Voice-Navigation** is an intuitive and accessible Android application designed to assist visually impaired individuals by providing seamless navigation using voice commands and audio guidance. The app allows users to:  

- Input source and destination using voice commands.  
- Select the starting point by tapping anywhere on the screen.  
- Receive real-time step-by-step audio navigation cues for safe mobility.  

---

## 🎯 **Key Features**  

✅ **Voice-to-Text Input**  
- Allows users to input source and destination through voice commands.  
- Utilizes `SpeechRecognizer` API for accurate speech recognition.  

✅ **Tap-to-Select Start Point**  
- Users can manually select their starting point by tapping anywhere on the screen.  
- Simplifies navigation without relying on GPS.  

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
git clone https://github.com/Phanisirisha-46/Voice-Navigation-app.git
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

1. **Launch the App:** Open the app and press the **"Tap Anywhere to Start"** button.  
2. **Voice Input:** Speak the destination or starting point.  
3. **Manual Start Point:** Tap anywhere on the screen to choose your starting point.  
4. **Audio Cues:** Follow the step-by-step audio instructions to reach your destination safely.  

---
##  **Output Screenshots**  

![WhatsApp Image 2025-03-21 at 21 28 14_21615e96](https://github.com/user-attachments/assets/460f5cb9-ce45-45c0-a143-cf6c50b9067c)

<img width="170" alt="image" src="https://github.com/user-attachments/assets/a40691c6-8d56-4bb3-8180-8bb50f9d76eb" />
<img width="166" alt="image" src="https://github.com/user-attachments/assets/57c36756-feb1-4e4e-aa57-1de6cac9248f" />
![WhatsApp Image 2025-03-21 at 21 26 00_6d0a77cf](https://github.com/user-attachments/assets/5840c5ce-4f2f-45b0-9b88-21ae432befe9)
![WhatsApp Image 2025-03-21 at 18 39 55_cd042224](https://github.com/user-attachments/assets/39e6099f-6124-465c-8814-e1addad2a423)
<img width="158" alt="image" src="https://github.com/user-attachments/assets/5e23d68d-60af-43f1-a123-770da863dbe5" />
<img width="158" alt="image" src="https://github.com/user-attachments/assets/6511efc4-f526-4abb-a66d-6bb73e6d65ee" />

---
## 🔒 **Permissions Required**  

- **Microphone Access:** To capture and process voice input.  
- **Internet Access:** To fetch route data using Google Maps API.  


---

✅ **Voice-Navigation** is committed to enhancing mobility and empowering visually impaired individuals with independence and confidence🌟

---
