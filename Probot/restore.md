[user]

Restore is planned for a future update (not tied to a specific phase).

--Status--

📋 Planned (Not Yet Implemented)
- Target: After Phase 1 (timing TBD)
- Track requests: <https://github.com/SmartFoundations/SmartIssueTracker/issues>

--What Restore Will Do--

Save and restore scaling/spacing configurations as presets. Create a grid with specific scaling and spacing settings, save it to a numbered slot, then quickly restore that exact configuration later.

**What Gets Saved:**
- Grid dimensions (X, Y, Z scaling)
- Spacing values (X, Y, Z spacing)
- Steps and Stagger settings (if configured)

**What Doesn't Get Saved:**
- Building type (you can restore settings to different building types)
- Recipe selection (recipes are building-specific)

--Example Use Case--

Create a 3x3x3 foundation grid with 1m spacing on all axes. Save this configuration to slot 1. Later, restore slot 1 to quickly recreate the same grid pattern with foundations, walls, or other structures - the spacing and scaling pattern is what's preserved.

--Related Features--

* Works with !scaleobjects, !spacing, !steps, and !stagger
* Perfect for creating consistent patterns across your factory
* Keybinds will be configurable in Options > Keybindings when implemented

--Related Commands--

* !development - Roadmap and priorities
* !knownissues - Feature status updates