# ⬡ Wumpus Logic Agent (Web-Based)

A web-based interactive simulation of the **Wumpus World**, where an agent explores a grid environment containing hidden hazards (Pits & Wumpus) and a goal (Gold). The system provides real-time visualization, percept feedback, and manual/automatic movement controls.

---

## 🎮 Overview

This project implements a dynamic grid-based environment inspired by the classic **Wumpus World Problem** from Artificial Intelligence.

The agent:
- Starts at a **random position**
- Navigates through the grid
- Encounters hidden hazards (Pits & Wumpus)
- Uses percepts (**Breeze, Stench, Glitter**) to understand surroundings
- Wins by finding the **Gold** or loses if it enters a hazard cell

---

## 🚀 Features

### 🧩 Environment
- Dynamic grid size (3×3 up to 10×10)
- Random placement of:
  - Pits
  - Wumpus
  - Gold
- Random agent start position

---

### 🎨 Visualization
| Cell Type | Color |
|----------|------|
| Unknown / Unvisited | Gray |
| Safe | Green |
| Pit / Wumpus | Red |
| Gold | Yellow |
| Agent | Yellow Border 🤖 |

- Hazards are hidden during gameplay
- Fully revealed when the game ends

---

### 👁️ Percepts System
The agent receives percepts based on adjacent cells:

| Percept | Meaning |
|--------|--------|
| 💨 Breeze | Adjacent to a Pit |
| 🟣 Stench | Adjacent to Wumpus |
| ✨ Glitter | Gold is present in current cell |

Percepts are displayed **with both icons and names** in real-time.

---

### 🎮 Controls

#### Manual Movement
- ⬆️ Up  
- ⬇️ Down  
- ⬅️ Left  
- ➡️ Right  
- Arrow keys also supported

#### Automatic Mode
- **AUTO RUN** button moves the agent randomly at fixed intervals

---

### 🧠 Game Outcomes

| Condition | Result |
|----------|--------|
| Agent finds Gold | 🎉 WIN |
| Agent enters Pit | 💀 DEAD |
| Agent meets Wumpus | 💀 DEAD |

At the end:
- All hidden hazards are revealed on the grid

---

## 🛠️ How to Run

1. Download or copy the **HTML file** (e.g., `index.html`) to your system.

2. Make sure everything is inside this **single HTML file** (no extra JS or CSS files required).

3. Open the file:
   - Double-click on `index.html`  
   **OR**  
   - Right-click → Open with → Chrome / Edge / Firefox

4. The game will start directly in the browser.

5. Controls:
   - Use arrow keys or on-screen buttons to move the agent
   - Click **AUTO RUN** for automatic movement
   - Select grid size before starting (3×3 to 10×10)

---

