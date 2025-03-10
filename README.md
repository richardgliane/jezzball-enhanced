# JezzBall Enhanced

A modern HTML5 Canvas implementation of the classic JezzBall arcade game. Players strategically draw walls to section off areas while avoiding bouncing balls.

![JezzBall Enhanced Gameplay](screenshot.png)

## 🎮 How to Play

1. Click the "Start Game" button to begin
2. Draw walls to section off areas of the screen:
   - Left Click: Create vertical wall
   - Right Click: Create horizontal wall
3. Clear the required percentage of the screen to advance to the next stage
4. Don't let balls hit growing walls - you have 3 lives!

## ✨ Features

- Modern, responsive HTML5 Canvas gameplay
- Colorful bouncing balls with physics
- Progress tracking system
- Multiple stages with increasing difficulty
- Lives and scoring system
- Sound effects and visual feedback
- Clean, modern UI with transitions

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/richardgliane/jezzball-enhanced.git
```

2. Navigate to the project directory:
```bash
cd jezzball-enhanced
```

3. Start a local server (using Python or any other HTTP server):
```bash
# Python 3
python -m http.server 8000

# Or with Node.js
npx http-server
```

4. Open your browser and visit:
```
http://localhost:8000
```

## 🛠️ Technologies Used

- HTML5 Canvas
- JavaScript (ES6+)
- CSS3

## 🎯 Game Mechanics

- Walls grow from the point of click in both directions
- Balls bounce realistically off walls and screen boundaries
- Areas are cleared when fully enclosed
- Each stage requires clearing a specific percentage of the screen
- Balls speed up as you progress through stages

## 📝 License

MIT License - feel free to use and modify for your own projects!

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/richardgliane/jezzball-enhanced/issues).

## 🙏 Acknowledgments

- Original JezzBall game by Microsoft
- Sound effects from MyInstants and FreeSound