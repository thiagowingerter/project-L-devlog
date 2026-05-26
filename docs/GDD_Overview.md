# PROJECT L: CORE GAME DESIGN DOCUMENT

## 1. EXECUTIVE SUMMARY
- **Genre:** Dark Fantasy Narrative RPG / Slice of Life Resource Management.
- **Engine:** Ren'Py (Python 3).
- **Core Loop:** Narrative Progression -> Weekly Schedule Management -> Dual-Stat Balancing (Logic vs. Instinct) -> Hidden Skill Checks -> Survival/Branching Endings.

## 2. CORE MECHANICS & SYSTEMS
### 2.1 The Duality System (Stat Management)
The game operates on a constant balancing act between two hidden psychological stats representing the protagonist's internal conflict.
- **Phase 1: Resistance:** Player choices strictly rely on logic and stoicism, increasing mental strain but passing tactical checks.
- **Phase 2: Integration:** Blending instinct with logic to unlock organic story progression.
- **Phase 3: Corruption:** Excessive reliance on dark triggers opens a hidden "Body-Horror" mutation route, altering the game's ending and the protagonist's physical state.

### 2.2 Schedule & Economy Loop
A progression system inspired by classic life-simulation mechanics.
- **Weekly Planning:** The player allocates time slots (Morning/Afternoon) to subclass activities (e.g., Apothecary, Tavern).
- **Economy vs. Sanity:** High-yield gold activities generate higher psychological strain. The player must balance financial survival against mental deterioration.

## 3. UI/UX DYNAMIC STORYTELLING
- **Sanity Glitches:** As psychological strain peaks, the UI stutters dynamically, dialogue boxes crack, and character nameplates glitch via Python-coded screen shakes.
- **Sensory Overload:** Specific triggers vignette the screen edges with warm/dark blurs to simulate physiological panic or adrenaline, breaking the static visual novel format.

## 4. TECHNICAL SPECIFICATIONS & PIPELINE
- **Framework:** Modular event-driven architecture using Git for version control.
- **AI Asset Pipeline:** Character sprites and 2.5D layered assets generated locally via Stable Diffusion (ComfyUI, Pony V6, Custom LoRAs) for high-fidelity, consistent art direction.
