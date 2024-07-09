<div align='center'>

<h4> <a href=https://paintedfriend.github.io/Simple-Theme-Manager/>View Demo</a> <span> · </span> <a href="https://github.com/Paintedfriend/Simple-Theme-Manager/blob/master/README.md"> Documentation </a> <span> · </span> <a href="https://github.com/Paintedfriend/Simple-Theme-Manager/issues"> Report Bug </a> <span> · </span> <a href="https://github.com/Paintedfriend/Simple-Theme-Manager/issues"> Request Feature </a> </h4>


</div>

### :dart: Features
- Light weight
- System theme support
- Toggles document attribute
- Freedom in css
- Saving to localStorage
- Easy to use
- Any framework

## :toolbox: Getting Started

### :bangbang: Prerequisites

- Install Node JS in your computer <a href="https://nodejs.org/en/">Here</a>

### :gear: Installation
In your terminal
```bash
npm i simple-theme-manager
```
In your main.js
```bash
import theme_manager from "simple-theme-manager"; // Import a module
window.theme_manager = theme_manager; // Connect the module to global access
```
On created app
```bash
theme_manager.init(); // Let's launch the module. If the theme is saved, it is applied. Otherwise, run in auto mode
```

### ✍️ Using
Apply theme <br>
<i>In auto mode, you can change the theme on your device, and it will also change in the application.</i>
```bash
theme_manager.apply("auto" || "light" || "dark"); // One of three modes is applied - auto, light or dark
```
Get current theme mode
```bash
theme_manager.getMode(); // Returns auto | light | dark
```
Get current theme
```bash
theme_manager.getTheme(); // Returns light | dark (even in auto mode)
```
Reset settings
```bash
theme_manager.reset(); // Deletes data from localStorage and applies auto mode
```
