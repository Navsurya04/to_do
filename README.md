# 📋 Task Progress Tracker by Navsurya

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![PWA](https://img.shields.io/badge/PWA-enabled-purple)

**The ultimate productivity app that fights procrastination at every level!**

A powerful, feature-rich task management Progressive Web App (PWA) with AI-powered insights, Focus Mode, dependency tracking, time blocking, and smart procrastination detection.

[🚀 **Live Demo**](https://your-username.github.io/task-tracker-pwa) | [📱 **Install App**](#installation)

---

## ✨ Features

### 🎯 **Focus Mode** - The Anti-Procrastination Trigger
- **Zero distractions**: Fullscreen mode showing only ONE task
- **25-minute Pomodoro timer** with notifications
- Automatically selects your highest priority task
- No choice paralysis - the app tells you what's next

### 🔗 **Dependency Mapping** - Task Logic
- Link tasks with prerequisites
- Dependent tasks stay hidden until prerequisites complete
- Prevents circular dependencies
- Keeps your to-do list realistic and logical

### ⏰ **Time Boxing** - Calendar Integration
- Drag-and-drop interface
- 24-hour daily calendar view
- Visual time allocation
- See if you actually have time for your tasks

### 🔥 **Procrastination Heatmap** - AI-Driven Insights
- Tracks task reschedules and edits
- Identifies patterns of avoidance
- **AI coaching** for problem tasks
- Get personalized action plans to break through blocks

### 🌙 **Auto-Shred** - End of Day Review
- Automatic cleanup at 11 PM
- 3 options: Reschedule, Archive, or Delete
- Prevents task debt buildup
- Start every day with a fresh, realistic list

### 📊 **Complete Task Management**
- ✅ Checkbox-based to-do lists
- 🎨 Priority levels (High/Medium/Low)
- 📁 Areas & Categories with color coding
- 📂 Subsections for detailed organization
- 📅 Interactive calendar with task indicators
- 📈 Multiple chart views (Line, Pie, Bar, Donut)
- 📊 Weekly progress tracking by area

### 🔔 **Smart Notifications**
- Customizable frequency (minutes or hours)
- Multiple notification types
- Browser notifications
- Configurable reminder settings

### 🤖 **AI-Powered Features**
- Weekly productivity insights
- Task-specific coaching
- Pattern recognition
- Personalized recommendations

### 💾 **Data & Privacy**
- 100% local storage
- No server uploads
- Works offline (PWA)
- All data stays on your device

---

## 🚀 Installation

### **Option 1: Install as PWA (Recommended)**

**On Mobile (Android/iOS):**
1. Visit the app URL in your browser
2. Tap the "Install" banner at the bottom
3. Or use browser menu: "Add to Home Screen"
4. App installs like a native app!

**On Desktop (Chrome/Edge):**
1. Visit the app URL
2. Click the install icon in the address bar
3. Or use browser menu: "Install Task Tracker"
4. Launches in standalone window!

### **Option 2: Clone & Host Locally**

```bash
# Clone the repository
git clone https://github.com/your-username/task-tracker-pwa.git

# Navigate to directory
cd task-tracker-pwa

# Open in browser
# Option A: Use a local server
python -m http.server 8000
# Then visit http://localhost:8000

# Option B: Just open index.html in your browser
```

### **Option 3: GitHub Pages (Free Hosting)**

1. Fork this repository
2. Go to Settings → Pages
3. Select "main" branch as source
4. Your app will be live at: `https://your-username.github.io/task-tracker-pwa`

---

## 📖 How to Use

### **Getting Started**
1. **Create Areas**: Click "+ Add Task" → Add Area (e.g., Work, Personal, Health)
2. **Add Tasks**: Fill in name, area, priority, and date
3. **Set Dependencies**: Use "🔗 Dependencies" to link related tasks
4. **Start Working**: Click "🎯 FOCUS MODE" to begin!

### **Focus Mode Workflow**
```
1. Click "🎯 FOCUS MODE"
2. See your highest priority task in fullscreen
3. Start 25-minute Pomodoro timer
4. Work without distractions
5. Mark complete or skip to next
6. Repeat!
```

### **Time Blocking**
```
1. Click "⏰ Time Block"
2. Drag tasks from left panel
3. Drop onto time slots (e.g., 2:00 PM)
4. Set duration
5. See your realistic daily schedule
```

### **Procrastination Analysis**
```
1. Use app normally for a week
2. Click "Analyze My Patterns"
3. See tasks you keep rescheduling
4. Get AI coaching for problem tasks
5. Break big tasks into smaller steps
```

---

## 🛠️ Technical Stack

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **Charts**: Chart.js
- **AI**: Anthropic Claude API (optional)
- **Storage**: LocalStorage
- **PWA**: Service Workers, Manifest
- **Architecture**: Pure client-side, no backend needed

---

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome/Edge (Desktop) | ✅ Full support + Install |
| Chrome (Android) | ✅ Full support + Install |
| Safari (iOS) | ✅ Full support + Add to Home Screen |
| Firefox | ✅ Works (no install prompt) |
| Safari (macOS) | ✅ Works (limited PWA features) |

---

## 🎨 Screenshots

### Main Dashboard
![Dashboard](screenshot-dashboard.png)

### Focus Mode
![Focus Mode](screenshot-focus.png)

### Calendar View
![Calendar](screenshot-calendar.png)

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Navsurya**

- Created with passion for productivity
- Built to fight procrastination
- Designed for real-world use

---

## 🙏 Acknowledgments

- Chart.js for beautiful visualizations
- Tailwind CSS for rapid styling
- Anthropic Claude for AI capabilities
- The productivity community for inspiration

---

## 📮 Support

If you find this app helpful:
- ⭐ Star this repository
- 🐛 Report bugs via Issues
- 💡 Suggest features via Issues
- 📢 Share with friends who struggle with productivity!

---

## 🗺️ Roadmap

- [ ] Export/Import tasks (JSON, CSV)
- [ ] Sync across devices (optional cloud)
- [ ] Habit tracking integration
- [ ] Team collaboration features
- [ ] Mobile-specific optimizations
- [ ] More AI coaching scenarios
- [ ] Gamification & achievements

---

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/your-username/task-tracker-pwa?style=social)
![GitHub forks](https://img.shields.io/github/forks/your-username/task-tracker-pwa?style=social)

---

**Made with ❤️ by Navsurya**

*"Stop procrastinating. Start accomplishing."*
