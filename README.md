# VISUAL MEMORY - Memory Game in MS Excel


## 🎮 PROJECT DESCRIPTION
**Visual Memory** is a logical memory challenge built entirely using **VBA**. The game is designed to test and improve the player's spatial memory.

The mechanics are simple but addictive: a pattern of white tiles appears briefly on a grid. The player must memorize the pattern and recreate it without making a single mistake. As the player progresses, the difficulty increases through dynamic board scaling and an increasing number of targets.

## ✨ KEY FEATURES
- **Dynamic Difficulty Scaling:** The board size and the number of tiles to find grow automatically as you progress, with complexity increasing every 3 levels.
- **Session High Score:** Tracks your best performance in real-time during the current session, encouraging self-improvement.
- **Anti-Tamper Design:** The game board is password-protected using `UserInterfaceOnly` logic, preventing accidental cell edits while allowing the game engine to run smoothly.
- **Optimized Rendering:** Integrated screen-updating management ensures the memorization phase is visible and consistent across different hardware configurations.
- **Dark Mode UI:** A clean, professional aesthetic designed for focus and reduced eye strain.

## 🚀 HOW TO RUN THE GAME
⚠️ SECURITY NOTICE
If you see a red bar: "Microsoft has blocked macros because the source of this file is untrusted"
➔ Close the Excel workbook.
➔ Right-click the file ➔ Properties.
➔ General Tab ➔ Locate Security (at the bottom).
➔ Enable "Unblock" ➔ Click Apply.
➔ Re-open the file and enable content.
1. **Open the File:** Launch the game using Microsoft Excel. Ensure the file extension is `.xlsm`.
2. **Enable Macros:** Upon opening, Excel will display a yellow **"Security Warning"** bar. Click **"Enable Content"** to allow the game logic to function.
3. **Automatic Initialization:** The game will run its setup routine automatically, preparing the interface.
4. **Start Playing:** Click the **"Start Game"** button on the main sheet to begin your first level.

## 💻 SYSTEM REQUIREMENTS
- **Software:** Microsoft Excel (2010 or newer recommended for full RGB color support).
- **Settings:** Macros must be enabled.
- **OS:** Windows environment or macOS with functional VBA support.

## 📂 DOCUMENTATION
For a deeper dive into the architecture and maintenance of the project, please refer to:
- **Functional Documentation:** Detailed gameplay rules and UI explanation.
- **Technical Documentation:** Deep dive into the VBA logic, variables, and event-driven architecture.
- **System Documentation:** Maintenance instructions, environmental requirements, and administrative passwords.

**Author:** Alex48191
**Year:** 2026