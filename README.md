# Freelancer Learning and Growth Platform 🚀

A modern web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) designed to help freelancers enhance their skills and grow their careers. The platform provides a comprehensive learning environment with course management, user authentication, and profile customization features.

## 🌟 Features

### Authentication & User Management
- 🔐 Secure JWT-based authentication
- 🔑 Google OAuth integration for easy sign-in
- 👤 Custom user profiles with avatar support
- 🔒 Role-based access control (Freelancer, Client, Admin)

### Course Management
- 📚 Browse available courses
- ✍️ Enroll in courses
- 📊 Track learning progress
- 🎯 View enrolled courses in dashboard

### Profile Features
- 📸 Profile picture upload and management
- ✏️ Edit personal information
- 🔍 View and update professional details
- 📱 Responsive design for all devices

## 🛠️ Technology Stack

### Frontend
- React.js
- React Router for navigation
- Context API for state management
- Modern CSS with Flexbox/Grid
- Responsive design principles

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- Passport.js for Google OAuth
- Multer for file uploads

### Security
- Password hashing with bcrypt
- JWT token authentication
- Protected API routes
- Input validation and sanitization

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn
- Google OAuth credentials

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/freelancer-growth-platform.git
cd freelancer-growth-platform
```

2. Install server dependencies
```bash
cd server
npm install
```

3. Install client dependencies
```bash
cd ../client
npm install
```

4. Set up environment variables

Create a `.env` file in the server directory:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
CLIENT_URL=http://localhost:3000
```

5. Start the development servers

In the server directory:
```bash
npm run dev
```

In the client directory:
```bash
npm start
```

The application will be available at `http://localhost:3000`

## 📱 Responsive Design

The platform is fully responsive and optimized for:
- 💻 Desktop computers
- 📱 Mobile devices
- 📟 Tablets
- 🖥️ Various screen sizes

## 🔒 Security Features

- Password hashing
- JWT token validation
- Protected API endpoints
- Input sanitization
- CORS configuration
- Secure file upload handling

## 🎨 UI/UX Features

- Modern, clean interface
- Intuitive navigation
- Loading states and animations
- Error handling and user feedback
- Dark mode support
- Responsive components

## 🛣️ Roadmap

- [ ] Add course rating system
- [ ] Implement chat functionality
- [ ] Add payment integration
- [ ] Create mentor-mentee matching system
- [ ] Add portfolio showcase feature
- [ ] Implement real-time notifications

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- Google OAuth integration
- MongoDB Atlas
- React.js community
- Node.js community
- All contributors and supporters

## 📧 Contact

Your Name - your.email@example.com
Project Link: [https://github.com/yourusername/freelancer-growth-platform](https://github.com/yourusername/freelancer-growth-platform)

---
Made with ❤️ for the freelance community