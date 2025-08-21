# 🎮 AI Project: Turn-Based Fighting Game  

<p align="center">
  <img src="https://img.shields.io/badge/Engine-Unity-000000?logo=unity" />
  <img src="https://img.shields.io/badge/Language-C%23-239120?logo=c-sharp" />
  <img src="https://img.shields.io/github/stars/Wasif00710/AI_Project_Turn_Based_Fighting_Game?style=social" />
  <img src="https://img.shields.io/github/forks/Wasif00710/AI_Project_Turn_Based_Fighting_Game?style=social" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat&logo=github" />
</p>

---

## 📖 Overview
This project is a **Turn-Based Fighting Game** powered by Unity and AI decision-making.  
The goal is to build a system where AI agents and players engage in tactical battles,  
demonstrating concepts of **state management, reinforcement learning, and turn-based mechanics**.  

---

✨ Features
Feature	Description
🎭 Turn-based combat	Player vs AI battles with tactical decision making
🤖 AI opponent	Reinforcement Learning algorithms decide AI moves
🛡️ Defensive mechanics	Guard, dodge, and counter-attack features
⚡ Special abilities	Unique skills unlocked during the battle
🎨 Customizable characters	Add your own characters with attributes
🚀 Installation & Setup
1️⃣ Extract Game Files

Download all split files (.part1.rar, .part2.rar, .part3.rar, …).

Place them in the same folder.

Right-click the first part (.part1.rar) → Select Extract Here.

WinRAR will automatically combine them into the full Unity project.

2️⃣ Open in Unity

Launch Unity Hub.

Click Add Project → Open.

Browse to the extracted folder (AI_Project_Turn-Based_Fighting_Game).

Select the project → Unity will fetch dependencies and load them.

3️⃣ Play & Enjoy 🎮

Once loaded, click ▶️ Play in Unity.

Explore player vs AI turn-based battles.

## 🧩 Game Flow (Mermaid Diagram)

🛠️ Tech Stack

🎮 Unity (latest stable version)

🐍 C# scripting

🧠 Reinforcement Learning for AI logic

🤝 Contributing

We ❤️ contributions!

Fork the repo 🍴

Create a new branch (feature/new-idea)

Commit your changes

Open a Pull Request

📜 License

This project is licensed under the MIT License – see LICENSE
 for details.

```mermaid
flowchart TD
    A[Player Turn] -->|Choose Attack/Defend| B[AI Turn]
    B -->|AI Decision (Reinforcement Learning)| C[Battle Outcome]
    C -->|Check HP| D{Game Over?}
    D -->|No| A
    D -->|Yes| E[Winner Declared 🎉]



