# 🌿 NatureLog – AI-Powered Wildlife Journal (Android App)

NatureLog is an Android application designed to help users identify, record, and reflect on plant and animal encounters. Whether you're hiking, birdwatching, or simply curious about the natural world, NatureLog provides a smart way to capture, organize, and explore your observations.

---

## 📱 Features

### 🔍 Scan & Identify
- Take a photo of a plant or animal.
- Automatically identifies species using AI and iNaturalist data.
- Displays scientific name and a brief Wikipedia summary.

### 📓 Journal System
- Saves entries with:
  - Image
  - Species name & scientific name
  - Timestamp
  - Wikipedia summary
  - Geolocation (latitude & longitude)
- View, edit, and delete entries easily.

### 🗺️ Map Integration
- Tap to open observation location in Google Maps (or browser fallback).
- Entries include GPS coordinates and formatted display.

### 🧹 Smart Storage Management
- Automatically deletes unused or discarded photos.
- Cleans up data on journal deletion to save device space.

### 🔐 API Token Setup
- Guided instructions for retrieving an iNaturalist API token.
- Clipboard paste + save flow with persistent local storage.
- Handles and remembers invalid/expired tokens.

### 🎨 User Interface
- Clean, minimalist layout with a natural-themed background.
- Responsive buttons and intuitive navigation.
- Contextual menu (planned/optional): multi-select and batch delete journal entries.

---

## 🛠️ Tech Stack

- **Language:** Java
- **Platform:** Android SDK
- **Architecture:** MVVM-ish with Room DB for local storage
- **UI:** XML-based layouts, Material Buttons
- **External APIs:** iNaturalist, Wikipedia
- **Tools:** OpenCV (for image processing), Google Maps Intent

---
## 🚀 Getting Started

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/naturelog.git
   ```
2. **Open in Android Studio.**
3. **Run on device or emulator.**
---
## 🔐 Token Setup Instructions
- Log into iNaturalist.
- Visit API Token Page.
- Copy the token and paste it into the app's token setup screen.
- The token is stored securely in SharedPreferences.
---



