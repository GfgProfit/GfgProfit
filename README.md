<div align="center">

# Bogdan · GfgProfit

### Senior Unity Programmer
**Game Systems · Graphics Programming · Engine Technology · Procedural Generation**

I build more than gameplay scripts: **game systems, rendering technology, asset pipelines, procedural worlds, and developer tools**.

<p>
  <img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white">
  <img alt="Unity 6" src="https://img.shields.io/badge/Unity_6-171717?style=for-the-badge&logo=unity&logoColor=white">
  <img alt="HDRP" src="https://img.shields.io/badge/HDRP-Graphics-374151?style=for-the-badge">
  <img alt="HLSL" src="https://img.shields.io/badge/HLSL-Shaders-4B5563?style=for-the-badge">
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
  <img alt="OpenGL" src="https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white">
</p>

**[Technical Skills](#technical-skills)** · **[Projects](#selected-projects)** · **[Engineering Mindset](#engineering-mindset)** · **[Русский](#на-русском)**

</div>

---

## About me

I'm a **Senior Unity Programmer** specializing in technically demanding game-development systems.

My experience goes beyond assembling scenes and components. I work with **C# architecture, real-time rendering, HLSL shaders, binary asset formats, content pipelines, procedural generation, gameplay simulation, runtime performance, and engine tooling**.

I also have a background in **C++/OpenGL engine programming** and earlier **low-level bootloader/OS experiments**. Understanding how a system works underneath the abstraction is a big part of how I approach engineering.

## Technical skills

### 🎮 Unity & C# engineering

- **Unity 6 and HDRP:** gameplay/runtime programming, component lifecycles, assets, prefabs, scene integration, ScriptableObjects and editor workflows.
- **Software architecture:** modular assemblies, clear subsystem responsibilities, interface-driven integrations, and separation between core logic and Unity-specific code.
- **Data-driven gameplay:** reusable definitions, runtime instances, identifiers, configuration, serialization, save/load flows, and validation.
- **Simulation and presentation separation:** independent gameplay state, behavior rules, visual/audio responses, and interactions between them.
- **State management:** state transitions, deterministic operations where appropriate, explicit error reporting, and persistence of gameplay data.
- **Reusable game modules:** components and systems that can be integrated across features without becoming tightly coupled to a single scene.

### 🎨 Real-time rendering & HLSL

- **Custom shader programming:** HLSL shaders and custom material implementations for Unity's High Definition Render Pipeline.
- **Physically based shading:** BRDF concepts, GGX/Burley models, roughness, metallic response, normal mapping, and material-light interactions.
- **Material and texture processing:** texture channel packing, tangent-space normal reconstruction, TBN handling, PBR conversion, and compatibility with external engine material data.
- **GPU-oriented rendering:** instancing, render-data preparation, matrix history, renderer batching considerations, and CPU/GPU workload analysis.
- **Optical rendering:** render-texture-based rifle scopes, variable magnification, focal-plane reticles, and SDF/MSDF rendering techniques.
- **Environmental visuals:** sky and weather integration, time-of-day transitions, cubemaps, lighting profiles, and atmospheric presentation.
- **Effects:** specialized shader-driven visuals, particle systems, Shader Graph, Visual Effect Graph, and effect-update optimization.

### 🧩 Game systems & simulation

- **FPS gameplay:** first-person controllers, cameras, movement, interactions, weapon systems and aiming behavior.
- **Weapons and ballistics:** shooting logic, impact processing, optics integration, and weapon-related state.
- **Inventory and equipment:** grid-based inventories, equipment slots, item data, stack operations, drag-and-drop interactions, and runtime item state.
- **Reliable item operations:** transfer/move/split/equip operations, slot constraints, validation, and atomic transactions.
- **Character and environmental interactions:** health/condition integration, physical reactions, anomaly-style gameplay effects, activation logic, and timed responses.
- **Wave-based gameplay:** enemy waves, combat progression, score/economy systems, and unlockable areas.
- **UI systems:** Unity uGUI, TextMeshPro, Input System integration, procedural grid layouts, custom equipment interfaces, and generated item icons.

### 🛠️ Engine tooling & content pipelines

- **Unity Editor tooling:** custom editor windows, inspectors, asset processors, diagnostics, validation utilities, and content-management workflows.
- **Binary format interpretation:** reading structured game data, building format-specific parsers, and translating foreign-engine representations into Unity.
- **X-Ray/Monolith interoperability:** experience with OGF, OMF, ANM, DDS, THM, LTX, geometry, skeletal animation, texture metadata and level resources.
- **Model and animation conversion:** mesh attributes, UVs, skinning, skeleton hierarchies, bind poses, animation data and runtime compatibility.
- **Texture conversion:** DDS formats, normal-map reconstruction, texture semantics, and HDRP material generation.
- **Mod-aware resource resolution:** Mod Organizer 2 profiles, mod priority rules, file conflicts, virtual resource selection and source traceability.
- **Import reliability:** predictable asset dependencies, reimport consistency, structured diagnostics and automated validation.
- **Tool architecture:** independent parsing logic, source management, asset generation, runtime consumers and dedicated tests.

### 🌍 Procedural generation & large worlds

- **Deterministic world generation:** seed-based generation, reproducible world layouts and stable world-space placement.
- **Terrain generation:** heightmaps, terrain shaping, biomes, environmental distribution and large-area terrain workflows.
- **World composition:** settlements, cities, points of interest, roads and rules for distributing content across environments.
- **Procedural networks:** road layouts, connectivity, routing/pathfinding concepts and spatial constraints.
- **Mesh generation:** procedurally constructed geometry and volumetric/field-based techniques, including Marching Cubes.
- **Runtime world management:** chunks, streaming, caching, visibility/culling and scene population.
- **Performance-aware generation:** large-world memory behavior, allocation control, and parallelization with Unity Jobs/Burst where appropriate.
- **Scale:** experience testing procedural worlds at approximately **10 × 10 km**.

### 📊 Performance engineering & diagnostics

- **Unity Profiler and profiling APIs:** CPU timings, ProfilerRecorder counters, managed allocations, frame metrics and rendering diagnostics.
- **Frame-time analysis:** frame pacing, percentile distributions, spikes, present timing and the distinction between throughput and consistency.
- **Controlled benchmarks:** repeatable camera scenarios, warmup phases, Editor/Player comparisons and machine-readable measurement reports.
- **A/B experiments:** baseline/candidate comparisons, unchanged-binary controls, regression detection and verification of measured improvements.
- **Rendering optimization:** instancing strategies, batching experiments, matrix processing and reducing redundant work.
- **Runtime optimization:** particle-frame caching, update-loop costs, memory allocations and component-level bottleneck identification.
- **Platform-specific debugging:** Unity Player builds, D3D11/D3D12 comparisons and investigation of HDRP or graphics-related assertions.
- **Evidence-based decisions:** profiling before optimizing, preserving reproducible test conditions and reporting limitations of collected metrics.

### ⚙️ C++, graphics APIs & low-level programming

- **C++:** earlier custom game-engine development and systems-level experiments.
- **OpenGL:** graphics programming, rendering fundamentals and engine-side rendering abstractions.
- **Computer architecture fundamentals:** memory, binary representations, boot processes, hardware-facing code and storage access.
- **Bootloader/OS experiments:** a bootloader and experimental kernel functionality, including work with disk-sector reading.
- **Cross-engine reasoning:** understanding how engine abstractions relate to file formats, rendering, data structures and lower-level execution.

### 🧪 Testing, tooling & team practices

- **Automated testing:** Unity EditMode/PlayMode checks, importer validation, regression suites and scenario-based verification.
- **Version control:** Git, GitHub, Git LFS, meaningful commits and traceable changes.
- **Technical investigation:** profiling reports, reproduction steps, comparative experiments, debugging notes and architecture documentation.
- **Team development:** experience as a **team lead / primary developer** on a game project, coordinating gameplay work with animation and UI/UX contributions.
- **AI-assisted development:** using coding agents and local AI tools as implementation/research assistants while retaining architectural decision-making and verification.

---

## Selected projects

### ☢️ [S.T.A.L.K.E.R.: Рейд во Мрак — Raid into Darkness](https://github.com/GfgProfit/stalker_raid_into_darkness)

**Unity 6 · HDRP · C# · HLSL · Engine Interoperability**

An independent, unofficial technical recreation of a heavily modified S.T.A.L.K.E.R.: Anomaly / X-Ray Monolith experience in Unity.

The project showcases **engine interoperability, custom asset import pipelines, shader development, environment rendering, gameplay system architecture, editor tooling, and performance engineering**.

### 🌍 WorldGeneration

**Procedural Generation · Large Worlds · Terrain · Streaming**

A standalone procedural-world technology project focused on **deterministic environments, biomes, terrain, settlements, roads, mesh generation, large-area rendering and runtime world management**.

*Private repository.*

### 🧟 Biohazard Protocol

**Unity · C# · FPS · Wave-based Gameplay · Team Leadership**

A zombie-survival wave shooter with combat, scoring, purchasing and map progression. **Team lead and primary developer**, working alongside animation and UI/UX contributors.

*Private repository.*

### 🎯 Nightfall

**Unity · C# · FPS Gameplay**

An earlier wave-based shooter project focused on gameplay systems and prototyping.

*Private repository.*

### More public repositories

[**Tower-Defence**](https://github.com/GfgProfit/Tower-Defence) · [**White-Desolation**](https://github.com/GfgProfit/White-Desolation) · [**All public repositories**](https://github.com/GfgProfit?tab=repositories)

---

## Engineering mindset

> **Understand the system. Design its boundaries. Measure its behavior. Verify the result.**

I value **maintainable architecture, predictable data flows, reproducible testing, and real performance measurements**.

I enjoy the problems where gameplay programming meets graphics, low-level formats, engine interoperability and large-scale runtime systems.

---

## На русском

<details>
<summary><b>Подробнее обо мне и моих навыках</b></summary>

Привет! Я **Богдан (GfgProfit)**, **Senior Unity Programmer**. Специализируюсь на технической разработке игр: архитектуре игровых систем, рендеринге, шейдерах, инструментах движка, процедурной генерации и оптимизации.

**Мои основные компетенции:**

- **Unity 6 / C# / HDRP:** архитектура игровых подсистем, разделение логики и представления, сериализация, Editor Tools, UI, инвентари, оружие, баллистика и игровые механики.
- **HLSL и рендеринг:** собственные шейдеры, PBR, работа с нормалями и TBN, инстансинг, погодные и атмосферные эффекты, оптика и прицельные сетки.
- **Импорт ресурсов и форматы движков:** OGF, OMF, ANM, DDS, THM, LTX, анимации и скелеты, интеграция с Unity Asset Pipeline, учёт приоритетов модов в MO2.
- **Процедурные миры:** детерминированная генерация, рельеф, биомы, города и дороги, чанки, стриминг, меши и оптимизация больших пространств.
- **Производительность:** Unity Profiler, FrameTimingManager, ProfilerRecorder, анализ времени кадра, контролируемые A/B-бенчмарки, регрессионные проверки и оптимизация CPU/рендера.
- **C++ / OpenGL:** опыт работы над собственным экспериментальным игровым движком и графической подсистемой.
- **Низкоуровневое программирование:** эксперименты с загрузчиком, ядром ОС, устройством памяти и чтением секторов диска.
- **Командная работа:** опыт ведущего разработчика проекта с участием аниматора и UI/UX-дизайнера.

Мой подход — **разобраться в архитектуре, отделить данные и симуляцию от визуала, воспроизвести проблему, измерить её и только затем менять реализацию**.

</details>

---

<div align="center">

**I build systems, not just scenes.**

[GitHub](https://github.com/GfgProfit) · [S.T.A.L.K.E.R.: RVM](https://github.com/GfgProfit/stalker_raid_into_darkness)

</div>
