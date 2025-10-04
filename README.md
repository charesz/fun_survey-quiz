# Pixel Pilot Quiz: Ship Commander🚀🌠

[Take the quiz here🚀]([https://charesz.github.io/fun_survey-quiz/])

Pixel Pilot Quiz: Ship Commander is a retro-styled, interactive web-based quiz game that immerses players in a spacefaring adventure. Players assume the role of a starship captain and answer fun, thematic questions to progress through missions, earn scores, and maintain their ship's integrity.

---

## ☄️Features

- **Retro Pixel Art Design**: Uses VT323 font, neon colors, and pixelated UI elements for a nostalgic arcade feel.
- **Dynamic Quiz Types**: Supports multiple-choice, yes/no, rating scale, and open-ended questions.
- **Life and Score System**: Players have a limited number of shields (lives) and earn points for correct answers.
- **Firebase Integration**:
  - Anonymous and custom authentication.
  - Real-time Firestore storage for user scores.
  - Supports potential leaderboard functionality.
- **Video Background**: Immersive space environment with a looping video backdrop.
- **Interactive Feedback**: Animated feedback for correct and incorrect answers.
- **Responsive Layout**: Works on desktop and mobile devices using Tailwind CSS.

---

## 🛠️ Technologies Used

- **HTML5 / CSS3 / JavaScript (ES6+)**
- **Tailwind CSS** for styling
- **Firebase**:
  - Authentication (Anonymous and Custom Token)
  - Firestore Database
- **Pixel Art Styling** and retro UI design
- **Video Background** for immersive gameplay

---

## 📂 Project Structure
```
/project-root
├── index.html # Main HTML file containing the game
├── space.mp4 # Background video (can be replaced)
├── mainspaceship.gif # Main spaceship visual
├── success.gif # Success animation
├── explosion.gif # Failure animation
└── README.md # Project documentation
```

---

## 🎮 How to Play

1. Open `index.html` in a web browser or click link [here.]([https://charesz.github.io/fun_survey-quiz/])
2. **Pilot Log-in**:
   - Enter your pilot call sign (any name).
   - Enter your spaceship secret code (minimum 4 digits).
3. **Mission Start**:
   - Confirm your identity and begin the mission.
4. **Answer Quiz Questions**:
   - Multiple-choice (MCQ)
   - Yes/No questions
   - Rating scale (1-5)
   - Open-ended prompts (fun, creative responses)
5. **Score & Lives**:
   - Correct answers increase your score.
   - Wrong answers reduce your shields (lives).
6. **Mission Feedback**:
   - Successfully complete the mission or fail if shields reach zero.
7. Your score is saved in Firebase for future retrieval or leaderboard display.

---
## 🎯 Future Improvements

- Implement **public leaderboards** with Firestore.
- Add **sound effects** for interactions.
- Make **missions adaptive** based on player performance.
- Enhance **mobile experience** with additional responsive tweaks.

---

## 👨‍🚀 Credits

Developed by [Mariane Charisse Cañete](https://github.com/charesz). Inspired by retro arcade games and space adventure themes.

