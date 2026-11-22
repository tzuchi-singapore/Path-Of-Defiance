# 仙逆·逆天路 · Path of Defiance

2.5D xianxia cultivation action RPG (Three.js) — farm stages, break through realms and evolve from **mortal to god**.

**Play:** https://tzuchi-singapore.github.io/Path-Of-Defiance/

- 7 realms: 凡人 → 凝气 → 筑基 → 结丹 → 元婴 → 化神 → 踏天, each with its own 3D hero model (`models/hero_t0-6.glb`)
- 6 chapters incl. 炎狱火域 (Inferno Lord) and 冰封雪渊 (Frost Empress)
- Static Tripo meshes are auto-rigged in code (humanoid + quadruped) with procedural keyframe animation, spring hair/cape, hologram materialize/dissolve, voronoi shatter for meteors / ice / pagoda
- Baked glow on textures (eyes, weapons, runes) is detected per model and animated (pulse + particles)

## Swapping models
Drop a GLB at the same path in `models/` (see `MODEL_DEF` in `index.html`).
Waiting for: `boss_firelord.glb`, `boss_icequeen.glb`, `mob_fireimp.glb`, `mob_frostwolf.glb` (falls back to existing models until added).
