# 🎮 Crazy Chess

A fully-featured chess game with AI opponent, built with vanilla JavaScript and deployed on GitHub Pages.

**🌐 [Play Now](https://athiestatom.github.io/Crazy-Chess/)**

## Features

✨ **Game Modes**
- 👥 Player vs Player - Local multiplayer chess
- 🤖 Player vs Computer - Challenge the AI opponent

🧠 **AI Engine**
- Minimax algorithm with alpha-beta pruning
- Adjustable difficulty levels (1-20)
- Stockfish.js integration for advanced gameplay
- Real-time move evaluation

♟️ **Chess Features**
- Full chess rule support (castling, en passant, promotion)
- Legal move highlighting with visual feedback
- Move history log with notation
- Undo functionality
- Check/Checkmate/Stalemate detection
- Last move highlighting

🎨 **Design**
- Sketch-style hand-drawn aesthetics
- Responsive board layout
- Smooth animations and hover effects
- Unicode chess pieces
- Mobile-friendly interface

## How to Play

1. **Choose Game Mode**: Select "Player vs Player" or "Player vs Computer"
2. **Make Moves**: Click a piece to select it, then click a square to move
   - Green borders = legal moves
   - Red borders = capture moves
3. **Special Moves**: 
   - **Castling**: Move king 2 squares toward rook (if conditions met)
   - **En Passant**: Capture pawn diagonally after its 2-square advance
   - **Promotion**: Select piece when pawn reaches opposite end
4. **Controls**:
   - ↶ Undo - Take back your last move
   - ⟲ New - Start a new game

## Technical Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **AI**: Minimax with alpha-beta pruning + Stockfish.js
- **Deployment**: GitHub Pages
- **Fonts**: Google Fonts (Caveat)

## Project Structure

```
Crazy-Chess/
├── index.html          # Main game file (HTML + CSS + JS)
└── README.md          # This file
```

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge ✅
- Firefox ✅
- Safari ✅
- Mobile browsers ✅

## License

Free to use and modify

## Author

Created by **AthiestAtom**

---

**Enjoy the game! ♔♚**
