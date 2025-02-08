# The Backrooms: Survival Behind the Scenes - Technical Design Document

- Game name: The Backrooms: Survival Behind the Scenes
- Developer: `TheDoorKnob Studio`
- Game engine: MyEngine
- Genre: Cooperative survival horror
- Target audience: 16+ (fans of horror, cooperative games and procedural generation)
- Platforms: PC (Windows, Linux)

## Overview

The Backrooms: Survival Behind the Scenes is a cooperative survival horror game developed by RedSky Studios using the MyEngine game engine. Players explore procedurally generated mazes, build structures, evade terrifying monsters, and work together in a dynamically changing environment.

## Core Mechanics

### 1. **Procedural Level Generation**

- Each playthrough features a unique, randomly generated maze.
- Environments dynamically shift, creating an ever-changing labyrinth.
- Secret passages and hidden rooms provide new exploration opportunities.

### 2. **Survival and Resource Management**

- Players must gather materials to craft makeshift weapons, tools, and barricades.
- Limited resources force players to make strategic decisions about survival.
- Food and stamina management affect movement speed and decision-making.

### 3. **Adaptive AI Monsters**

- Monsters adapt to player behavior, becoming more aggressive or cautious.
- Different types of monsters have unique tracking methods (sound, light, movement).
- Some creatures can mimic human voices to lure players into traps.

### 4. **Dynamic Lighting System**

- Light sources can attract or repel specific monsters.
- Flashlights, UV lights, and infrared vision provide different strategic advantages.
- Flickering and malfunctioning lights add to the horror atmosphere.

### 5. **Building and Defense**

- Players can construct barricades, traps, and safe zones.
- Materials scavenged from the environment are used for fortifications.
- Some structures degrade over time, requiring maintenance.

### 6. **Psychological Horror Mechanics**

- Players experience hallucinations if they stay in darkness too long.
- Prolonged exposure to stress causes visual and auditory distortions.
- Some monsters can only be avoided by remaining completely still.

### 7. **False Signals and Deception**

- Some doors lead to dead ends or loops, misleading players.
- Phantom sounds and fake radio transmissions create paranoia.
- Players must distinguish real threats from illusions.

### 8. **Environmental Changes Over Time**

- The maze dynamically shifts, creating new paths and sealing old ones.
- Walls collapse, revealing hidden areas or trapping players.
- Certain rooms may become unstable and dangerous.

### 9. **Alternative Monster Interactions**

- Players can use distractions like throwing objects to mislead enemies.
- Some creatures react to specific sounds or frequencies.
- Monsters can be repelled using improvised tools or tactics.

### 10. **Random Events and Anomalies**

- Unpredictable events like power failures, cave-ins, and ghostly apparitions.
- Players may find remnants of past survivors, providing lore and clues.
- Rare encounters with neutral or hostile entities that change gameplay.

### 11. **Character Customization and Roles**

- Players can choose special abilities that impact survival strategies.
- Roles such as Engineer, Scout, or Medic grant unique advantages.
- Skills improve through gameplay, allowing for long-term progression.

## Technical Requirements

### **Engine & Graphics**

- Game built using **MyEngine** (custom engine developed by RedSky Studios).
- Supports **ray tracing** for enhanced lighting and shadows.
- Optimized for **procedural generation** and dynamic world updates.

### **Networking & Multiplayer**

- **Cooperative multiplayer** with up to 4 players.
- **Dedicated servers** to manage game instances.
- **Voice chat with spatial audio** for realism and immersion.

### **Audio Design**

- 3D positional audio to enhance monster detection and paranoia.
- Randomized environmental noises to increase tension.
- Adaptive soundtrack that reacts to player actions and threat levels.

### **AI System**

- Monster AI uses **behavior trees** to simulate intelligent tracking.
- Pathfinding system adapts to changing maze structures.
- AI dynamically adjusts difficulty based on player progress.

## Development Roadmap

### **Phase 1: Core System Implementation**

- [x] Procedural maze generation
- [x] Basic movement and interaction mechanics
- [x] Monster AI prototype

### **Phase 2: Advanced Gameplay Features**

- [ ] Dynamic lighting system
- [ ] Cooperative multiplayer functionality
- [ ] Base building and fortifications

### **Phase 3: Optimization and Polish**

- [ ] AI improvements and difficulty balancing
- [ ] Sound design and psychological horror elements
- [ ] UI and accessibility features

### **Phase 4: Community and Expansion**

- [ ] Custom level creation tools
- [ ] Modding support and Steam Workshop integration
- [ ] Regular content updates and new monsters

## Conclusion

The Backrooms: Survival Behind the Scenes aims to deliver a terrifying yet engaging cooperative horror experience. By combining procedural generation, psychological horror, and strategic survival elements, the game offers a unique and evolving challenge for players. Further development will expand gameplay features, enhance visuals, and refine multiplayer interactions to ensure a truly immersive experience.
