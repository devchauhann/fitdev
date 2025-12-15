# FitDev - Productivity Suite

A modern, pastel-themed productivity application designed for developers and students to manage tasks, track habits, set goals, and maintain focus through deep work sessions.

## 🌟 Features

### 📋 Task Management
- Create, edit, and delete tasks with priorities
- Filter tasks by status (All, Pending, Completed) and priority levels
- Visual indicators for overdue tasks
- Task procrastination tracking with push-to-tomorrow functionality
- Category-based organization (Study, Code, Personal)

### 🎯 Focus Mode
- Digital Pomodoro timer with customizable durations
- Immersive full-screen focus environment
- Ambient soundscapes (Rain, Forest, Cafe, White Noise)
- Real-time clock display during sessions
- Break timer functionality (5min and 15min options)
- XP reward system for completed focus sessions

### 📅 Calendar View
- Monthly calendar with task visualization
- Interactive date navigation
- Task indicators on dates with pending items
- Today highlighting

### 📊 Analytics & Tracking
- Weekly focus productivity charts
- Task distribution by category
- Procrastination heatmap visualization
- Daily habit tracking with streak counters
- Efficiency score calculations

### 🎯 Goal Management
- Long-term goal setting with progress tracking
- Visual progress bars
- Deadline management
- Goal completion tracking

### 👤 Profile Customization
- Avatar selection from multiple options
- Customizable display name and role/title
- Profile settings persistence
- Theme preferences

### 📱 Mobile Responsive
- Fully responsive design for all screen sizes
- Mobile-optimized navigation menu
- Touch-friendly interface
- Hamburger menu for mobile devices

## 🎨 Design

The application features a modern pastel color scheme with:
- **Background**: Warm cream (`#FDFBF7`)
- **Accent Colors**: Soft pastels including pink (`#FFD1DC`), blue (`#BDE0FE`), green (`#D1F7C4`), and purple (`#E0C3FC`)
- **Typography**: Nunito for general text, JetBrains Mono for timers
- **Icons**: Lucide icon library
- **Animations**: Smooth transitions and micro-interactions

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with Tailwind CSS framework
- **JavaScript (ES6+)**: Core functionality and interactivity
- **Tailwind CSS**: Utility-first CSS framework
- **Lucide Icons**: Modern icon library
- **Canvas Confetti**: Celebration animations
- **Local Storage**: Data persistence
- **Dicebear Avatars**: Avatar generation API

## 📁 Project Structure

```
fitdev/
├── index.html      # Initial version
└── README.md       # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server setup required - runs entirely in the browser

### Installation
1. Clone or download this repository
2. Open `main.html` in your preferred web browser
3. Start using the application immediately!

### First Time Setup
1. Navigate to the Settings page
2. Customize your profile with name, role, and avatar
3. Create your first task or goal
4. Explore the different views and features

## 💡 Usage Guide

### Creating Tasks
1. Click the "Add Task" button on the Dashboard
2. Fill in task title, category, priority, and due date
3. Click "Create Task" to save

### Focus Sessions
1. Go to the Focus Mode tab
2. Add tasks to your focus schedule or use existing ones
3. Click "Start" on any scheduled task
4. Use the full-screen timer with optional ambient sounds
5. Take breaks using the break buttons (5min/15min)

### Habit Tracking
1. Navigate to the Tracker tab
2. View your procrastination heatmap
3. Check off daily habits and build streaks
4. Add new habits using the "Add Habit" button

### Goal Setting
1. Visit the Goals tab
2. Click "New Goal" to create long-term objectives
3. Set deadlines and track progress
4. Update progress as you work toward your goals

## 🎮 Features Breakdown

### Dashboard
- Overview of pending and completed tasks
- Quick access to task creation
- Procrastination meter
- Upcoming events sidebar

### Focus Mode
- Customizable work session durations
- Full-screen immersive environment
- Soundscape options for concentration
- Break management system
- Progress tracking with XP rewards

### Calendar
- Monthly view with task visualization
- Interactive date selection
- Task distribution across dates

### Analytics
- Weekly productivity charts
- Category-based task distribution
- Visual progress indicators

### Tracker
- Procrastination heatmap (50-day view)
- Daily habit management
- Streak tracking system

### Goals
- Long-term objective setting
- Progress percentage tracking
- Deadline management
- Visual progress bars

### Settings
- Profile customization
- Avatar selection
- Name and role editing
- Data management options

## 🔧 Customization

### Adding New Task Categories
Modify the category options in the task creation modal:
```html
<select id="task-category">
    <option value="Study">Study</option>
    <option value="Code">Code</option>
    <option value="Personal">Personal</option>
    <!-- Add new categories here -->
</select>
```

### Modifying Color Scheme
Update the Tailwind color configuration:
```javascript
colors: {
    pastel: {
        bg: '#FDFBF7',
        pink: '#FFD1DC',
        blue: '#BDE0FE',
        // Add or modify colors
    }
}
```

### Adding Soundscapes
Extend the sound toggle functionality:
```javascript
function toggleSound(type) {
    // Add new sound types here
}
```

## 📱 Browser Compatibility

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

## 🤝 Contributing

Contributions are welcome! Please feel free to:
1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- **Tailwind CSS** for the utility-first CSS framework
- **Lucide** for the beautiful icon set
- **Dicebear** for avatar generation
- **Canvas Confetti** for celebration animations
- **Google Fonts** for typography (Nunito, JetBrains Mono)

## 🐛 Known Issues

- Sounds are simulated (no actual audio files)
- Data persistence is browser-dependent (local storage)
- Some features may require modern browser APIs

## 🔮 Future Enhancements

- [ ] Dark mode toggle
- [ ] Data export/import functionality
- [ ] Collaboration features
- [ ] Mobile app version
- [ ] Integration with external calendar services
- [ ] Advanced analytics and reporting
- [ ] Customizable themes
- [ ] Real ambient sound integration
- [ ] Cloud data synchronization

---

**Built with ❤️ for productivity enthusiasts**
