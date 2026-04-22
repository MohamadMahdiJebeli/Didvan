<img width="150" alt="Didvan" src="https://github.com/user-attachments/assets/947304b8-aea5-4888-94a4-3870bd571709" />


**👁️ [Didvan - Strategic Monitoring System](https://didvan.com)** : Didvan is a Flutter-based intelligent strategic monitoring system and a comprehensive suite of interactive future-study tools designed to serve as the intellectual arm for businesses navigating the future.

> **Note:** This repository is for demonstration and portfolio purposes only. The source code is proprietary and closed-source.
>
> 🏢 **Deployment:** This application is currently in active use by Mobarakeh Steel Company (Foolad Mobarakeh).

---

## 🚀 Features

- **Strategic monitoring** and horizon scanning for temporal geography.
- **Interactive futures research** and scenario planning tools.
- **Decision support system** providing actionable insights for organizations.
- **Anticipatory systems** to navigate uncertainties and unprecedented future events.

---

## 📸 Images

<img src="https://github.com/user-attachments/assets/481b1190-ddee-46bd-9bfd-5d6a89f35a4a" alt="Didvan 1" width="200" />
<img src="https://github.com/user-attachments/assets/8f7ba79e-7dcb-4b87-a119-88965745f63a" alt="Didvan 2" width="200" />
<img src="https://github.com/user-attachments/assets/5e68b701-cab4-4623-9c5a-40a25b4d9e31" alt="Didvan 3" width="200" />
<img src="https://github.com/user-attachments/assets/bbe55309-7c4c-46fc-ae0f-2035c5e88fca" alt="Didvan 4" width="200" />


---

## 🛠️ Tech Stack & Libraries

This project relies on a robust and highly modular architecture using modern Flutter development practices. Based on the source code, the following core technologies and libraries are utilized:

* **State Management:** Provider pattern (via `lib/providers/`) & Feature-specific State Handlers (`*_state.dart`)
* **Networking & API:** Custom Network/Request Layer (`lib/services/network/`)
* **Backend & Notifications:** Firebase Cloud Messaging (FCM) & Firebase Services
* **Local Storage:** Custom Storage Layer (`lib/services/storage/`)
* **Routing:** Custom Route Generator (`lib/routes/route_generator.dart`)
* **Media & Players:** Custom Video Player and Audio Visualizers (`lib/views/widgets/video/`, `lib/views/widgets/audio/`)
* **Advanced UI & Graphics:** Custom Fragment Shaders (`liquid_glass_lens.frag`), Glassmorphism, and 3D Carousels
* **Web Integration:** JS Interop (`lib/services/js/`) for advanced Web Renderer configurations
* **Other Utilities:** Markdown Rendering, PDF Viewer, App Home Widgets (`home_widget_repository`), and RAG AI Services.

---

## 📂 Architecture Overview (Folder Structure)

The application follows a clean, highly modular **Feature-Based Architecture** ensuring scalability and maintainability. The core logic is separated from the UI presentation layer:

```text
lib/
├── assets/             # Local assets (Fonts, Icons, SVGs, Lottie/GIF animations, JS files)
├── config/             # App-wide configurations (ThemeData, Design Configs)
├── constants/          # Constant variables (App icons, Asset paths)
├── models/             # Data models, DTOs, and Entities (AI, Statistics, Content, etc.)
├── providers/          # Global state management and core business logic providers
├── routes/             # Custom route generation and app navigation map
├── services/           # External and internal service integrations
│   ├── ai/             # AI APIs and RAG (Retrieval-Augmented Generation) services
│   ├── media/          # Audio, Voice, and Video processing
│   ├── network/        # HTTP Request helpers and API calling logic
│   ├── notification/   # Firebase and local push notification services
│   ├── storage/        # Local persistent storage handling
│   └── ...             # Other services (WebView, Home Widget, Story, etc.)
├── shaders/            # Custom GLSL fragment shaders (e.g., liquid glass)
├── utils/              # Helper functions, formatters, and Dart extensions
└── views/              # Presentation layer (UI) organized by feature
    ├── ai/             # AI Assistant, Chat, and Tools screens
    ├── authentication/ # Login, Password reset, and OTP verification
    ├── home/           # Main dashboard, Media, Podcasts, Radar, and Statistics
    ├── profile/        # User settings, Direct messages, and Preferences
    ├── widgets/        # Highly reusable, atomic UI components (Didvan UI Kit)
    └── ...             # Other modular screens (Onboarding, PDF Viewer, Splash)
```
## 🌐[Didvan Official Website](https://https://didvan.com/):
For more information and to experience the platform, check out our website:

https://didvan.com
