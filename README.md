# 🐦 Bird Sort Quest Solver

A web-based puzzle solver for the Bird Sort Quest game with advanced features including discovery mode and hidden mode for progressive bird revelation.

## 🎮 Live Demo

Visit: [https://YOUR-USERNAME.github.io/bird-sort-solver/](https://YOUR-USERNAME.github.io/bird-sort-solver/)

## ✨ Features

- **Puzzle Solver**: Automatically finds optimal solutions using beam search algorithm
- **Discovery Mode**: Reveals hidden birds step-by-step
- **Hidden Mode**: Progressive bird revelation during solution playback
- **Bird Customization**: Change colors and upload custom images
- **Database Management**: Save and load puzzles
- **Flying Animations**: Smooth bird movement animations
- **Edit Mode**: Create custom puzzles
- **Solution Playback**: Step through solutions with speed controls

## 🚀 Quick Start

### Option 1: View Online
Just visit the GitHub Pages link above!

### Option 2: Run Locally

1. Clone this repository:
```bash
git clone https://github.com/YOUR-USERNAME/bird-sort-solver.git
cd bird-sort-solver
```

2. Open `index.html` in your browser:
```bash
open index.html  # macOS
# or just double-click the file
```

That's it! No build tools or npm required.

## 📁 Project Structure

```
bird-sort-solver/
├── index.html              # Main HTML file with CDN links
├── BirdSortSolver-CDN.jsx  # React component (JSX)
└── README.md               # This file
```

## 🛠️ Technology Stack

- **React 18** (via CDN)
- **Tailwind CSS** (via CDN)
- **Babel Standalone** (for JSX transformation)
- Pure JavaScript (no build tools needed!)

## 📖 How to Use

1. **Setup Puzzle**: Use Edit Mode to configure your puzzle
2. **Solve**: Click "Solve Puzzle" to find the solution
3. **Playback**: Use playback controls to step through the solution
4. **Hidden Mode**: Toggle hidden mode for progressive bird revelation
5. **Save/Load**: Save puzzles to a database file for later use

### Discovery Mode

For puzzles with unknown birds:
1. Mark uncertain positions as "unsure" (right-click in edit mode)
2. Enable Discovery Mode
3. Follow the suggested moves to reveal hidden birds
4. Record what you find

### Hidden Mode

When viewing solutions:
1. Toggle "Hidden Mode" in playback controls
2. Only top birds are visible initially
3. Birds are revealed progressively as you step through
4. Adjacent birds of the same type are revealed together

## 🎨 Customization

- **Bird Colors**: Click color pickers in the Bird Palette
- **Bird Images**: Upload custom images for each bird type
- **Bird Size**: Adjust the size slider (32-64px)
- **Unsure Color**: Choose the color for uncertain positions

## 💾 Database Features

- **Save Game**: Save current puzzle configuration and solution
- **Load Game**: Restore saved puzzles
- **Save Theme**: Save your customized colors and images
- **Load Theme**: Restore saved themes
- **Export/Import**: Download and upload database files

## 🔧 Development

This project uses no build tools! The JSX is transformed at runtime by Babel Standalone.

To modify:
1. Edit `BirdSortSolver-CDN.jsx`
2. Refresh your browser
3. Changes appear immediately

## 📝 Notes

- Works best in modern browsers (Chrome, Firefox, Safari, Edge)
- Large puzzles may take a moment to solve
- Database files are JSON and can be edited manually
- All data is stored in browser localStorage or downloaded files

## 🤝 Contributing

Feel free to open issues or submit pull requests!

## 📄 License

MIT License - feel free to use this for any purpose!

## 🙏 Acknowledgments

Built for the Bird Sort Quest mobile game community.

---

**Note**: Replace `YOUR-USERNAME` in the URLs with your actual GitHub username!
