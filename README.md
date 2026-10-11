ThirdEye AI 👁️

ThirdEye AI is an assistive vision project designed to help visually impaired people understand their surroundings through AI-powered object detection, hazard alerts, and voice guidance.

Features
Real-time object detection using the device camera
Hazard warnings with visual indicators
English and Hindi language support
Voice feedback for detected objects and hazards
Gemini-powered scene analysis
Supabase integration for navigation alerts
SOS interface for emergency assistance
Tech Stack
Frontend: Next.js, React, TypeScript, Tailwind CSS
Computer Vision: TensorFlow.js, COCO-SSD
Backend: Python, Flask
AI: Google Gemini
Database: Supabase
Getting Started
Requirements
Install Node.js and Python first.

Installation

Clone the repository and open its folder in Command Prompt.

npm install

Install the Python dependencies:

pip install -r requirements.txt
Configure the required API credentials and environment variables before running the application.

Run the Project

If start-app.bat is included, run:

start-app.bat
Otherwise, start the backend and frontend in separate terminals:

python agent_backend.py
npm run dev
Open http://localhost:3000 in your browser.

Note
ThirdEye AI is a hackathon prototype. Its warnings are intended to supplement, not replace, established mobility aids.

Future Scope
Improved hazard detection
More Indian languages
Offline AI processing
Wearable device integration
Voice Input commands to talk to ai and run the whole app
