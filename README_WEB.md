# Snake AI Trainer - Web Version

This project has been configured to run in web browsers using Pygbag!

## Running Locally

To test the web version locally:

```bash
cd Snake-RL
python -m pygbag main.py
```

Then open your browser to `http://localhost:8000`

## Deploying to GitHub Pages

The web version will be automatically built and deployed to GitHub Pages using GitHub Actions.

## How It Works

- **main.py**: The async entry point for the web version
- **Pygbag**: Converts the Python/Pygame code to WebAssembly
- **GitHub Pages**: Hosts the compiled web version

## Features

Watch the AI learn to play Snake in real-time in your browser:
- Neural network Q-learning
- Live training visualization
- Score tracking and plotting
- Progressive improvement over games

## Browser Compatibility

Works best in modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari

Requires WebAssembly support.