# Augmented Reality Dementia Support Tool  

This repository contains an **Augmented Reality (AR) application** developed using **Unity and Vuforia Engine**, with **C#** as the primary scripting language. The tool is designed as a basic support system for dementia patients experiencing **semantic memory loss**. It enables patients to recall significant people in their lives by displaying **videos of loved ones** when scanning familiar objects using AR.  

## 🔹 **Key Features**  
- **Object Recognition with Vuforia:** Uses **Vuforia Image Targeting** to recognize objects and trigger relevant videos.  
- **Video Playback in AR:** Once an object is scanned, a **pre-linked video of a loved one** appears, offering personalized memory reinforcement.  
- **User-Friendly UI:** Simple interaction and intuitive controls make it accessible for dementia patients.  
- **Optimized for Mobile Devices:** Works on **Android & iOS**, making it easy for caregivers to implement.  

## 🔹 **Technical Details**  
### **1. Tools & Frameworks Used**  
- **Unity 3D** (Primary development environment)  
- **Vuforia Engine** (For AR tracking and object recognition)  
- **C#** (For scripting AR interactions and video playback logic)  

### **2. Implementation Flow**  
1. **Object Recognition:**  
   - Uses **Vuforia Image Target** to detect pre-defined objects.  
   - Each object is mapped to a corresponding **video file** stored in the application.  

2. **Video Display & Playback:**  
   - **Unity VideoPlayer** component is used to load and play the associated video.  
   - Videos appear as **floating UI panels** in the AR space.  

3. **Memory Reinforcement Mechanism:**  
   - The patient interacts with familiar objects in their environment.  
   - Once scanned, the video of a **family member or loved one** plays, helping them recall relationships.  

### **3. Key Unity Components Used**  
- **ARCamera** (Handles Vuforia tracking)  
- **ImageTarget** (Recognizes objects linked to videos)  
- **VideoPlayer Component** (Plays stored videos on scan)  
- **UI Canvas** (Displays the video interface)  

 🔹 **Setup & Installation**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/AR-Dementia-Support.git
   ```
2. Open the project in **Unity (2021+ recommended)**.  
3. Install **Vuforia Engine** via Unity Package Manager.  
4. Add and configure **Vuforia License Key** in Unity.  
5. Deploy the app to an **Android/iOS** device.  

## 🔹 **Future Enhancements**  
- Support for **voice-based memory recall**  
- Integration with **cloud storage** for dynamically updating videos  
- Implementing **gesture-based interactions** for ease of use  

This project aims to make **cognitive assistance more accessible** for individuals with dementia, helping them reconnect with their memories through **immersive AR experiences**. 🚀
