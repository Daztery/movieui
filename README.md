# 🎬 Movie UI – SwiftUI

A minimalist and modular iOS movie app built with **SwiftUI**, focusing on clean UI composition and reusable components. This project serves as a UI prototype and foundation for integrating real data later on.

---

## 🚀 Features

- Built entirely with **SwiftUI**.
- Modular UI architecture with reusable components.
- Grid layout for movie posters.
- Movie detail screen with overview and backdrop.
- Genre tag styling.
- Light and dark mode support.
- Organized into `Views`, `Components`, and `Models`.

---

## 🧩 Tech Stack

- **Language:** Swift  
- **Framework:** SwiftUI  
- **Architecture:** Lightweight MVVM (UI only)  
- **Design:** Custom theming with dark mode support  
- **Previews:** Enabled for all components

---

## 📁 Project Structure

```
MovieUI/
├── Components/       # Reusable UI elements (MoviePoster, Tag, etc.)
├── Views/            # Screens (Home, Detail)
├── Models/           # Static models for mock data
└── Assets/           # Images and colors
```

---

## 🛠️ Getting Started

1. Clone the repository:  
   ```bash
   git clone https://github.com/Daztery/movieui.git
   ```
2. Open `MovieUI.xcodeproj` in **Xcode 14+**.
3. Build and run the app on the iOS Simulator or real device.

---

## 🎯 Purpose

This project focuses on:

- Practicing modern SwiftUI component structure.
- Rapid prototyping of a movie UI.
- Demonstrating clean SwiftUI code for portfolios.

It can be extended by integrating data from TMDB or any REST API.

---

## 🔄 Next Steps

- Add navigation with `NavigationStack`.
- Connect to a movie API (e.g., TMDB).
- Add ViewModels and networking.
- Introduce animations and transitions.
- UI testing with XCTest and ViewInspector.

