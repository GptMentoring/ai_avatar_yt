AI Agent & Web Application
This project includes a Python-based AI agent backend and a React-based frontend powered by LiveKit.

🚀 Getting Started
Follow these steps to set up and run both the backend and frontend.

📁 Backend Setup
1. Configure Environment Variables
Create a .env file inside the backend folder and add all required configuration values (such as API keys, environment settings, etc.).

2. Install Dependencies
Open a terminal and run:

bash
Copy
Edit
cd backend
pip install -r requirements.txt
3. Start Backend Services
Run the backend server and the AI agent:

nginx
Copy
Edit
python server.py
python agent.py dev
🌐 Frontend Setup (Website)
1. Configure LiveKit URL
In the website folder, create or update the .env file and add your LiveKit server URL.

2. Install Frontend Dependencies
Run the following commands:

bash
Copy
Edit
cd website
npm install
npm install @livekit/components-react @livekit/components-styles livekit-client --save
3. Start the Web Application
Start the development server:

arduino
Copy
Edit
npm run dev
✅ Prerequisites
Make sure the following are installed on your machine:

Python 3.x
Download Python

Node.js
Download Node.js

🛠 Notes
Run the backend and frontend in separate terminal windows.

Ensure that both .env files (backend/.env and website/.env) are correctly set up before starting the services.

📄 License
[Specify your license here, e.g., MIT License]
