# FIFA World Cup 2026 - Game

A pixel-perfect replica of the FIFA World Cup 2026 game interface.

## Structure

```
├── game-clean.html      # Main game page
├── bg.png              # Background image
├── header/             # Header images
│   ├── header-bg.png
│   ├── header-left.png
│   ├── header-center.png
│   └── header-right.png
├── players/            # Player images
│   ├── ANDRADE-ANDRES.png
│   ├── BARCENAS-YOEL.png
│   └── ...
└── archive/            # Old files (gitignored)
```

## Features

- Responsive design (mobile-first)
- Overlapping hint circles
- Player cards with real images
- Dynamic sizing with CSS `clamp()` and `min()`

## Usage

Simply open `game-clean.html` in a browser or run:

```bash
npx serve .
```
