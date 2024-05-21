# Chat Application

Welcome to the Chat Application project! This is a web-based chat application that utilizes WebSockets to enable real-time communication between users. Below you'll find all the information you need to get started with the project.


## Features
- Real-time messaging
- User authentication
- Private and group chats
- Typing indicators
- Message notifications
- Multiple Chat Rooms

## Technologies Used

### Frontend:
- HTML5
- CSS3
- JavaScript (ES6)

### Backend:
- Node.js
- WebSocket (ws library)

## Installation

### Prerequisites
Ensure you have the following installed on your machine:
- Node.js (version 14 or higher)
- npm (version 6 or higher)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/chat-application.git
   cd chat-application
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:
   ```env
   PORT=3500
   ```

4. **Start the server:**
   ```bash
   npm start
   ```

5. **Open the application:**
   Navigate to `http://localhost:3500` in your web browser.

## Usage

1. **Open the Application:**
   Navigate to `http://localhost:3500` in your web browser.

2. **Start Chatting:**
   - Enter a chat room name to create or join a room.
   - Send messages in real-time and see messages from other users instantly.

3. **Additional Features:**
   - View typing indicators when other users are typing.
   - Receive notifications for new messages.

## Project Structure

```
chat-application/
├── public/                 # Static assets
│   ├── index.html          # Main HTML file
│   └── styles.css          # CSS file
├── server/                 # Backend code (Node.js, WebSocket)
│   ├── index.js            # Entry point for the server
├── .gitignore              # Git ignore file
└── README.md               # Readme file
```

## Contributing

We welcome contributions to the Chat Application project! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
