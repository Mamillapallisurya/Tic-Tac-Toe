Tic-Tac-Toe
Tic-Tac-Toe is a simple yet fun game that supports both local and online multiplayer modes. Play with your friends or challenge an opponent online!

Features
Local Multiplayer: Play with a friend on the same device.
Online Multiplayer: Connect with players online using WebSockets.
Real-time Gameplay: Smooth, real-time moves using Socket.io.
Persistent Game State: Game data is stored in MongoDB.
Installation
Prerequisites
Make sure you have the following installed:

Node.js
MongoDB
Steps
Clone the repository:
git clone https://github.com/sathwikv2005/Tic-Tac-Toe.git
cd Tic-Tac-Toe
Install dependencies:
npm install
Create a .env file in the root directory and add your MongoDB connection string:
MONGOURI=your_mongo_connection_string
Start the server:
npm start
Open the frontend in your browser:
http://localhost:6700
Usage
Open the game and select Local PvP to play with a friend on the same device.
Select Online PvP, enter a room ID, and share it with a friend to play online.
Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Real-time Communication: Socket.io
