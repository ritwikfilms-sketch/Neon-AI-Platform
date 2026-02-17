# Neon-AI-Platformhttps://github.com/ritwikfilms-sketch
Neon AI Platform Ultimate – Interactive AI web app with GPT Chat, Text-to-Image generator, and Male/Female Voice TTS. Futuristic neon UI, glassmorphism cards, responsive and ready for live demo.
# नियॉन-एआई-प्लेटफ़ॉर्म / Neon AI Platform

![Neon AI Logo](assets/logo.png)

[GitHub Repo Link](https://github.com/ritwikfilms-sketch/Neon-AI-Platform)

*नियॉन एआई प्लेटफॉर्म अल्टीमेट / Neon AI Platform Ultimate* –  
Interactive AI Web App with GPT Chat, Image Generator & Voice Assistant (Male/Female).  
Futuristic neon UI, glassmorphism cards, fully responsive, ready for live demo.

---

## 🚀 Features / विशेषताएँ

•⁠  ⁠*Chat AI / चैट AI*  
  GPT-powered intelligent chat / GPT आधारित स्मार्ट चैट  

•⁠  ⁠*Image Generator / इमेज जेनरेटर*  
  Create AI images from text prompts / टेक्स्ट से AI इमेज बनाएँ  

•⁠  ⁠*Voice Assistant / वॉइस असिस्टेंट*  
  Male & Female TTS / मेल और फीमेल वॉइस, हिंदी + English  

•⁠  ⁠*Futuristic UI / भविष्यवादी UI*  
  Neon colors, glowing effects, smooth transitions / नियॉन रंग, ग्लोइंग प्रभाव, स्मूद ट्रांज़िशन्स  

---

## 🛠 Setup & Run / सेटअप और रन

1.⁠ ⁠Clone the repo / रेपो क्लोन करें:
```bash
git clone https://github.com/ritwikfilms-sketch/Neon-AI-Platform.git
cd Neon-AI-Platform# 1️⃣ Clone the repo / रेपो क्लोन करें
git clone https://github.com/ritwikfilms-sketch/Neon-AI-Platform.git
cd Neon-AI-Platform

# 2️⃣ Install Node.js dependencies / निर्भरता इंस्टॉल करें
npm install

# 3️⃣ Create .env file / .env फ़ाइल बनाएं
# Open a text editor और add your OpenAI API key
# .env content:
OPENAI_API_KEY=your_openai_api_key_here

# 4️⃣ Run backend API server / बैकएंड API सर्वर चलाएँ
node api.js &

# 5️⃣ Serve frontend / फ्रंटएंड सर्व करें
npx serve .

# 6️⃣ Open the app in your browser / ब्राउज़र में URL खोलें
# Example: http://localhost:5000
---

# Neon-AI-Platform / नियॉन-एआई-प्लेटफ़ॉर्म

[GitHub Repo](https://github.com/ritwikfilms-sketch/Neon-AI-Platform)

![Neon AI Hero](assets/logo.png)

---

## 🌟 Overview / परिचय

*Neon AI Platform Ultimate* – Interactive AI Web App with:  

•⁠  ⁠*GPT Chat*  
•⁠  ⁠*Text-to-Image Generator*  
•⁠  ⁠*Voice Assistant (Male & Female, Hindi + English)*  

Futuristic neon UI, glassmorphism cards, fully responsive, ready for live demo.  

[🌐 Live Demo](https://ritwikfilms-sketch.github.io/Neon-AI-Platform/)

---

## 💡 Features / विशेषताएँ

•⁠  ⁠*Chat AI / चैट AI*  
  GPT-powered intelligent chat / GPT आधारित स्मार्ट चैट  

•⁠  ⁠*Image Generator / इमेज जेनरेटर*  
  Create AI images from text prompts / टेक्स्ट से AI इमेज बनाएँ  

•⁠  ⁠*Voice Assistant / वॉइस असिस्टेंट*  
  Male & Female TTS, Hindi + English / मेल और फीमेल वॉइस  

•⁠  ⁠*Futuristic UI / भविष्यवादी UI*  
  Neon colors, glowing effects, smooth transitions / नियॉन रंग, ग्लोइंग प्रभाव, स्मूद ट्रांज़िशन्स  

---

## 🖥️ Project StructureNeon-AI-Platform/ │ ├─ index.html           <-- Main page (hero, AI tool cards) ├─ style.css            <-- Styling & neon theme ├─ scripts/ │    └─ main.js         <-- Chat, Image, Voice functionality ├─ assets/ │    ├─ logo.png │    └─ ...other images/icons ├─ package.json         <-- Node dependencies └─ README.md            <-- Setup & deployment guide---

## ⚡ How to Setup & Run / सेटअप और रन

```bash
# Clone repo
git clone https://github.com/ritwikfilms-sketch/Neon-AI-Platform.git
cd Neon-AI-Platform

# Install dependencies
npm install

# Create .env file with OpenAI API key
echo "OPENAI_API_KEY=your_openai_api_key_here" > .env

# Run backend API server
node scripts/main.js &

# Serve frontend
npx serve .

# Open in browser
# Example: http://localhost:5000[18/02/26, 3:22:19 AM] ritwikspandey: <input id="chatInput" placeholder="Type your message">
<button onclick="chatAI()">Send</button>
<div id="chatOutput"></div>
[18/02/26, 3:22:29 AM] ritwikspandey: <input id="imagePrompt" placeholder="Image prompt">
<button onclick="generateImage()">Generate</button>
<div id="imageResult"></div>
[18/02/26, 3:22:43 AM] ritwikspandey: <button onclick="playVoice()">Play Welcome Voice</button>
