# 🎮 Simon Game - Memory Challenge

A classic electronic memory game where players must repeat increasingly longer sequences of colors and sounds. Test your memory and concentration with this fun, interactive web-based Simon game!

## 🎯 About the Game

Simon Game is a memory skill game inspired by the classic 1970s electronic game. The game generates a random sequence of colored buttons (Red, Blue, Green, Yellow) with corresponding sounds. Your goal is to memorize and repeat the sequence correctly. Each round adds one more step to the sequence, making it progressively more challenging!

## 🕹️ How to Play

### Basic Gameplay:
1. **Start the Game**: Press any key on your keyboard to begin
2. **Watch Carefully**: One of the colored buttons will flash and play a sound
3. **Repeat the Sequence**: Click the buttons in the same order
4. **Level Up**: If correct, the game adds one more color to the sequence
5. **Continue Playing**: Keep repeating the growing sequence
6. **Game Over**: If you click the wrong button, the game ends

### Step-by-Step Example:
Level 1: Game shows 🔴 RED → You click 🔴 RED ✅
Level 2: Game shows 🔴 RED → 🟢 GREEN → You click 🔴 RED → 🟢 GREEN ✅
Level 3: Game shows 🔴 RED → 🟢 GREEN → 🔵 BLUE → You click 🔴 RED → 🟢 GREEN → 🔵 BLUE ✅
...and so on!

text

## ✨ Game Features

- **Interactive Visual Feedback**: Buttons flash and animate when pressed
- **Sound Effects**: Each color has its own unique sound
- **Level Progression**: Difficulty increases with each successful round
- **Game Over Effect**: Screen flashes red when you make a mistake
- **Responsive Design**: Plays well on both desktop and mobile devices
- **Retro Styling**: Classic arcade-style fonts and design

## 💻 Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure and layout |
| CSS3 | Styling, animations, and responsive design |
| JavaScript (ES6) | Game logic and interactivity |
| jQuery 3.3.1 | DOM manipulation and event handling |
| Google Fonts | "Press Start 2P" retro font |

## 📥 Installation

### Option 1: Clone from GitHub
```bash
git clone https://github.com/yourusername/simon-game.git
cd simon-game
Option 2: Download ZIP
Download the project ZIP file

Extract to your desired folder

Open the folder

🚀 How to Run
Local Setup:
Ensure you have the following files in your project folder:

text
simon-game/
├── index.html
├── game.js
├── styles.css
├── README.md
└── sounds/
    ├── red.mp3
    ├── blue.mp3
    ├── green.mp3
    ├── yellow.mp3
    └── wrong.mp3
Open the Game:

Double-click index.html file

OR use a local server:

bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
Open browser and navigate to http://localhost:8000

Start Playing:

Press any key on your keyboard

Follow the sequence!

Live Demo:
You can also play online at: https://izza-faris.github.io/Simon_Game/

📁 File Structure
text
simon-game/
│
├── index.html          # Main game interface
├── game.js            # Game logic and mechanics
├── styles.css         # Visual styling and animations
├── README.md          # Game documentation
│
└── sounds/            # Audio files directory
    ├── red.mp3        # Red button sound
    ├── blue.mp3       # Blue button sound
    ├── green.mp3      # Green button sound
    ├── yellow.mp3     # Yellow button sound
    └── wrong.mp3      # Error sound

📜 Game Rules
Starting Rule: Game only starts when any keyboard key is pressed

Sequence Rule: You must click exactly in the order shown

Timing Rule: No time limit - take your time to remember!

Mistake Rule: One wrong click ends the game immediately

Restart Rule: After game over, press any key to restart from Level 0

Level Rule: Each correct sequence advances you to the next level

🎮 Controls
Action	Control
Start/Restart Game	Press any keyboard key
Select RED	Click on RED button or tap on mobile
Select BLUE	Click on BLUE button or tap on mobile
Select GREEN	Click on GREEN button or tap on mobile
Select YELLOW	Click on YELLOW button or tap on mobile
🎨 Customization
Changing Colors:
Edit styles.css:

css
.red { background-color: #ff0000; }  /* Change to any color */
.green { background-color: #00ff00; }
.blue { background-color: #0000ff; }
.yellow { background-color: #ffff00; }
Changing Sounds:
Replace the MP3 files in the sounds/ folder with your own audio files (must keep same filenames)

Changing Speed:
In game.js, modify the timeout duration:

javascript
setTimeout(function () {
  nextSequence();
}, 1000); // Change 1000 to adjust wait time (milliseconds)
🔧 Troubleshooting

Problem	Solution
Game doesn't start	Make sure you pressed any keyboard key
No sound	Check if sound files exist in sounds/ folder
Buttons not flashing	Verify jQuery is loading properly
Game freezes	Refresh the page and try again
Mobile not working	Ensure touch events are enabled in browser


🚧 Future Improvements
Add high score tracking using localStorage

Implement difficulty levels (easy, medium, hard)

Add visual pattern hints

Create multiplayer mode

Add vibration feedback for mobile devices

Include sound toggle option

Add score sharing on social media

Create different color themes

🎯 Scoring System
Level	Sequence Length
0-5	Easy - Short sequences
6-10	Medium - Moderate difficulty
11-15	Hard - Challenging
16+	Expert - Extreme difficulty
💡 Tips & Tricks
Say it out loud: Verbalize colors as they appear ("Red, Blue, Green...")

Chunk the sequence: Group colors in pairs or threes

Use patterns: Look for repeating patterns in the sequence

Stay focused: Minimize distractions while playing

Practice regularly: Memory improves with consistent practice

📊 Browser Compatibility
Browser	Version	Support
Chrome	90+	✅ Fully supported
Firefox	88+	✅ Fully supported
Safari	14+	✅ Fully supported
Edge	90+	✅ Fully supported
Opera	76+	✅ Fully supported
Mobile Browsers	Latest	✅ Fully supported
📝 Credits
Game Logic: Inspired by the classic Simon electronic game

Font: 'Press Start 2P' from Google Fonts

jQuery: Google Hosted Libraries

Sounds: Standard Simon game sound effects

📄 License
This project is open source and available under the MIT License.

👥 Contributing
Feel free to fork this project and submit pull requests for improvements!

📞 Support
If you encounter any issues or have suggestions:

Open an issue on GitHub

Contact the developer

Check the troubleshooting section above

🎉 Enjoy the Game!
Test your memory, challenge your friends, and try to beat your high score. Remember - practice makes perfect!

Press any key to start your memory journey! 🚀
