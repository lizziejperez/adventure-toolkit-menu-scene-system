# Adventure Toolkit: Menu & Scene System (Unity C#)

A reusable, adventure game–style menu and scene management system built in Unity using C#.

This project is part of the **Adventure Toolkit series**, focused on creating modular, beginner-friendly systems that can be easily integrated into Unity projects.

🚧 **Status: In Development (V1 Planning)**

## Overview

This system is designed to provide a clean and simple foundation for:

* Title screens
* Scene transitions
* Pause menus
* Basic game flow structure

The goal is to build a **plug-and-play menu system** that is easy to understand, extend, and reuse across projects.

## Planned Features (V1)

* Title screen with:

  * Play button
  * Quit button

* Scene management:

  * Load gameplay scene from menu
  * Return to title screen

* Pause system:

  * Toggle pause menu (Escape key)
  * Resume gameplay
  * Return to title

* UI system:

  * Built using Unity Canvas and Buttons
  * Simple, readable hierarchy

* Clean C# scripts:

  * Scene loading controller
  * Menu interaction handling
  * Pause state management

## Planned Demo

The project will include:

* **TitleScene**

  * Main menu UI
  * Navigation to gameplay

* **GameScene**

  * Basic environment
  * Pause menu UI

## Project Structure (Planned)

```
Assets/AdventureToolkit/MenuSceneSystem/
├── Scripts/
├── Prefabs/
├── Scenes/
└── UI/
```

## Design Goals

* Beginner-friendly and easy to follow
* Clean separation of UI and logic
* Minimal setup required
* Modular and reusable across projects
* Consistent with other Adventure Toolkit systems

## What This System Will Demonstrate

* Scene management using Unity’s SceneManager
* UI interaction with buttons and events
* Basic game flow architecture
* Pause handling using `Time.timeScale`
* Clean, maintainable Unity project structure

## Future Improvements

* Settings menu (audio, controls)
* Scene transition effects (fade in/out)
* Controller / new Input System support
* Save/load system integration

## Additional Notes

This system is intended to pair with other modules in the Adventure Toolkit series, including:

* Top-Down Movement System
* Future interaction and gameplay systems

### Need help customizing or extending this system?

I offer freelance help for Unity and game development:
[https://www.fiverr.com/lizziejperez](https://www.fiverr.com/lizziejperez)
