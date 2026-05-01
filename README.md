# InstantEngine

InstantEngine is a high-performance, rule-driven game creation engine designed for rapid iteration and minimal friction. It provides a streamlined, icon-based editor alongside intelligent systems that assist in building, testing, and refining gameplay in real time.

Levels, mechanics, and items can be created in seconds through the integrated Builder system, while an automated playtesting system continuously simulates player input across multiple runs. This process identifies issues such as failed jumps, difficulty spikes, and invalid paths before release.

The engine emphasizes clarity and responsiveness, featuring a minimal interface, consistent interaction patterns, automatic state persistence, and stable performance even in large-scale levels with continuous simulation.

InstantEngine is built to reduce development overhead and accelerate the path from concept to a fully playable experience.

---

# Features

## Intelligent Systems for easier work
- Automated level and system generation (Builder)  
- Procedural item creation (weapons, tools, consumables, passive effects)  
- Real-time playtesting through input simulation (no teleport-based logic)  
- Multi-run adaptive behavior refinement  
- Memory tracking (failures, successful paths, interaction history)  
- Predictive movement validation for reliable actions  
- Configurable behavior modes (Careful, Aggressive, Explorer)  
- Stuck detection with recovery and strategy switching  

## Plugin System for further customization
- JSON-based plugin architecture for extending engine functionality  
- Rule-driven actions (e.g., `place.block`, effects, behaviors)  
- External content can extend functionality without modifying core engine code  
- Clear separation between engine logic and user-defined content  

## Interface and Interaction designed for clarity first 
- Icon-driven interface with minimal visual clutter  
- Consistent layout system (spacing, alignment, color usage)  
- Smooth transitions and interaction feedback  
- Command-style interface for fast access to tools and actions  
- Context-aware cursor system  

## Editor Tools for getting things done quickly
- Drag selection with multi-object support  
- Context menu operations:
  - Copy  
  - Paste  
  - Duplicate  
  - Delete  
  - Save as preset  

- Preset system for reusable configurations and rapid placement  

## Data and Persistence so nothing gets lost
- Automatic save system with persistent player data (progress, inventory, statistics)  
- Contextual assistant system for guidance and feature discovery  

## Data and Persistence so nothing gets lost
- Optimized rendering and update cycles  
- Chunk-based processing for large environments and simulations  

## Export for a clean final result
- Clean export pipeline without editor interface elements  
- Complete gameplay flow (menu, initialization, gameplay loop)  

## Platform that runs wherever you need it
- Runs entirely in the browser with no installation required  

---

# License so everyone knows the rules

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

## Permissions
- You may copy and redistribute the material in any medium or format  
- You may modify and build upon the material  

## Conditions
- Attribution: Appropriate credit must be provided  
- NonCommercial: The material may not be used for commercial purposes  
- ShareAlike: Derivative works must be distributed under the same license  
- Indication of Changes: Modifications must be clearly documented  

## Restrictions
- Commercial use of the engine or derivative works is not permitted  

Full license text is available in the LICENSE file.

---

# Plugin and Content Licensing for when ownership matters

- The core engine is distributed under the license above  
- User-created plugins, rules, and JSON configurations remain the property of their respective authors  
- Shared extensions should use a compatible license to ensure interoperability  

---

# Disclaimer

This software is provided "as is", without warranty of any kind, express or implied. The authors are not liable for any damages arising from its use.

---

# Summary

InstantEngine focuses on speed, consistency, and extensibility. It combines structured systems, automated validation, and a flexible plugin architecture to support efficient development and reliable results.
