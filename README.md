# EchoChat

Welcome to EchoChat, a real-time chatting web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) along with Socket.IO for seamless real-time communication. This project aims to provide users with an intuitive platform to engage in instant messaging while leveraging modern web technologies.

---

## Project Overview 📚:

EchoChat offers users a platform for secure and real-time communication, equipped with advanced features to enhance their chatting experience.

---

## Features 🖼️:

### Secure Login & Registration with JWT ⚠️
EchoChat provides secure login and registration with JWT token authentication. Users can optionally personalize their accounts with profile pictures, enhancing their experience on the platform.

### Real-Time User Status and Typing Indicators 🤙
EchoChat shows real-time user online status and typing indicators in chat, enhancing interaction and communication on the platform.

### Group Chat 👨‍👩‍👦‍👦
EchoChat allows users to create groups and engage in group chats, enabling seamless collaboration and communication among multiple users in real-time.

### Real-Time Notifications 🔔
EchoChat provides instant notifications in real-time, keeping users updated on new messages for timely communication and engagement.

### Dark Mode 🌚
EchoChat offers a sleek and modern dark mode option, providing users with a comfortable viewing experience in low-light environments and reducing eye strain during extended usage.

### Responsive Mobile Design 📱
EchoChat boasts a responsive mobile design, ensuring seamless access and usability across various devices and screen sizes. Users can enjoy the full functionality of the application on their smartphones or tablets, enhancing accessibility and convenience on the go.

---

## Tech-Stack 💻:

### Frontend
- React.js
- Framer motion (for animations)

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Real-Time Communication
- Socket.IO

### Authentication
- JWT (JSON Web Tokens)

---

## Installation Setup 🧰

To run this project locally, you need to follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/vibhorarya12/EchoChat-MERN-CHAT-APP.git
```

### 2. Install Dependencies for Client
Navigate to the client folder:
```bash
cd client/echochat
```
Install dependencies using npm:
```bash
npm install
```

### 3. Environment Variables Setup for Client
Navigate to the client directory:
```bash
cd client/echochat
```
Create a new `.env` file:
```bash
touch .env && echo REACT_APP_API_KEY=http://localhost:5000 > .env
```

### 4. Install Dependencies for Server
Navigate to the server folder:
```bash
cd ../..
cd server
```
Install dependencies using npm:
```bash
npm install
```

### 5. Environment Variables Setup for Server
Within the server directory, create a new `.env` file:
```bash
touch .env
```
Open the `.env` file and add these variables:
```
PORT = 5000
DATABASE = Your MongoDb atlas connection string here
JWT = Awz76234Screet@77
```
⚠️ Note: For the `DATABASE` variable, a MongoDB Atlas connection string is required. Please refer to [MongoDB Atlas Connection String Guide](https://www.mongodb.com/docs/guides/atlas/connection-string/).

### 6. Run Server
Start the server:
```bash
npm start
```

### 7. Run Client Application
Navigate to the client directory:
```bash
cd ../client/echochat
```
Start the React app:
```bash
npm start
```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

---

## 📧 Contact

For any questions or feedback, feel free to contact me via this repository.

---

### 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

