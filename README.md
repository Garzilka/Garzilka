<img width="1700" height="460" alt="github-header-banner (1)" src="https://github.com/user-attachments/assets/c64f28d0-4323-4006-b621-fe04f32be1f3" />

# Alexander Polyakov 👋
### Senior Unreal Engine / C++ Developer

---

<details>
<summary><b>🌍 Нажмите здесь для просмотра на РУССКОМ ЯЗЫКЕ</b></summary>

> Я опытный инженер-программист, специализирующийся на **Unreal Engine (C++ / Blueprints)**, архитектуре игровых систем и разработке инструментов автоматизации редактора. Имею успешный опыт доведения сложных систем от начального проектирования до production-ready реализации. Мой главный фокус — написание чистого, масштабируемого и оптимизированного по производительности кода без «blueprint-спагетти». Помимо игровой индустрии, активно развиваюсь в системном программировании на C++ (асинхронные сети, многопоточность, WebRTC).

### 🛠️ Технологический стек и экспертиза

#### Разработка на C++ и системное программирование (Core C++ & Systems)
* **Языковые стандарты:** Глубокое знание современного C++ (C++17, C++20), STL.
* **Сетевой стек и асинхронность:** Boost.Asio, корутины (`asio::awaitable`), многопоточные пулы задач (`ThreadPool`), асинхронное кэширование состояний, паттерны Сага/Актер (Saga/Actor).
* **Безопасность и криптография:** OpenSSL (`libcrypto`), сквозное шифрование (AES-256-GCM), обмены ключами ECDH (P-256), хеширование и деривация (SHA-256, PBKDF2).
* **Базы данных и сериализация:** SQL-запросы, проектирование неблокирующих очередей БД, парсинг данных через `nlohmann/json`.

#### Архитектура и инструменты Unreal Engine (Game Engine & Core Architecture)
* **Движки и фреймворки:** Unreal Engine (UE4 / UE5), архитектура сложных систем данных (Data-Driven Inventory Framework), разработка кастомных инструментов автоматизации редактора (Editor Utility Tools).
* **Искусственный интеллект (AI):** Behavior Trees, Environmental Query System (EQS), кастомные AI Tasks, Decorators и Services.
* **Анимация и визуализация:** Программирование сложных анимационных систем, спецэффекты и частицы (Niagara, Particle Systems).

#### Интерфейсы и работа со звуком (UI & Audio Engineering)
* **Интерфейсы (UI/UX):** Разработка UI-компонентов как в Unreal Engine (UMG, Slate, CommonUI, паттерн MVVM), так и для десктопных приложений (Qt, QML).
* **Аудиосистемы (Audio):** Интеграция низкоуровневых WebRTC-библиотек (LiveKit SDK), пакетизация и инжекция PCM-звука, системные аудиомикшеры (`QAudioSource`, `QAudioSink`, `QIODevice`), Sound Cues и Audio Mixers.

#### Инфраструктура и оптимизация (DevOps & Optimization)
* **Среда и ОС:** Windows, Linux, Visual Studio, VS Code.
* **Инструменты и DevOps:** Системы контроля версий (Git / GitHub), автоматизация сборки (Jenkins, Docker), CI/CD пайплайны.
* **Оптимизация:** Профилирование производительности CPU/GPU (Unreal Insights), поиск утечек памяти (Memory Profiling & Optimization, искоренение Heap Corruption).

---

### 💼 Коммерческий опыт

#### **Senior Unreal Engine / C++ Developer** | **Pioner** (MMO FPS)
*03/2021 – По настоящее время*
* **Архитектура ключевых систем:** Руководил полным циклом проектирования и внедрения сложных систем геймплея, искусственного интеллекта и инвентаря от стадии прототипа до production-ready состояния.
* **Оптимизация производительности:** Проводил глубокое профилирование CPU/GPU и низкоуровневую оптимизацию памяти с помощью Unreal Insights, что значительно повысило FPS и стабильность игры под высокой нагрузкой.
* **Техническое лидерство:** Обеспечивал техническое руководство командой разработки, внедрял стандарты чистого, масштабируемого кода и data-driven паттерны, полностью искореняя «blueprint-спагетти».
* **Разработка инструментов:** Разработал кастомные Editor Utility Tools для автоматизации рабочих процессов дизайнеров, что кратно ускорило пайплайн интеграции технического контента.

