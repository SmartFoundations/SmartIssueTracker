[user]

Auto-Connect is planned for Phase 2 of Smart! Foundations.

--Status--

🚧 In Development (Phase 2)
- Not available in v22 (Phase 1). Manual connections required for now.
- Track progress and open issues here: <https://github.com/SmartFoundations/SmartIssueTracker/issues>

--What Auto-Connect Will Do--

Automatically place belts (and later pipes) between:
- Splitters/Mergers ↔ Production buildings
- Pipeline Junction Cross ↔ Fluid buildings (planned)

Goals:
- Smart routing that respects building I/O
- Clean, consistent layouts at scale
- Works alongside scaling/spacing/steps/stagger

--Example Workflows (Planned)--

- Place a Merger next to an Assembler → Auto-Connect runs a belt to the correct input.
- Place a Splitter chain along a row of manufacturers → Auto-Connect feeds each building.
- Fluids: Place a Pipeline Junction Cross near Refineries → Auto-Connect links pipes (phase follow-up).

--Staggered Splitters (Planned)--

For multi-input buildings, Auto-Connect may suggest staggered heights for splitters to keep belt work clean and unobstructed.

--Temporarily Disable Suggestion (Planned UX)--

If a suggestion appears when you don’t want it, you’ll be able to quickly disable Auto-Connect for the current placement attempt (exact control will be finalized in Phase 2 UX pass).

--Related Commands--

* !knownissues — Current status (Auto-Connect in development)
* !spacing, !steps, !stagger — Pair with Auto-Connect for clean scaled layouts
* !scaleobjects — Build at scale; Auto-Connect will integrate with scaled grids

--Notes--

- Multi-player support is limited; Auto-Connect behavior in MP will be validated during Phase 2.
- For now, connect belts/pipes manually. See !knownissues for updates.