# Rule Engine Application

This is a rule engine application that allows users to create, combine, and evaluate conditional rules using a dynamic interface. The backend is powered by FastAPI with MongoDB for data persistence, and the frontend is built using React with Vite.

## Features

- **Create Rules**: Allows users to create new rules based on attributes like age, department, income, and spend.
- **Evaluate Rules**: Users can evaluate rules against provided data inputs to determine eligibility.
- **Combine Rules**: Multiple rules can be combined to create complex logical conditions.
- **Frontend**: A responsive interface built with React and styled using Tailwind CSS.
- **Backend**: A FastAPI-based backend for managing rules, rule evaluation, and communication with MongoDB.

1. Navigate to the backend directory:

   ```bash
   cd backend
   Create a Python virtual environment and install dependencies:
   python -m venv venv
source venv/bin/activate  # For Windows, use venv\Scripts\activate
pip install -r requirements.txt
Set up MongoDB and configure your connection string in the .env file.

Start the FastAPI server:

bash
Copy code
uvicorn app.main:app --reload

Frontend
Navigate to the frontend directory:

bash
Copy code
cd frontend
Install the dependencies:

bash
Copy code
npm install
Run the frontend development server:

bash
Copy code
npm run dev
The app should now be running at http://localhost:3000.

API Endpoints
Create Rule: POST /rules/create
Evaluate Rule: POST /rules/evaluate
Combine Rules: POST /rules/combine

