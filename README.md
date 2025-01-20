<div align="center">

# PrepPal

</div>

PrepPal is your ultimate AI-powered interview preparation assistant. Whether you're gearing up for technical, behavioral, or industry-specific interviews, PrepPal provides personalized and interactive mock interviews to help you ace the big day.

## Features

- **Interactive Mock Interviews**: Simulates real interview scenarios with dynamic question-and-answer sessions.
- **AI Feedback**: Receive detailed feedback on your responses, including strengths and areas for improvement.
- **Customizable Question Sets**: Focus on technical, behavioural, or domain-specific questions.
- **Progress Tracking**: Monitor your improvement over time with insightful analytics.
- **24/7 Accessibility**: Practice interviews anytime, anywhere.


## Technologies Used

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Flask, Python
- **API's**: OpenAI API, GCP, Cohere API
- **Libraries**: OpenCV, 
- **Database**: SQLite, SQLAlchemy


## Installation

To run PrepPal locally, follow these steps:

### Running the Frontend:

1. Clone the repository:
   ```bash
   git clone https://github.com/Ajith-Bondili/ai_interviewer
   ```

2. Navigate to the project directory:
   ```bash
   cd frontend
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and go to `http://localhost:5173` to use the frontend of PrepPal.

### Running the Backend:

6. Create a Flask virtual environment:

   ```bash
   virtualenv flask
   cd flask
   source bin/activate
   cd ..
   pip install -r requirements.txt
   ```

7. After installing all modules, initialize the backend:

   ```bash
   cd backend
   python3 app.py
   ```

## Environment Variables

To run PrepPal, you need to configure the following environment variables in a `.env` file:

```env
OPENAI_API_KEY="your openai-api key"
COHERE_API_KEY="your cohere-api key"
```

## Live Demo
This is the Live Demo of our [submission](https://dorahacks.io/buidl/21711) to UofTHacks 12:
armaan add link to full video

### Give PrepPal a try and take your interview preparation to the next level!
