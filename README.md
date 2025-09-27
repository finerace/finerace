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

<br>

<details>
<summary>Русская Версия</summary>

<p align="right">
  <img src="https://flagpedia.net/data/flags/w20/gb.png" width="20" alt="English">
  <a href="https://github.com/finerace/finerace/edit/main/README.md#finerace-saveliy-grizan"> English Version</a>
  <a href="https://github.com/FineRace">
    <img src="https://i.postimg.cc/nzjMnxmF/mini-icon.png" width="30" alt="icon" align="left">
  </a>
</p>

<h1 align="center">FineRace (Гризан Савелий)</h1>
<h3 align="center">Middle Unity Developer</h3>

<p align="center">
  Разработчик на Unity с фокусом на создании чистой, масштабируемой архитектуры и реализации сложных игровых систем. Практикую инженерный подход к разработке для создания стабильных и поддерживаемых продуктов.
  <br>
  <strong>Статус: Открыт к предложениям о работе (удаленно).</strong>
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
<summary><strong>📌 TL;DR (Ключевые достижения)</strong></summary>
<br>

*   🏛️ **Архитектура и эффективность:** 
    *   **Кейс 1:** Спроектировал [**модульную, data-driven архитектуру кастомизации**](https://github.com/FineRace/Artists-Simulator?tab=readme-ov-file#ii-meta--progression-systems), которая **ускорила добавление нового контента на ~75%** и снизила зависимость гейм-дизайна от программиста.
    *   **Кейс 2:** Провёл рефакторинг сложного "God-Object" до чистой, поддерживаемой [**MVP Архитектуры**](https://github.com/FineRace/Artists-Simulator?tab=readme-ov-file#-%D0%BE%D1%82-%D0%BC%D0%BE%D0%BD%D0%BE%D0%BB%D0%B8%D1%82%D0%B0-%D0%BA-%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D0%BA%D0%B5%D0%B9%D1%81-%D1%81%D1%82%D0%B0%D0%B4%D0%B8).

*   ⚡ **Оптимизация производительности:** 
    *   **Кейс 1:** Провел комплексную оптимизацию, добившись [**ускорения операций с текстурами на ~40%**](https://github.com/FineRace/Artists-Simulator?tab=readme-ov-file#i-core-gameplay-systems) и значительного снижения пикового потребления памяти.
    *   **Кейс 2:** Разработал [**алгоритм процедурной генерации города**](https://github.com/FineRace/Tanks-Yandex-Games?tab=readme-ov-file#-%D0%BA%D0%B5%D0%B9%D1%81-%D1%81%D1%82%D0%B0%D0%B4%D0%B8-%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D0%B4%D1%83%D1%80%D0%BD%D0%B0%D1%8F-%D0%B3%D0%B5%D0%BD%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D1%8F-%D0%B3%D0%BE%D1%80%D0%BE%D0%B4%D1%81%D0%BA%D0%B8%D1%85-%D1%83%D1%80%D0%BE%D0%B2%D0%BD%D0%B5%D0%B9), что уменьшило размер билда на ~30% и многократно ускорило проектирование новых уровней.  

*   🚀 **Коммерческий опыт и сложные системы:** Реализовал **сложные игровые системы** ([Save-Anywhere](https://github.com/FineRace/Ancelight-FPS-Project?tab=readme-ov-file#-%D0%BA%D0%B5%D0%B9%D1%81-%D1%81%D1%82%D0%B0%D0%B4%D0%B8-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D0%BB%D0%BD%D0%BE%D0%B9-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B-%D1%81%D0%BE%D1%85%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D0%B9), [тактический AI с 15+ типами врагов](https://github.com/FineRace/Ancelight-FPS-Project?tab=readme-ov-file#ii-ai-%D0%B8-%D0%B8%D0%B3%D1%80%D0%BE%D0%B2%D1%8B%D0%B5-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B8), [система оценки точности рисования](https://github.com/FineRace/Artists-Simulator?tab=readme-ov-file#i-core-gameplay-systems)), а также выпустил [**несколько коммерческих проектов**](#-portfolio-проекты), в Google Play и Яндекс.Играх с полной интеграцией платформенных SDK.

*   ✨ **Метапрограммирование и ускорение разработки:** Разработал [**open-source AOP-плагин**](https://github.com/FineRace/MethodBoundaryAspect.Fody-for-Unity) (IL-weaving), который [**сокращает шаблонный код до +60%**](https://github.com/FineRace/MethodBoundaryAspect.Fody-for-Unity?tab=readme-ov-file#-the-solution-write-aspects-not-boilerplate).

</details>

---

<details>
<summary><strong>🛠️ Показать мой стек технологий</strong></summary>
<br>

*   💻 **Языки и Платформы:**
    *   C# (продвинутый), HLSL (базовый)
    *   PC (Windows), Mobile (Android), WebGL

*   🏛️ **Архитектура и Паттерны:**
    *   **Принципы:** SOLID, KISS, YAGNI, DRY
    *   **Паттерны:** DI/IoC (**Zenject**), FSM, ECS (основы), MVP, MVVM, MVC, AOP (**Fody**)
    *   **GoF:** Singleton, Factory, Observer, Command, State, Pool, Adapter, Decorator, Facade, Strategy

*   ⚙️ **Unity Core & Subsystems:**
    *   **Рендеринг:** URP, HDRP, Built-in RP, Shader Graph, Particle System, Post-Processing
    *   **Управление ресурсами:** Addressable Asset System, Asset Bundles
    *   **UI:** uGUI, UI Toolkit (основы)
    *   **Асинхронность:** **UniTask**, Async/Await, Coroutines
    *   **Прочее:** Physics 2D/3D, Animator, Timeline, Cinemachine, Input System

*   🎨 **Инструменты, SDK и ПО:**
    *   **Инструменты:** Git (Gitflow), Rider, Visual Studio, VS Code
    *   **Плагины:** **DOTween**, ProBuilder, Polybrush
    *   **SDK и API:** Yandex.Games SDK, Google Play Services, VK Games API, Unity Ads, FMOD, JSON (Newtonsoft)
    *   **Графика и Аудио:** Blender, Adobe Photoshop, Illustrator, Audition, Aseprite

</details>

---

<details>
<summary><strong>📂 Portfolio (Проекты)</strong></summary>
<br>

Мое портфолио демонстрирует практический опыт решения задач разного масштаба. Ниже представлены ключевые проекты, отражающие мой подход к разработке: от быстрой прототипизации на геймджемах до проектирования комплексных архитектур для выпущенных игр.

<a name="portfolio-проекты"></a>
#### Флагманские и Open-Source проекты
*   📱 **[Artist's Simulator](https://github.com/FineRace/Artists-Simulator)**
    
    Выпущенная в Google Play мобильная игра, построенная на принципах чистой архитектуры. Проект является практической реализацией принципов SOLID, DI, FSM и асинхронного подхода для создания поддерживаемого и легко расширяемого продукта.
    *   **Ключевые достижения:**
        *   Разработана гибкая data-driven архитектура на базе **DI (Zenject)**, что позволило гейм-дизайнерам настраивать контент без участия программиста.
        *   Проведен полный рефакторинг UI-модуля (магазин) по паттерну **MVP**, что декомпозировало "God Object" на независимые, тестируемые компоненты.
        *   Внедрено асинхронное ядро на **UniTask** и **Addressables** для обеспечения плавной работы приложения без фризов.
        *   Использован собственный **AOP-плагин** для сокращения boilerplate-кода (логирование, обработка исключений) примерно на 60%.

*   ✨ **[AOP Plugin for Unity](https://github.com/FineRace/MethodBoundaryAspect.Fody-for-Unity)**
    
    Open-source инструмент для метапрограммирования, позволяющий применять аспектно-ориентированный подход в Unity для написания более чистого кода.
    *   **Ключевые достижения:**
        *   Реализована работа с **IL-кодом (weaving)** на базе Fody, позволяющая "вплетать" логику в методы на этапе компиляции без оверхеда в рантайме.
        *   Решена нетривиальная задача совместимости с **асинхронными методами (UniTask)** и генерируемыми компилятором стейт-машинами, что является частой проблемой для AOP-инструментов в Unity.

---
#### Технические проекты и опубликованные игры
*   🔫 **[Ancelight FPS](https://github.com/FineRace/Ancelight-FPS-Project)**

    Полноценный фреймворк для классического FPS, созданный для глубокой проработки и реализации взаимосвязанных игровых систем с нуля.
    *   **Ключевые достижения:**
        *   Реализована **система сохранений "Save-Anywhere"**, позволяющая "заморозить" и восстановить состояние всего игрового мира в любой момент, включая положение врагов, пуль и триггеров.
        *   Создан тактический **AI с командным взаимодействием**: враги оповещают союзников о тревоге и могут вести огонь на упреждение.
        *   Написан продвинутый **контроллер персонажа** с action-механиками: крюк-кошка на `SpringJoint` и система рывков (dashes).
        *   Разработана data-driven система оружия на `ScriptableObjects` и кастомная процедурная отдача.

*   🤖 **[Drift Tanks VS Zombies](https://github.com/FineRace/Tanks-Yandex-Games)**

    WebGL-игра, опубликованная на платформе Яндекс.Игры, с фокусом на процедурной генерации и интеграции с веб-платформой.
    *   **Ключевые достижения:**
        *   Разработан многоэтапный **алгоритм процедурной генерации** городских уровней, создающий уникальные карты по одному `seed`.
        *   Реализована полная интеграция с **Yandex.Games SDK** (авторизация, облачные сохранения, IAP, реклама).
        *   Создан кастомный **`Rigidbody`-контроллер танка** с реалистичной симуляцией работы подвески, инерцией и механикой дрифта.

---
#### Опыт командной работы и геймджемов
*   🦊 **[Fox Factory](https://github.com/FineRace/FoxFactory) & Fox Town**
    
    Серия проектов, созданных в сжатые сроки (72 часа) в составе одной и той же команды для геймджемов (Indie Varvar's Jam, VK Игры).
    *   **Ключевые достижения:**
        *   Выступил в роли **единственного программиста** в обоих проектах, успешно реализуя видение гейм-дизайнеров и художников.
        *   Демонстрация стабильной и эффективной командной работы, быстрой реализации идей и умения адаптироваться под требования разных платформ.

*   🏃 **[Job Runner](https://finerace.itch.io/job-runner)**
    
    Минималистичный 2D-платформер, созданный для геймджема в одиночку.
    *   **Ключевые достижения:**
        *   Практика в быстрой реализации и завершении проекта от идеи до готового билда в рамках жестких временных ограничений.

---
#### Ранние проекты и эксперименты
*   🦎 **Russ VS Lizards: Battle for the Baikal**
    
    Top-down shooter, созданный для эксперимента с "сырой" интеграцией API.
    *   **Ключевые достижения:**
        *   Реализовано прямое взаимодействие с API Яндекс.Игр через **HTTP-запросы**, минуя стандартный SDK, для авторизации и отправки данных.

*   ⚪ **Peem Poom**

    Одна из ранних казуальных игр, выпущенная в Google Play.
    *   **Ключевые достижения:**
        *   Получен опыт полного цикла релиза мобильной игры и интеграции **Google Play API** (лидерборды, достижения).

*   🧟 **Zoox**

    Первый серьезный 2D-проект в жанре зомби-апокалипсиса, разработанный в 14 лет.
    *   **Ключевые достижения:**
        *   Демонстрация раннего освоения всего пайплайна разработки: от идеи до релиза, включая **создание всей 2D-графики с нуля** в Adobe Illustrator.

</details>

</details>
