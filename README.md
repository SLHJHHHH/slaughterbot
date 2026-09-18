# SlaughterBot (FNF V-Slice Bot & Dear ImGui Menu)

An autonomous open-source bot and menu featuring a **Dear ImGui (Dark Theme)** style for **Friday Night Funkin' (V-Slice v0.8.6+)**.

**Author:** `Slaughterhouse`  
**License:** MIT

---

## Modular Architecture
1. `scripts/modules/SlaughterBotModule.hxc` — The bot core (handles Pure Sick hits, Combo/Score popups, Downscroll, and NoHurtCam).
2. `scripts/modules/SlaughterGuiModule.hxc` — A standalone GUI class featuring Dear ImGui Dark Theme rendering, mouse window dragging, tabs, and interactive checkboxes.

---

## Controls & Dear ImGui Navigation
- **`[INSERT]`** or **`[ESC]`** — Open / close the ImGui window.
- **Mouse Controls:**
  - Hold the Left Mouse Button (LMB) on the title bar to **drag the window across the screen**.
  - **`[-]`** button in the header — Collapse / Expand the window body.
  - **`[x]`** button in the header — Close the window.
  - Click on the **`[Game]`**, **`[Visuals]`**, **`[Misc]`**, or **`[About]`** tabs to switch views.
  - Click on the checkboxes **`[✓]`** to toggle settings instantly.
- **Keyboard Controls:**
  - **`[1] / [2] / [3] / [4]`** or **`[TAB]`** — Switch tabs.
  - **`[A]`** — Toggle the top checkbox of the active tab.
  - **`[B]`** — Toggle the bottom checkbox of the active tab.

---

## Installation & Setup
1. Copy the `fnfbot` folder into your `Friday Night Funkin/mods/` directory.
2. Launch the game. Upon startup, an initialization card will appear: `SlaughterBot is initializing...`.
3. Once loaded, the Dear ImGui Dark Theme window will open automatically.
4. Configure your options using either the mouse or keyboard, and enjoy the game!
