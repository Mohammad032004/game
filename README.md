# 🎮 PROJECT: AFTERMATH

### When civilization falls, survival becomes the only rule.

**PROJECT: AFTERMATH** is an advanced 3D post-apocalyptic survival game developed using **Unity and C#**, designed to run directly in modern web browsers.

Set in a world devastated by a mysterious global catastrophe, players must explore abandoned environments, collect resources, survive hostile encounters, craft essential equipment, build settlements and uncover the truth behind the collapse of civilization.

The project aims to combine immersive third-person gameplay, intelligent enemy behaviour, survival mechanics and cinematic environmental storytelling into an optimized browser-based gaming experience.

---

## 🌍 Game Overview

| Information | Details |
|---|---|
| Project Name | PROJECT: AFTERMATH |
| Genre | Survival / Action / Adventure |
| Game Engine | Unity 6 LTS |
| Programming Language | C# |
| Rendering Pipeline | Universal Render Pipeline (URP) |
| Game Perspective | Third-Person |
| Graphics Style | Realistic / Cinematic |
| Primary Platform | Web Browser |
| Build Target | WebGL |
| Target Devices | Desktop and Mobile Browsers |
| Game Mode | Single-Player with Optional Multiplayer |
| Development Status | In Development |
| Repository | PROJECT-AFTERMATH |

**Tagline:** *The world ended. Your story begins.*

---

## 📖 Storyline

### Year 2049 — Five Years After The Collapse

Civilization has fallen.

A mysterious global disaster known as **The Collapse** destroyed modern infrastructure, disrupted communication networks and left humanity struggling to survive.

Cities have become abandoned wastelands. Food and clean water are scarce. Autonomous defence systems have turned hostile, and dangerous creatures roam the ruins.

Humanity survives in scattered settlements, with every remaining resource becoming a matter of life and death.

You play as **Alex Carter**, a former field engineer who wakes up inside an abandoned medical facility with fragmented memories.

With limited resources and an uncertain past, you must explore the devastated world, find survivors, uncover hidden secrets and discover what really caused The Collapse.

Your decisions will shape the future of what remains of humanity.

---

## 🎯 Core Gameplay Features

The following features form the planned gameplay experience.

### 🧍 1. Third-Person Character System
- Realistic third-person character movement.
- Walking, running and jumping.
- Camera following and rotation.
- Character animations.
- Interactive environment.

### ❤️ 2. Advanced Survival Mechanics
- Player health management.
- Hunger and hydration systems.
- Stamina management.
- Food and water consumption.
- Medical treatment and recovery.
- Environmental survival challenges.

### 🎒 3. Inventory and Resource Management
- Interactive inventory system.
- Resource collection.
- Item stacking and management.
- Equipment and weapon storage.
- Item categories and descriptions.

### 🔨 4. Crafting System
- Craft survival equipment.
- Create medical supplies.
- Manufacture basic tools.
- Build essential survival structures.
- Resource-based crafting recipes.

### ⚔️ 5. Combat System
- Melee combat.
- Ranged weapons.
- Weapon switching and reloading.
- Enemy damage and hit reactions.
- Stealth and tactical encounters.

### 🤖 6. Intelligent Enemy AI
- Autonomous enemy behaviour.
- Vision-based player detection.
- Sound-based detection.
- Dynamic enemy patrols.
- Player tracking and pursuit.
- Adaptive difficulty and threat evaluation.

### 🏕️ 7. Base Building
- Construct shelters.
- Build defensive structures.
- Create storage systems.
- Establish crafting stations.
- Upgrade survivor settlements.

### 📜 8. Mission and Quest System
- Story-driven missions.
- Optional side quests.
- Dynamic world events.
- Exploration objectives.
- Mission progression and rewards.

### 🌐 9. Optional Multiplayer Expansion
- Online player sessions.
- Multiplayer exploration.
- Shared survival experiences.
- Player interaction.
- Online progression features.

*Multiplayer is planned as a later development milestone. The initial release will prioritize a complete single-player experience.*

---

## 🗺️ Game World

The world of AFTERMATH is divided into interconnected exploration zones.

| Zone | Description |
|---|---|
| Dead City | Abandoned buildings, ruined streets and valuable resources. |
| Silent Forest | Dense vegetation, wildlife and hidden shelters. |
| Military Outpost | Military equipment, ammunition and hostile defence systems. |
| Research Facility | Secret experiments and discoveries about The Collapse. |
| Survivor Settlement | Trading, crafting, missions and base building. |

