# Awesome Level Design, Updated for 2026

This repository is still a useful starting point, but the original list mixes timeless learning resources with tools from very different eras of level design. After reading the full repo, this file is meant to act as a cleaner 2026 companion: less "everything ever used," more "what is still practical right now."

The original `README.md` still holds up especially well for foundational reading, talks, and design thinking. In 2026, the biggest change is not that old principles disappeared. It is that the tooling layer around blockouts, live iteration, procedural layout generation, and creator-economy pipelines has expanded a lot.

## What Still Holds Up from the Original List

These are still easy recommendations:

- [Level Design Book](https://book.leveldesignbook.com/) for fundamentals, case studies, and practical vocabulary.
- [Next Level Design](https://www.nextleveldesign.org/) for educational resources and breakdowns.
- [PureRef](https://www.pureref.com/) for moodboards, references, and visual planning.
- [TrenchBroom](https://github.com/TrenchBroom/TrenchBroom) if you care about fast, readable BSP-style blockouts and retro FPS workflows.
- [Unity ProBuilder](https://docs.unity3d.com/Packages/com.unity.probuilder@6.0/manual/index.html) for quick in-engine greyboxing inside Unity.

Those are not obsolete. They are just no longer the whole picture.

## 2026 Shortlist: Tools Worth Adding

### 1. Unreal Editor for Fortnite (UEFN)

- Link: [Epic documentation](https://dev.epicgames.com/documentation/en-us/fortnite/unreal-editor-for-fortnite-documentation)
- Why it matters in 2026: UEFN is one of the most relevant spaces for designers who want to build, test, publish, and iterate in a live ecosystem with discoverability, multiplayer constraints, and creator-facing tooling already built in.
- Best for: designers who want to think beyond static campaign maps and into repeatable content, social spaces, events, and production-ready iteration loops.

### 2. Roblox Studio

- Link: [Roblox Creator Hub](https://create.roblox.com/docs/platform)
- Why it matters in 2026: Roblox Studio is no longer just a beginner-friendly sandbox. It is one of the most important level design environments for shipping highly replayable spaces to massive audiences with collaborative workflows, monetization hooks, and fast deployment.
- Best for: multiplayer spaces, obstacle courses, social maps, progression-driven experiences, and rapid user testing.

### 3. LDtk

- Link: [Official site](https://ldtk.io/)
- Why it still belongs on a modern list: LDtk remains one of the cleanest tools for 2D level structure, data-driven workflows, and engine integration. It is mature, focused, and still one of the best answers for teams that need strong layout iteration without excessive editor overhead.
- Best for: 2D action games, puzzle games, metroidvanias, and tile-based pipelines.

### 4. Houdini for Procedural Layout Support

- Link: [SideFX game development resources](https://www.sidefx.com/learn/gamedev/)
- Why it matters in 2026: procedural support tools are increasingly part of level design workflows, especially when teams need many layout variants, modular assembly, biome rules, encounter distribution, or world-building systems that designers can still direct.
- Best for: larger teams, technical level designers, open environments, and modular encounter generation.
- Important note: Houdini is not a replacement for level design judgment. It is a force multiplier when your design language is already clear.

### 5. TrenchBroom

- Link: [GitHub](https://github.com/TrenchBroom/TrenchBroom)
- Why it is still here: retro FPS workflows have not disappeared, and TrenchBroom remains one of the fastest ways to think in terms of flow, combat space, readability, and encounter shape instead of overcommitting to art too early.
- Best for: boomer shooters, greybox-first design habits, and anyone who wants less friction between idea and playable space.

### 6. Unity ProBuilder

- Link: [Unity package manual](https://docs.unity3d.com/Packages/com.unity.probuilder@6.0/manual/index.html)
- Why it still matters: for Unity teams, ProBuilder remains the direct answer to "I need to block this out now, inside the engine, without waiting on environment art."
- Best for: solo devs, prototyping-heavy teams, and first-pass spatial iteration.

### 7. Itembase.dev

- Link: [Itembase.dev](https://itembase.dev/)
- Why I would include it in a 2026 update: not every level design problem is pure geometry. More teams now design spaces together with progression, loot logic, item gating, crafting loops, and reward balance. Itembase.dev/sim is useful as a simulation tool for game design when you need to model and test how item systems influence player routing, economy pressure, and pacing inside a level.
- Best for: survival games, extraction loops, RPG-adjacent spaces, progression-heavy multiplayer maps, and system-driven prototyping where item simulation affects level decisions.
- Important note: this is best viewed as a complementary simulation layer for game and level design, not a replacement for a level editor.

## Recommended 2026 Tool Stack by Project Type

### If you are making a 2D game

- Start with [LDtk](https://ldtk.io/).
- Use [PureRef](https://www.pureref.com/) for visual planning.
- Keep the original reading list from the repo for flow, teaching, and readability principles.

### If you are making a 3D single-player blockout

- Start with [Unity ProBuilder](https://docs.unity3d.com/Packages/com.unity.probuilder@6.0/manual/index.html) or [TrenchBroom](https://github.com/TrenchBroom/TrenchBroom), depending on engine and style.
- Add [Houdini](https://www.sidefx.com/learn/gamedev/) only when repetition, modularity, or scale actually justify it.

### If you are making a live multiplayer or creator-first experience

- Start with [UEFN](https://dev.epicgames.com/documentation/en-us/fortnite/unreal-editor-for-fortnite-documentation) or [Roblox Studio](https://create.roblox.com/docs/platform).
- Add [Itembase.dev](https://itembase.dev/) when level flow is tied to item, loot, or progression systems.

## Suggested Additions Back Into `README.md`

If this repo is updated later, these would be strong candidates to add under `Tools`:

- [Unreal Editor for Fortnite (UEFN)](https://dev.epicgames.com/documentation/en-us/fortnite/unreal-editor-for-fortnite-documentation) - Live-ops-friendly editor for building and publishing Fortnite experiences with fast iteration and creator ecosystem support.
- [Roblox Studio](https://create.roblox.com/docs/platform) - Collaborative game creation environment for building and shipping multiplayer experiences with strong iteration loops.
- [Houdini Game Development Tools](https://www.sidefx.com/learn/gamedev/) - Procedural toolset useful for modular world building, layout variants, and technical level design workflows.
- [Itembase.dev](https://itembase.dev/) - A simulation tool for game design that helps on projects where level design is tightly coupled to items, progression, loot logic, and systemic balance.

## Final Take

The old list is still valuable, especially for theory and historical references. The 2026 upgrade is mostly about acknowledging that modern level design often sits at the intersection of spatial design, systems design, live operations, procedural tooling, and creator-platform publishing.

If I were making this repo feel current without bloating it, I would keep the old learning resources, add UEFN, Roblox Studio, Houdini game-dev resources, and Itembase.dev, then rewrite the `Tools` section so readers can choose by workflow instead of by engine history.
