# Word Bird

A fast-paced word categorization game where you navigate a bird through colored boxes, picking the odd word out from each column.

## 🎮 Gameplay

Fly your bird through columns of words. Each column has 5 words - 4 belong to one category, 1 belongs to a different category. Tap/click to flap and navigate to the odd word out.

### How to Play
- **Objective**: Guide the bird to the word that doesn't belong with the others
- **Controls**: Tap/click to flap upward, gravity pulls you down
- **Scoring**: +1 for each correct word, combos multiply your score
- **Difficulty**: Increases as you score more - obstacles get closer together

### Categories
Words are organized into semantic categories like:
- **Animals**: lion, tiger, bear, wolf
- **Fruits**: apple, banana, orange, grape  
- **Countries**: france, germany, italy, spain
- **Colors**: red, blue, green, yellow
- And many more!

## 🚀 Live Game

Play now at: [https://rexuvia.com/games/word-bird](https://rexuvia.com/games/word-bird)

## 🛠️ Technical Details

### Built With
- **HTML5 Canvas** for rendering
- **Vanilla JavaScript** (no frameworks)
- **Responsive design** that works on all screen sizes
- **Local storage** for high score tracking

### Features
- **Responsive obstacle spacing**: Adapts to different screen sizes
- **Dynamic difficulty**: Game gets faster and more challenging as you progress
- **Visual feedback**: Particle effects, screen shake, and color cues
- **Combo system**: Chain correct answers for multiplier bonuses
- **Hint system**: Helpful hints when you make mistakes

### Recent Improvements
- **March 16, 2026**: Fixed obstacle spacing for different screen sizes
  - Responsive spacing that scales with screen width
  - Faster first obstacle appearance on wide screens
  - Better vertical playability on tall screens
  - Centered boxes when they don't fill entire screen

## 📱 Platform Support

- **Desktop**: Full keyboard and mouse support
- **Mobile**: Touch-optimized controls
- **Tablet**: Responsive layout for all screen sizes
- **Accessibility**: Color-blind friendly design with distinct shapes

## 🎨 Design Philosophy

Word Bird combines:
- **Cognitive challenge**: Quick category recognition
- **Motor skill**: Precise navigation through tight spaces  
- **Progressive difficulty**: Smooth learning curve
- **Visual polish**: Neon aesthetic with smooth animations

## 🔧 Development

### Running Locally
```bash
# Clone the repository
git clone https://github.com/rexuvia/word-bird.git

# Open index.html in a browser
open index.html  # or use your preferred method
```

### File Structure
```
word-bird/
├── index.html          # Main game file (self-contained)
├── README.md           # This documentation
└── .gitignore          # Git configuration
```

### Self-Contained Design
The entire game is in a single HTML file for:
- Easy deployment
- No build process required
- Simple hosting on any static server
- Fast loading times

## 📊 Performance

- **60 FPS target** on modern devices
- **GPU-accelerated** rendering
- **Efficient collision detection**
- **Memory-efficient** particle system

## 🤝 Contributing

While this is a personal project, suggestions are welcome! The game is designed to be:
1. **Self-contained**: All code in one HTML file
2. **Maintainable**: Clean, commented JavaScript
3. **Extensible**: Easy to add new word categories

### Adding New Categories
Edit the `CATS` object in the JavaScript to add new word groups.

## 📄 License

This project is part of the [Rexuvia](https://rexuvia.com) collection of interactive experiments and games.

## 🔗 Links

- **Live Game**: [https://rexuvia.com/games/word-bird](https://rexuvia.com/games/word-bird)
- **Source Code**: [https://github.com/rexuvia/word-bird](https://github.com/rexuvia/word-bird)
- **Rexuvia Games**: [https://rexuvia.com/games](https://rexuvia.com/games)
- **Issue Tracker**: [https://github.com/rexuvia/word-bird/issues](https://github.com/rexuvia/word-bird/issues)

## 🙏 Acknowledgments

- Inspired by classic categorization and reaction games
- Built as part of the Rexuvia daily game generation project
- Thanks to all playtesters for feedback on gameplay balance

---

*Part of the Rexuvia interactive experiments collection - exploring the intersection of games, learning, and web technology.*