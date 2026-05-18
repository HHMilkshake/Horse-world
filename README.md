# 🐴 Horse World

A horse simulation game built with React, TypeScript, and Canvas API.

## Features

- **Procedurally Generated World**: Explore a randomly generated map with different terrain types
- **Horse AI System**: Horses have realistic behaviors, stats, and needs
- **Interactive Gameplay**: Click to select horses and manage their activities
- **Real-time Simulation**: 60 FPS game loop with continuous horse updates
- **Management System**: Feed, pet, and rest your horses to keep them healthy and happy

## Game Mechanics

### Horse Stats
- **Health**: Affected by hunger and happiness
- **Hunger**: Increases over time, can be reduced by feeding
- **Energy**: Depletes during activities, restored by sleeping
- **Happiness**: Improves through petting and playing

### Terrain Types
- 🟩 **Grass**: Safe terrain for roaming
- 💧 **Water**: Can be dangerous, horses avoid
- 🌲 **Forest**: Natural habitat
- ⛰️ **Mountain**: Difficult terrain
- 🏠 **Stable**: Safe haven for horses

### Activities
- **Idle**: Resting state
- **Moving**: Traveling to target destination
- **Eating**: Consuming food to reduce hunger
- **Sleeping**: Restoring energy
- **Playing**: Social interaction for happiness

## Getting Started

### Prerequisites
- Node.js 14+ 
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/HHMilkshake/Horse-world.git
cd Horse-world

# Install dependencies
npm install

# Start development server
npm start
```

The game will open at `http://localhost:3000`

### Build for Production

```bash
npm run build
```

## How to Play

1. **Select a Horse**: Click on any horse to select it (a red ring appears)
2. **Move**: Click on any location on the map to move your selected horse there
3. **Manage Stats**: Use the control buttons to feed, pet, or rest your horse
4. **Watch Behavior**: Observe your horses as they autonomously handle their needs

## Project Structure

```
src/
├── components/       # React components
│   ├── Game.tsx     # Main game component
│   └── Game.css     # Game styles
├── game/
│   └── horse.ts     # Horse simulation logic
├── world/
│   └── map.ts       # World generation and map system
├── App.tsx          # App entry point
├── App.css          # App styles
├── index.tsx        # React DOM render
└── index.css        # Global styles
```

## Technologies

- **React 18**: UI framework
- **TypeScript**: Type-safe JavaScript
- **Canvas API**: Game rendering
- **CSS3**: Styling and animations

## Future Enhancements

- [ ] Horse breeding system
- [ ] Multiple game regions
- [ ] Multiplayer support
- [ ] Advanced AI pathfinding
- [ ] Sound and music
- [ ] Save/load system
- [ ] Horse customization
- [ ] Racing mini-games

## License

MIT

## Author

HHMilkshake

---

Enjoy your horse simulation adventure! 🐴✨
