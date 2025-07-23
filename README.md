# letsChat


chat-app/
├── server/
│   ├── config/
│   │   ├── db.js
│   │   └── config.js
│   ├── controllers/
│   │   ├── auth.controller.js
│   │   ├── message.controller.js
│   │   └── user.controller.js
│   ├── middleware/
│   │   ├── auth.middleware.js
│   │   └── error.middleware.js
│   ├── models/
│   │   ├── message.model.js
│   │   ├── user.model.js
│   │   └── chat.model.js
│   ├── routes/
│   │   ├── auth.routes.js
│   │   ├── message.routes.js
│   │   └── user.routes.js
│   ├── services/
│   │   ├── encryption.service.js
│   │   ├── socket.service.js
│   │   └── token.service.js
│   ├── utils/
│   │   ├── constants.js
│   │   ├── helpers.js
│   │   └── validators.js
│   ├── .env
│   ├── app.js
│   ├── server.js
│   ├── package.json
│   └── README.md


chat-app/
├── client/
│   ├── public/
│   │   ├── index.html
│   │   └── assets/
│   │       ├── images/
│   │       └── fonts/
│   ├── src/
│   │   ├── components/
│   │   │   ├── auth/
│   │   │   │   ├── Login.jsx
│   │   │   │   └── Register.jsx
│   │   │   ├── chat/
│   │   │   │   ├── ChatWindow.jsx
│   │   │   │   ├── Message.jsx
│   │   │   │   ├── MessageList.jsx
│   │   │   │   ├── Sidebar.jsx
│   │   │   │   └── ChatInput.jsx
│   │   │   └── common/
│   │   │       ├── Button.jsx
│   │   │       ├── Input.jsx
│   │   │       └── Modal.jsx
│   │   ├── context/
│   │   │   ├── AuthContext.jsx
│   │   │   └── ChatContext.jsx
│   │   ├── hooks/
│   │   │   ├── useAuth.js
│   │   │   └── useChat.js
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── Chat.jsx
│   │   │   └── Profile.jsx
│   │   ├── services/
│   │   │   ├── api.js
│   │   │   ├── auth.js
│   │   │   ├── chat.js
│   │   │   └── encryption.js
│   │   ├── utils/
│   │   │   ├── constants.js
│   │   │   ├── helpers.js
│   │   │   └── validators.js
│   │   ├── App.jsx
│   │   ├── index.jsx
│   │   └── index.css
│   ├── .env
│   ├── package.json
│   └── README.md
