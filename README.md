# 🌟 SpellSense XR
### **ASL Fingerspelling Trainer for Meta Quest (MR/VR + Hand Tracking + Context-Aware AI)**

SpellSense XR is a mixed-reality learning experience built for the Meta Quest that lets users **fingerspell letters in the air and see their letters and words appear in 3D space**.  
Designed for the SensAI Hack San Francisco, this project explores:

- **Natural hand-tracking interactions**
- **Fingerspelling recognition using letter poses**
- **Context-aware AI for adaptive practice**
- **Passthrough MR experiences that anchor words in the user’s real environment**

This prototype demonstrates how XR and AI can support accessible, intuitive ASL learning tools — all without controllers.

---

## ✨ Features

### 🖐️ Hand Tracking–Based Letter Recognition
- Uses Meta XR Hand Tracking to detect hand poses  
- Supports **a subset of ASL fingerspelling letters** optimized for hackathon scope  
- Real-time stability smoothing for more accurate detection  
- Letters appear above the user's hand as they are recognized  

### 🔤 Word Building Pipeline
- Stable pose → accepted as a letter  
- Letters concatenate into a word in front of the user  
- Visual feedback for correct/incorrect letters and word completion  

### 🧠 Context-Aware AI Adaptive Practice
- Adjusts difficulty based on user performance  
- Optional passthrough awareness: anchors practice words near surfaces or objects  

### 🌈 Immersive Mixed Reality Experience
- Passthrough MR environment  
- Floating 3D UI, particles, and sound effects  
- Word “blooms” or animations trigger on completion  

---

## 🏆 SensAI Hack Challenge Fit

### ✔ Best Implementation of Hand Tracking
### ✔ Best Use of AI + PCA
### ✔ Mixed / Virtual Reality Experience

---

## 🎥 Demo Video  
_Add your demo link here_

---

## 📱 Installation

```
adb install SpellSenseXR.apk
```

---

## 🧰 Tech Stack

- Unity or Unreal  
- Meta XR SDK  
- Hand Tracking API  
- Passthrough API  
- PCA (Context-Aware AI)

---

## 🗂 Project Structure

```
SpellSenseXR/
  Assets/
    Scripts/
      HandTracking/
      WordBuilder.cs
      AdaptiveDifficulty.cs
      MRUIController.cs
  APK/
  Demo/
  README.md
```

---

## 🚀 Roadmap

- Hand tracking ✓  
- Letter recognition  
- Word building  
- Adaptive practice  
- MR UI  
- Demo polish  

---

## 👥 Team

- Erin Moore — Project Lead, Hand Tracking, Interaction Design

---

## 📄 License  
MIT License

---

## 🙌 Acknowledgements
Meta XR SDK, SensAI Hack, ASL educators
