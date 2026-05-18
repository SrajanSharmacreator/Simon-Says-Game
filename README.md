# 🎮 Simon Says Game

A classic **memory-based Simon Says game** built with vanilla HTML, CSS, and JavaScript. Test your memory and reflexes by repeating increasingly longer sequences of colors!

## 📋 Table of Contents
- [Features](#features)
- [How to Play](#how-to-play)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Game Mechanics](#game-mechanics)
- [Project Structure](#project-structure)

## ✨ Features

- 🎯 **Progressive Difficulty** - Each level adds a new color to the sequence
- 🏆 **High Score Tracking** - Your best score is saved during the session
- ⚡ **Flash Effects** - Visual feedback when buttons are pressed
- 🎨 **Colorful UI** - 4 vibrant colored buttons (Red, Yellow, Green, Purple)
- ⌨️ **Easy to Play** - Press any key to start!
- 📱 **Responsive Design** - Works on different screen sizes

## 🎮 How to Play

1. **Start the Game** - Press any key on your keyboard
2. **Watch the Sequence** - The game will flash a random color
3. **Repeat the Sequence** - Click the buttons in the same order
4. **Level Up** - Each level adds one more color to the sequence
5. **Game Over** - If you click the wrong button, the game ends
6. **View High Score** - Your best score is displayed at the bottom
7. **Play Again** - Press any key to restart and try to beat your high score

## 🛠️ Technologies Used

- **HTML5** - Structure and markup
- **CSS3** - Styling and animations
- **JavaScript (ES6)** - Game logic and interactivity

## 🚀 Getting Started

### Option 1: Play Online
Simply open `simon.html` in your web browser.

### Option 2: Clone the Repository
```bash
git clone https://github.com/SrajanSharmacreator/Simon-Says-Game.git
cd Simon-Says-Game
```

Then open `simon.html` in your browser.

### Files Included
- `simon.html` - Game structure
- `simon.css` - Game styling
- `simon.js` - Game logic

## 🎯 Game Mechanics

### Game Flow
- **Level** increases by 1 each round
- **Game Sequence** grows by 1 color per level
- **User Sequence** tracks your button clicks
- **Flash Effect** provides visual feedback (250ms white flash)

### Winning Condition
- Match the entire game sequence correctly to advance to the next level

### Losing Condition
- Click a wrong button and the game ends
- Background turns red briefly as visual feedback
- Your score and high score are displayed

### High Score System
- Tracks the highest level reached during your gaming session
- Persists until you refresh the page
- Displayed at the bottom of the screen

## 📁 Project Structure

```
Simon-Says-Game/
│
├── simon.html       # Main game interface
├── simon.css        # Styling and animations
├── simon.js         # Game logic
└── README.md        # Documentation
```

## 🎨 Color Palette

| Color | Code | RGB |
|-------|------|-----|
| Yellow | #f99b45 | 249, 155, 69 |
| Red | #d95980 | 217, 89, 128 |
| Purple | #819ff9 | 129, 159, 249 |
| Green | #63aac0 | 99, 170, 192 |

## 🎮 Game Controls

| Action | Key/Button |
|--------|-----------|
| Start Game | Any Key |
| Click Button | Mouse Click |
| Restart | Any Key (after game over) |

## 💡 Tips to Improve Your Score

1. **Focus** - Pay close attention to the sequence
2. **Pattern Recognition** - Look for patterns in the colors
3. **Practice** - Your memory will improve with each game
4. **Take Breaks** - Don't get frustrated, take a moment between games
5. **Speed Up Gradually** - As you get better, you'll naturally click faster

## 🚧 Future Enhancements

Potential features for future versions:
- 🔊 Sound effects for each button
- 🎵 Background music
- 🌙 Dark mode theme
- 💾 Persistent high score (using localStorage)
- 🎚️ Difficulty levels (Easy, Medium, Hard)
- ⏱️ Time-based challenges
- 📊 Statistics and analytics
- 🏅 Leaderboard system

## 📝 License

This project is open source and available for educational purposes.

## 👨‍💻 Author

**Srajan Sharma**

Feel free to fork, modify, and improve this game!

---

**Enjoy the game and challenge yourself to beat your high score! 🎉**
