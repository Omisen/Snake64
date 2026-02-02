# Snake64 🐍

A classic Snake game implementation written in Rust using the `bracket-lib` terminal library. Navigate your snake, eat fruits, grow longer, and try to beat your high score without colliding with yourself!

## 🎮 Features

- **Classic Snake Gameplay**: Control a snake that grows longer as it eats fruit
- **Terminal-Based Graphics**: Built with bracket-lib for a retro terminal aesthetic
- **Pac-Man Effect**: Snake wraps around screen edges for continuous gameplay
- **Main Menu System**: Clean start menu and game over screens
- **Score Tracking**: Track your snake's length as your score
- **Smooth Controls**: Responsive directional controls with frame-rate capping

## 📋 Requirements

- **Rust**: 1.70+ (2024 edition)
- **Cargo**: Latest stable version

## 🚀 Installation

### From Source

1. Clone the repository:
```bash
git clone https://github.com/Omisen/Snake64.git
cd Snake64
```

2. Build and run:
```bash
cargo run
```

## 🎯 How to Play

1. Launch the game using `cargo run`
2. Press **SPACE** or **ENTER** at the main menu to start
3. Use **arrow keys** to control the snake's direction:
   - **↑** - Move Up
   - **↓** - Move Down
   - **←** - Move Left
   - **→** - Move Right
4. Eat fruits (🍎) to grow your snake and increase your score
5. Avoid colliding with your own tail!
6. The snake wraps around screen edges (Pac-Man style)

### Game Mechanics

- **Screen Size**: 80x50 terminal characters
- **Frame Rate**: 15 FPS for smooth gameplay
- **Starting Length**: 4 segments
- **Growth**: +1 segment per fruit eaten
- **Win Condition**: None - keep growing as long as you can!
- **Lose Condition**: Colliding with your own tail


## 📦 Dependencies

- **[bracket-lib](https://github.com/amethyst/bracket-lib)** (v0.8.7) - Terminal rendering and input handling
- **[rand](https://github.com/rust-random/rand)** (v0.9.0) - Random number generation for fruit placement


## 📝 License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [bracket-lib](https://github.com/amethyst/bracket-lib) by the Amethyst team
- Inspired by the classic Snake game

---

**Enjoy the game! 🐍**