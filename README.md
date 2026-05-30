# Care Cubs Interactive Experience

Welcome to the **Care Cubs** platform repository! This project hosts a suite of immersive web-based interactive experiences, games, and web apps. The platform aims to provide fun, educational, and engaging content.

## 📁 Repository Structure and File Descriptions

Here are the key coding files included in this repository and their current roles:

- **`index.html`** *(formerly `landing_page.html`)*
  - **Description:** The main landing page for Care Cubs. Contains the hero section and introduction to the platform.
  - **Role:** Sets the theme, acts as the entry point, and redirects users to the experience hub.

- **`games_list.html`**
  - **Description:** The interactive hub or directory for the platform.
  - **Role:** Shows all the available experiences as interactive cards. You can launch any experience from here (e.g., AirPaint, Tetris, Mirror Bot).

- **`airpaint.html`** 
  - **Description:** Air Canvas Pro (AirPaint). An interactive, touchless drawing application.
  - **Role:** Uses advanced webcam hand-tracking, Kalman Filter stabilization, and pinch gestures to allow users to paint in the air.

- **`tetris.html`**
  - **Description:** Care Cubs Tetris.
  - **Role:** A modern, stylized version of the classic arcade game, playable directly in the browser. 

- **`newgame.html`** 
  - **Description:** Mirror Bot - Elite Customizer.
  - **Role:** An interactive mini-game/customization tool where users can engage with a virtual robot.

*(Note: Extraneous scripts and images that had no role acting in the live platform have been removed to keep the repository clean).*

---

## 🚀 Progress Made So Far

*   **Core Navigation & UI:** The landing page (`index.html`) and the experience directory (`games_list.html`) are fully functional with a futuristic and responsive design.
*   **AirPaint (AR Web App):** 
    * Real-time webcam hand-tracking integrated via MediaPipe.
    * Smooth tracking with mathematical stabilization (Kalman filter) to prevent jitter.
    * Fully working drawing actions via finger pinching, with a customizable color palette and hardware-accelerated drawing context.
*   **Tetris & Mirror Bot:** Both standalone web environments are built out with their own respective art directions and functionalities, accessible via the main directory.
*   **Environment Stability:** Syntax errors, minor bugs, and duplicate variable definitions have been ironed out in all main pages.

---

## 🚧 Features Yet to Arrive (Roadmap)

While the platform is live and operational, there are still exciting features on the horizon:

1.  **Mobile Support Enhancements:** Optimizing the games (like Tetris and Mirror Bot) for touchscreen interactions so they work smoothly on mobile browsers.
2.  **User Profiles & High Scores:** Implementing local storage to save user high scores for Tetris and custom configurations for Mirror Bot.
3.  **Expanded AirPaint Features:** 
    * Exporting and downloading your canvas as an image.
    * Adding diverse brush types, stamps, and an eraser tool.
4.  **Audio Ambience:** Bringing background music, interaction sound effects, and volume controls into the `games_list.html` and `index.html`.
5.  **New Mini-Games:** Adding more interactive web games to the Care Cubs lineup!

---

## 🛠 How to Use (Live Site)

Since the main landing page is correctly named `index.html`, GitHub Pages will see this repository's root as a complete website. 

1. **Visit the URL:** Once hosted on GitHub Pages, you will automatically land on the Home page.
2. **Access Experiences:** Click the main call-to-action to enter the `games_list.html`.
3. **Play/Draw:** Select any game card. If using Airpaint, give the browser camera permissions and hold your hand up to the webcam. Pinch your thumb and index finger to start drawing.
