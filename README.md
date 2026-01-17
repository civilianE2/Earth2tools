# E2V1 Seasonal Visualizer (Earth2tools) 🌍⏳

An interactive, high-precision global map visualizer for the **E2V1 time system**. This engine simulates a world where time is accelerated by a factor of four ($4 \times$), blending orbital mechanics with the unique time dilation concepts of the Earthie project.

## 🔗 Live Demo
**[Launch the Interactive Map](https://civiliane2.github.io/Earth2tools/)**

---

## 💡 About the Project
This application is a web-based implementation of the **E2V1 (Earth 2.0 Version 1)** time system. In this model, the Earth completes four "internal" day-night cycles for every single rotation in real-time. 

The visualizer calculates the **Solar Terminator** (the line between day and night) using spherical trigonometry, factoring in the Earth's axial tilt (declination) to produce accurate seasonal curves instead of simple vertical bars.

### Credits & Inspiration
The core logic and temporal acceleration are inspired by **Eugene Boondock** and the **Earthie** project.
* **Official Website:** [https://www.earthie.world/](https://www.earthie.world/)
* Special thanks to Kraganov and the Earth2 Portal project:
* **Official Website:** [https://earth2portal.net/](https://earth2portal.net/)/)
* 
* 

---

## ✨ Key Features
* **4x Time Acceleration:** Watch the day-night cycle sweep across the globe at 400% speed.
* **Seasonal Curvature:** Real-time calculation of the "hourglass" shadow shape based on the current day of the year.
* **15° Time Zone Locking:** The clock is synchronized to 24 distinct longitudinal zones to ensure local time integrity across the globe.
* **Interactive Solar HUD:**
    * Click anywhere to see the **Live E2V1 Clock** with ticking seconds.
    * Real-world **Sunrise & Sunset** (UTC) data for any coordinate.
    * Automatic detection of **Polar Night** and **Midnight Sun**.

---

## 🛠 Technical Details
The project is built with:
* **Leaflet.js**: For mapping and coordinate systems.
* **CartoDB Dark Matter**: High-contrast tiles for clear shadow visibility.
* **Spherical Trigonometry**: Solar altitude calculations using:
  $$\sin(h) = \sin(\phi) \sin(\delta) + \cos(\phi) \cos(\delta) \cos(H)$$



---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/civilianE2/Earth2tools.git](https://github.com/civilianE2/Earth2tools.git)
