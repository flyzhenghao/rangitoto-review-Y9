# 🎓 Rangitoto Year 9 Review Hub

A gamified learning platform to help Year 9 students review their subjects during the summer holidays.

![Screenshot](screenshot.png)

## ✨ Features

### 📚 Subjects Covered
- **Mathematics** - Number & Algebra, Geometry & Measurement, Statistics
- **English ESOL** - Reading & Vocabulary, Grammar, Writing Skills
- **Science** - Chemistry, Biology, Physics
- **Social Science** - NZ History, Geography, Civics

### 🎮 Gamification Elements
- ⚡ **XP Points** - Earn experience for every exam
- 🔥 **Daily Streaks** - Build consistency with streak tracking
- 🏅 **Badges** - Unlock achievements for milestones
- 📊 **Progress Charts** - Visual tracking of your learning
- ⏱️ **Timed Challenges** - Race against the clock for bonus XP

### 📈 NCEA Grading System
Your scores are automatically converted to NCEA grades:
- **N0-N2**: Not Achieved (0-39%)
- **A3-A4**: Achieved (40-59%)
- **M5-M6**: Merit (60-79%)
- **E7-E8**: Excellence (80-100%)

### 📅 6-Week Study Plan
Pre-built study schedule from December 6, 2025 to January 17, 2026:
1. Week 1: Math - Number & Algebra
2. Week 2: English - Reading & Vocabulary
3. Week 3: Math - Geometry & Measurement
4. Week 4: Science - Chemistry & Biology
5. Week 5: English - Grammar & Writing
6. Week 6: All Subjects Review

### 💪 Health Index
Track how well you're keeping up with your study plan!

## 🚀 Quick Start

### Option 1: Use GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Set Source to "Deploy from a branch"
4. Select "main" branch and "/ (root)" folder
5. Your site will be live at `https://YOUR_USERNAME.github.io/rangitoto-review-app`

### Option 2: Run Locally
Just open `index.html` in your web browser!

## 📱 Works On
- ✅ Desktop browsers (Chrome, Firefox, Safari, Edge)
- ✅ Tablets
- ✅ Mobile phones

## 💾 Data Storage
All your progress is saved automatically in your browser's local storage. Your data includes:
- XP and streaks
- Exam history
- Earned badges
- Weekly progress

**Note**: Data is stored per browser. If you switch browsers or clear browser data, your progress will reset.

## 🔧 For Developers

### Tech Stack
- React 18 (via CDN)
- Tailwind CSS
- Chart.js for progress visualization
- Canvas Confetti for celebrations
- Pure JavaScript (no build step required!)

### File Structure
```
rangitoto-review-app/
├── index.html      # Main application (everything in one file!)
├── README.md       # This file
└── .nojekyll       # Tells GitHub to skip Jekyll processing
```

### Adding More Questions
Edit the `questionDatabase` object in index.html. Each question follows this format:

```javascript
{
    id: "unique_id",
    type: "multiple", // or "short" or "fill"
    question: "Your question here?",
    options: ["A", "B", "C", "D"], // for multiple choice
    correct: 0, // index of correct answer (or array of strings for short/fill)
    explanation: "Why this is the answer",
    difficulty: "A3-A4" // NCEA grade level
}
```

## 🎯 Future Enhancements
- [ ] Cloud sync with Firebase
- [ ] More questions per topic
- [ ] Multiplayer quiz mode
- [ ] Parent/teacher dashboard
- [ ] PDF export of progress reports

## 📄 License
MIT License - Feel free to use and modify!

## 🙏 Acknowledgments
- Curriculum based on New Zealand Year 9 standards
- Inspired by Duolingo, Khan Academy, and other gamified learning platforms
- Built for Rangitoto College students

---

Made with 💜 for Year 9 students preparing for Year 10!