Each zone will feature unique environmental storytelling, exploration opportunities, resources and threats.

---

## 🛠️ Technology Stack

### Game Development

| Technology | Purpose |
|---|---|
| Unity 6 LTS | Game development engine |
| C# | Gameplay programming |
| URP | Rendering and graphics |
| Unity Input System | Desktop and mobile controls |
| Unity AI Navigation | Enemy navigation |
| ScriptableObjects | Game data management |
| Blender | 3D modelling and asset creation |

### Backend and Online Services

| Technology | Purpose |
|---|---|
| Node.js | Backend runtime |
| TypeScript | Backend development |
| Express.js | REST API |
| PostgreSQL | Player and game data |
| JWT / Secure Sessions | Authentication |
| WebSockets | Real-time communication where required |

### Development Tools

- Visual Studio / JetBrains Rider
- Git
- GitHub
- Blender
- Unity Profiler

---

## 🏗️ System Architecture

The project follows a modular architecture that separates gameplay systems, presentation, data management and online services.

```text
PROJECT-AFTERMATH/
│
├── Assets/
│   ├── _Project/
│   │   ├── Art/
│   │   ├── Audio/
│   │   ├── Animations/
│   │   ├── Prefabs/
│   │   ├── Scenes/
│   │   ├── Scripts/
│   │   │   ├── Core/
│   │   │   ├── Player/
│   │   │   ├── Camera/
│   │   │   ├── Combat/
│   │   │   ├── Survival/
│   │   │   ├── Inventory/
│   │   │   ├── Crafting/
│   │   │   ├── AI/
│   │   │   ├── World/
│   │   │   ├── Missions/
│   │   │   ├── Building/
│   │   │   ├── UI/
│   │   │   ├── SaveSystem/
│   │   │   ├── Audio/
│   │   │   └── Online/
│   │   │
│   │   ├── ScriptableObjects/
│   │   ├── Settings/
│   │   └── Tests/
│   │
│   ├── ThirdParty/
│   └── Plugins/
│
├── Backend/
│   ├── src/
│   │   ├── auth/
│   │   ├── players/
│   │   ├── progress/
│   │   ├── leaderboard/
│   │   └── database/
│   └── tests/
│
├── Documentation/
│
├── Packages/
├── ProjectSettings/
├── .gitignore
└── README.md
```

---

## 🔄 Gameplay Loop

The core gameplay experience follows a continuous survival progression cycle.

```text
       SURVIVOR SETTLEMENT
                |
                v
        SELECT A MISSION
                |
                v
          EXPLORE WORLD
                |
                v
       COLLECT RESOURCES
                |
                v
       ENCOUNTER ENEMIES
                |
                v
       COMBAT / STEALTH
                |
                v
       COMPLETE OBJECTIVES
                |
                v
         RETURN TO BASE
                |
                v
       CRAFT & UPGRADE
                |
                v
        SAVE PROGRESS
                |
                +------> REPEAT
```

---

## 🧠 Advanced AI System

One of the major technical objectives of PROJECT: AFTERMATH is the development of intelligent enemy behaviour.

The planned AI architecture combines:

- Finite State Machines.
- Behaviour Trees.
- Utility-based decision-making.
- Vision and hearing perception.
- Enemy memory systems.
- Dynamic threat evaluation.
- Adaptive difficulty.

Enemies will respond to player actions rather than relying entirely on fixed movement and attack sequences.

An additional research objective is to compare traditional scripted enemy behaviour with adaptive AI approaches through measurable gameplay and performance evaluations.

---

## 🚀 Development Roadmap

The project will be developed incrementally through the following milestones.

| Phase | Development Milestone | Status |
|---|---|---|
| 01 | Project Setup and Architecture | ⬜ Planned |
| 02 | Third-Person Player Controller | ⬜ Planned |
| 03 | Camera and Animation System | ⬜ Planned |
| 04 | Survival Mechanics | ⬜ Planned |
| 05 | Inventory and Resource Management | ⬜ Planned |
| 06 | Combat System | ⬜ Planned |
| 07 | Intelligent Enemy AI | ⬜ Planned |
| 08 | World and Environment Development | ⬜ Planned |
| 09 | Crafting and Base Building | ⬜ Planned |
| 10 | Missions and Progression | ⬜ Planned |
| 11 | Save System and Backend | ⬜ Planned |
| 12 | Optional Multiplayer | ⬜ Planned |
| 13 | WebGL Optimization | ⬜ Planned |
| 14 | Testing and Deployment | ⬜ Planned |

