🔥 FireAlertNX

FireAlertNX is an automated fire and hazard monitoring system designed for early detection, real-time threat identification, and instant emergency notification dispatch.

✨ Features

- Real-Time Detection: Live video stream analysis (computer vision/color-space or AI model) and sensor input processing for smoke and fire signatures in industrial zones.
- Automated Dispatch & Alerts: Immediate Web/Browser notifictications delivery.
- Monitoring & Status Display: Real-time visual dashboard indicating threat levels, timestamps, and camera feed telemetry.
- Event Logging: Persistent log of triggered alerts, detection confidence scores, and system operational states.

🛠️ Tech Stack

- Core / Backend: Python/jsx
- Computer Vision: NumPy
- Notification Services: Web/Browser notifictications
- Sensors / Hardware (if applicable): Arduino / Raspberry Pi integration via Thingsboard Cloud

🚀 Getting Started

1. Set Up Environment

Windows (CMD):

python -m venv venv
venv\Scripts\activate

macOS / Linux:

python3 -m venv venv
source venv/bin/activate

2. Install Dependencies
   
pip install -r requirements.txt

4. Configure Environment Variables
Create a .env file in the project root:

Code snippet
# Alert Configuration
ALERT_EMAIL=your_email@example.com
ALERT_PHONE=+1234567890

# API / Service Keys
TWILIO_ACCOUNT_SID=your_sid_here
TWILIO_AUTH_TOKEN=your_token_here

4. Run FireAlertNX

python main.py
