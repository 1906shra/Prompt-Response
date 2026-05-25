# HabitFlow — Modern Habit Tracker Application
#dployed Link:https://habittracker234.netlify.app/
> A premium, scalable, and production-ready Habit Tracker application designed to help users build positive routines, improve productivity, maintain consistency, and achieve long-term personal growth.

---

#  Overview

HabitFlow is a modern full-stack productivity platform that combines:

- Habit Tracking
- Productivity Analytics
- Gamification
- Social Accountability
- AI-Powered Suggestions
- Smart Notifications

The application is designed to provide a world-class SaaS experience across desktop and mobile devices.

---

#  Features

##  Core Features

- Create & Manage Habits
- Track Daily Progress
- Streak Monitoring
- Productivity Analytics
- Smart Notifications
- Gamification System
- Community & Social Features
- AI Productivity Suggestions
- Offline Support (PWA)
- Responsive Design
- Dark & Light Themes

---

# 🛠️ Tech Stack

## Frontend

- React.js + Vite
- Tailwind CSS
- Framer Motion
- React Router DOM
- Axios
- Context API / Redux Toolkit
- Recharts / Chart.js
- React Hook Form

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt
- Nodemailer

## Deployment

- Frontend → Vercel
- Backend → Render / Railway
- Database → MongoDB Atlas

---

# 🎨 UI/UX Features

- Premium Modern Interface
- Glassmorphism & Neumorphism
- Smooth Animations
- Fully Responsive Design
- Loading Skeletons
- Elegant Typography
- Accessibility Support
- Touch-Friendly Navigation

---

# 📄 Application Pages

---

## 1️⃣ Landing Page

### Sections

- Hero Section
- Features Showcase
- Testimonials
- Pricing Plans
- Footer

### Features

- Smooth Scrolling
- Responsive Navbar
- CTA Buttons
- Framer Motion Animations

---

## 2️⃣ Authentication Page

### Features

- Login & Signup
- Remember Me
- Forgot Password
- Social Login
- JWT Authentication
- Password Hashing
- Protected Routes
- Form Validation

---

## 3️⃣ User Dashboard

### Dashboard Widgets

- Habit Summary
- Streak Cards
- Productivity Score
- Motivation Quotes
- Calendar Widget

### Functionalities

- Real-Time Updates
- Interactive Cards
- Animated Statistics

---

## 4️⃣ Habit Management Page

### Features

- Create Habit
- Edit Habit
- Delete Habit
- Archive Habit
- Mark Completion
- Drag & Drop Reordering
- Search & Filtering

### Categories

- Fitness
- Study
- Meditation
- Reading
- Water Intake
- Sleep

---

## 5️⃣ Habit Analytics Page

### Analytics Features

- Weekly Progress Charts
- Monthly Trends
- Category Analysis
- Productivity Heatmaps
- Smart Insights Engine

---

## 6️⃣ Calendar & Timeline Page

### Features

- Interactive Calendar
- Timeline View
- Habit History
- Progress Records
- Date Filters

---

## 7️⃣ Gamification & Rewards Page

### Features

- Achievement Badges
- XP System
- Coins & Rewards
- Leaderboards
- Challenges

---

## 8️⃣ Reminder & Notification Page

### Features

- Daily Reminders
- Weekly Reminders
- Push Notifications
- Email Notifications
- Notification History

---

## 9️⃣ Community & Social Page

### Features

- Community Feed
- Likes & Comments
- Habit Groups
- Public Profiles
- Social Challenges

---

## Settings & Profile Page

### Features

- Editable User Profile
- Theme Settings
- Privacy Controls
- Change Password
- Export User Data
- Backup Progress

---

#  Security Features

- JWT Authentication
- Password Hashing
- Rate Limiting
- Secure Headers
- Input Sanitization
- XSS Protection
- MongoDB Validation

---

# 📊 Backend APIs

## Authentication APIs

- Register
- Login
- Logout
- Refresh Token
- Forgot Password
- Reset Password

## Habit APIs

- Create Habit
- Update Habit
- Delete Habit
- Fetch Habits
- Mark Completion

## Analytics APIs

- Weekly Reports
- Monthly Reports
- Streak Analysis

## Notification APIs

- Create Reminders
- Send Notifications
- Fetch Notification History

---

#  Database Schema

## User Schema

```js
{
  username,
  email,
  password,
  avatar,
  bio,
  achievements,
  streak,
  settings
}
```

## Habit Schema

```js
{
  title,
  description,
  category,
  frequency,
  completedDates,
  streakCount,
  reminders,
  difficulty
}
```

## Notification Schema

```js
{
  message,
  type,
  userId,
  readStatus,
  scheduledTime
}
```

---

#  Recommended Folder Structure

## Frontend

```bash
src/
├── components/
├── pages/
├── context/
├── hooks/
├── services/
├── routes/
├── layouts/
├── utils/
├── assets/
└── animations/
```

## Backend

```bash
server/
├── controllers/
├── routes/
├── middleware/
├── models/
├── config/
├── utils/
├── services/
└── validators/
```

---

#  Advanced Features

## AI Productivity Suggestions

- Habit Recommendations
- Productivity Improvement Suggestions
- Streak Break Prediction
- Productivity Pattern Analysis

## Offline Support

- PWA Functionality
- Local Caching
- Offline Synchronization

## Accessibility

- Keyboard Navigation
- Screen Reader Support
- High Contrast Mode

---

#  Performance Optimization

- Lazy Loading
- Code Splitting
- Optimized API Calls
- Image Optimization
- Caching Strategies

---

#  Admin Panel Features

## Dashboard

- User Statistics
- Active Users
- Habit Trends
- Revenue Analytics

## Management

- User Management
- Community Moderation
- Report Handling
- Analytics Overview

---

#  Additional Enhancements

- Animated Onboarding
- Progress Rings
- Confetti Celebration Effects
- Sound Effects Toggle
- Focus Mode
- Pomodoro Timer
- Habit Templates
- Smart Recommendations
- Daily Summaries
- Email Productivity Reports

---

#  Mobile Responsiveness

The application is optimized for:

- Mobile Devices
- Tablets
- Desktop Screens
- Touch Interactions
- Responsive Charts

---

#  Animations

Framer Motion is used for:

- Page Transitions
- Hover Effects
- Modal Animations
- Sidebar Transitions
- Loading States
- Animated Counters

---

#  Installation

## Clone Repository

```bash
git clone https://github.com/1906shra/habitflow
cd habitflow
```

---

## Frontend Setup

```bash
cd client
npm install
npm run dev
```

---

## Backend Setup

```bash
cd server
npm install
npm run dev
```

---

#  Environment Variables

## Backend `.env`

```env
PORT=5000

MONGODB_URI=your_mongodb_connection

JWT_SECRET=your_jwt_secret

EMAIL_USER=your_email
EMAIL_PASS=your_email_password

CLIENT_URL=http://localhost:5173
```

---

#  Deployment

## Frontend

Deploy on:

- Vercel

## Backend

Deploy on:

- Render
- Railway

## Database

Use:

- MongoDB Atlas

---

#  Expected Quality Standards

HabitFlow is designed to:

- Follow Clean Architecture Principles
- Use Scalable & Reusable Components
- Maintain High Performance
- Deliver Premium User Experience
- Follow Industry Best Practices

---

#  Final Goal

HabitFlow aims to become a world-class productivity platform combining:

- Productivity
- Motivation
- Analytics
- Social Engagement
- AI-Powered Insights
- Modern UI/UX
- Scalable Architecture

---

#  License

MIT License

---

#  Author

Developed with  by Shraddha Tripathi
