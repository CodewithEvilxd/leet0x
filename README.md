# 🚀 LeetSys - System Design Learning Platform

> **Master System Design Concepts with Interactive Learning Dashboard**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Next.js](https://img.shields.io/badge/Next.js-15.2.0-black.svg?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0.0-blue.svg?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.0-06B6D4.svg?logo=tailwind-css)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-12.9.4-purple.svg)](https://www.framer.com/motion/)

## 📖 Overview

LeetSys is a comprehensive system design learning platform that helps developers master distributed systems, scalability, and architectural patterns through interactive problem-solving. The platform features a modern, responsive interface with progress tracking, detailed analytics, and guided learning paths.

## ✨ Key Features

### 🎯 **Interactive Learning System**
- **Structured Problem Sets**: 20+ system design questions across Easy, Medium, and Hard difficulty levels
- **Subtopic Breakdown**: Each question is broken down into manageable subtopics with detailed guidance
- **Progress Tracking**: Visual progress indicators and completion statistics
- **Real-time Updates**: Instant feedback and progress synchronization

### 📊 **Advanced Analytics Dashboard**
- **Progress Visualization**: Bar charts and pie charts showing completion rates by difficulty
- **Language Distribution**: Track programming languages used across different problems
- **Recent Activity**: Monitor your latest attempts and learning patterns
- **Performance Metrics**: Detailed statistics on completion rates and attempts

### 🎨 **Modern User Experience**
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Dark/Light Mode**: Built-in theme support with smooth transitions
- **Smooth Animations**: Framer Motion powered interactions and micro-animations
- **Intuitive Navigation**: Clean sidebar navigation with organized sections

### 🔧 **Developer-Friendly Features**
- **Local Storage**: Persistent progress tracking across sessions
- **Search & Filter**: Find specific questions by difficulty or search terms
- **Settings Management**: Customizable user preferences and avatar selection
- **Notification System**: Smart notifications for progress milestones

## 🏗️ System Design Questions Covered

### 🟢 **Easy Level (6 Questions)**
- **URL Shortener Service**: Base62 encoding, redirect handling, database schema
- **Chat Application**: WebSocket setup, message display, storage systems
- **File Upload System**: Upload APIs, storage management, access control
- **Task Manager**: CRUD operations, task organization, status tracking
- **Voting System**: Poll creation, vote submission, results display
- **Bookmark Manager**: URL storage, categorization, tagging system

### 🟡 **Medium Level (5 Questions)**
- **Distributed Cache**: LRU eviction, consistent hashing, Redis integration
- **API Rate Limiter**: Token bucket algorithm, Redis storage, middleware
- **News Feed System**: Content ranking, post storage, real-time updates
- **Job Queue System**: Queue management, worker processes, error handling
- **Notification System**: Multi-channel delivery, user preferences, rate limiting

### 🔴 **Hard Level (9 Questions)**
- **Search Engine**: Text tokenization, inverted index, TF-IDF scoring
- **Stock Trading System**: Order matching, market data, fault tolerance
- **Video Streaming**: Encoding, chunked streaming, CDN integration
- **Ride-Sharing Platform**: Driver matching, geolocation, pricing engine
- **Distributed File System**: Chunking, replication, consistency models
- **Recommendation Engine**: Collaborative filtering, content-based filtering
- **Real-Time Analytics**: Data ingestion, aggregation, visualization
- **Distributed Lock Manager**: Lock acquisition, deadlock detection
- **And more...**

## 🛠️ Technology Stack

### **Frontend Framework**
- **Next.js 15.2.0**: React framework with App Router and server-side rendering
- **React 18.3.1**: Modern React with hooks and concurrent features
- **TypeScript 5.0.0**: Type-safe development with strict type checking

### **Styling & UI**
- **Tailwind CSS 3.4.1**: Utility-first CSS framework for rapid UI development
- **Radix UI**: Accessible, unstyled UI components
- **Framer Motion 12.9.4**: Production-ready motion library for animations
- **Lucide React**: Beautiful, customizable icons

### **Data Visualization**
- **Recharts 2.15.3**: Composable charting library for React
- **Progress Indicators**: Custom progress bars and completion tracking

### **State Management**
- **React Context**: Built-in state management with localStorage persistence
- **Custom Hooks**: Reusable logic for questions and user data

### **Development Tools**
- **Biome**: Fast formatter and linter for JavaScript/TypeScript
- **ESLint**: Code quality and consistency enforcement
- **PostCSS**: CSS processing and optimization

## 📁 Project Structure

```
LeetSys/
├── src/
│   ├── app/                    # Next.js App Router pages
│   │   ├── ClientBody.tsx      # Main application component
│   │   ├── layout.tsx          # Root layout with providers
│   │   ├── page.tsx            # Home page
│   │   └── globals.css         # Global styles
│   ├── components/             # Reusable UI components
│   │   ├── ui/                 # Base UI components (Radix-based)
│   │   ├── dashboard-stats.tsx # Analytics dashboard
│   │   ├── questions-grid.tsx  # Question display grid
│   │   ├── question-card.tsx   # Individual question cards
│   │   ├── sidebar.tsx         # Navigation sidebar
│   │   └── ...                 # Other feature components
│   ├── data/                   # Data layer
│   │   ├── questions.ts        # Question types and utilities
│   │   └── more-questions.ts   # Question database
│   ├── lib/                    # Utilities and context
│   │   ├── context.tsx         # React context for state management
│   │   └── utils.ts            # Helper functions
│   └── hooks/                  # Custom React hooks
│       └── useUser.ts          # User management hook
├── public/                     # Static assets
├── package.json                # Dependencies and scripts
├── tailwind.config.ts          # Tailwind configuration
├── tsconfig.json               # TypeScript configuration
└── README.md                   # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- **Node.js**: Version 18.0.0 or higher
- **Package Manager**: Bun (recommended), npm, yarn, or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/CodewithEvilxd/leet0x.git
   cd leet0x
   ```

2. **Install dependencies**
   ```bash
   # Using Bun (recommended)
   bun install
   
   # Using npm
   npm install
   
   # Using yarn
   yarn install
   
   # Using pnpm
   pnpm install
   ```

3. **Start the development server**
   ```bash
   # Using Bun
   bun run dev
   
   # Using npm
   npm run dev
   
   # Using yarn
   yarn dev
   
   # Using pnpm
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

### Available Scripts

```bash
# Development
bun run dev          # Start development server with Turbopack
bun run build        # Build for production
bun run start        # Start production server

# Code Quality
bun run lint         # Run Biome linter and TypeScript checks
bun run format       # Format code with Biome
```

## 📊 Features in Detail

### **Question Management System**
- **Structured Learning**: Each system design question is broken down into 3-7 subtopics
- **Guided Implementation**: Detailed guidance for each subtopic with implementation hints
- **Progress Tracking**: Automatic progress calculation based on completed subtopics
- **Attempt History**: Track when you last worked on each question

### **Analytics Dashboard**
- **Difficulty-based Progress**: Visual progress bars for Easy, Medium, and Hard questions
- **Language Usage**: Pie chart showing programming languages used across problems
- **Recent Activity**: Timeline of your latest question attempts
- **Completion Statistics**: Real-time statistics on overall progress

### **User Experience Features**
- **Personalization**: Set your name and choose an avatar
- **Persistent Storage**: All progress is saved locally in your browser
- **Search Functionality**: Find questions by title or difficulty
- **Filter Options**: Filter questions by difficulty level
- **Responsive Design**: Works seamlessly across all device sizes

### **Technical Implementation**
- **Type Safety**: Full TypeScript implementation with strict type checking
- **Performance Optimized**: Efficient state management and minimal re-renders
- **Accessibility**: WCAG compliant components with proper ARIA labels
- **Modern React Patterns**: Hooks, Context API, and functional components

## 🎯 Learning Path

### **Beginner Track (Easy Questions)**
Start with fundamental system design concepts:
1. **URL Shortener**: Learn about encoding, redirection, and basic data storage
2. **Chat Application**: Understand real-time communication and WebSocket handling
3. **File Upload System**: Master file handling and storage systems
4. **Task Manager**: Practice CRUD operations and data management
5. **Voting System**: Learn about user interactions and data integrity
6. **Bookmark Manager**: Understand data organization and categorization

### **Intermediate Track (Medium Questions)**
Advance to distributed systems concepts:
1. **Distributed Cache**: Master caching strategies and consistent hashing
2. **API Rate Limiter**: Learn about traffic control and Redis integration
3. **News Feed System**: Understand content ranking and real-time updates
4. **Job Queue System**: Practice background processing and error handling
5. **Notification System**: Master multi-channel communication

### **Advanced Track (Hard Questions)**
Tackle complex distributed systems:
1. **Search Engine**: Build text processing and indexing systems
2. **Stock Trading System**: Master high-frequency trading and order matching
3. **Video Streaming**: Learn about media processing and CDN optimization
4. **Ride-Sharing Platform**: Understand real-time location services
5. **Distributed File System**: Master data distribution and replication
6. **And more advanced topics...**

## 🤝 Contributing

We welcome contributions to improve LeetSys! Here's how you can help:

### **Adding New Questions**
1. Fork the repository
2. Add new questions to `src/data/more-questions.ts`
3. Follow the existing question structure with subtopics and guidance
4. Submit a pull request

### **Improving Documentation**
1. Update README.md with new features or clarifications
2. Add inline code comments for complex logic
3. Create additional documentation for advanced features

### **Bug Reports & Feature Requests**
1. Open an issue on GitHub
2. Provide detailed description of the problem or feature
3. Include steps to reproduce (for bugs)
4. Suggest potential solutions (for features)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Radix UI** for accessible component primitives
- **Tailwind CSS** for the utility-first styling approach
- **Framer Motion** for smooth animations and transitions
- **Recharts** for beautiful data visualization
- **Lucide** for the comprehensive icon library

## 📞 Support

If you have any questions or need help with LeetSys:

- **GitHub Issues**: [Create an issue](https://github.com/CodewithEvilxd/leet0x/issues)
- **Documentation**: Check this README and inline code comments
- **Community**: Join our discussions in GitHub Discussions

---

**Happy Learning! 🚀**

*Master system design concepts one question at a time with LeetSys.*
