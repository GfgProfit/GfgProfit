<!--
  GfgProfit / GitHub Profile README
  Publish in the root of a PUBLIC repository named exactly: GfgProfit/GfgProfit
  Private projects are described at a high level and are intentionally NOT linked.
  Review the private-project section before making this README public.
-->

<div align="center">

# GfgProfit

### Game Systems · Graphics Programming · Engine Technology

**Hi, I'm Bogdan.** I build the systems behind games: rendering, asset pipelines,
procedural worlds, gameplay architecture, and tools to measure what actually happens at runtime.

*From C++/OpenGL and low-level experiments to large-scale Unity 6 HDRP projects.*

<p>
  <a href="https://github.com/GfgProfit/stalker_raid_into_darkness"><img alt="Current project: S.T.A.L.K.E.R. RVM" src="https://img.shields.io/badge/MAIN_PROJECT-S.T.A.L.K.E.R._RVM-46665B?style=for-the-badge" /></a>
  <a href="https://github.com/GfgProfit?tab=repositories"><img alt="GitHub repositories" src="https://img.shields.io/badge/EXPLORE-MY_REPOSITORIES-24292F?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p>
  <img alt="C Sharp" src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white" />
  <img alt="C Plus Plus" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img alt="HLSL" src="https://img.shields.io/badge/HLSL-Shader_Programming-4B5563?style=flat-square" />
  <img alt="Unity" src="https://img.shields.io/badge/Unity_6-000000?style=flat-square&logo=unity&logoColor=white" />
  <img alt="HDRP" src="https://img.shields.io/badge/HDRP-Rendering-374151?style=flat-square" />
  <img alt="OpenGL" src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" />
</p>

