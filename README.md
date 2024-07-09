<div align='center'>

<h4> <a href=https://paintedfriend.github.io/Simple-Theme-Manager/>View Demo</a> <span> · </span> <a href="https://github.com/Paintedfriend/Simple-Theme-Manager/blob/master/README.md"> Documentation </a> <span> · </span> <a href="https://github.com/Paintedfriend/Simple-Theme-Manager/issues"> Report Bug </a> <span> · </span> <a href="https://github.com/Paintedfriend/Simple-Theme-Manager/issues"> Request Feature </a> </h4>


</div>

# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)


## :star2: About the Project

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

- Install Node JS in your computer<a href="https://nodejs.org/en/"> Here</a>


### :gear: Installation

In your terminal
```bash
npm i simple-theme-manager
```
In your main.js
```bash
import theme_manager from "simple-theme-manager"; window.theme_manager = theme_manager;
```
On created app
```bash
theme_manager.init();
```
Apply theme
```bash
theme_manager.apply("auto" | "light" | "dark");
```
Get current theme mode
```bash
theme_manager.getMode()
```
Get current theme
```bash
theme_manager.getTheme()
```
Reset settings
```bash
theme_manager.reset()
```
