# ![image](https://i.ibb.co/mb6P0BN/Smart-Thumb.png) Smart! Mod

![Status](https://img.shields.io/badge/Status-Release%20Candidate-brightgreen) ![Version](https://img.shields.io/badge/Target-Satisfactory%201.1+-blue) ![Engine](https://img.shields.io/badge/Engine-UE%205.3-blue) ![SML](https://img.shields.io/badge/SML-3.11.x-blue) ![Multiplayer](https://img.shields.io/badge/Multiplayer-Testing-orange)

> **Note:** Multiplayer is not currently supported, but under active testing with partial success. Multiplayer support may be added in a future update.

---

## 🎉 Phase 1 Completed, Release Imminent!

**Announcement Date:** October 21, 2025

Smart! is being completely rebuilt from the ground up for **Satisfactory 1.1+** using Unreal Engine 5.3 and the latest Satisfactory Mod Loader (SML 3.11.x).

**Current Status:** Release Candidate - launching soon

**What's New in the Rebuild:**
- 🎨 **Redesigned HUD** - Modern, cleaner interface for displaying grid and mode information
- ⌨️ **Native Keybind Integration** - Configure Smart! keybinds directly in Satisfactory's Options menu alongside vanilla controls
- 📐 **Multi-Axis Spacing** - Adjust spacing independently on X, Y, and Z axes (original was single-axis only)
- 📏 **Multi-Axis Steps** - Vertical stepping patterns configurable per axis
- ⚡ **Multi-Axis Stagger** - Progressive offset patterns for diagonal layouts and vertical lean effects (X/Y for horizontal diagonals, ZX/ZY for tower lean)

**Development Roadmap:**

### Phase 1: Scaling (Release Candidate - In Testing)
- ✅ **Grid Scaling** - Scale foundations, buildings, and storage in X, Y, Z dimensions
- ✅ **Arrow Visualization** - Visual indicators showing which axis is being scaled
- ✅ **HUD Counter Display** - Real-time display of grid dimensions and settings
- ✅ **Spacing Mode** - Adjust spacing between scaled structures
- ✅ **Steps Mode** - Vertical stepping patterns
- ✅ **Stagger Mode** - Progressive offset patterns (horizontal diagonals + vertical lean)
- ✅ **Enhanced Input System** - Modifier keys (Z, X, Z+X) for axis selection
- ✅ **Supported Items** - Foundations, production buildings (factories), storage containers, most walls, splitters, mergers, power poles

### Phase 2: Autoconnect (Planned)
- 📋 **Automatic Connections** - Auto-connect belts and pipes between buildings, splitters, and mergers
- 📋 **Smart Routing** - Intelligent pathfinding for belt/pipe placement
- 📋 **Multi-Building Support** - Connect entire grids of production buildings automatically

### Phase 3: Extend (Planned)
- 📋 **Building Duplication** - Duplicate buildings with all settings preserved
- 📋 **Connection Copying** - Copy belt and pipe connections from original to duplicate
- 📋 **Recipe Preservation** - Maintain configured recipes across duplicates

### Phase 4: Camera (Planned - May Release as Separate Mod)
- 📋 **Hologram Preview** - View from proposed building's perspective before placement
- 📋 **Planning Tool** - Visualize sight lines and factory layouts
- 📋 **Screenshot Mode** - Capture views from planned building locations

**Beyond Phases:** Based on community interest, additional features may include:
- Quality of life improvements
- Enhanced user interface
- Additional building type support
- Community-requested features

**Release Plan:** 🚀 **Phase 1 releasing imminently!** The first public release includes the complete Scaling feature set with Grid Scaling, Spacing, Steps, and Stagger modes. Check back soon or join the Discord for release announcements!

---

## 💬 Join Our Discord Community

[![Discord](https://img.shields.io/discord/799091523173613589?color=7289da&label=Discord&logo=discord&logoColor=white)](https://discord.gg/SgXY4CwXYw)

**Join the Smart! Discord:** [https://discord.gg/SgXY4CwXYw](https://discord.gg/SgXY4CwXYw)

### Why Join?

**📢 Get Help & Support**
- Quick answers to setup and usage questions
- Troubleshooting assistance from the community
- Direct support from the development team
- **Bug Reports:** Submit issues at [GitHub Issue Tracker](https://github.com/SmartFoundations/SmartIssueTracker/issues)

**🎮 See What's New**
- Screenshots and videos of features in development
- Early previews of upcoming releases
- Behind-the-scenes development updates

**🧪 Join Testing**
- Be among the first to test new features
- Provide feedback that shapes development
- Get early access to experimental builds

**💡 Share & Discuss**
- Showcase your builds using Smart!
- Share tips and tricks with other players
- Suggest new features and improvements
- Vote on development priorities

**🔔 Stay Informed**
- Release announcements
- Development progress reports
- Community events and challenges

### Quick Start
New to Smart!? The Discord is the best place to:
- Get setup help
- Learn how to use features
- See examples from experienced users
- Ask questions in real-time

**Everyone is welcome!** Whether you're a long-time user or just curious about the mod, join us at [discord.gg/SgXY4CwXYw](https://discord.gg/SgXY4CwXYw)

---

## ❓ Frequently Asked Questions (FAQ)

### What items can Smart! scale?
Smart! currently supports:
- **Foundations** - All foundation types and sizes
- **Production Buildings** - Constructors, assemblers, manufacturers, refineries, smelters, foundries, packagers, blenders, particle accelerators
- **Storage** - Storage containers (all tiers), fluid buffers, industrial fluid buffers
- **Walls** - Most wall types (standard, windows, gates)
- **Logistics** - Splitters, mergers (all tiers)
- **Power** - Power poles (all types)

### What items are NOT yet supported?
Items requiring multi-click or click-and-drag placement are not yet supported, including:
- Resource extractors (miners, oil pumps, water extractors)
- Wall/floor holes (conveyor, pipe holes)
- Some roof pieces
- Signs and displays
- Beams and pillars
- Multi-step placement items

**Note:** These items are not permanently excluded. Support for additional building types is planned for future updates.

### Does Smart! work in multiplayer?
Multiplayer is not currently supported but is under active testing with partial success. Multiplayer support may be added in a future update.

### Is Smart! open source?
The source code for Smart! is not publicly available at this time. We plan to release the source code as open source once all planned phases (Phases 1-4) are complete and we are ready to accept community code contributions. Open sourcing the codebase is on the roadmap, but we want to ensure the mod is feature-complete and stable before making the code public and opening it up for contributions.

---

## 🎮 Controls

Smart! uses **native Satisfactory keybinds** that can be customized in **Options > Keybindings > Smart! Scaling Controls**.

### Grid Scaling (Create Multi-Item Grids)

| Action | Default Key | Description |
|--------|-------------|-------------|
| Increase/Decrease X | `NumPad 8` / `NumPad 5` | Adjust grid width (rows) |
| Increase/Decrease Y | `NumPad 6` / `NumPad 4` | Adjust grid depth (columns) |
| Increase/Decrease Z | `NumPad 9` / `NumPad 3` | Adjust grid height (layers) |
| Increase/Decrease X (Alternate) | `X` (hold) + `Scroll Wheel` or `NumPad 8/5` | Adjust grid width with mouse wheel or NumPad |
| Increase/Decrease Y (Alternate) | `Z` (hold) + `Scroll Wheel` or `NumPad 8/5` | Adjust grid depth with mouse wheel or NumPad |
| Increase/Decrease Z (Alternate) | `X` + `Z` (hold both) + `Scroll Wheel` or `NumPad 8/5` | Adjust grid height with mouse wheel or NumPad |

**Usage Example:** Press `NumPad 8` to create an 8x1x1 grid, then `NumPad 6` to make it 8x4x1. Or hold `X` and scroll to adjust X count.

### Spacing Mode (Adjust Gap Between Items)

| Action | Default Key | Description |
|--------|-------------|-------------|
| Activate Spacing Mode | `;` (hold) | Hold to enable spacing adjustments |
| Increase/Decrease Spacing | `Scroll Wheel` or `NumPad 8/5` (while holding `;`) | Adjust spacing on active axis |
| Cycle Axis | `Num0` (while holding `;`) | Switch between X → Y → Z axes |

**Usage Example:** Hold `;`, scroll wheel or `NumPad 8/5` to add 2m spacing, press `Num0` to switch to Y axis, scroll to add 1m Y spacing.

### Steps Mode (Create Vertical Stairs/Steps)

| Action | Default Key | Description |
|--------|-------------|-------------|
| Activate Steps Mode | `I` (hold) | Hold to enable step adjustments |
| Increase/Decrease Steps | `Scroll Wheel` or `NumPad 8/5` (while holding `I`) | Adjust vertical rise on active axis |
| Cycle Axis | `Num0` (while holding `I`) | Switch between X → Y axes |

**Usage Example:** Hold `I`, scroll wheel or `NumPad 8/5` to create 0.5m steps per column. Works with X or Y axis.

### Stagger Mode (Create Diagonal/Lean Patterns)

| Action | Default Key | Description |
|--------|-------------|-------------|
| Activate Stagger Mode | `Y` (hold) | Hold to enable stagger adjustments |
| Increase/Decrease Stagger | `Scroll Wheel` or `NumPad 8/5` (while holding `Y`) | Adjust offset on active axis |
| Cycle Axis | `Num0` (while holding `Y`) | Switch between X → Y → ZX → ZY axes |

**Stagger Axes:**
- **X/Y**: Horizontal diagonal patterns (sideways/forward offsets)
- **ZX/ZY**: Vertical lean patterns (tower leans forward/sideways as it rises)

**Usage Example:** Hold `Y`, press `Num0` until "ZX", scroll to create a leaning tower effect.

### Visual Aids

| Action | Default Key | Description |
|--------|-------------|-------------|
| Toggle Arrows | `NumPad 0` | Show/hide axis direction arrows on holograms |

**Note:** All keybinds can be customized in-game via **Options > Keybindings > Smart! Scaling Controls**

---

## 👥 The Team

### Current Team
* **Alex** - Original author and Project Advisor (providing guidance and counsel for the 1.1 rebuild)
* **Finalomega** - Lead Developer and Documentation Writer for the Satisfactory 1.1 rebuild
* **Raudoc2K1** - Support Staff, Tester, Discord Moderator, and Content Creator (RightMindGamming on [YouTube](https://www.youtube.com/channel/UCfy5lG-teOehpD9oYLjT7rA) and [Twitch](https://www.twitch.tv/rightmindgamming))

### Original Contributors
* **Robb** - Update 8 port with partial functionality, SML expertise and advice
* **Deantendo** - Created the amazing mod icon
* **HWEEKS** - Original description author

## 💝 Thanks

Huge thanks to **Marcio** for all his help from the beginning of my path as mod creator, **TwoTwoEleven** for his awesome code examples from MM, to **Archengius** for his fine example of overriding the default buildings and to **Mircea** for some fine thoughts. Thanks **jay96** for your amazing idea about arrows.

## 💰 Support Smart! Development

Smart! is a passion project built for the community. This complete rebuild has required significant investment in development expenses (primarily AI compute for code assistance and testing infrastructure) - all funded out of pocket.

**Future Development Costs:**
Continuing work on Phase 2 (Autoconnect), Phase 3 (Extend), and Phase 4 (Camera) will require ongoing investment in development tools and AI-assisted research. If you're enjoying Smart! and want to see these features become reality, your support helps make it sustainable.

☕ **[Support on Ko-fi](https://ko-fi.com/finalomega)**

**What Your Support Enables:**
- Continued development of planned features
- Faster updates and bug fixes  
- Community-requested enhancements
- Sustainable development pace

No pressure - donations are completely optional. But if Smart! adds value to your game, every contribution helps offset costs and keeps development active. Thank you for your support! 🙏

---

## 🎥 Videos

Smart! has had quite a few videos made for it, and we're incredibly appreciative of it!

| Version 20 Overview and Tutorial by [RightMindGamming](https://www.youtube.com/channel/UCfy5lG-teOehpD9oYLjT7rA) | Preview of the new camera feature | Preview of the new lift height counter feature |
|:---:|:---:|:---:|
| [![v20 tutorial](https://i.ibb.co/RNQDqBM/RMGv20-Tutorial.jpg)](https://www.youtube.com/watch?v=R1nEiSfskPA) | [![camera feature](https://i.ibb.co/wgq4sW7/cameras-screen-small.png)](https://youtu.be/bPHYtuWp2aI) | [![lift height counter feature](https://i.ibb.co/LNTXtWJ/snf-small.png)](https://youtu.be/ZMSZaEa-3No) |

Here are some videos for prior versions of Smart!:

| Version 17 | Version 16 | Version 15 |
|:---:|:---:|:---:|
| [![poster for v17](https://i.ibb.co/KjS6Q1D/V-17-Promo-mp4-20210708-090600-306.png)](https://youtu.be/vKPQ5YPPsU8) | [![poster for v16](https://i.ibb.co/pJfhJR2/Preview-Template-Small.jpg)](https://youtu.be/MmkfqByx0i0) | [![poster for v15](https://i.ibb.co/mb2WJNz/Preview-Template-Small.jpg)](https://youtu.be/jxfJR3ullJI) |

| Version 14 | Version 12 | Version 11 |
|:-:|:-:|:-:|
|[![poster for v14](https://i.ibb.co/jGG28hx/Preview-Small.jpg)](https://youtu.be/-HbCKSABeWE)|[![poster for v12](https://i.ibb.co/vXXDVst/v-12-small.jpg)](https://youtu.be/thC8RvniApQ)|[![poster for v11](https://i.ibb.co/WcNB78B/V-11-small.jpg)](https://youtu.be/5qE3G4KbJXM)|
|v10|v9|v8|
|[![poster for v10](https://i.ibb.co/C1n8b1j/V-10-small.jpg)](https://youtu.be/ejINdaaRQtU)|[![poster for v9](https://i.ibb.co/5k6vD83/V-9-small.jpg)](https://youtu.be/UQVYEl7d9Tg)|[![poster for v8](https://i.ibb.co/0GYmQz3/V-8-small.jpg)](https://youtu.be/4H0Bbzhq1_E)|
|v7|v6|v5|
|[![poster for v7](https://i.ibb.co/mTT1PhY/V7-small.jpg)](https://youtu.be/BQqahJcdKfM)|[![poster for v6](https://i.ibb.co/P6GkWqB/V6-small.jpg)](https://youtu.be/8_H7TJvwJC4)|[![poster for v5](https://i.ibb.co/YRSdCwk/V5-small.jpg)](https://youtu.be/qnLOsYsZOXg)|

| Mod review by [ImKibitz](https://www.youtube.com/channel/UCz9qw5nupdzCGwHwQiqs7qA) | In-depth review by [Magenty](https://www.youtube.com/channel/UCL8hC7X4mpAKdoP5gwdKkBQ) | First review by [TotalXclipse](https://www.youtube.com/channel/UC2SNK_S7tvROHS_KJdIiEFg) |
|:---:|:---:|:---:|
| [![Kibitz review](https://i.ibb.co/47ycz1r/kibitz-review-preview.jpg)](https://youtu.be/JSL6kSgzYJk) | [![Magenty review](https://i.ibb.co/Sx3zSjH/magnety-review-preview.jpg)](https://youtu.be/O7jHpKhhqaY) | [![TotalXclipse review](https://i.ibb.co/55nr9T6/Total-Xclipse-review-preview.jpg)](https://youtu.be/wIfhqBxiufk) |

---

<details>
<summary><h1>📜 Legacy Documentation (Smart! v21 for Satisfactory Update 8) - Click to expand</h1></summary>

**⚠️ Important Notice:** The following documentation is for the **last published version** of Smart! (v21), which was designed for **Satisfactory Update 8**. This version is no longer maintained and is not compatible with Satisfactory 1.1+. The information below is preserved for historical reference and for users still playing on older game versions.

For current development status and features being rebuilt for Satisfactory 1.1+, see the sections above.

---

| Version 21 (Improved Nudge Mode) Overview by [RightMindGamming](https://www.youtube.com/watch?v=NyYymsMa5Gg) | 
|:---:|
| [![v20 tutorial](https://img.youtube.com/vi/NyYymsMa5Gg/hq1.jpg)](https://www.youtube.com/watch?v=NyYymsMa5Gg) | 

## Overview

Get ready to take your factory building to the next level with Smart! This revolutionary mod is the Swiss Army knife of factory building dreams, delivering game-changing features that will blow your mind!

With Smart!, you'll enjoy base-game-friendly enhancements that enable you to scale your builds like never before. You'll have access to automation tools that connect belts, splitters, mergers, and more, so you can focus on the grand vision and be as efficient as possible.

But that's not all! Smart! also offers incredible tools that help you accurately place your objects where you want them. Say goodbye to guesswork and hello to counters, measurements, and cameras that make building a breeze.

And the best part? You can use Smart! guilt-free! Smart! ensures that you still have to pay resources as if you built everything manually, so you don't have to worry about breaking game balance or cheating. Plus, Smart! won't enable building anything you can't build with the base game tools, so you can safely remove Smart! if needed in the future.

## Features

* **Scaling**: Create many copies of foundations, buildings, storage, and more in all three dimensions.
* **Autoconnect**: Autoconnect splitters and mergers to one or more buildings with belts and pipes.
* **Extend**: Duplicate a building with settings, belts, and connectors.
* **Spacing**: Adjust the spacing between structures you scale out.
* **Restore**: Copy and restore scaling and spacing settings for later use.
* **Lift Height Counter**: Display the height of a lift from the starting point or from the world's base height.
* **Camera**: An overlay that shows a view from the proposed building's perspective.

### Discord server

Join us at: <https://discord.gg/SgXY4CwXYw> and get help, discuss the mod, showcase your work, or submit bug reports or feature requests! In the #botspam channel, you can use the chat command "!help" to get general assistance, with support for the most common help requests.

### Recent Updates

* Updated this description to improve clarity and formatting (2/20/2023)
* Updated this description to new layout with pure markdown formatting (11/14/2022)
* v20 released
  * Notice: Updates to the default keybinds! Now use \</\> or \<-\> to open the main menu!
  * Support for pipes with auto-connect
  * Support for pipes with extend
  * Camera added for accurate positioning of structures
  * Lift Height Counter added to assist with accurate height calculations
  * Extend now supports copying conveyors or lifts between the structure and the splitter/merger. However, cannot be a mix of both.
* Smart Mod v20 Overview & Tutorial by RightMindGamming provides a feature overview and tutorial in collaboration with the Smart team (Find it in the videos below!)

### Introduction

Smart! is _the_ Swiss Army knife of your factory building dreams! There are a few key areas where we can help you take your factory building to the next level!

### 🏗️ Foundations, Walls, Ramps

Smart! will allow you to build entire foundations, walls, and ramps in a single click. Go from building each foundation, wall, and ramp individually to laying them out 100 by 100 if you'd like! (and you have enough space for that much concrete!)

### 🏭 Buildings

Smart! has fine control tools allowing you to create entire rows of buildings, carefully spaced apart to allow you to sneak belts or poles between them, consistently! (if you're into making pretty patterns with your layouts!)

### 📦 Belts, Mergers, Splitters, Stack

Smart! makes it easy to layout and space all manner of item transportation. With auto-snapping belts you can even lay down a row of splitters that auto-connect to themselves and the closest machines! (unless you enjoy the alignment game with splitters and mergers...)

### 🎮 Controls

Smart! has a simple button layout, and lots of visual helpers. We don't require that you build any special tools, unlock any special recipe, or use custom foundations or buildings. We extend the base functionality of the game, we don't rebuild it!

Our button layout is:

| Button | Modifiers | Effect |
| ------ | :-------: | -----: |
| `Left Shift` | must be held + scroll | increase/decrease count along the x axis |
| `Z` | must be held + scroll | increase/decrease count along the y axis |
| `Z` + `Left Shift` | must be held + scroll (or use up/down arrow) | increase/decrease count along the z axis |
| `Scroll Wheel` | any key | increases or decreases the key selected |
| `U` | must be held + scroll | increase/decrease steps up/down |
| `T` | must be held + scroll | increase/decrease swirl left/right |
| `L` | must be held + scroll | increase/decrease levitation up/down |
| `P` | must be held + scroll | increase/decrease spacing between items |
| `H` | toggle | lock building position to inspect |
| `/` or `-` | toggle | toggle settings screen |
| `Left/Right Arrow` | one press per increment | increase/decrease count along the x axis |
| `Up/Down Arrow` | one press per increment | increase/decrease count along the y axis |
| `Z + /` | Toggle Mod On/Off | Will enable or disable Smart! |
|`Double-Tap Left-Shift` | Disable Smart for the current build | Useful for times you need to align something that Smart seems to prevent. |

</details>

---

## 🤖 AI Disclosure

Smart! v22 represents a complete rebuild for Satisfactory 1.1 by Finalomega (lead developer). This version was developed with assistance from multiple AI models including Anthropic's Claude, OpenAI's Codex, and GPT-5, accessed via Windsurf by Cognition. An MCP server with vector database indexed with Satisfactory Mod Loader (SML) codebase and Alex's original Smart! source code was provided to the models to add Satisfactory modding expertise.

AI assistance was used for:
- Architecture design and code structure
- C++ implementation and debugging
- Performance analysis and optimization
- Enhanced Input system integration
- Documentation and technical research
- API migration to Satisfactory 1.1

All implementation decisions, testing, refinement, and creative direction by Finalomega. AI was used as a development tool, similar to how developers use IDEs, compilers, and debuggers. Final responsibility for all code quality, functionality, and maintenance remains with the human developer.

Original Smart! mod (v1-v21) was created by Alex through Satisfactory Early Access without AI assistance. Smart! v22 is a ground-up rebuild by Finalomega for Satisfactory 1.1, developed with AI assistance.
