# 🦖🎮 Google T-Rex Runner (C# WPF)

**Google T-Rex Runner** is a simple yet addictive endless runner game inspired by the classic Chrome offline dinosaur game. This project demonstrates 2D game mechanics, animation, input handling, collision detection, and smooth rendering using **C#** and **WPF**.

Built with performance and minimalism in mind, the game features:

* Keyboard (Up and Down) input for jump and duck actions
* Randomly spawning obstacles with increasing difficulty
* Score tracking based on distance run
* Simple game over and restart mechanics

---

## 🖼️ Game Preview

<img width="896" height="520" alt="T-Rex" src="https://github.com/user-attachments/assets/be092d98-efb8-4f50-9aeb-b91a7c97c143" />


---

## 📌 Key Features

* 🎮 **Spacebar or Up Arrow to jump**
* ⬇️ **Down Arrow to duck**
* 🪨 **Random cacti and flying pterodactyl obstacles**
* 💥 **Collision detection with game over screen**
* 🔁 **Restart game from game over screen**
* 📈 **Progressively faster gameplay for challenge**
* 🎨 **Smooth animations with WPF Storyboards and Canvas**

---

## 🛠️ Tech Stack

* **Language:** C# 10+
* **Framework:** .NET 6+ (or .NET Framework)
* **GUI Framework:** WPF (Windows Presentation Foundation)
* **IDE:** Visual Studio 2022 or newer recommended

---

## 💻 System Requirements

Make sure your system meets the following before running the app:

* ✅ Windows 10 or later
* ✅ .NET 6 Runtime or appropriate .NET Framework installed
* ✅ Visual Studio with WPF workload for development

---

## 📦 Project Structure

```bash
TRexRunner/
├── App.xaml                # Application startup  
├── MainWindow.xaml         # Main game window (UI + canvas)  
├── MainWindow.xaml.cs      # Game logic, rendering, and event handling  
├── Assets/                 # Images, sprite sheets, sound effects  
├── Models/                 # Game entities (T-Rex, Obstacles)  
├── Utils/                  # Helper classes (collision, timers)  
└── README.md               # This file  
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/TRexRunner.git
cd TRexRunner
```

### 2. Open the Project

Open `TRexRunner.sln` in Visual Studio.

### 3. Build and Run

* Press **F5** or click **Start** to build and run the game.

---

## 🎯 Gameplay Instructions

* Press **Spacebar** or **Up Arrow** to jump over obstacles.
* Press **Down Arrow** to duck under flying enemies.
* Avoid hitting cacti or pterodactyls.
* Your score increases as you run longer.
* When you collide, the game ends and shows your final score.
* Press **R** or click **Restart** to play again.

---

## ⚙️ Customization Tips

* 🎨 Swap or add obstacle and dinosaur sprites in the `Assets` folder.
* ⏱️ Adjust game speed and difficulty in `MainWindow.xaml.cs` (timer intervals).
* 📊 Enhance scoring or add high score persistence using local storage or files.
* 🔊 Add sound effects or background music using WPF `MediaPlayer`.

---

## 📚 Concepts Demonstrated

* Event-driven programming with WPF
* Animation and game loop using `DispatcherTimer`
* Keyboard input handling
* Basic collision detection with bounding rectangles
* Object-oriented design for game entities
* Simple state management (running vs game over)

---

## 🧪 Known Limitations

* No mobile or touch input support
* Simple rectangular collision (no pixel-perfect)
* No pause functionality
* Limited obstacle variety

---

## 📜 License

This project is open-source and free for educational or personal use.

---

## 🙌 Acknowledgements

Inspired by the Google Chrome offline T-Rex runner game. Thanks to the WPF community for enabling powerful desktop UI and game development with ease!
