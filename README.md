# Conway’s Game of Life 

## Introduction
Conway’s Game of Life is a cellular automaton . This project is a JavaScript implementation that uses the HTML5 Canvas API to display and interact with the simulation.

## Features
- Interactive grid-based simulation  
- Real-time rendering with Canvas  
- Control buttons and keyboard shortcuts  
- Predefined classic patterns  

## Project Structure
### Game Class
Responsible for the core logic of the simulation:
- Grid initialization
- Random cell generation
- Neighbor counting
- Applying Conway’s Game of Life rules

### Renderer Class
- Renders the grid on an HTML5 Canvas
- Displays live cells as white squares

## How to Use
1. Open the `localhost` in your web browser.
2. Use the **Start** button or press `s` to run or pause the simulation.
3. Click **Randomize** or press `r` to generate random live cells.
4. Click **Clear** or press `c` to reset the grid.
5. Add predefined patterns using buttons or keyboard shortcuts:
   - `g` – Glider Gun  
   - `p` – Pulsar  
   - `d` – Penta-Decathlon
6. Observe how the cells evolve over time based on Conway’s rules.

## Controls
**Keyboard Shortcuts:**
- `s` – Start / Stop simulation  
- `r` – Randomize grid  
- `c` – Clear grid  
- `g` – Add Glider Gun  
- `p` – Add Pulsar  
- `d` – Add Penta-Decathlon

## How to Run

Ensure Node.js is installed on your computer.  
Open a terminal in the project folder.  
Install dependencies:  
```
npm install
```
Start the Vite development server:  
```
npm run dev  
```  
Open the provided localhost URL in your browser. 
