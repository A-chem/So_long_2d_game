
# 🎮 So_long (42 Project)

`So_long` is a 42 project focused on creating a **2D top-down game in C** using **MiniLibX**. The main objective is to navigate a map, collect all items, and reach the exit while handling proper game logic and graphics.

<img width="512" height="512" alt="unnamed" src="https://github.com/user-attachments/assets/4db9f94b-9c80-42d1-8718-a67358edf401" />

---

## 🚀 Project Overview

The program loads a map from a `.ber` file and renders it using MiniLibX. The player can move using keyboard input and must collect all items before reaching the exit. The game tracks the number of moves and ends when the player wins.

Key elements of the map:

* `1` → Wall  
* `0` → Empty space  
* `P` → Player start position  
* `C` → Collectible  
* `E` → Exit  

---

## 🔑 Key Concepts

* **Map Parsing & Validation**: Ensure the map is rectangular, surrounded by walls, and contains required elements (player, collectibles, exit).  
* **Graphics & Rendering**: Draw each tile using MiniLibX images.  
* **Player Movement**: Update the map and redraw the game in response to keyboard input.  
* **Game Logic**: Track moves, collected items, and win/lose conditions.  
* **Memory Management**: Allocate and free memory correctly to avoid leaks.  

---

## ⚙️ Requirements

* Must read a map from a `.ber` file.  
* Must render the map correctly using MiniLibX.  
* Must allow player movement with keyboard input.  
* Must track collected items and moves.  
* Must end the game when the player reaches the exit after collecting all items.  
* Must handle invalid maps gracefully.  

---

## 📝 Example Usage

```bash
./so_long maps/map.ber
````

The game will display the map, and the player can move using arrow keys or `WASD`. Collect all `C`s and reach `E` to win.

---

## 🎯 Learning Outcomes

* Learn **2D graphics programming in C** using MiniLibX.
* Handle **keyboard input and events**.
* Implement **game logic, move tracking, and map validation**.
* Practice **dynamic memory management and error handling**.

---

## ✅ Status

✔️ Project completed and validated at 42.

---

## 📚 Further Resources

* [MiniLibX Library Explained (Medium Article)] https://medium.com/@devabdilah/minilibx-mlx-ff9ad1c52521

---
