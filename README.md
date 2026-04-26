# Ambient Capital

A property trading board game for the AI startup world. Standard Monopoly rules, SF tech ecosystem flavor.

🎮 **[Play Now](#)** | 📖 **[View Rulebook](rulebook.html)**

## About

**Ambient Capital** is a web-based Monopoly-style game themed around the AI/SF startup ecosystem. It features:

- **Exact Monopoly mechanics** - Same rules, same values, same gameplay
- **AI startup theme** - Properties like "Sam Altman's Napkin," "The YC Batch," and "Thine HQ"
- **2-6 players** - Hot seat multiplayer on the same device
- **Pure client-side** - No server required, runs entirely in the browser

## Game Features

- 40 board spaces including 22 properties across 8 color groups
- 4 Railroads (YC Batch, SF→NYC Red-Eye, Caltrain, Paul Graham's Yacht)
- 2 Utilities (GPU Cluster, AWS Credits)
- Vibe Cards and Pivot Cards (Community Chest & Chance equivalents)
- Building mechanics with "Engineers" (houses) and "GPU Clusters" (hotels)
- Mortgage system, trading, auctions, and bankruptcy rules
- Mobile-responsive design

## Tech Stack

- Pure HTML/CSS/JavaScript
- No dependencies or build process
- Self-contained single-page application
- Google Fonts (Playfair Display, DM Mono, DM Sans)

## Files

- `index.html` - Main game interface
- `rulebook.html` - Complete rulebook with all game rules
- `README.md` - This file

## Local Development

1. Clone or download this repository
2. Open `index.html` in a modern web browser
3. No build step or server required!

```bash
# Simple local server (optional)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Deployment to GitHub Pages

1. Create a new GitHub repository
2. Push this code to the repository
3. Go to Settings → Pages
4. Set Source to "Deploy from a branch"
5. Select `main` branch and `/ (root)` folder
6. Click Save

Your game will be live at `https://your-username.github.io/your-repo-name/`

## How to Play

1. Open the game and click "Start Game"
2. Enter 2-6 player names and choose archetypes
3. Roll dice, buy properties, build Engineers and GPU Clusters
4. Trade with other players, mortgage properties when cash-strapped
5. Last player remaining who hasn't gone bankrupt wins!

## Game Rules Summary

- Each player starts with $1,500
- Roll dice to move around the board
- Buy unowned properties or they go to auction
- Own all properties in a color group to build
- Pay rent when landing on opponent's properties
- Go to "Just Pivoting" (jail) by rolling doubles 3 times
- Mortgage properties for half their purchase price
- Build evenly across property groups
- Last founder standing wins!

For complete rules, see [rulebook.html](rulebook.html).

## Credits

- Game design: Standard Monopoly mechanics
- Theme and flavor: AI/SF startup ecosystem
- Featured property: **Thine HQ** at position 39 (Boardwalk) - [thine.com](https://thine.com)

## License

This is a fan-made themed version of Monopoly. Monopoly is a registered trademark of Hasbro, Inc.

---

**Built for founders, VCs, and people who say "we're building in the open."**
