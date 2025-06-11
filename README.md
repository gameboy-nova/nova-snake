## 🎮 Snake

### 📝 Description  
A single-player classic snake game where the player controls a growing snake that eats food on the screen.

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
