# NaanMudhalvan-Project

# Personalized Content Recommender Chatbot

A simple AI-powered chatbot that offers personalized content recommendations based on user interests. This project features a web-based frontend (`index.html`) and a Flask-based backend (`app.py`).


## 🧠 Features

- Understands user-stated interests (e.g., "I'm interested in technology, health").
- Offers tailored content suggestions across categories like Technology, Sports, Health, and Entertainment.
- Simple and interactive chat-based UI.
- Built with HTML/CSS/JS (frontend) and Flask (backend).

## 📁 Project Structure

.
├── index.html         # Frontend UI
├── app.py             # Flask backend server

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Flask

### Installation

1. Clone this repository:
   bash
   git clone https://github.com/yourusername/content-recommender-chatbot.git
   cd content-recommender-chatbot

2. Install dependencies:

   bash
   pip install flask flask-cors
   

3. Run the Flask app:

   bash
   python app.py

4. Open `index.html` in your browser or serve it via a local HTTP server.

## 📦 API Endpoint

### `/chat` – POST

**Request:**

json
{
  "user_id": "user_001",
  "message": "I'm interested in technology, health"
}

**Response:**

json
{
  "response": "Got it! You're interested in technology, health."
}

## 📌 Example Flow

1. User: "I'm interested in technology, health"
2. Bot: "Got it! You're interested in technology, health."
3. User: "Can you recommend me something?"
4. Bot: "Here are some recommendations: ..."

## 🛠️ Future Improvements

* NLP-based intent recognition.
* Persistent user profiles.
* Multilingual support.

## 🙌 Acknowledgments

Inspired by the need for smarter customer engagement and personalized recommendations.

## 🙌 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.



