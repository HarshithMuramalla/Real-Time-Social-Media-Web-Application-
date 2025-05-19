# Real-Time Social Media Web Application

A modern, responsive social media platform built with React.js and Node.js, featuring real-time updates, user authentication, and interactive social features.

![Social Media App Preview](https://via.placeholder.com/800x400?text=Social+Media+App+Preview)

## ✨ Features

- 🔐 User Authentication (Signup/Login)
- 👥 User Profiles and Friend System
- 💬 Real-time Chat and Notifications
- 📱 Responsive Design for all devices
- 📱 News Feed with Live Updates
- ⚡ Optimized Performance with React
- 🔄 Real-time Updates with WebSockets

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm (v6 or later) or yarn
- MongoDB (for the backend database)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/HarshithMuramalla/Real-Time-Social-Media-Web-Application-.git
   cd Real-Time-Social-Media-Web-Application
   ```

2. **Install dependencies**
   ```bash
   # Install client dependencies
   npm install
   
   # Install server dependencies
   cd Server
   npm install
   cd ..
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory with the following variables:
   ```
   REACT_APP_API_URL=http://localhost:5000
   ```
   
   Create another `.env` file in the `Server` directory:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```

4. **Start the development servers**
   In the root directory, run:
   ```bash
   # Start the frontend
   npm start
   
   # In a new terminal, start the backend
   cd Server
   npm start
   ```

5. **Open your browser**
   The application will be available at [http://localhost:3000](http://localhost:3000)

## 📱 Features in Detail

### User Authentication
- Secure JWT-based authentication
- Protected routes
- Password hashing

### Social Features
- Add/remove friends
- Real-time friend requests
- User profiles with customizable information

### Real-time Updates
- Live notifications
- Instant messaging
- Real-time post updates

## 🛠️ Built With

- **Frontend**: React.js, React Router, Context API, CSS Modules
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Real-time**: Socket.io
- **Authentication**: JWT (JSON Web Tokens)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Create React App for the project setup
- All contributors and open-source libraries used

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run server`

Starts the backend server in development mode with nodemon for automatic restarts.

### `npm run dev`

Runs both the frontend and backend in development mode concurrently.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

Harshith Muramalla - [@your_twitter](https://twitter.com/your_twitter) - your.email@example.com

Project Link: [https://github.com/HarshithMuramalla/Real-Time-Social-Media-Web-Application-](https://github.com/HarshithMuramalla/Real-Time-Social-Media-Web-Application-)

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- [Create React App](https://create-react-app.dev/)
- [React Icons](https://react-icons.github.io/react-icons/)
- [Socket.IO](https://socket.io/)
- [MongoDB](https://www.mongodb.com/)
- [Express](https://expressjs.com/)
