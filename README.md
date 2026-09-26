# 🎌 Animesnax - Premium Anime Streaming Platform

A modern, feature-rich anime streaming website with a powerful video player, extensive anime database, and user-friendly interface.

## ✨ Features

### 🎬 Video Player
- HLS/MP4 streaming support
- Quality selection (720p, 1080p, 4K)
- Playback speed control
- Progress bar with chapter markers
- Subtitle support
- Fullscreen mode
- Picture-in-Picture

### 📚 Anime Database
- Thousands of anime titles
- Detailed anime information (synopsis, genres, rating, cast)
- Episode management
- Series & Movie support
- Multiple language support

### 👤 User Features
- User authentication & registration
- Watch history tracking
- Bookmarks/Favorites
- Custom watchlist
- Personalized recommendations
- User profiles

### 🔍 Discovery & Search
- Advanced search filters
- Genre-based filtering
- Rating/popularity sorting
- Trending anime section
- New releases
- Seasonal shows

### 🎨 UI/UX
- Responsive design (Mobile, Tablet, Desktop)
- Dark/Light theme toggle
- Beautiful animations
- Smooth transitions
- Accessibility compliant

## 🛠️ Tech Stack

### Frontend
- **React 18** - UI Framework
- **Tailwind CSS** - Styling
- **Redux/Zustand** - State Management
- **HLS.js** - Video streaming
- **Axios** - HTTP Client
- **React Router** - Navigation

### Backend
- **Node.js** - Runtime
- **Express.js** - Web Framework
- **MongoDB** - Database
- **JWT** - Authentication
- **Multer** - File uploads

### DevOps
- **Docker** - Containerization
- **GitHub Actions** - CI/CD

## 📁 Project Structure

```
Animesnax/
├── frontend/              # React application
│   ├── src/
│   │   ├── components/   # Reusable components
│   │   ├── pages/        # Page components
│   │   ├── stores/       # State management
│   │   ├── hooks/        # Custom hooks
│   │   ├── utils/        # Utility functions
│   │   └── styles/       # Tailwind & CSS
│   └── public/
├── backend/               # Express API
│   ├── models/           # MongoDB schemas
│   ├── routes/           # API routes
│   ├── controllers/      # Route handlers
│   ├── middleware/       # Auth & validation
│   ├── config/           # Configuration
│   └── utils/            # Helper functions
├── docker-compose.yml    # Docker setup
├── .env.example          # Environment variables
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v16+)
- MongoDB
- npm/yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/noobabhi716-dev/Animesnax.git
cd Animesnax
```

2. Install dependencies
```bash
# Frontend
cd frontend && npm install

# Backend
cd ../backend && npm install
```

3. Setup environment variables
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Start development servers
```bash
# Terminal 1 - Backend
cd backend && npm run dev

# Terminal 2 - Frontend
cd frontend && npm start
```

## 📖 API Documentation

API endpoints for anime, episodes, users, and streaming.

## 🤝 Contributing

Contributions are welcome! Please read our contributing guidelines.

## 📄 License

MIT License - feel free to use this project

## 📞 Support

For issues and questions, please open an issue on GitHub.

---

Made with ❤️ by Noobabhi716
