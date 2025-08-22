# 8-Puzzle Solver

This project provides a graphical interface to solve the **8-Puzzle problem** using different search algorithms.  
The interface is implemented in **Python (Tkinter GUI)**.

---

## How to Run

You can run the program either from a **Python development environment** or directly from a **terminal** (if Python is in your PATH):

```bash
python interface.py
```

---

## Instructions

1. Press the button **“Enter initial state”**.  
   Type the initial state as a sequence of 9 digits, where the **blank tile is represented with 0**.  

   Example:  
   ```
   125340687
   ```
   corresponds to:

   |1|2|5|  
   |3|4|0|  
   |6|8|7|

2. Select the **search strategy** from the drop-down menu **“Search Algorithm”**.  
   - If the chosen strategy requires a maximum depth, a pop-up window will appear to enter the value.

3. Press the button **“Solve”**.

4. The program will display information about the search process:
   - Nodes generated  
   - Nodes expanded  
   - Maximum nodes stored  
   - Solution cost  
   - Search depth  
   - Running time  

5. Use the control buttons below the puzzle to navigate through the solution:
   - **Reset**  
   - **Step backward / forward**  
   - **Fast backward / forward**  
   - **Stop**

---

## Available Search Algorithms

- BFS (Breadth-First Search)  
- DFS (Graph Search)  
- DFS (Backtracking)  
- Voraz (Manhattan)  
- ID (Iterative Deepening)  
- A* Manhattan  
- A* Euclidean  
- IDA* Manhattan  
- A* Misplaced Tiles  
- A* Sequences  
- A* Rows Columns  

---

## Requirements

- Python 3.x  
- Tkinter (included in most Python installations)  

---

## Example Output

```
Algorithm: A* Manhattan
Initial state: 125340687
---------------------------------
Nodes generated: 309
Nodes expanded: 114
Max. nodes stored: 191
Solution cost: 17
Search depth: 17
Running Time: 0.01 s
```
