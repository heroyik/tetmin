# Tetris Minimal

A clean, responsive, and mobile-friendly implementation of the classic Tetris game built with vanilla HTML, CSS, and JavaScript.

## Features

- **Classic Gameplay**: Full implementation of the standard 7 Tetris pieces (I, L, J, O, Z, S, T).
- **Responsive Design**: Optimized for both desktop and mobile devices with dynamic viewport sizing.
- **Audio System**: Custom synthesized sound effects using the Web Audio API and background music.
- **Touch Controls**: On-screen grid-based controls for mobile playability.
- **Game States**: Includes Start, Pause, and Game Over screens.
- **Progress Tracking**: Real-time Score, Level, and Next Piece preview.

## How to Play

### Desktop (Keyboard)

- **← / → Arrow Keys**: Move Piece Left / Right
- **↓ Arrow Key**: Soft Drop
- **↑ Arrow Key / Q**: Rotate Piece
- **Spacebar**: Hard Drop (Instant placement)
- **P**: Pause / Resume

### Mobile (Touch / On-Screen Buttons)

- **← / →**: Move Piece Left / Right
- **↓**: Soft Drop
- **⏬**: Hard Drop
- **↻**: Rotate Piece
- **Utility Buttons**: Stop ⏹️, Pause ⏸️, Mute 🔊

## Technology Stack

- **HTML5**: Semantic structure and Canvas API for rendering the game board.
- **CSS3**: Modern styling with CSS variables, Flexbox/Grid for layout, and glassmorphism effects (`backdrop-filter`).
- **JavaScript (ES6+)**: Game logic, collision detection, and audio synthesis without any external framework dependencies.

## Installation & Usage

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Tap "TAP TO START" to begin playing.

## Credits

- Concept & Development: "민비서의 콧노래 ♪"
- Background Music: Tetris Theme (Archive.org)
