# 📱 React Native

This repository contains source code and exercises developed with **React Native** using **JavaScript**, created for the React Native course. It focuses on building mobile applications and learning core programming and UI concepts.

---

## 📘 Course Info

- **Level:** Undergraduate (Beginner)  
- **Language:** JavaScript  
- **Framework:** React Native  

---

## 📂 Contents

- 📦 React Native Project Structure  
- ⚛️ Components & Props  
- 🔁 State Management and Hooks (e.g., `useState`)  
- 🧭 Navigation with React Navigation  
- 🧩 List Rendering & Conditional Rendering  
- 📲 Handling Input & Forms  
- 🎨 Styling with `StyleSheet`  
- 🔄 API Fetching using `fetch()` or Axios
- 📝 Assignments  

---

## 🛠️ Tools & Technologies

- ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) **JavaScript** — Core programming language  
- ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) **React Native** — Cross-platform mobile app framework  
- ![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37) **Expo** — Development tooling used by this repository  
- ![VSCode](https://img.shields.io/badge/VSCode-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) **Visual Studio Code** — Code editor  

---

## Getting started

This repository uses **Expo SDK 48**. Use Node.js/npm and an Expo client or development build compatible with that historical SDK. The latest Expo Go client may not support it; upgrading Expo is a separate code change.

```bash
git clone https://github.com/NiraphatK/react-native-js-learning.git
cd react-native-js-learning
npm ci
npx expo start
```

Press `a` for a configured Android emulator, `i` for an iOS simulator on macOS, or use an SDK-compatible client on a device. The scripts in `package.json` also expose `npm run android`, `npm run ios`, and `npm run web`.

## Exercise index

- `App.js` is the active application entry point.
- `App1.js` and other root `App*.js` files are alternative exercises; they are not separate applications.
- `components/` contains reusable UI and component examples.
- `screens/` contains screen/navigation examples.
- `javascriptFile/` contains standalone JavaScript exercises.
- `pages/` contains additional navigation examples.

To try a different root exercise, back up your local changes and select its component from `App.js`. Some exercises require external APIs or a local backend; inspect their service URLs before running. This is a collection of course exercises, so not every alternative example is wired into the current app. No automated test script is defined; check the selected exercise in the emulator/device.
