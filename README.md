# 🔐 Resono – Dual Biometric Audiovisual Lock  

> *"Resono resonates only with you — your face and your voice are the keys."*  

---

## ✨ Overview  
Resono is a **next-gen dual biometric lock** built with a **Raspberry Pi**, combining **face recognition** 👁️ and **voice verification** 🎙️ for secure, real-time authentication.  

It doesn’t just open doors — it ensures they open **only for you**.  

---

## 🚀 Features  
- 🧑‍🤝‍🧑 **Dual Biometrics** – 95% accurate face recognition (OpenCV) + 90% accurate voice verification (SpeechRecognition).  
- ⚡ **Real-Time Security** – optimized Python pipelines improved efficiency by **40%** on resource-limited hardware.  
- 🔧 **Hardware Integration** – servo-driven electronic lock controlled via **GPIO**.  
- 🛠️ **Custom 3D Design** – lock housing designed in **SolidWorks** and 3D-printed for modular, secure assembly.  
- 📸 **Facial Dataset** – built with **500+ images** for robust training and inference.  

---

## 🖥️ Tech Stack  
- **Raspberry Pi** 🥧 – hardware brain  
- **Python** 🐍 – core programming  
- **OpenCV** 👁️ – face recognition  
- **SpeechRecognition** 🎙️ – voice authentication  
- **GPIO** ⚡ – hardware + servo control  
- **SolidWorks + 3D Printing** 🖨️ – mechanical design & integration  

---

## ⚙️ How It Works  
1. Raspberry Pi powers on 🔌.  
2. **Camera module** captures your face 📸 → OpenCV checks recognition.  
3. **Microphone** listens 🎤 → SpeechRecognition verifies your voice.  
4. ✅ If both pass → **servo actuates lock** → door opens 🔓.  
5. ❌ If mismatch → system stays locked 🔒.  
