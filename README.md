# 🚗 Car Chatbot Collection

This project contains two CarBot chatbot implementations, each showcasing a different approach to user interaction and functionality. Both files are standalone and written in HTML and JavaScript.

## 📁 Files Overview

### 1. `carbot-firebase.html`
An interactive car inquiry chatbot that:
- Connects to **Firebase Firestore**.
- Loads car data dynamically from the `cars` collection.
- Allows users to request a test drive or ask to be contacted.
- Saves inquiries in the `inquiries` collection with timestamps.

🔹 **Use Case**: Real car dealership inquiries.  
🔹 **Requires Firebase project setup.**

---

### 2. `carbot-static.html`
A modern-looking chatbot with:
- Clean and responsive UI.
- Hardcoded car list (no Firebase needed).
- Test drive/contact workflow simulation.

🔹 **Use Case**: UI demonstration or static preview without backend.

---

## 🚀 Getting Started

1. **Clone the repository:**
```bash
git clone https://github.com/A-Samod/event-car-chatbot.git
cd event-car-chatbot
```
2. **Open any file directly in your browser::**

- `carbot-firebase.html`
- `carbot-static.html`

3. For Firebase Setup (carbot-firebase.html):

- Replace the `firebaseConfig` placeholder with your actual Firebase project credentials.
- Create a Firestore collection named `cars` with fields: `model`, `year`, `price`.
- Inquiries will be saved in the `inquiries` collection.