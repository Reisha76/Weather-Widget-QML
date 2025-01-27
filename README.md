# QML Weather Widget

A minimal **Qt Quick** application showcasing real-time weather transitions for three cities—Moscow, Ankara, and Madrid. This project emphasizes dynamic color, gradient, and animation changes, illustrating how QML can create visually appealing user interfaces.

---

## Features

- **Animated Transitions**  
  - Smooth color gradients and property animations that change based on selected city (e.g., frosty, hot, clear).
- **Clickable Sun Element**  
  - Click the sun to cycle through the weather states for each city.
- **Dynamic Date & Time**  
  - Automatically updates the current date/time using Qt’s timer utilities.
- **Clean Architecture**  
  - Organized code split into QML for UI (`Main.qml`) and C++ for application setup (`main.cpp`).

---

## Files in This Repository

1. **`main.cpp`**  
   - C++ entry point for the application.
2. **`Main.qml`**  
   - Primary QML UI code showcasing animations and weather-state logic.
3. **`CMakeLists.txt`**  
   - CMake configuration file to build the project.

> Note: The `build/` folder and other environment-specific files (`*.user`) are excluded.

---

## Getting Started

1. **Clone or Download**  
   ```bash
   git clone https://github.com/<YourUsername>/WeatherWidget.git
   cd WeatherWidget
2. Build

**Create a Build Folder**  
# Build

### Create a Build Folder
```bash
mkdir build && cd build
```
**Run CMake**  
```bash
cmake ..
```
**Compile**  
```bash
cmake --build .
```
**Run**  
After a successful build, run the resulting binary from the build directory (e.g., `./WeatherWidget` or `WeatherWidget.exe` on Windows).

**Dependencies:**  
This project requires a working installation of **Qt** (Qt 5 or higher) with QML support and **CMake** (version 3.5+ recommended).

---

# Usage
1. **Launch the application.**  
2. **Observe** the date/time display updating in real-time.  
3. **Click the sun** to switch through **Moscow**, **Ankara**, and **Madrid** weather animations.

---

# Future Improvements
- **Real Weather API:** Replace hardcoded temperatures with live data from an online API.  
- **Additional Cities:** Add more locations or weather states (e.g., rain, snow).  
- **Refined Animations:** Explore complex transitions or new visual elements for a richer user experience.

---

# License
This project is under the **MIT License** (or your chosen license), allowing free use, modification, and distribution with required attribution.

---

# References & Resources
- **Qt QML Documentation** – Official resource for QML and Qt Quick.  
- **Qt Quick Animations** – Reference for property animations in QML.  
- **CMake Documentation** – Official documentation for CMake build system.

---

Enjoy exploring the **QML Weather Widget**, and feel free to contribute enhancements or report any issues!
