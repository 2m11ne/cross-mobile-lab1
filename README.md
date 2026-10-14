# Cross-Platform Mobile Lab 1 — Part 1

Implementation of **Part 1** of the Cross-Platform Mobile App Development tutorial (React Native and Flutter side by side).

## 📦 Contents

This repo contains the same Notes app built twice:

| Folder | Framework | Tech |
|--------|-----------|------|
| `notes-app/` | React Native | Expo SDK 57, Expo Router, TypeScript |
| `notes_app/` | Flutter | Flutter 3.47, Dart 3.13, go_router 18 |

## ✨ Features (Part 1)

- 🏠 Home screen with navigation
- 📝 Notes list (Welcome + Shopping by default)
- ➕ Create a new note via modal/dialog
- ✏️ Edit an existing note
- 🗑️ Delete a note
- 🔄 Empty state ("No notes yet.")

> Notes are stored in memory only in Part 1 (no database yet).

## 🚀 Run the apps

### React Native (Expo)
```bash
cd notes-app
npm install
npx expo start
# Press "a" for Android
