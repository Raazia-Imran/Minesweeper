# 🧠 Minesweeper Clone in Unity  
**🎮 Nostalgic Games – Part 3**

A modern take on the classic Windows **Minesweeper**, built using **Unity** and **C#** as part of my self-initiated *Nostalgic Games Series*. This project helped me strengthen my grip on grid-based logic, recursion, and clean game structure in Unity.

---

## 🛠 Built With

- 🎮 Unity (2021.3 LTS+)
- 💻 C#
- 🧠 Visual Studio
- 🎨 Custom 2D Sprites (Photoshop)

---

## 🚩 Features

- Dynamic **grid-based gameplay**
- Left-click to **reveal cells**
- Right-click to **place/remove flags**
- Recursive logic to reveal empty zones
- **Bomb detection** with game over animation
- **Victory state** detection
- **Timer + Mine counter**
- **Restart button** for replayability

---

## 📂 Project Structure

```

Assets/
├── Scripts/
│   ├── Cell.cs
│   ├── GridManager.cs
│   ├── GameManager.cs
│   └── Timer.cs
├── Sprites/
│   ├── Bomb.png
│   ├── Flag.png
│   └── CellStates/
├── Scenes/
│   └── Minesweeper.unity
└── UI/
└── Canvas (Timer, Mine Counter, Buttons)

````

---

## ▶️ How to Play

- Left-click a cell to reveal it
- Right-click to place a flag on a suspected bomb
- Uncover all safe cells to win
- Hitting a bomb ends the game

---

## 🧩 How to Run

### 🔧 Prerequisites

- Unity Hub + Unity Editor (preferably 2021.3 LTS or above)
- Visual Studio with Unity integration

### 📥 Setup Steps

1. **Clone this repository**  
```bash
git clone https://github.com/yourusername/Minesweeper-Unity.git
````

2. **Open in Unity Hub**

   * Add the cloned folder as a new project

3. **Open the Scene**

   * Navigate to `Assets/Scenes/Minesweeper.unity`

4. **Click ▶️ Play** in Unity Editor to start the game

---

## 🧠 What I Learned

* Recursive logic and safe zone flood fill
* Managing game states and player feedback
* Working with **Tilemaps**, **2D Colliders**, and UI
* Creating clean, modular C# scripts
* Handling win/loss conditions

---

## 💡 Future Improvements

* Difficulty selection (Easy, Medium, Hard)
* Custom board size support
* Sound effects and animations
* Mobile touch controls
* High score system


## 📚 Related Projects

This is part of my **Nostalgic Games Series**:

1. Super Mario Clone (Unity)
2. Flappy Bird
3. **Minesweeper** ← *You are here*
4. Tetris Clone
5. Classic Dash

---

## 🙋‍♀️ About Me

Hi, I'm **Raazia Imran Reshamwala** – a first-year Software Engineering student passionate about game development and visual problem solving. This project helped me think logically and visually, and I hope it helps other beginners as well!

---

## ⭐️ Support

If you found this useful or learned something new, feel free to star ⭐ the repo and follow for more nostalgic clones and beginner-friendly games!

```

