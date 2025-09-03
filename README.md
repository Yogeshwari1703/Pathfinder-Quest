
# 🕹️ Pathfinder Quest
**A Pygame visualization of Best First Search vs A\* pathfinding algorithms**

---

## 📖 About the Game
Pathfinder Quest is an interactive grid-based pathfinding visualizer built using **Python** and **Pygame**.  
It allows players to:
- Set **Start** and **End** nodes.
- Add **barriers (walls)** to create obstacles.
- Run two different algorithms:
  - **Best First Search (Greedy Search)** 🟦
  - **A\* Search Algorithm** 🟥  

This makes it easy to compare how each algorithm explores the grid and finds the shortest path.

---

## 🎮 Controls
- **Left Click**:  
  - First click → Set **Start Node** (Green)  
  - Second click → Set **End Node** (Purple)  
  - After that → Place **Barriers** (Black)  
- **Right Click**: Remove/reset a node  
- **B Key**: Run **Best First Search**  
- **A Key**: Run **A\*** Search  
- **Close Window**: Quit the program  

---

## ⚙️ Installation
1. Clone the repository:
  ````
   git clone https://github.com/yourusername/pathfinder-quest.git
````

2. Navigate into the project folder:

   ```bash
   cd pathfinder-quest
   ```
3. Install dependencies:

   ```bash
   pip install pygame
   ```
4. Run the game:

   ```bash
   python main.py
   ```

---

## 📊 Algorithms Compared

* **Best First Search**:

  * Greedy approach, uses only the heuristic (Manhattan distance).
  * Fast but not always optimal.

* **A\* Search**:

  * Uses both **actual cost (g)** and **heuristic (h)**.
  * Guarantees the shortest path if the heuristic is admissible.


---

## 📜 License

This project is open-source under the **MIT License**.

---

🚀 Explore, block, and find the path with **Pathfinder Quest**!
