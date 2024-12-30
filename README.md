# Realtime Chat Application


## 🌟 Overview
A modern, responsive, and feature-rich realtime chat web application designed and built by **Abdelrhman Fikri**. The app enables users to communicate in real-time with:

- Authentication & authorization
- User profiles
- Responsive design
- Real-time messaging with status updates

[View Repository](https://github.com/abdelrhman2148/Realtime-Chat-App)

[Live App](https://chitchatapp.abdelrhmanfikri.tech/)

---

## 🎯 Features

- **Tech Stack**: MERN (MongoDB, Express, React, Node.js) + Socket.IO + TailwindCSS + Daisy UI
- **Authentication & Authorization**: Secured with JWT
- **Realtime Messaging**: Powered by Socket.IO for instant communication
- **Online User Status**: Display online/offline status dynamically
- **Global State Management**: Managed seamlessly with Zustand
- **Error Handling**: Robust client & server-side error management
- **Professional Deployment**: Hosted for FREE using AWS EC2 with Nginx

---

## 🚀 Getting Started

### Prerequisites

- **Node.js**: >= 14.x
- **MongoDB Atlas Account**
- **Cloudinary Account** for image uploads

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/abdelrhman2148/Realtime-Chat-App.git
   cd Realtime-Chat-App
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:

   Create a `.env` file in the root directory and add:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   PORT=5001
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   NODE_ENV=development
   ```

### Building and Running the Application

1. Build the application:
   ```bash
   npm run build
   ```

2. Start the application:
   ```bash
   npm start
   ```

The application will be available at `http://localhost:5001`.

---

## 🛠️ Development Timeline

1. **Backend Setup**: Basic server configuration with Express.js
2. **Database Integration**: MongoDB Atlas setup
3. **Authentication**: Signup, Login, Logout, and JWT integration
4. **UI Development**: Pages for signup, login, profile, settings, and home
5. **Socket.IO Integration**: Real-time messaging implementation
6. **Deployment**: AWS EC2 instance with Nginx configuration
7. **Testing**: End-to-end testing and final optimizations

---

## 🎃 Highlights

- 🌟 **Tech Stack**: MERN + Socket.IO + TailwindCSS + Daisy UI
- 🎃 **Authentication**: JWT-based user authentication and authorization
- 👾 **Real-time Messaging**: Implemented using Socket.IO
- 🚀 **Online User Status**: Live updates for user presence
- 👌 **Global State Management**: Zustand for efficient state handling
- 🐞 **Error Handling**: Server & client-side error handling mechanisms
- ⭐ **Pro Deployment**: Hosted on AWS EC2 for free!
- ⏳ **And much more!**

---

## 🤔 Challenges Faced

- Setting up AWS EC2 with Nginx
- Implementing real-time communication with Socket.IO
- Debugging and ensuring consistent error handling

---

## 📘 Lessons Learned

- Advanced deployment techniques using AWS and Nginx
- Real-time communication with WebSockets
- Debugging complex server and client interactions

---

## 🛠️ Areas for Improvement

- Optimize performance with caching mechanisms
- Enhance user experience with notifications and multimedia sharing
- Improve scalability for larger user bases

---

## 📈 Next Steps

- Add support for multimedia file sharing in chats
- Implement server-side rendering for improved performance
- Integrate OAuth for secure third-party authentication

---

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments
Special thanks to the ALX SE Pathway for providing this opportunity to grow and learn.

---

## 🌟 Conclusion
This project has been a transformative experience, showcasing skills in full-stack development, deployment, and real-time communication. Thank you for the opportunity to build, learn, and innovate!

---

## 📺 Tutorial
Watch the [YouTube Tutorial](https://youtu.be/F4TyMFqIMj0) for step-by-step guidance on building and deploying the app.