**[Current project](#-featured-project)** · **[Skills](#-what-i-work-on)** · **[Projects](#-other-projects)** · **[Русский](#-на-русском)**

</div>

---

## ☢️ Featured project

### [S.T.A.L.K.E.R.: Рейд во Мрак / Raid into Darkness](https://github.com/GfgProfit/stalker_raid_into_darkness)

**Active development · Public repository · Unity 6 · HDRP · C# · HLSL**

An **unofficial, independent port** of a heavily modified S.T.A.L.K.E.R.: Anomaly / X-Ray Monolith setup to Unity 6 HDRP. This is not X-Ray embedded inside Unity: the engine-facing systems and tooling are being reimplemented around a new C# architecture.

What is already part of the project:

- **X-Ray compatibility tooling:** import pipelines for OGF, OMF, ANM, texture/material metadata and level data; source resolution across Mod Organizer 2 profiles and mod priorities.
- **Custom rendering:** HDRP material/shader work in HLSL, PBR workflows, normal/TBN handling, specialized visuals, instancing, weather and environmental lighting.
- **Gameplay foundations:** first-person systems, weapons and ballistics, optics/reticles, inventory and equipment, anomaly logic and effects.
- **Engineering infrastructure:** Editor tools, reproducible benchmarks, regression checks and performance investigations in both Editor and Player builds.

> The port is **in progress**, not a finished playable replacement for the original game. This is an **unofficial fan project**, not affiliated with GSC Game World.

**[Explore the source and technical documentation →](https://github.com/GfgProfit/stalker_raid_into_darkness)**

---

## 🧠 What I work on

| Area | Hands-on experience |
| :-- | :-- |
| **Game systems** | C# architecture, FPS systems, weapons and ballistics, grid inventory, equipment, wave-based gameplay, state management, simulation/visual separation. |
| **Rendering & shaders** | HLSL, Unity HDRP, PBR lighting/materials, TBN and normal mapping, GGX/Burley shading concepts, instanced rendering, optics and visual effects. |
| **Engine & asset tooling** | Unity Editor scripting, binary-format parsing, custom asset importers, animations and skeletons, texture/material conversion, MO2-aware resource resolution. |
| **Procedural generation** | Seed-based deterministic worlds, terrain and biomes, roads, cities, points of interest, placement rules, chunk streaming, culling and mesh generation. |
| **Performance engineering** | CPU-side profiling, frame pacing investigations, allocation tracking, repeatable A/B benchmarks, regression tests and evidence-based optimization. |
| **Lower-level programming** | Earlier C++/OpenGL engine work; experiments with bootloaders, OS-kernel fundamentals and direct disk-sector access. |

<details>
<summary><b>🔬 Detailed technical toolbox</b></summary>

### Languages and core technologies

- **C#** — primary language for game systems, editor extensions, importers and runtime tooling.
- **C++** — earlier engine and low-level programming projects.
- **HLSL** — custom shaders and rendering work in Unity HDRP.
- **OpenGL** — graphics API experience from earlier engine experiments.

### Unity / rendering

- Unity 6, **High Definition Render Pipeline (HDRP)**, ScriptableObjects, Editor/asset workflows.
- Shader development, PBR shading, textures and material pipelines, instancing, particles/VFX.
- Visual Effect Graph, Shader Graph, Unity Input System, uGUI / TextMeshPro.
- Model, rig, animation and content conversion from external engine formats.

### Importing and format interoperability

- X-Ray formats and metadata: **OGF, OMF, ANM, DDS, THM, LTX**, plus level/geometry/collision/detail data.
- Import source resolution for **Mod Organizer 2**: active profiles, priorities and resource conflicts.
- Reimport stability, dependency tracking, AssetDatabase integration and validation.

### Procedural world technology

- Deterministic seeds, terrain/biome generation, heightmaps and 16-bit terrain stamps.
- Cities, roads, POIs, world-space placement, persistent IDs and chunk-independent results.
- Mesh generation, **Marching Cubes**, chunk streaming and visibility/culling systems.
- Unity **Jobs + Burst**, caching and runtime allocation analysis.

### Testing and workflow

- Unity EditMode/PlayMode tests, repeatable import checks and performance regressions.
- Profiling and A/B comparisons with controlled Player builds; frame-time and GC-allocation analysis.
- Git, GitHub, Git LFS, code reviews, technical reports and AI-assisted development workflows.

</details>

---

## 🌍 Other projects

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">Focus</th>
    <th align="left">Availability</th>
  </tr>
  <tr>
    <td><b>WorldGeneration</b></td>
    <td>Large procedural worlds inspired by survival sandboxes: terrain, biomes, settlements, roads, deterministic generation, custom rendering and runtime streaming.</td>
    <td>Private project</td>
  </tr>
  <tr>
    <td><b>Biohazard Protocol</b></td>
    <td>Wave-based zombie survival shooter; combat, score/economy mechanics and map progression. Served as team lead / primary developer.</td>
    <td>Private project</td>
  </tr>
  <tr>
    <td><b>Nightfall</b></td>
    <td>Earlier wave-based shooter project and gameplay prototyping.</td>
    <td>Private project</td>
  </tr>
  <tr>
    <td><b>Tower-Defence</b></a></td>
    <td>Earlier game-development project.</td>
    <td>Private project</td>
  </tr>
  <tr>
    <td><b>White-Desolation</b></a></td>
    <td>Additional game-development repository.</td>
    <td>Private project</td>
  </tr>
</table>

<details>
<summary><b>📈 A few engineering highlights</b></summary>

- Built and tested **large procedural worlds (up to 10 × 10 km)**, including terrain, settlements, placement and streaming systems.
- In a specific local **WorldGeneration Player benchmark**, observed approximately **280 FPS** with **0 B/frame managed GC allocations**. These are scenario- and hardware-dependent measurements, not a general performance guarantee.
- Worked on measurable optimizations in RVM, including particle-frame caching, matrix-history handling, renderer batching experiments and frame-pacing investigations.
- Used repeatable experiments and regression checks to distinguish code changes from unrelated measurement noise.

</details>

---

## 🛠️ How I approach engineering

**Make it reproducible. Measure it. Then change it.**

- Prefer clear **data, simulation and presentation boundaries** instead of tightly coupled scene logic.
- Treat import pipelines as engineering systems: **determinism, traceability, idempotence and validation** matter.
- Investigate frame-time problems with **profiles and controlled comparisons**, not just an FPS counter.
- When porting older games, preserve the original behavior where practical while modernizing the implementation.
- Use AI coding tools to accelerate research, reviews and implementation **without outsourcing architectural decisions or validation**.

### Next on my roadmap *(planned, not shipped)*

- Finish the S.T.A.L.K.E.R. port and continue stabilizing its rendering, game systems and performance.
- Add **co-op multiplayer with Mirror** after the core single-player port.
- Develop an **SDK and modding ecosystem** with configuration, extensibility and dedicated tooling.
- Continue exploring custom AI/navigation and procedural character-animation systems.

---

## 🇷🇺 На русском

<details>
<summary><b>Кто я и чем занимаюсь — кратко на русском</b></summary>

Привет! Я **GfgProfit (Богдан)**. Разрабатываю игровые системы, графику, инструменты для движков и процедурные миры. Мне интереснее не просто собрать сцену, а разобраться, **как устроены её рендеринг, симуляция, импорт ресурсов и производительность**.

**Мои основные направления:**

- **C# / Unity 6 HDRP:** игровые системы, инвентарь, оружие, баллистика, аномалии, погода, редакторские инструменты.
- **HLSL / графика:** собственные шейдеры, физически корректное освещение, материалы, инстансинг, спецэффекты и оптика.
- **Импорт и совместимость:** бинарные форматы X-Ray (OGF/OMF/ANM и другие), ресурсы локаций, MO2, анимации и HDRP-материалы.
- **Процедурная генерация:** большие миры, биомы, города, дороги, чанки, стриминг, Jobs/Burst и детерминированность.
- **Оптимизация:** профилирование, диагностика времени кадра, контролируемые A/B-тесты, бенчмарки и регрессионные проверки.
- **C++ / OpenGL / низкий уровень:** ранее занимался экспериментальным движком, загрузчиком и основами собственного ядра ОС.

**Главный проект сейчас:** [S.T.A.L.K.E.R.: «Рейд во Мрак»](https://github.com/GfgProfit/stalker_raid_into_darkness) — перенос X-Ray/Monolith-сборки на Unity 6 HDRP с собственной архитектурой на C#.

**Другие проекты:** WorldGeneration (процедурный генератор мира), Biohazard Protocol (волновой зомби-шутер; командная разработка), Nightfall (волновой шутер), а также небольшие публичные репозитории.

**В планах, а не в списке готовых возможностей:** кооператив через Mirror, SDK, моддинг и расширенные системы AI/навигации.

</details>

---

<div align="center">

**I build systems, not just scenes.**

<sub>Projects are always evolving. The source code and current progress speak louder than a wall of skill badges.</sub>

<br />

<a href="https://github.com/GfgProfit">GitHub profile</a> · <a href="https://github.com/GfgProfit/stalker_raid_into_darkness">S.T.A.L.K.E.R.: RVM</a>

</div>