#### **Gameplay Programmer** | **Orange Cast** (Sci-Fi Action RPG)
*12/2020 – 03/2021*
* **Разработка геймплея:** Создавал основные игровые механики, компоненты перемещения персонажей и боевые системы в реальном времени с использованием модульного C++ и Blueprints.
* **Оптимизация фреймворка:** Переписал тяжелые унаследованные системы фреймворка на оптимизированный C++, снизив нагрузку на Tick и улучшив общую масштабируемость проекта.
* **Инструменты автоматизации:** Внедрил специализированные расширения Unreal Editor для упрощения управления техническими ассетами и контроля пайплайна визуальных эффектов.

#### **Core Systems Engineer** | **ExoTanks** (Action Shooter)
*06/2020 – 11/2020*
* **Сетевые механики:** Разрабатывал и рефакторил основные сетевые системы геймплея, обеспечивая высокую отзывчивость и точную синхронизацию в мультиплеерных матчах.
* **Оптимизация ресурсов:** Взаимодействовал с техническими художниками для оптимизации объема занимаемой памяти и рантайм-логики тяжелых визуальных ассетов и VFX-компонентов.
* **Надежная кодовая база:** Применял принципы ООП и SOLID для создания стабильных, легко расширяемых игровых модулей, что снизило количество системных багов в продакшене.

---

### 📁 Избранные Open-Source Проекты

#### 💬 [VOX](https://github.com/Garzilka/VOX) — Асинхронная экосистема мессенджера
* **Стек:** `Modern C++ (C++20)` `Boost.Asio` `OpenSSL` `LiveKit SDK (WebRTC)` `Qt 6` `QML`
* Спроектировал высокопроизводительный монорепозиторий, включающий асинхронный сервер чата, десктопный клиент и лаунчер.
* Реализовал неблокирующий сетевой движок на базе Boost.Asio C++20 корутин (`asio::awaitable`).
* Разработал потокобезопасный ленивый кэш состояний с механизмом *Request Coalescing* для защиты базы данных от эффекта лавины.
* Разработал архитектуру короткоживущих сервисов-саг (`UserLoginBroadcaster`) для асинхронных барьеров событий без риска взаимных блокировок (Deadlocks).
* Интегрировал сквозное шифрование: хэндшейки на ECDH (P-256) и шифрование трафика на AES-256-GCM.
* Создал многопоточный модуль маршалинга звука, связав низкоуровневый WebRTC LiveKit SDK с системными `QAudioSink`/`QMicCapture`.

#### 🎒 [One](https://github.com/Garzilka/One) — Data-Driven фреймворк инвентаря
* **Стек:** `Unreal Engine (UE4 / UE5)` `Core C++` `Data-Driven Design`
* Разработал модульную, масштабируемую архитектуру инвентаря для игровых систем. Фреймворк полностью опирается на data-driven паттерны, что исключает «blueprint-спагетти» и обеспечивает чистую инкапсуляцию данных.

#### 🖼️ [RandomizePhoto](https://github.com/Garzilka/Nomad) — Утилита аугментации датасетов
* **Стек:** `Modern C++` `Qt 6` `QML` `Image Processing`
* Создал десктопное приложение для аугментации графических датасетов. Реализовал алгоритмы «умного» смешивания фото с интуитивным QML-интерфейсом и оптимизированным параллельным конвейером обработки файлов.

#### 🗺️ [PlayerNavigationSystem](https://github.com/Garzilka/PlayerNavigationSystem) — Компонент продвинутой навигации
* **Стек:** `Unreal Engine (UE4 / UE5)` `Core C++` `Gameplay Programming`
* Создал продвинутый рантайм-компонент навигации для актеров, обеспечивающий модульный поиск путей и трекинг целей. Компонент полностью отвязан от других систем, оптимизирует обновление путей и снижает нагрузку на CPU на сложных уровнях.

