# 📸 Invigil-Ease: E-Proctoring System
Invigil-ease is an e-proctoring system to monitor candidates during online exams. It detects suspicious activities, calculates a suspicion level, and generates a detailed report with timestamps of potential cheating incidents.

## ✨ Key Features

- ✅ **Real-Time Face & Eye Tracking**  
  Uses OpenCV and MediaPipe FaceMesh to monitor facial movements, eye direction, and head orientation.

- ✅ **Suspicion Score Algorithm**  
  Detects suspicious behavior such as:
  - Multiple faces in the frame
  - Frequent gaze deviation
  - Candidate absence from the screen

- ✅ **Automated PDF Reports**  
  Generates detailed exam reports with:
  - Timestamps of suspicious activities
  - Candidate metadata
  - Overall suspicion score

- ✅ **Flask Backend with SQL Integration**  
  Efficiently stores:
  - Candidate details
  - Session logs
  - Suspicion events

- ✅ **React Admin Dashboard**  
  Provides an intuitive dashboard for examiners to:
  - Monitor candidates
  - Review logs and reports
  - Take real-time decisions

## 🛠 Tech Stack

| Category       | Technology                |
|----------------|---------------------------|
| Frontend       | React.js                  |
| AI Processing  | OpenCV, MediaPipe FaceMesh|
| Backend        | Flask (Python)            |
| Database       | SQL                       |

## 🚀 How It Works

1. **Candidate logs in** through the React interface.
2. **AI monitoring** begins using webcam feed via FaceMesh.
3. **Real-time tracking** of eyes, face orientation, and presence.
4. **Suspicion level** is calculated and updated dynamically.
5. **PDF report** is generated and saved at the end of the session.

## Demo

![Image](https://github.com/user-attachments/assets/ec648c69-9cd7-4912-8d5e-ee7fb38385bb)

![Image](https://github.com/user-attachments/assets/a411a19d-e8ae-42f0-8d80-41af930b2f42)

![Image](https://github.com/user-attachments/assets/6e6ee0c8-93a7-4c44-b004-5492704153ae)

![Image](https://github.com/user-attachments/assets/e457adcb-85b2-4081-90ea-ee598c040084)

## 🧪 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/407raina/Invigil-ease.git
cd Invigil-ease


