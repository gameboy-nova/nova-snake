<p align="center">
<img src="https://github.com/user-attachments/assets/bfbb3a7e-0d50-4bb0-8640-6f42f269f9f3" width="300">
</p>

<h1 align="center"> 
Snake
</h1>
<p align="center">
A single-player classic snake game where the player controls a growing snake that eats food on the screen.
</p>

---
## 🎮 Gameplay Showcase

Here’s a quick look at the game in action:
<p align="center">
<img src="https://github.com/user-attachments/assets/4618f4e2-003d-40a8-af22-c74b5ee0a067" width="500">
</p>

---

### 🕹️ Controls

| Button   | Action    |
|----------|-----------|
| A_UP     | Move up   |
| A_DOWN   | Move down |
| A_LEFT   | Move left |
| A_RIGHT  | Move right|
| EXIT     | Exit game |

---

### 📦 Memory Usage  
- Grid: 20×15 blocks (each block = 2 bytes → total: **600 bytes**)  
- Snake coordinates and apple stored in structured memory  
- Movement based on indexed updates of the snake body  

---

### 🧠 Logic Overview  
The snake is represented as a list of coordinates in a buffer.  
When it eats food, it grows longer.

---

### 🧩 Game Loop Structure  
1. Read input  
2. Move snake  
3. Check collisions  
4. Update screen  
5. Delay  

---

### ❌ End Conditions  
- Collision with self  
- Exit input is received  

---

### 🧪 Notes & Improvements  
- Add speed increase for higher difficulty over time
