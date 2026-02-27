# 🏋️ 90-Day Calisthenics Mastery Tracker

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)

> A beautiful, offline-first web app for tracking your 90-day calisthenics journey. No installation required. No internet needed. Just open and start training.

**[🚀 Try it now!](https://agadrapin.github.io/calisthenics-90-day-tracker/)**

---

## ✨ Features

### **Core Functionality**
- 🎯 **4 Structured Workout Days** - Core, Hips, Hanging, Skills with detailed exercise lists
- 📊 **90-Day Progress Tracker** - Baseline testing every 4 weeks with auto-calculated targets
- 🎖️ **Skill Milestones** - Track achievements across 5 progressive levels (Beginner → Elite)
- 📅 **Weekly Training Log** - Dropdown selects for easy workout logging (A/B/C/D/R for rest)
- 📈 **Progress Charts** - Visual analytics powered by Chart.js
- 💪 **16 Essential Exercises** - Complete guide with filterable cards by difficulty level
- 🔄 **Recovery & Nutrition** - Personalized protein/hydration targets based on your weight (metric)

### **Smart Features**
- ✅ **Auto-save Everything** - All data saves to browser localStorage as you type
- 📥 **Export/Import Data** - Download backups as JSON, restore anytime
- 📱 **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
- 🌙 **Dark Theme Design** - Easy on the eyes with modern gradient UI
- 🔒 **100% Offline** - Works without internet after first load
- 🚀 **No Installation** - Just open the HTML file and go
- 🔥 **Streak Tracking** - Rest days (R) don't break your streak!
- 📍 **Auto-updates Dates** - Tab updates when reopened (no refresh needed)

---

## 🚀 Quick Start

### **Option 1: Use Online (Recommended)**

1. **[Click here to open the tracker](https://agadrapin.github.io/calisthenics-90-day-tracker/)**
2. Bookmark the page for easy access
3. That's it! Start training 💪

### **Option 2: Download & Use Locally**

1. **Download the file:**
   - Click the green **"Code"** button above
   - Select **"Download ZIP"**
   - Extract the ZIP file
   - OR download `index.html` directly

2. **Open the tracker:**
   - Navigate to the extracted folder
   - Double-click `index.html`
   - Bookmark the file location in your browser

3. **Start using:**
   - Go to **"Data Management"** tab
   - Fill in your profile (name, weight, start date)
   - Click **"Save Profile"**
   - Begin your 90-day journey!

---

## 📖 How to Use

### **First Time Setup (5 minutes)**

#### **1. Set Your Profile**
- Navigate to **"Data Management"** tab
- Enter:
  - Your name
  - Weight in kg (used for nutrition calculations)
  - Start date (today or your planned start)
- Click **"💾 Save Profile"**

#### **2. Do Baseline Testing**
- Go to **"90-Day Plan"** tab → **"Baseline Testing"**
- Test yourself on each movement:
  - Deep Squat Hold
  - Hollow Body Hold
  - L-Sit Hold
  - Dead Hang
  - Hanging Leg Raise
  - Pike Compression
  - Wall Handstand
  - Pistol Squats
- Record your Day 1 numbers
- Retest every 4 weeks (Week 4, 8, 12)

#### **3. Learn the Workouts**
- Check **"Workout Days"** tab
- Review the 4 workout types:
  - **Day A:** Core & Compression
  - **Day B:** Hips & Mobility
  - **Day C:** Hanging & Pulling
  - **Day D:** Skills & Balance (optional)
- Read **"Exercise Guide"** for proper form on all movements

---

### **Daily Usage (2 minutes)**

#### **1. Complete Your Workout**
- Follow the prescribed workout for the day
- Use the carousel navigation to switch between Days A/B/C/D
- Reference Exercise Guide as needed for form cues

#### **2. Log Your Session**
- Go to **"90-Day Plan"** → **"Weekly Training Log"**
- Find today's date/week
- Select from dropdown:
  - **A** - Day A workout
  - **B** - Day B workout
  - **C** - Day C workout
  - **D** - Day D workout
  - **R** - Rest day (won't break streak!)
  - **-** - Unlogged day
- Add notes in the "Biggest Win" column
- Everything auto-saves instantly!

#### **3. Track Your Progress**
Check the sidebar for live stats:
- 🔥 **Current Streak** - Consecutive days logged (workouts OR rest)
- 💪 **Workouts Done** - Total training sessions (A/B/C/D only)
- 📅 **Days Remaining** - Until 90-day completion

---

### **Weekly Review & Maintenance**

#### **Retest Progress (Every 4 Weeks)**
- Week 4, 8, and Day 90: Retest all baseline movements
- Update numbers in the tracker
- Watch your progress compound!

#### **Export Backup (Weekly Recommended)**
- Go to **"Data Management"**
- Click **"📥 Download Progress Data"**
- Save the JSON file: `calisthenics-progress-YYYY-MM-DD.json`
- Store it somewhere safe (cloud storage, email to yourself)

#### **Import Backup (If Needed)**
- Click **"📤 Upload Data File"**
- Select your JSON backup
- All progress instantly restored!

---

## 🎯 Program Structure

### **Weekly Training Schedule**

**Recommended Frequency:** 3-4 workouts per week

**Example Week:**
```
Monday    → Day A (Core)
Tuesday   → Rest (R)
Wednesday → Day B (Hips)
Thursday  → Rest (R)
Friday    → Day C (Hanging)
Saturday  → Day D (Skills) - optional
Sunday    → Rest (R)
```

### **90-Day Phases**

| Phase | Weeks | Focus | Goal |
|-------|-------|-------|------|
| **Foundation** | 1-4 | Learn positions, joint prep | 30-40s hollow hold, assisted pistols |
| **Strength** | 5-8 | Build compression & control | Full L-sit progression, leg raises to waist |
| **Deload** | 9 | Recovery week | Reduce volume 40-50% |
| **Integration** | 10-12 | Skill mastery | Full L-sit 30s, toes-to-bar, handstand 60s |

---

## 💾 Data Management

### **How Auto-Save Works**
All data automatically saves to your browser's localStorage as you type or select:
- ✅ Profile information
- ✅ Baseline test results
- ✅ Milestone checkboxes
- ✅ Weekly training log
- ✅ Notes and achievements

**No manual save button needed!**

### **Export Your Data**
1. Go to **"Data Management"** tab
2. Click **"📥 Download Progress Data"**
3. File saves as: `calisthenics-progress-YYYY-MM-DD.json`
4. Keep this file safe for backups!

### **Import Saved Data**
1. Click **"📤 Upload Data File"**
2. Select your `.json` backup file
3. Confirm the upload
4. Page reloads with all your data restored

### **Clear & Start Fresh**
- Use the **"🗑️ Clear All Data"** button to reset everything
- **Warning:** This is permanent! Export first if you want to save progress
- Perfect for starting a new 90-day cycle

---

## 🏃‍♂️ Workout Days Overview

### **Day A - Core & Compression**
Focus: Abs, hip flexors, active flexibility
- Hollow Body Holds
- Hanging Knee Raises → Leg Raises
- Pike Compression Lifts
- L-Sit Progressions
- Deep Squat Holds

### **Day B - Hips & Mobility**
Focus: Deep hip range, unilateral strength
- Deep Squat Holds
- Cossack Squats
- Pistol Squat Progressions
- Hip Flexor Stretches
- 90/90 Hip Rotations

### **Day C - Hanging & Pulling**
Focus: Grip, lat engagement, core stability
- Dead Hangs
- Scapular Pulls
- Hanging Leg Raises
- Windshield Wipers (advanced)
- Passive Pike Stretches

### **Day D - Skills & Balance** *(Optional)*
Focus: Total body control, mobility integration
- Wall Handstand Holds
- Pike Hold Compression
- Crow Pose / Frog Stand
- Shoulder Mobility Drills

---

## 🎖️ Skill Milestones

Track your progress through 5 levels:

### 🌱 **Level 1 - Mobility Foundations**
- 60 sec deep squat comfort
- 45 sec hollow hold
- 60 sec dead hang

### 🔰 **Level 2 - Compression Strength**
- Pike compression lifts (15 reps)
- Full pistol squats both legs
- Bent-knee L-sit (20+ sec)

### ⚡ **Level 3 - Integrated Strength**
- Full L-sit (30 sec)
- Straight-leg raises to bar
- 60 sec wall handstand

### 🔥 **Level 4 - Advanced Control**
- Toes-to-bar controlled
- Hanging windshield wipers
- Handstand shoulder taps

### 🧠 **Level 5 - Elite Skills** *(Optional)*
- Press to handstand
- Dragon flag
- Front lever progression

---

## 🛠️ Technical Details

### **Built With**
- Pure HTML5, CSS3, JavaScript (ES6+)
- Chart.js (CDN) for progress visualization
- localStorage API for data persistence
- No frameworks, no build tools, no dependencies

### **Browser Compatibility**
Tested and working on:
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### **File Size**
- Single HTML file: ~150KB
- No external dependencies (except Chart.js CDN)
- Loads instantly, works offline

### **Privacy & Security**
- 🔒 **100% client-side** - Your data never leaves your device
- 🚫 **No analytics** or tracking scripts
- 🚫 **No cookies** required
- 🚫 **No external requests** (after initial Chart.js load)
- 🔐 **localStorage only** - Data stays in your browser

---

## 📱 Mobile Usage

The tracker is fully responsive and works great on phones and tablets:

- 📱 **Collapsible sidebar** - Tap hamburger menu to access navigation
- 👆 **Touch-friendly** - Large buttons and dropdowns
- 🔄 **Swipe support** - Navigate workout carousel with swipe gestures
- 📊 **Readable charts** - Optimized for small screens
- ⌨️ **Mobile keyboards** - Proper input types for dates, numbers

---

## 🤝 Contributing

Found a bug? Have a feature idea? Contributions welcome!

### **Report Issues**
1. Go to the [Issues tab](https://github.com/agadrapin/calisthenics-90-day-tracker/issues)
2. Click "New Issue"
3. Describe the bug or feature request
4. Add screenshots if helpful

### **Submit Pull Requests**
1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes
4. Test thoroughly
5. Commit: `git commit -m "Add feature description"`
6. Push: `git push origin feature-name`
7. Open a Pull Request

---

## 📄 License

MIT License - See [LICENSE](LICENSE) file for details.

**You are free to:**
- ✅ Use commercially
- ✅ Modify as needed
- ✅ Distribute copies
- ✅ Use privately

**Just include the original license and copyright notice.**

---

## 🙏 Acknowledgments

This tracker was created to help people build:
- **Strength** through progressive calisthenics
- **Mobility** through intentional practice
- **Discipline** through consistent tracking

### **Inspired by:**
- Bodyweight fitness community
- Progressive overload principles
- The power of tracking and consistency

---

## 💬 Support & Community

- 🐛 **Bug reports:** [Open an issue](https://github.com/agadrapin/calisthenics-90-day-tracker/issues)
- 💡 **Feature requests:** [Start a discussion](https://github.com/agadrapin/calisthenics-90-day-tracker/discussions)
- ⭐ **Like this project?** Star the repo to show support!
- 🔀 **Want to contribute?** Fork and submit a PR!

---

## 📊 Roadmap

Future enhancements being considered:

- [ ] Additional workout templates (pull-ups, push-ups progressions)
- [ ] PDF export for printable workout cards
- [ ] Dark/light theme toggle
- [ ] Multi-language support
- [ ] Voice workout timer
- [ ] Exercise video demonstrations
- [ ] Social sharing for milestones
- [ ] PWA (Progressive Web App) for offline install

**Vote on features or suggest new ones in [Discussions](https://github.com/agadrapin/calisthenics-90-day-tracker/discussions)!**

---

## ❓ FAQ

**Q: Do I need to download anything?**  
A: No! Just open the link or the HTML file. Works in any modern browser.

**Q: Will my data be lost if I close the browser?**  
A: No! Everything saves to localStorage automatically. Your data persists across sessions.

**Q: Can I use this on my phone?**  
A: Yes! It's fully responsive and works great on mobile devices.

**Q: What if I want to switch devices?**  
A: Export your data (JSON file) from the old device, then import it on the new device.

**Q: Can I modify the workouts?**  
A: The workouts are fixed in this version, but you can edit the HTML file to customize them!

**Q: Do rest days break my streak?**  
A: No! Selecting "R" (rest) in the log maintains your streak. Only empty/unlogged days break it.

**Q: How do I reset and start over?**  
A: Go to Data Management → Click "Clear All Data" → Confirm. Fresh start!

---

## 🎯 Success Tips

**For Best Results:**

1. **Be Consistent** - 3-4 workouts per week, every week
2. **Log Everything** - Track workouts AND rest days (R)
3. **Test Regularly** - Retest every 4 weeks to see gains
4. **Focus on Form** - Quality over quantity always
5. **Export Weekly** - Back up your data regularly
6. **Trust the Process** - 90 days of consistency = real results

**Remember:** Progress > Perfection. Show up, log your work, trust the process.

---

**Ready to transform in 90 days?**

**[🚀 Start Your Journey Now!](https://agadrapin.github.io/calisthenics-90-day-tracker/)**

---

<div align="center">

Made with 💪 for the calisthenics community

**[⭐ Star this repo](https://github.com/agadrapin/calisthenics-90-day-tracker)** if you found it helpful!

</div>
