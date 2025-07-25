🛠️ Setup Instructions
Add your information to the .env file in the backend folder.
This should include your API keys, model settings, and any other required variables.

Go to the backend folder:

bash
Copy
Edit
cd backend
Install the required Python packages:

nginx
Copy
Edit
pip install -r requirements.txt
Start the backend server:

nginx
Copy
Edit
python server.py
In a new terminal, start the AI agent:

nginx
Copy
Edit
python agent.py dev
Now go to the website folder and add your LiveKit URL to the .env file.

Navigate to the website folder:

bash
Copy
Edit
cd website
Install the frontend dependencies:

sql
Copy
Edit
npm install
npm install @livekit/components-react @livekit/components-styles livekit-client --save
Start the frontend:

arduino
Copy
Edit
npm run dev
✅ Requirements
Python 3.x installed

Node.js installed

LiveKit account with server URL

.env files configured correctly in both backend and website folders

