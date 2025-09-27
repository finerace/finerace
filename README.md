<p align="right">
  <img src="https://flagpedia.net/data/flags/w20/ru.png" width="20" alt="Русский">
  <a href="#finerace-гризан-савелий">Русская версия</a>
  <a href="https://github.com/FineRace">
    <img src="https://i.postimg.cc/nzjMnxmF/mini-icon.png" width="30" alt="icon" align="left">
</p>

<h1 align="center">FineRace (Saveliy Grizan)</h1>
<h3 align="center">Middle Unity Developer</h3>

<p align="center">
  A Unity developer focused on creating clean, scalable architecture and implementing complex gameplay systems. I apply an engineering approach to development to build stable and maintainable products.
  <br>
  <strong>Status: Open to remote work opportunities.</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/finerace/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://t.me/finerace" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
  </a>
</p>

---

<details>
<summary><strong>📌 TL;DR (Key Achievements)</strong></summary>
<br>

*   🏛️ **Architecture & Efficiency:** 
    *   **Case 1:** Designed a [**modular, data-driven customization architecture**](https://github.com/FineRace/Artists-Simulator?tab=readme-ov-file#%EF%B8%8F-implemented-modular-systems) that **accelerated new content implementation by ~75%** and reduced the game design team's dependency on programmers.
    *   **Case 2:** Refactored a complex "God-Object" into a clean, maintainable [**MVP Architecture**](https://github.com/FineRace/Artists-Simulator?tab=readme-ov-file#-from-monolith-to-modularity-a-case-study).

*   ⚡ **Performance Optimization:** 
    *   **Case 1:** Conducted comprehensive optimizations, achieving a [**~40% performance increase in texture operations**](https://github.com/FineRace/Artists-Simulator?tab=readme-ov-file#%EF%B8%8F-implemented-modular-systems) and a significant reduction in peak memory usage.
    *   **Case 2:** Developed a [**procedural city generation algorithm**](https://github.com/finerace/Drift-Tanks-Vs-Zombies?tab=readme-ov-file#-case-study-procedural-generation-of-city-levels), which reduced the build size by ~30% and significantly sped up the design of new levels.  

*   🚀 **Commercial Experience & Complex Systems:** Implemented **complex gameplay systems** [Save-Anywhere](https://github.com/finerace/Ancelight?tab=readme-ov-file#-case-study-designing-a-comprehensive-save-system), [tactical AI with 15+ enemy types](https://github.com/finerace/Drift-Tanks-Vs-Zombies?tab=readme-ov-file#%EF%B8%8F-other-implemented-systems), [drawing accuracy evaluation system](https://github.com/FineRace/Artists-Simulator?tab=readme-ov-file#i-core-gameplay-systems-1)), and shipped [**several commercial projects**](#portfolio-projects), on Google Play and Yandex.Games with full platform SDK integration.

*   ✨ **Metaprogramming & Development Velocity:** Developed an [**open-source AOP plugin**](https://github.com/FineRace/MethodBoundaryAspect.Fody-for-Unity) (IL-weaving) that [**reduces boilerplate code by up to 60%**](https://github.com/FineRace/MethodBoundaryAspect.Fody-for-Unity?tab=readme-ov-file#-the-solution-write-aspects-not-boilerplate).

</details>

---

<details>
<summary><strong>🛠️ Show My Tech Stack</strong></summary>
<br>

*   💻 **Languages & Platforms:**
    *   C# (advanced), HLSL (basics)
    *   PC (Windows), Mobile (Android), WebGL

*   🏛️ **Architecture & Patterns:**
    *   **Principles:** SOLID, KISS, YAGNI, DRY
    *   **Patterns:** DI/IoC (**Zenject**), FSM, ECS (basics), MVP, MVVM, MVC, AOP (**Fody**)
    *   **GoF:** Singleton, Factory, Observer, Command, State, Pool, Adapter, Decorator, Facade, Strategy

*   ⚙️ **Unity Core & Subsystems:**
    *   **Rendering:** URP, HDRP, Built-in RP, Shader Graph, Particle System, Post-Processing
    *   **Asset Management:** Addressable Asset System, Asset Bundles
    *   **UI:** uGUI, UI Toolkit (basics)
    *   **Asynchronous:** **UniTask**, Async/Await, Coroutines
    *   **Other:** Physics 2D/3D, Animator, Timeline, Cinemachine, Input System

*   🎨 **Tools, SDKs & Software:**
    *   **Tools:** Git (Gitflow), Rider, Visual Studio, VS Code
    *   **Plugins:** **DOTween**, ProBuilder, Polybrush
    *   **SDK & API:** Yandex.Games SDK, Google Play Services, VK Games API, Unity Ads, FMOD, JSON (Newtonsoft)
    *   **Graphics & Audio:** Blender, Adobe Photoshop, Illustrator, Audition, Aseprite

</details>

---

<details>
<summary><strong>📂 Portfolio (Projects)</strong></summary>
<br>

My portfolio showcases practical experience in solving problems of various scales. Below are key projects that reflect my development approach, from rapid prototyping in game jams to designing complex architectures for shipped titles.

<a name="portfolio-projects"></a>
#### Flagship & Open-Source Projects
*   📱 **[Artist's Simulator](https://github.com/FineRace/Artists-Simulator)**
    
    A mobile game released on Google Play, built on the principles of clean architecture. This project is a practical implementation of SOLID, DI, FSM, and asynchronous programming to create a maintainable and easily extendable product.
    *   **Key Achievements:**
        *   Developed a flexible data-driven architecture using **DI (Zenject)**, enabling game designers to configure content without programmer involvement.
        *   Conducted a full refactoring of the shop UI module from a "God Object" to the **MVP** pattern, decomposing it into independent, testable components.
        *   Implemented an asynchronous core with **UniTask** and **Addressables** to ensure a smooth, freeze-free application experience.
        *   Used a custom **AOP plugin** to reduce boilerplate code (logging, exception handling) by approximately 60%.

*   ✨ **[AOP Plugin for Unity](https://github.com/FineRace/MethodBoundaryAspect.Fody-for-Unity)**
    
    An open-source metaprogramming tool that enables an aspect-oriented approach in Unity for writing cleaner code.
    *   **Key Achievements:**
        *   Implemented **IL-code weaving** using Fody, allowing logic to be injected into methods at compile time with zero runtime overhead.
        *   Solved the non-trivial challenge of compatibility with **asynchronous methods (UniTask)** and compiler-generated state machines, a common issue for AOP tools in Unity.

---
#### Technical Projects & Shipped Games
*   🔫 **[Ancelight FPS](https://github.com/FineRace/Ancelight-FPS-Project)**

    A complete framework for a classic FPS, created to deeply explore and implement interconnected gameplay systems from scratch.
    *   **Key Achievements:**
        *   Implemented a **"Save-Anywhere" system**, allowing the entire game world's state to be "frozen" and restored at any moment, including enemy positions, projectiles, and triggers.
        *   Created **tactical AI with team interaction**: enemies alert allies and can perform predictive shooting.
        *   Wrote an advanced **character controller** with action mechanics: a grappling hook on a `SpringJoint` and a dash system.
        *   Developed a data-driven weapon system using `ScriptableObjects` and custom procedural recoil.

*   🤖 **[Drift Tanks VS Zombies](https://github.com/FineRace/Tanks-Yandex-Games)**

    A WebGL game published on the Yandex.Games platform, with a focus on procedural generation and web platform integration.
    *   **Key Achievements:**
        *   Developed a multi-stage **procedural city generation algorithm** that creates unique maps from a single `seed`.
        *   Implemented full integration with the **Yandex.Games SDK** (authentication, cloud saves, IAP, ads).
        *   Created a custom **`Rigidbody`-based tank controller** with realistic suspension simulation, inertia, and drifting mechanics.

---
#### Teamwork & Game Jam Experience
*   🦊 **[Fox Factory](https://github.com/FineRace/FoxFactory) & Fox Town**
    
    A series of projects created under tight deadlines (72 hours) with the same team for game jams (Indie Varvar's Jam, VK Games).
    *   **Key Achievements:**
        *   Served as the **sole programmer** in both projects, successfully bringing the vision of game designers and artists to life.
        *   Demonstrated stable and effective teamwork, rapid idea implementation, and the ability to adapt to different platform requirements.

*   🏃 **[Job Runner](https://finerace.itch.io/job-runner)**
    
    A minimalist 2D platformer created solo for a game jam.
    *   **Key Achievements:**
        *   Practiced the rapid implementation and completion of a project from concept to a finished build within strict time constraints.

---
#### Early Projects & Experiments
*   🦎 **Russ VS Lizards: Battle for the Baikal**
    
    A top-down shooter created to experiment with "raw" API integration.
    *   **Key Achievements:**
        *   Implemented direct interaction with the Yandex.Games API via **HTTP requests**, bypassing the standard SDK for authentication and data submission.

*   ⚪ **Peem Poom**

    An early casual game released on Google Play.
    *   **Key Achievements:**
        *   Gained experience with the full mobile game release cycle and **Google Play API** integration (leaderboards, achievements).

*   🧟 **Zoox**

    The first serious 2D project, a zombie apocalypse game developed at the age of 14.
    *   **Key Achievements:**
        *   Demonstrates an early mastery of the entire development pipeline, from concept to release, including **creating all 2D graphics from scratch** in Adobe Illustrator.

</details>
