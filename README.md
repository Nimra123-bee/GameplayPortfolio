# 🧩 Block Slider – 2D Puzzle Game

Block Slider is a 2D grid-based puzzle game developed in Unity, where players strategically slide blocks horizontally to clear lines, manage space, and complete level objectives under different constraints.

---

## 🎥 Gameplay Preview

[GameplayVideo](https://drive.google.com/file/d/1MLoKvM1qd6xZey5ZnUeU8o9R_iSYy60G/view?usp=drive_link)

---

## 📸 Screenshots

[Screenshots](https://github.com/Nimra123-bee/Gameplay_Screenshots)

---

## 🎯 Core Gameplay

- Players slide blocks **horizontally (left/right)**  
- Each move causes the **grid to rise**  
- Blocks **fall automatically** into empty spaces  
- Completing a full row clears it, regardless of block color or shape  
- Line clears trigger **VFX and score updates**

---

## 🧠 Game Systems

### 🟦 Grid & Mechanics
- Custom grid system for block placement and alignment  
- Gravity-based falling system  
- Row detection and clearing logic  

### 🎮 Level System
Implemented using ScriptableObjects with dynamic scaling:

- **Move-Based Levels**
  - Limited number of grid rises (moves)
  - Increasing difficulty (fewer moves, more targets)

- **Timer-Based Levels**
  - Time-limited gameplay
  - Increasing time and line targets per level

- **Progress-Based Levels**
  - Fill progress bar by clearing lines  

---

## 💰 Reward & Combo System

- Rewards based on player efficiency  
- Optimized performance → higher coin rewards  

**Combo System:**
- 2 lines → +1 coin  
- 3 lines → +3 coins  
- 4+ lines → higher rewards  

---

## ⚡ Power-Ups

- ⏱️ Time Extend – increases level time  
- 📈 Rise Extend – clears bottom rows  
- 💥 Block Burst – removes blocking tiles  
- ↩️ Undo – reverses last move (including score & progress rollback)

---

## 🎨 UI & Visual Feedback

- UI animations using DOTween  
- Smooth panel transitions and text animations  
- Coin animations and reward feedback system  

---

## ✨ VFX Implementation

- Custom VFX created using:
  - Unity Particle System  
  - Shader Graph  
  - Post Processing  

Includes:
- Line clear effects
- coins feedback
- confettie effect
- Combo feedback  
- Pickup effects  
- Reward animations (coin fly, confetti)

---

## 🧩 Technical Challenges

- **Grid Alignment Issues**
  - Fixed using pixel adjustments and cell center calculations  

- **Dynamic VFX Coloring**
  - Implemented logic to detect last block contributing to line completion  

- **UI & World Space Rendering Conflict**
  - Resolved by using Screen Space - Camera canvas for VFX layering  

---

## 🛠️ Tools & Technologies

- Unity (2D)  
- C#  
- DOTween  
- Particle System  
- Shader Graph  
- Post Processing  

---

## 📌 Status

Currently in development. Upcoming features include:
- Shop system  
- Ads integration  
