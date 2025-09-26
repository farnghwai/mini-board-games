# 迷你棋盤遊戲 (Mini Board Games)

Classic strategy board games with modern web design and Chinese interface.

## 🎮 Live Demo

**Play Now:** [https://farnghwai.github.io/mini-board-games/](https://farnghwai.github.io/mini-board-games/)

## 🎯 Games Available

### 圍棋 (Go)
- **Play:** [Go Game](https://farnghwai.github.io/mini-board-games/go-game-chinese.html)
- Ancient strategy game focusing on territory control
- 9x9 board optimized for mobile play
- AI opponent with multiple difficulty levels
- Territory scoring with detailed explanations

### 五子棋 (Gomoku)
- **Play:** [Gomoku Game](https://farnghwai.github.io/mini-board-games/gomoku-game-chinese.html)
- Connect five stones in a row to win
- 15x15 board with strategic gameplay
- AI opponent with adaptive difficulty
- Clean, intuitive interface

## ✨ Features

- **Mobile-First Design**: Optimized for smartphones and tablets
- **Traditional Chinese Interface**: Native language support
- **AI Opponent (小克)**: Intelligent computer player
- **No Dependencies**: Pure HTML/CSS/JavaScript
- **Responsive Layout**: Works on all screen sizes
- **Accessibility**: Keyboard navigation and screen reader support
- **Offline Ready**: No internet required after initial load

## 🔧 Technical Details

- **Framework**: None (Vanilla web technologies)
- **Dependencies**: Zero external libraries
- **Build Process**: None required
- **Hosting**: GitHub Pages compatible
- **Browser Support**: Modern browsers (Chrome 88+, Safari 14+, Firefox 85+)

## 🎲 How to Play

### 圍棋 (Go)
1. Players alternate placing black and white stones
2. Capture opponent stones by surrounding them
3. Control more territory than your opponent to win
4. Game ends when both players pass consecutively

### 五子棋 (Gomoku)
1. Players alternate placing black and white stones
2. First to get five stones in a row (horizontal, vertical, or diagonal) wins
3. Strategic blocking and positioning are key
4. Game is won immediately upon achieving five in a row

## 🛠️ Development

### Running Locally
```bash
# Clone the repository
git clone https://github.com/farnghwai/mini-board-games.git
cd mini-board-games

# Open any HTML file directly in your browser
open index.html
# or
python -m http.server 8000  # Then visit http://localhost:8000
```

### File Structure
```
├── index.html                 # Landing page with game selection
├── shared-styles.css          # Common styles for all games
├── go-game-chinese.html       # Go game implementation
├── gomoku-game-chinese.html   # Gomoku game implementation
└── README.md                  # This file
```

### Design Principles
- **Single-Screen Experience**: No scrolling during gameplay
- **Touch-First Interactions**: Designed for mobile touch input
- **Consistent Theming**: Shared design language across games
- **Accessibility**: WCAG compliance and keyboard support

## 📱 Browser Compatibility

- Chrome/Chromium 88+
- Safari 14+ (iOS/macOS)
- Firefox 85+
- Edge 88+

## 🎨 Design Philosophy

This project follows strict design principles:
- **Mobile-First**: Optimized for touch devices and small screens
- **Accessibility**: WCAG compliant with keyboard navigation
- **Single-Screen Experience**: No scrolling during gameplay
- **Consistent Theming**: Shared design language across games
- **Performance**: Zero dependencies, fast loading

## 📄 License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the [LICENSE](LICENSE) file for details.

**Key points:**
- ✅ Free to use, modify, and distribute
- ✅ Source code must remain open
- ✅ Modifications must be shared under the same license
- ✅ Commercial use allowed

## 🤖 AI Development Credits

### Claude Code
- Go & Gomoku game implementations
- Shared styles architecture (shared-styles.css)
- SEO meta tags and optimization
- README documentation

### Google Gemini
- Landing page design (index.html)

---

**Built with ❤️ using vanilla web technologies and AI assistance**