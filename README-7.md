# 8×8 Rock-Paper-Scissors Q-Learner Simulation

## Overview
This project is an **interactive reinforcement learning simulation** where four Q-learning agents compete on an 8×8 grid using Rock, Paper, and Scissors as strategic items. Each agent starts in a corner and moves around the board, picking up items and battling other agents according to classic RPS rules.

The goal is to claim at least 40 tiles (over 50% of the board) or to be the last surviving agent. Over time, agents learn optimal strategies for when to pick up or skip items, balancing survival, territory control, and combat outcomes.

---

## Features
- **Four Q-learning agents** (Red, Blue, Green, Yellow) compete on the board.  
- **Classic RPS mechanics** determine combat outcomes (Rock > Scissors, Scissors > Paper, Paper > Rock).  
- **Rewards system** encourages territory capture, winning battles, and surviving games.  
- **Q-learning updates** are applied based on step rewards, wins, losses, and item pickups.  
- **Auto Next mode** plays continuous games, allowing agents to refine strategies across multiple rounds.  
- **Dynamic item spawning** every 20–30 steps keeps the board balanced and competitive.  
- **Interactive UI controls**:
  - Start, Pause, and New Map buttons.  
  - Adjustable speed (steps per second).  
  - Adjustable ε (exploration rate).  
- **Statistics panel** shows tile counts, game wins, and per-item victory trends.  
- **Game log** records battles, item spawns, and winners.

---

## How to Run
1. Open `RPSGame.html` in a modern web browser (Chrome, Firefox, Safari).  
2. Click **Start** to begin the simulation.  
3. Adjust parameters (speed, ε) to observe how they affect agent learning.  
4. Use **Auto Next** to watch repeated games and long-term learning patterns.  

---

## Educational Value
This project demonstrates how **multi-agent reinforcement learning** works in a competitive environment.  
It is useful for studying:  
- Exploration vs. exploitation tradeoffs.  
- Emergent strategies in adversarial multi-agent systems.  
- How localized rewards (tile claiming) and global outcomes (wins/losses) shape agent policies.  

---

## File
- `RPSGame.html` → Full interactive simulation with embedded JavaScript and UI.  
