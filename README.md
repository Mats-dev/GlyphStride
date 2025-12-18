# GlyphStride

An offline-first, privacy-focused fitness app that puts you in control of your data.

## Core Philosophy

GlyphStride is designed for athletes who value privacy, simplicity, and ownership of their data. Unlike mainstream fitness platforms, GlyphStride is:

*   **Offline-First**: All your activity data is stored locally on your device in an SQLite database. No servers, no cloud, no accounts needed.
*   **Privacy-Focused**: Since your data never leaves your device (unless you choose to export it), your privacy is guaranteed.
*   **Minimalist & Usable**: A clean, intuitive interface that focuses on the essential metrics, getting out of your way so you can focus on your activity.
*   **Free & Open**: The app is free to use, with future development supported by optional donations.

## Current Features (Test Version)

*   **Multi-Sport Tracking**: Support for six activities: running, walking, cycling, HIIT, snowboarding, and dancing.
*   **GPS & Sensor Data**: Tracks distance, time, pace, and elevation gain.
*   **Activity Naming & Notes**: Personalize your workouts with custom names and detailed notes (including database migrations for existing data).
*   **Auto-Pause Detection**: Smart tracking that automatically pauses when you stop moving and resumes when you accelerate, using a robust internal timer for maximum reliability.
*   **Advanced Fitness Metrics**:
    *   **Training Load (TRIMP)**: Scientific workload calculation based on heart rate intensity.
    *   **VO2 Max Estimation**: Track your cardiovascular progress over time.
    *   **Personalized Calculations**: Configure birth year, resting HR, and max HR for pinpoint accuracy.
*   **Activity Analysis Charts**: Visualize your performance with detailed interactive charts for Pace, Elevation, and Heart Rate (with dynamic scaling and zoom).
*   **Enhanced Reliability**: Built-in WakeLock support ensures tracking never stops in the background, even during long sessions.
*   **Smart Heart Rate Integration**:
    *   **Direct BLE Connection**: Connects to heart rate monitors directly via Bluetooth.
    *   **Reactive Logic**: Recognizes connections mid-activity.
    *   **Activity Prompts**: Reminds you to connect your sensor before starting a workout.
    *   **Detailed Stats**: View live heart rate during activity and Average HR in your history.
*   **Activity History**: A detailed history list showing stats, route maps, and analysis charts for every session.
*   **Support**: A Ko-fi button for users who wish to support the project's development.
*   **Connectivity & Export**:
    *   **Offline Maps**: Download maps for use without an internet connection.
*   **Advanced Data Analysis**:
    *   **Unit Toggle**: Switch between kilometers and miles.
*   **Advanced Personalization & Analytics**:
    *   **Zen Mode**: A minimalist tracking UI with a real-time pulsating heart-rate glyph to focus on the somatic experience.
    *   **Procedural Route Glyphs**: Unique geometric art generated from every activity's path, displayed in history and details.
    *   **Local Coach Insights AI**: Privacy-first, on-device analysis of your performance trends, consistency, and fatigue (user-togglable in settings).
 *   **Advanced Customization**:
 *   **Appearance Settings**: Toggle Coach Insights on/off to declutter your home screen.
     *   **Responsive Dashboard**: Activity tracking controls that adapt to any screen size for perfect visibility.
 *   **Social & Community**:
     *   **GitHub Release notes**: Detailed changelogs provided for every major update.

## Known Issues

*   **Health Connect (Google Fit) Integration**: On some devices (particularly Android 16 Preview or devices with outdated system components without Play Store access), Health Connect permissions may fail with an "App needs update" error. This does **not** affect the direct Bluetooth Heart Rate functionality.

## Roadmap Status

GlyphStride is under active development. Recently completed:
- [x] **Activity Naming & Notes**
- [x] **Smart Auto-Pause Detection**
- [x] **Training Load & VO2 Max Estimation**
- [x] **Advanced Personalization (Zen Mode & Glyphs)**
- [x] **Local AI Insights (Beta)**

Our vision for GlyphStride is ambitious. Next priorities include:
*   **Advanced Wearable Integration**: Expanded support via Health Connect/HealthKit when available.
*   **Motivational Tools**:
    *   **Streaks**: Keep track of weekly goals (e.g., "Run 3 times this week").
    *   **Glyphs & Notifications**: Earn unique "glyphs" for achievements to stay motivated.
*   **Accessibility**: Voice and text-based assistance during activities.
*   **Connectivity & Export**:
    *   **Data Export**: Manually export your activities to Google Fit, Apple Health, and Strava.
