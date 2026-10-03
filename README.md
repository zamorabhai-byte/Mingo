# Mingo

> A WhatsApp-like messaging app with a stripped-down, distraction-free interface.
> Text and images only. No noise. Just conversations.

![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-in%20development-orange)

---

## 📸 Preview

| Chat List | Conversation | Composer |
|-----------|--------------|----------|
| ![Chats](./screenshots/chats.png) | ![Chat](./screenshots/chat.png) | ![Composer](./screenshots/composer.png) |

> _Screenshots coming soon._

---

## ✨ Features

- 💬 **Real-time 1:1 messaging** — powered by Firestore listeners
- 🖼️ **Image sharing** — send photos with a single tap
- 🔔 **Push notifications** — via Firebase Cloud Messaging
- 📴 **Offline support** — messages queue and sync automatically
- 🎨 **Minimal UI** — monochrome palette, no badges, no clutter
- 🔐 **Secure auth** — email/phone sign-in with Firebase Auth

---

## 🚫 What Mingo Intentionally Leaves Out

This is a **minimal** messenger. The following are deliberately excluded:

- ❌ Status / Stories
- ❌ Voice & video calls
- ❌ Read receipts (blue ticks)
- ❌ Typing indicators
- ❌ Stickers, GIFs, reactions
- ❌ Group chats (coming later)

Less is more.

---

## 🛠️ Built With

- **[React Native](https://reactnative.dev/)** — cross-platform mobile framework
- **[Firebase](https://firebase.google.com/)**
  - Auth — user sign-in
  - Firestore — real-time messages
  - Storage — image hosting
  - Cloud Messaging — push notifications
- **[React Navigation](https://reactnavigation.org/)** — screen routing
- **[Inter](https://rsms.me/inter/)** — typography

---

## 🚀 Getting Started

### Prerequisites

- Node.js ≥ 18
- npm or yarn
- React Native CLI or Expo
- A Firebase project

### Installation

```bash
# Clone the repository
git clone https://github.com/zamorabhai-byte/Mingo.git
cd Mingo

# Install dependencies
npm install

# iOS only
cd ios && pod install && cd ..

# Start the dev server
npm start
