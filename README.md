# Tetris Minimal

A clean, responsive, and mobile-friendly implementation of the classic Tetris game built with vanilla HTML, CSS, JavaScript, and Supabase.

## Features

- **Classic Gameplay**: Full implementation of the standard 7 Tetris pieces (I, L, J, O, Z, S, T).
- **🏆 Global Leaderboard**: Persistent high score system powered by Supabase.
- **Responsive Design**: Optimized for both desktop and mobile devices with dynamic viewport sizing.
- **Audio System**: Custom synthesized sound effects using the Web Audio API and background music.
- **Touch Controls**: On-screen grid-based controls for mobile playability.
- **Game States**: Includes Start, Pause, and Game Over screens.

## How to Play

### High Scores
Check the top 5 scores globally! If you achieve a new high score, you'll be prompted to enter your name.

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
- **CSS3**: Modern styling with CSS variables, Flexbox/Grid for layout, and glassmorphism effects.
- **JavaScript (ES6+)**: Game logic, collision detection, and audio synthesis.
- **Supabase**: Backend-as-a-Service for storing high scores (PostgreSQL).

## Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/heroyik/tetmin.git
   ```

2. **Supabase Setup**:
   - Create a project on [Supabase](https://supabase.com).
   - Run the SQL in `setup_highscores.sql` to create the table and policies.
   - Create a file `js/config.js` with your credentials:
     ```javascript
     const SUPABASE_CONFIG = {
         url: 'YOUR_SUPABASE_PROJECT_URL',
         key: 'YOUR_SUPABASE_ANON_KEY'
     };
     window.SUPABASE_CONFIG = SUPABASE_CONFIG;
     ```

3. **Run**:
   - Open `index.html` in a browser.

## Credits

- Concept & Development: "민비서의 콧노래 ♪"
- Background Music: Tetris Theme (Archive.org)
