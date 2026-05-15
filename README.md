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
1. **Open the File:** Ensure you are using Microsoft Excel and the file extension is `.xlsm`.

2. **Enable Editing:** If a yellow bar appears **(Protected View)**, click **"Enable Editing"**. This is necessary to move past the read-only mode.

⚠️ **IMPORTANT: RED SECURITY BAR (If it appears after editing is enabled)**
If Excel now shows a red bar: "Microsoft has blocked macros because the source of this file is untrusted":

➔ **Close** the Excel workbook.
➔ **Right-click** the `.xlsm` file in your folder ➔ **Properties**.
➔ **General Tab** ➔ Locate **Security** at the bottom ➔ Check **"Unblock"**.
➔ Click **Apply** and **OK**, then **re-open** the file.

3. **Enable Content:** Once the red bar is gone (or if you only see a yellow Security Warning), click "Enable Content" to activate the VBA logic.

4. **Automatic Initialization:** The game will run its setup routine, preparing the board and the record system.

5. **Start Playing:** Click the **"Start Game"** button on the main sheet to begin.

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