Real-Time Chat Application 💬

A simple real-time chat application built using Python, Flask, and WebSockets.
This project allows multiple users to send and receive messages instantly without refreshing the page.

Features

- Real-time messaging between users
- Simple and responsive chat interface
- Instant message updates using WebSockets
- Lightweight Flask backend

Technologies Used

- Python
- Flask
- Flask-SocketIO
- HTML
- CSS
- JavaScript

Project Structure

realtime-chat-app/
│
├── templates/
│ └── index.html
│
├── static/
│ └── style.css
│
├── app.py
├── requirements.txt
└── README.md

How to Run the Project

1. Install dependencies

pip install -r requirements.txt

2. Run the application

python app.py

3. Open your browser and go to:

http://127.0.0.1:5000

How It Works

The application uses Flask-SocketIO to enable WebSocket communication between the client and server.
When a user sends a message, it is broadcast to all connected users instantly.

Future Improvements

- Add usernames
- Private messaging
- Message timestamps
- Better UI design

Author

Abinandhana
