# Game Design Documentation

This repository contains open-source design documentation for Ilkmaar, a social simulation game focused on creature interactions, resource management, and world-building. These materials are provided as part of an NSF project.

## Overview

The game design is built around several interconnected systems that create engaging gameplay through creature relationships, resource gathering, crafting, and world management. Players interact with different factions of creatures, gather and craft resources, and help maintain balance in the game world.

### Core Systems

#### 🌍 World Systems
- **Time**: Four times of day, seven-day weeks, and four seasons that influence game mechanics
- **Weather**: Dynamic weather system affecting resource spawning and creature behavior
- **Map**: Hierarchical world structure (World > Islands > Plots > Patches > Nodes)

#### 🦊 Creatures and Factions
- Four main factions: Light, Shadow, Growth, and Stability
- Each faction has unique creatures with individual stats and behaviors
- Creatures engage in various activities and can form relationships with players

#### 🌿 Resources and Spawning
- Different resource types across categories (Fruit, Sweet, Magic, Material)
- Dynamic spawning system influenced by weather, time, and location
- Resource quality affected by various environmental factors

#### 🛠️ Crafting and Items
- Craftable items including Foods, Health Potions, Gifts, and Growth Potions
- Complex crafting logic based on resource combinations
- Item effects vary based on creature preferences and stats

#### 📊 Data and Progression
- Quest system with scrolls that include queries, data, and displays
- Progression through levels unlocking more detailed data analysis
- Learning progression from simple patterns to complex relationships

## Documentation Files

- [Ilkmaar Logic & Data System Overview](Ilkmaar%20Logic_Data%20System%20Overview.md): Comprehensive breakdown of game systems and mechanics
- [Ilkmaar Simulated Data Overview](Ilkmaar%20Simulated%20Data%20Overview.md): Analysis of simulated game data and patterns
- [Item Effects: Game and Data Progressions Design](Item%20Effects_%20Game%20and%20Data%20Progressions%20Design.md): Details on item effects, progression systems, and quest designs
- [Lightning Talk Proposal](FINAL_Lightning%20Talk%20Proposal.docx.pdf): Project overview presentation

## Proposed Documentation Structure

For better organization, consider organizing files into the following structure:

```
docs/
├── systems/          # Core game systems documentation
│   ├── world.md      # World, time, weather and map mechanics
│   ├── creatures.md  # Creature systems and factions
│   ├── resources.md  # Resource types and spawning
│   └── crafting.md   # Crafting and item mechanics
├── data/             # Data and progression systems
│   ├── progression.md # Learning progression designs
│   ├── quests.md     # Quest and scroll systems
│   └── datasets/     # Simulated datasets and visualizations
└── presentations/    # Project presentations and proposals
```

## Usage & Citation

These design documents are released as open-source materials for educational and research purposes. When using these materials, please cite:

```
Game Design Documentation. (2025). Concord Learning. 
NSF Grant #2214516
```

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Acknowledgments

This material is based upon work supported by the National Science Foundation under Grant No. 2214516. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.