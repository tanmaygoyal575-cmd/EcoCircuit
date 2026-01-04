# ♻️ EcoCircuit

> **TechSprint Project Submission** > **Team:** EcoWarriors  
> **Theme:** Open Innovation (Sustainable E-Waste Management)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-MVP%20Ready-green.svg)
![Tech](https://img.shields.io/badge/AI-TensorFlow.js-orange)

## 📖 Problem Statement
Electronic waste is the world's fastest-growing domestic waste stream. Less than 20% of e-waste is formally recycled because consumers lack easy identification tools and knowledge of where to dispose of electronics responsibly.

## 💡 The Solution
**EcoCircuit** is a comprehensive web platform that leverages on-device Artificial Intelligence to instantly identify e-waste items via a smartphone camera. It calculates the specific environmental impact of recycling that item and connects users to the nearest certified recycling facilities.

## ✨ Key Features
- **🕵️‍♂️ AI E-Waste Scanner:** Real-time object detection using TensorFlow.js (Runs entirely in the browser for privacy).
- **🧮 Impact Calculator:** Instantly estimates CO₂ emissions prevented, trees planted, and energy saved.
- **📍 Solutions Map:** Geolocation-based finder for certified recycling centers (Relative to Gwalior, India context).
- **👤 User Dashboard:** Gamified profile tracking submission history, badges, and global rankings.
- **📝 Submission Wizard:** A streamlined process to schedule e-waste pickups.

## 📸 Screenshots

### 1. AI Scanner & Home
*Real-time identification of electronic items directly in the browser.*
![AI Scanner](screenshots/ai-scanner.png)

### 2. Solutions Map
*Locates certified recycling facilities near the user.*
![Solutions Map](screenshots/solutions-map.png)

### 3. Impact Calculator
*Calculates potential environmental savings for specific devices.*
![Impact Calculator](screenshots/impact-calculator.png)

### 4. Global Impact Dashboard
*Live tracking of the platform's collective environmental stats.*
![Global Dashboard](screenshots/global-dashboard.png)

### 5. Submission Wizard
*Streamlined process to schedule e-waste pickups.*
![Submission Wizard](screenshots/submission-wizard.png)

### 6. User Profile
*Gamified dashboard tracking individual contributions and badges.*
![User Profile](screenshots/user-profile.png)

## 🛠️ Technology Stack
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **AI/ML:** TensorFlow.js (COCO-SSD Model)
* **APIs:** Browser MediaDevices API (Camera), Geolocation API
* **Deployment:** GitHub Pages

## 🚀 How to Run Locally
1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/EcoCircuit.git](https://github.com/your-username/EcoCircuit.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd EcoCircuit
    ```
3.  Open `index.html` in any modern web browser (Chrome/Edge/Firefox).
    * *Note: For the camera to work, the site must be served over HTTPS or localhost.*

## 👥 Team Details
* **Team Leader:** Tanmay Goyal
* **Members:** Tanya Gupta, Daksh Bansal, Ayushi Chaudhary

---
*Built for Google Developer Group On Campus TechSprint.*
