# Socket.IO Chat Application

This is a simple chat application built with Socket.IO and Express.js. It allows users to communicate in real-time.

## Features
- Real-time chat messaging
- Typing indicators
- User nicknames
- User connection and disconnection notifications
- Private messaging

## Access Server

   ```bash
   http://161.35.107.154:3000/
   ```
## Messaging
- When you open the application, you will be prompted to enter your nickname.
- Type your message in the input field and press "Send" to broadcast it to all connected users. Your message will be prefixed with your nickname (e.g., You: Hello! for ypurself and YourNickName: Hello! for other users).
- All users will receive your message and see it in the chat window.
- To send a private message to another user, use the command /msg [nickname] [message].
- For example, to send a message "Hello" to a user named "Alice", you would type /msg Alice Hello.

## Note
- Access the server in multiple tabs to create simulation of a chat app between multiple users.
