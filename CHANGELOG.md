# Praxis - Patch Notes (Alpha v9.2) - 13 July, 2026

## 🐛 Bug Fixes

- **Singleplayer Map Vote Bypass:** Fixed an issue where singleplayer sessions triggered unnecessary map voting prompts. Players in singleplayer can now switch maps directly without initiating a vote.

---

# Praxis - Patch Notes (Alpha v9.1) - 12 July, 2026

## ✨ New Features

- **Map Voting System** implemented.  
  - When a player selects a map via the Map GUI, a prompt is sent to all active players asking if they agree to change the map (e.g., "Change map to Castle?"). The server tallies the votes, and the map changes only if the majority votes "Yes". If "No" wins, the current map stays loaded.

## 🐛 Bug Fixes

- **Forced Map Transition Resolved:** Fixed the issue where a single player could force a map change for everyone in multiplayer. Map transitions are now democratically controlled by the new voting system.

---

# Praxis - Patch Notes (Alpha v9.0) - 12 July, 2026

## ✨ New Features

- **Map Selector GUI** added.  
  - Players can now switch between different maps (Baseplate and Castle) via the in-game Map GUI. Loading a map automatically unloads and deletes the previous map from memory.

- **Volumetric Clouds** added.  
  - Atmospheric depth and visuals have been enhanced with dynamic volumetric cloud rendering.

## 🔧 Improvements

- **Graphics & Lighting** upgraded.  
  - Overall environmental visuals and lighting quality have been significantly improved.

## ⚠️ Known Issues

- **Forced Map Transition in Multiplayer:** When playing in multiplayer sessions, if any player changes the map, all players are automatically transferred to the selected map.

---

# Praxis - Patch Notes (Alpha v8.9) - 11 July, 2026

## ✨ New Features

- **Player Ragdoll Interaction** added.  
  - Players can now use the Axis Weapon to grab and pick up other players while they are in a ragdoll state. Grabbing is strictly allowed only when the target player is actively ragdolled.

---

# Praxis - Patch Notes (Alpha v8.8) - 6 July, 2026

## ✨ New Features

- **Elastic Mode** added.  
  - Introduces flexible/stretchy physics constraints for tools and objects.

- **Ragdoll System** implemented.  
  - Characters and entities now react dynamically to physics and impacts with realistic ragdoll physics. Pressing **[G]** toggles ragdoll mode on and off.

## 🔧 Improvements

- **Rope Mechanism** upgraded.  
  - Converted from static beams to full physical constraints for realistic rope physics and behavior.

- **Save & Load System** optimized.  
  - Slightly improved and made compatible with Elastic Mode.

- **Camera Optimization** applied.  
  - The camera logic has been enhanced; while the game is normally locked to a first-person (FPS) view, the camera dynamically switches to a third-person (TPS) perspective whenever the character enters a ragdoll state.

---

# Praxis - (Alpha v8.7) – July 4, 2026

## ✨ New Features

- **Balloon Mod**
  - Added a new balloon attachment system. Players can now select any physics-enabled object and press 'B' to attach a balloon, allowing for creative floating builds with smooth, controlled ascent.

- **Fly Toggle**
  - Introduced a standalone flight mode. Players can toggle flight on and off at any time using the 'V' key, independent of equipped tools, for easier navigation and building.

---

# Praxis - (Alpha v8.6) – July 2, 2026

## 🔧 Improvements

- **Button click latency reduction.**
  - Optimized the sound playback system to eliminate input lag, ensuring immediate audio feedback when interacting with UI elements.

---

# Praxis - (Alpha v8.5) – June 27, 2026

## ✨ New Features

- **Click Sound**
  - A custom click sound effect has been added to the buttons.

- **Enhanced UI Animations.**
  - Added smooth transition animations to GUI panels to improve user experience.

- **Health Bar Visual Update.**
  - Integrated custom heart icons into the health bar UI for a more polished look.