#### 🎬 [AddTrackToSequences](https://github.com/Garzilka/AddTrackToSequences) — Автоматизация Unreal Editor
* **Стек:** `Unreal Engine (UE4 / UE5)` `Core C++` `Slate / Custom Editor Tools`
* Разработал расширение для автоматизации рутинных задач редактора, которое автоматически внедряет кастомные треки данных напрямую в Level Sequences, сокращая время работы технических художников и аниматоров.

---

### 💼 Контакты для связи:
* **Telegram:** [@nnomaddd](https://t.me)
* **Email:** Garzilka@mail.ru
</details>

<details open>
<summary><b>🌍 Click here to view in ENGLISH</b></summary>

> I am an experienced software engineer specializing in **Unreal Engine (C++ / Blueprints)**, gameplay systems architecture, and tool development. With a strong track record of bringing features from initial architectural design to production-ready implementation, I focus on writing clean, scalable, and performance-optimized code — without blueprint spaghetti. Beyond game development, I actively engineer low-level C++ systems involving asynchronous networking, multithreading, and WebRTC protocols.

### 🛠️ Tech Stack & Expertise

#### Core C++ & Systems Engineering
* **Language Standards:** Deep expertise in Modern C++ (C++17, C++20) and robust utilization of the STL.
* **Network & Asynchrony:** Boost.Asio, C++20 Coroutines (`asio::awaitable`), multithreaded task pools (`ThreadPool`), asynchronous state caching, and Saga/Actor patterns.
* **Security & Cryptography:** OpenSSL (`libcrypto`), end-to-end encryption (AES-256-GCM), ECDH (Key Exchange via P-256 curve), secure hashing, and key derivation (SHA-256, PBKDF2).
* **Databases & Serialization:** SQL query optimization, non-blocking DB task queues, and zero-copy data parsing via `nlohmann/json`.

#### Game Engine & Core UE Architecture
* **Engines & Frameworks:** Unreal Engine (UE4 / UE5), architecture of complex data-driven frameworks (e.g., Modular Inventory Systems), and development of custom Editor Utility Tools.
* **Artificial Intelligence (AI):** Behavior Trees, Environment Query System (EQS), custom AI Tasks, Decorators, and Services.
* **Animation & VFX:** Advanced animation programming, runtime systems, and real-time visual effects (Niagara, Cascade Particle Systems).

#### UI & Audio Engineering
* **Interfaces (UI/UX):** UI component architecture in both Unreal Engine (UMG, Slate, CommonUI, MVVM pattern) and desktop application frameworks (Qt, QML).
* **Audio Systems:** Integration of low-level WebRTC libraries (LiveKit SDK), PCM audio packetization/injection, hardware-level mixers (`QAudioSource`, `QAudioSink`, `QIODevice`), Sound Cues, and Audio Mixers.

#### DevOps, Environment & Optimization
* **Environments & OS:** Windows, Linux, Visual Studio, VS Code.
* **Tools & DevOps:** Version control systems (Git / GitHub), build automation (Jenkins, Docker), and CI/CD pipelines.
* **Performance Tuning:** CPU/GPU profiling (Unreal Insights), memory leak detection, and resolving complex low-level memory issues (Memory Profiling, mitigating Heap Corruption).


### 💼 Commercial Experience

#### **Senior Unreal Engine / C++ Developer** | **Pioner** (MMO FPS)
*03/2021 – Present*
* **Architected Core Systems:** Spearheaded the full-cycle architecture and implementation of complex gameplay, AI, and inventory systems from scratch to production-ready state.
* **Performance Optimization:** Driven deep CPU/GPU profiling and low-level memory optimizations using Unreal Insights, significantly increasing frame rates and stability under high stress.
* **Technical Leadership:** Provided technical guidance across the development team, enforcing clean, scalable code standards and data-driven patterns while eliminating blueprint spaghetti.
* **Tool Development:** Engineered custom Editor Utility Tools to automate designer workflows, drastically accelerating technical content integration pipelines.

#### **Gameplay Programmer** | **Orange Cast** (Sci-Fi Action RPG)
*12/2020 – 03/2021*
* **Gameplay Engineering:** Developed core mechanics, character movement components, and real-time combat systems using modular C++ and Blueprints.
* **Framework Optimization:** Rewrote heavy legacy framework systems in optimized C++, reducing tick overhead and improving overall project scalability.
* **Custom Tools:** Implemented specialized Unreal Editor extensions to streamline technical asset management and visual effects pipeline control.

#### **Core Systems Engineer** | **ExoTanks** (Action Shooter)
*06/2020 – 11/2020*
* **Networked Mechanics:** Engineered and refactored core networked-ready gameplay systems ensuring high responsiveness and precise synchronization in multiplayer matches.
* **Asset Optimization:** Collaborated with technical artists to optimize memory footprint and runtime logic of heavy visual assets and VFX components.
* **Robust Codebase:** Applied OOP and SOLID principles to build robust, easily expandable game modules, reducing systemic bugs in production.

### 📁 Featured Open-Source Projects

#### 💬 [VOX](https://github.com/Garzilka/VOX) — Asynchronous Messenger Ecosystem
* **Tech Stack:** `Modern C++ (C++20)` `Boost.Asio` `OpenSSL` `LiveKit SDK (WebRTC)` `Qt 6` `QML`
* **Core Contribution:** Engineered a high-performance monorepository featuring an asynchronous server, desktop client, and launcher.
* **Key Achievements:** 
  * Implemented an lock-free network engine using Boost.Asio C++20 Coroutines (`asio::awaitable`).
  * Designed a thread-safe, lazy-loaded user state cache with *Request Coalescing* to mitigate Thundering Herd issues.
  * Architected a short-lived *Saga Pattern* (`UserLoginBroadcaster`) for asynchronous event barriers without multi-threaded deadlocks.
  * Established an E2E encrypted pipeline using ECDH (P-256) for handshakes and AES-256-GCM for packet encryption.
  * Implemented a multi-threaded audio marshalling system integrating the low-level WebRTC LiveKit SDK with `QAudioSink`/`QMicCapture`.

#### 🎒 [One](https://github.com/Garzilka/One) — Data-Driven Inventory Framework
* **Tech Stack:** `Unreal Engine (UE4 / UE5)` `Core C++` `Data-Driven Design`
* **Core Contribution:** Developed a robust, highly modular, and production-ready inventory architecture for gameplay systems.
* **Key Achievements:** Highly optimized framework relying on data-driven design patterns to completely eliminate Blueprint spaghetti, ensuring seamless runtime scaling and clean data encapsulation.

#### 🖼️ [RandomizePhoto](https://github.com/Garzilka/Nomad) — Smart Dataset Augmentation Utility
* **Tech Stack:** `Modern C++` `Qt 6` `QML` `Image Processing`
* **Core Contribution:** Built a high-performance desktop application for image dataset augmentation.
* **Key Achievements:** Implemented a smart photo-mixing utility with an intuitive QML interface, optimizing parallel file processing pipelines for deep learning dataset preparation.

#### 🗺️ [PlayerNavigationSystem](https://github.com/Garzilka/PlayerNavigationSystem) — Advanced Component Pathfinding
* **Tech Stack:** `Unreal Engine (UE4 / UE5)` `Core C++` `Gameplay Programming`
* **Core Contribution:** Designed an advanced gameplay navigation component providing modular tracking and pathfinding.
* **Key Achievements:** Built a highly decoupled runtime actor component that seamlessly extends engine navigation capabilities, optimizing path updates and reducing overhead in complex levels.

#### 🎬 [AddTrackToSequences](https://github.com/Garzilka/AddTrackToSequences) — Unreal Editor Automation Utility
* **Tech Stack:** `Unreal Engine (UE4 / UE5)` `Core C++` `Slate / Custom Editor Tools`
* **Core Contribution:** Created an workflow-automation editor tool to streamline pipeline tracking data.
* **Key Achievements:** Spearheaded an editor extension that automates adding custom tracking data directly into Level Sequences, significantly cutting down repetitive manual labor for technical artists and animators.


### 💼 Connect with me

* **Email:** [Garzilka@mail.ru]
* **Telegram:** [nnomaddd]

</details>
