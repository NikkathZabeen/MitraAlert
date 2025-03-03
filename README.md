# MiTRA Alert 🚨  
*A Smart Solution for Real-Time Disaster Awareness and Safety*  

## Overview  
MiTRA Alert is a web-based platform designed to provide real-time disaster alerts, prevent misinformation, and enable community collaboration. It integrates user authentication, location-based alerts, and fake news detection to enhance public safety.  

## 🌟 Features  
### 🔐 User Authentication & OTP Verification  
- Users sign up with name, email, and password  
- Email/SMS OTP verification for account activation  
- JWT-based authentication for secure login sessions  

### 📍 Location-Based Alerts & Notifications  
- Fetches user location via browser permissions  
- Retrieves disaster alerts using external APIs  
- Sends notifications via:  
  - SMS (Twilio API)  
  - WhatsApp messages  
  - Web notifications  

### 🗺 Disaster Mapping & Nearby Hazards  
- Utilizes **Google Maps API** and **Leaflet.js** for mapping  
- Displays disaster-affected areas on a map  
- Highlights alerts near the user's location  

### 📰 Fake News Detection for Tweets/News  
- Machine learning model trained on **Kaggle’s fake news dataset**  
- Uses **Natural Language Processing (NLP)** to analyze news/tweets  
- Predicts real or fake with a confidence score and explanation  

### 🗣 Community Updates & Disaster Discussion  
- **Location-based forums** for affected users  
- Users can:  
  - Report incidents  
  - Share safety measures  
  - Discuss ongoing disasters  
- **Moderation System:** Admins monitor discussions to prevent spam/misinformation  
- **Real-time chat using WebSockets (Socket.io)**  

### 📜 Historical Disaster Data & Safety Measures  
- Displays past disaster records  
- Provides survival tips and preventive measures  
- Educates users on disaster preparedness  

## 🏗 System Architecture  
- **Frontend:** React.js, Leaflet.js, Bootstrap  
- **Backend:** Node.js, Express.js, MongoDB  
- **Machine Learning:** Python, Flask, Scikit-learn  
- **APIs & Services:**  
  - Twilio (SMS/WhatsApp)  
  - Google Maps API  
  - OpenWeather API  

## 🚀 Future Enhancements  
- Voice Alerts & AI Assistants  
- Integration with Government Agencies  
- Mobile App Development  

## 📧 Contact  
👤 **Nikkath Zabeen Shaik**  
📩 Email: [nikkath23bcs60@iiitkottayam.ac.in](mailto:nikkath23bcs60@iiitkottayam.ac.in)  
🌐 Portfolio: [Your Portfolio Link]  

---
**🌍 Stay Safe, Stay Informed!** 🚀  
