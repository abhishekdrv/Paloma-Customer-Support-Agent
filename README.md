# Paloma AI Chatbot  

## 📌 Project Overview  
Paloma AI Chatbot ([Chatbot Link](ask.palomarealty.in))is an **AI-powered multilingual chatbot** developed for *Paloma The Grandeur*, a luxurious residential project by **Paloma Realty LLP**. The chatbot supports **text-based and AI voice-based** interactions, helping users inquire about apartments, amenities, and other project details in multiple languages.  

## 🚀 Features  
- **Multilingual Support:** Interact in multiple languages for a seamless user experience.  
- **Text & Voice-Based Conversations:** Choose between text-based chat or AI-driven voice responses.  
- **AI-Powered Responses:** Utilizes OpenAI's API for **context-aware** and **knowledge-based** query resolution.  
- **Pre-Trained Knowledge Base:** Provides **accurate information** based on Paloma Realty’s official data.  
- **24/7 Customer Support:** Enables potential buyers to get instant responses without human intervention.  

## 🛠 Tech Stack  
- **Frontend & Backend:** MERN Stack (MongoDB, Express.js, React.js, Node.js)  
- **APIs Used:**  
  - [OpenAI API](https://openai.com/) – For intelligent, context-based responses  
  - [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime) – For real-time AI voice-based conversations  

## 🏗 Setup & Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/abhishekdrv/Paloma-Customer-Support-Agent.git
cd Paloma-Customer-Support-Agent
```

### ⚛️ Running the Frontend (Next.js)

📁 Navigate to the frontend folder

```bash 
cd frontend
```

📦 Install dependencies

```bash 
npm install
```

⚙️ Set up environment variables

```bash
OPENAI_API_KEY=your_openai_api_key_here
```

🏃‍♂️ Start the development server

```bash
npm run dev
```

### 🐍 Running the Backend (Python – FastAPI)

📁 Navigate to the backend folder

```bash 
cd backend
```

🧪 Create a virtual environment and activate it

```bash
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows
```

Install Requirements.txt

```bash
pip install -r requirements.txt
```

⚙️ Set up environment variables

```bash
OPENAI_API_KEY=your_openai_api_key_here
VAPI_API_KEY=your_vapi_api_key_here
```

🏃‍♂️ Start the server

```bash
uvicorn main:app --reload
```
