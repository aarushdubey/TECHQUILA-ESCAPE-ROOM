# TECHQUILA Escape Room 🎮

An interactive web-based escape room puzzle game developed for the **Smart Tech Club ALOHA Event**. This project challenges players to solve multi-stage technical puzzles combining networking, security, mathematics, and system administration concepts.

**Live Demo:** [techquila-escape-room.onrender.com](https://techquila-escape-room.onrender.com/)

---

## 🎯 Overview

TECHQUILA is a gamified learning experience designed to make technical concepts engaging and fun. Players progress through multiple stages, each unlocking new puzzles and challenges. The game combines frontend interactivity with creative problem-solving to teach real-world tech concepts.

### Key Features

✨ **Multi-Stage Gameplay** - Two progressive stages with increasing difficulty
🔐 **Security-Themed Challenges** - Network checks, authentication, and verification puzzles
🎨 **Modern UI** - Built with Tailwind CSS with a sleek hacker aesthetic
⚡ **Interactive Puzzles** - Real-time feedback with terminal-style output
📊 **Math Challenges** - Final verification puzzle combining multiple solutions
🎵 **Audio Feedback** - Win sound effects for successful puzzle completion

---

## 📋 How to Play

### Stage 1: System Reboot Sequence

1. **Turn on Main Power** - Activate the system to unlock puzzle panels
2. **Core Systems Check** - Complete 4 system diagnostics:
   - Scan Network Routes (14 active nodes)
   - Verify Memory Integrity (32 GB verified)
   - Initialize I/O Ports (Temperature range 80-100°C)
   - Check Core Processor (Clock speed 4 GHz with L1 up, L2 down, L3 up)
3. **Authentication Levers** - Set levers in the correct sequence: UP → DOWN → UP
4. **Coolant & Temperature** - Activate coolant pump and calibrate temperature to 88°C
5. **Router Reboot** - Restart routers #1 and #3
6. **Math Verification** - Calculate: (Code3 - Code2) + (Code1 × 3) - Code4
   - Expected answer: 60

### Stage 2: Advanced Security Protocol

Access the next level of challenges after completing Stage 1.

---

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, Tailwind CSS
- **Scripting**: Vanilla JavaScript (no dependencies)
- **Animation**: CSS animations + Canvas Matrix effect
- **Responsive Design**: Mobile-friendly with touch support
- **Deployment**: Render

---

## 📁 Project Structure

```
TECHQUILA-ESCAPE-ROOM/
├── index.html           # Stage 1: System Reboot Sequence
├── stage2.html          # Stage 2: Advanced challenges
├── win_sound.mp3        # Victory audio
└── README.md            # This file
```

### File Descriptions

| File | Purpose |
|------|---------|
| **index.html** | Main game interface for Stage 1 with all puzzle logic and interactive elements |
| **stage2.html** | Continuation of the escape room experience with advanced challenges |
| **win_sound.mp3** | Audio feedback played when completing stages successfully |

---

## 🚀 Getting Started

### Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/aarushdubey/TECHQUILA-ESCAPE-ROOM.git
   cd TECHQUILA-ESCAPE-ROOM
   ```

2. **Open in browser**
   - Double-click `index.html` to play locally
   - Or use a local server: `python -m http.server 8000`
   - Visit `http://localhost:8000`

### Online Access

Visit the deployed version: [techquila-escape-room.onrender.com](https://techquila-escape-room.onrender.com/)

---

## 🎓 Educational Value

This project teaches:

- **System Administration**: Process management, temperature monitoring, power control
- **Network Concepts**: Router configuration, network topology, data verification
- **Security Practices**: Authentication sequences, verification protocols
- **Problem-Solving**: Multi-step logical challenges and mathematical reasoning
- **JavaScript**: DOM manipulation, event handling, state management
- **Web Development**: Responsive design, CSS animations, user interaction

---

## 🔧 Features Breakdown

### Interactive Elements

- **Power Control System** - Toggle main system power
- **Terminal Output** - Real-time feedback on actions taken
- **Status Indicators** - Visual locks/unlocks showing puzzle progress
- **Multi-Input Puzzles** - Combine different input types (buttons, sliders, toggles)
- **Mathematical Verification** - Final step requires calculation
- **Progress Tracking** - All puzzle solutions displayed in code fragments

### Technical Highlights

- **State Management**: Maintains game progress and unlocked codes
- **Event Listeners**: Tracks button clicks, slider inputs, and toggles
- **DOM Manipulation**: Dynamic UI updates based on game state
- **Canvas Animation**: Matrix-style background effect
- **Responsive Layout**: Adapts to desktop, tablet, and mobile screens

---

## 💡 Puzzle Solutions (No Spoilers!)

The puzzles are designed to teach concepts through discovery. Hints are provided in the terminal. Try to solve them yourself first!

Key mechanic: Each puzzle contributes a numerical "code" that combines into the final answer.

---

## 📱 Browser Compatibility

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 🎨 Design Philosophy

- **Immersive Theme**: Hacker/sysadmin aesthetic with tech terminology
- **Progressive Disclosure**: Puzzles unlock as previous ones complete
- **Accessibility**: Clear instructions and helpful terminal hints
- **Mobile Responsive**: Fully playable on all screen sizes
- **No External Dependencies**: Pure HTML/CSS/JavaScript for performance

---

## 🔮 Future Enhancements

- [ ] Stage 3 with network security challenges
- [ ] Leaderboard with completion times
- [ ] Difficulty levels (Easy/Medium/Hard)
- [ ] Multiplayer/Cooperative mode
- [ ] Detailed tutorial mode
- [ ] Additional sound effects and visual feedback
- [ ] Save/Load game state
- [ ] Hint system with progressive reveals

---

## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to:

- Report bugs and issues
- Suggest new puzzle ideas
- Propose UI/UX improvements
- Add accessibility features

---

## 📄 License

This project is available under the MIT License - see LICENSE file for details.

---

## 🙌 Credits

**Created for:** Smart Tech Club ALOHA Event  
**Developer:** Aravindh Dubey  
**Repository:** [github.com/aarushdubey/TECHQUILA-ESCAPE-ROOM](https://github.com/aarushdubey/TECHQUILA-ESCAPE-ROOM)

---

## 📞 Support & Questions

- 🐛 Found a bug? Open an issue
- 💬 Have questions? Check the hints in the game terminal
- 🎮 Want to play? Visit the [live demo](https://techquila-escape-room.onrender.com/)

---

**Happy Solving! 🎯**
