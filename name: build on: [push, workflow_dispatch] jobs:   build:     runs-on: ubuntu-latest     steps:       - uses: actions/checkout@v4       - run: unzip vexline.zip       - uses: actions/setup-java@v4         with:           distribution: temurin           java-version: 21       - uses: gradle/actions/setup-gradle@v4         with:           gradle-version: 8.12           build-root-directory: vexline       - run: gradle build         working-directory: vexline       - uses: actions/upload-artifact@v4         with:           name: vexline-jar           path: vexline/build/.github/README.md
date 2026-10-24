# Vexline (Fabric, Minecraft 1.21.11)

Build:  gradle build   (needs JDK 21)  ->  build/libs/vexline-1.0.0.jar
Put the jar and Fabric API (0.141.x for 1.21.11) in your mods folder with Fabric Loader.

Right Shift opens the GUI. Left-click a module to toggle, right-click for settings.
Config: .minecraft/config/vexline.json

Modules: Fullbright, Zoom, FPS Boost, Toggle Sprint, FPS / Coordinates / Module List HUD, GUI themes.
Add your own: extend Module, register it in ModuleManager.init().