*Development status will be updated as individual systems become functional and tested.*

---

## 💻 Getting Started

### Prerequisites

Before starting development, install:

1. [Unity Hub](https://unity.com/download)
2. Unity 6 LTS Editor with Web Build Support.
3. Visual Studio or JetBrains Rider.
4. Git.
5. Blender (optional, for 3D asset development).

### Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/PROJECT-AFTERMATH.git

cd PROJECT-AFTERMATH
```

### Open the Project

1. Open Unity Hub.
2. Select **Add Project from Disk**.
3. Navigate to the cloned repository.
4. Open the project using the configured Unity 6 LTS editor version.
5. Allow Unity to import the project assets and packages.

### Build for Web

1. Open Unity.
2. Navigate to **File → Build Profiles**.
3. Select the Web platform.
4. Switch the active build platform if necessary.
5. Configure the Web build settings.
6. Select Build.
7. Deploy the generated WebGL build to a compatible static web host.

> Note: A working WebGL build will be published once the initial playable prototype is ready. Browser deployment requires appropriate hosting headers and configuration for the selected Unity build settings.

---

## ⚡ Performance and Optimization

Since the game targets desktop and mobile browsers, optimization is a core development requirement.

Planned optimization techniques include:

- Universal Render Pipeline.
- Level of Detail (LOD).
- Occlusion culling.
- Texture compression.
- Baked lighting.
- Optimized shaders.
- Efficient asset loading.
- Object pooling.
- Reduced draw calls.
- Platform-specific quality settings.
- Mobile-friendly UI and controls.

Initial performance goals:

| Metric | Target |
|---|---|
| Desktop | 45–60 FPS |
| Mobile | Around 30 FPS |
| Initial download | Aim for under 50 MB |
| Rendering | Optimized URP |
| Platform | Modern compatible browsers |

Actual performance will depend on hardware, browser capabilities, asset complexity and build configuration.

---

## 🧪 Testing and Evaluation

The project will be evaluated across several dimensions:

**Gameplay Testing**
- Player movement and interaction.
- Combat and damage calculations.
- Inventory and crafting.
- Survival mechanics.
- Mission progression.

**AI Evaluation**
- Detection accuracy.
- Enemy response time.
- Decision-making consistency.
- Adaptive behaviour.
- CPU performance.

**Performance Testing**
- Frames per second.
- Memory consumption.
- Initial loading time.
- Asset loading performance.
- Desktop and mobile browser compatibility.

**Reliability Testing**
- Save and load functionality.
- Data consistency.
- Network failure handling.
- Recovery from interrupted sessions.

---

## 🔮 Future Scope

Potential future enhancements include:

- Expanded open-world environments.
- More intelligent enemy behaviours.
- Advanced environmental simulation.
- Weather and dynamic day/night cycles.
- Wildlife and ecosystem simulation.
- More complex settlement management.
- Cooperative multiplayer.
- Cloud-based player progression.
- Advanced adaptive AI research.

---

## 🤝 Contributing

Contributions, suggestions and feedback are welcome.

If you would like to contribute:

1. Fork the repository.
2. Create a feature branch.
3. Implement your changes.
4. Test your implementation.
5. Submit a pull request describing your changes.

Please ensure that third-party assets and packages have appropriate licenses before including them.

---

## 📜 License

The project's license will be finalized before public distribution.

Until a license is added to the repository, all rights are reserved by the project owner. Do not assume that the source code or assets are available for redistribution or commercial reuse.

---

## 👨‍💻 Project Development

**PROJECT: AFTERMATH** is an independent game-development project focused on combining survival gameplay, intelligent AI systems, realistic environments and browser-based gaming technologies.

The objective is to develop an immersive, technically advanced and accessible survival experience.

---

<p align="center">

### 🌍 THE WORLD HAS FALLEN.
### 🔥 SURVIVAL IS JUST THE BEGINNING.

**PROJECT: AFTERMATH**

*Explore. Survive. Adapt. Rebuild.*

</p>
