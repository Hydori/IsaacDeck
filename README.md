# IsaacDeck

> A deck builder tool for **The Binding of Isaac: Four Souls** — generate balanced, customized card decks based on player count and personal preferences.

---

## Features

- 🃏 **Preset-based generation** — select a preset adapted to your number of players and generate a balanced deck in one click
- ⚖️ **2-player preset** — cards considered frustrating or unbalanced in duels are automatically excluded
- 👁️ **Card zoom** — hover over any card to see it enlarged and read its effects
- ✅ **Manual customization** — click any card to include or exclude it from the deck before generating
- 🎲 **Random generation** — each generation produces a different deck while respecting preset ratios
- 📱 **Fully responsive** — optimized for both desktop and mobile (long press to zoom, tap to toggle)

---

## Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

- **React + Vite** — fast, lightweight SPA
- **Tailwind CSS v4** — utility-first styling
- **Context API + useState** — global state management
- **Vercel** — deployment

---

## Getting Started

### Prerequisites

- Node.js >= 18
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/IsaacDeck.git

# Navigate to the project directory
cd IsaacDeck

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will be available at `http://localhost:5173`

---

## Project Structure

```
src/
├── components/
│   ├── ui/
│   │   └── CardItem.jsx        # Individual card display
│   └── layout/
│       ├── CardSection.jsx     # Card selection grid by type
│       └── DeckSection.jsx     # Generated deck results by type
├── context/
│   └── AppContext.jsx          # Global state
├── data/
│   ├── cards.json              # Base game card data
│   └── presets.json            # Preset rules and ratios
├── hooks/
│   └── useDeckGenerator.js     # Deck generation logic
├── App.jsx
└── main.jsx
```

---

## Roadmap

- [ ] Additional presets (3 players, 4+ players)
- [ ] Draft mode preset
- [ ] Coop mode preset
- [ ] Custom preset creation
- [ ] Deck save & seed system
- [ ] Expansion support

---

## About

This project was built as a personal tool to improve the Four Souls experience for 2-player games, and as a portfolio project to demonstrate front-end development skills.

Built with ❤️ by [William](https://github.com/Hydori)
