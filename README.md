# Valkaw

![Banner](https://i.ibb.co/QFt5LMHm/standard.gif)

> **Maximize your Minecraft performance with the ultimate optimization modpack!**

[![GitHub](https://img.shields.io/badge/Page-Github?style=flat&logo=GitHub&logoColor=white&logoSize=96&label=GitHub&labelColor=grey&color=009C0F&link=https%3A%2F%2Fgithub.com%2FConfiac1563%2FValkaw-Client)](https://github.com/Confiac1563/valkaw)
[![Modrinth](https://img.shields.io/badge/Page-modrinth?style=flat&logo=modrinth&logoColor=dark_green&logoSize=96&label=Modrinth&labelColor=grey&color=009C0F&link=https%3A%2F%2Fmodrinth.com%2Fmodpack%2Fvalkaw-client)](https://modrinth.com/modpack/valkaw)
[![WynnCraft](https://img.shields.io/badge/Modpack-wynn?style=flat&logo=modrinth&logoColor=dark_green&logoSize=16&label=WynnCraft&labelColor=grey&color=009C0F)](https://modrinth.com/modpack/wynnperf)

---

## What is Valkaw?

Valkaw is a high-performance modpack forked from **Sliwed Optimize**. We're constantly updating it to squeeze out better frame rates and fix issues, ensuring the project keeps moving forward smoothly.

![Valkaw Screenshot](https://github.com/user-attachments/assets/86987bb4-cc30-4fe3-b3b3-221e50c26f87)

---

## Core Features

We've focused on three main upgrades to make your game lighter and faster:

**Fastest Performance HUD**  
Powered by Hudder, FlexHUD, and CustomHUD, this displays the stats you actually need without hogging your resources.

**Smart Resource Manager**  
We use FerriteCore and "Put A Plug In it!" to keep your RAM usage in check. Plus, **EntityCulling** uses your CPU to calculate what you can see in real-time, skipping the rendering of anything hidden behind blocks.

**OptiFine Features**  
Missing Zoom or Dynamic Lights? No problem. With **WI Zoom** and **LambDynamicLights**, you get those familiar features back, now running on the faster Sodium or VulkanMod engines.

---

## Main Optimization Mods

Valkaw offers two different rendering paths depending on your hardware. Choose the version that best suits your system!

### 1. Sodium Edition (Standard)

The standard, highly compatible optimization route using the OpenGL API. Perfect for most users and supports shaders.

<details>
<summary><b>Click to expand the Sodium modlist</b></summary>

*   **Sodium:** The absolute best modern rendering engine for Minecraft.
*   **Lithium:** General-purpose optimization for game physics, AI, and block ticking.
*   **FerriteCore:** Significantly reduces the memory footprint of the game.
*   **EntityCulling:** Skips rendering hidden entities/tiles to boost performance.
*   **Iris Shaders:** Seamless, high-performance shader support (the best OptiFine alternative).

</details>

### 2. VulkanMod Edition (Maximum Raw Performance)

A wildly powerful route that completely replaces OpenGL with the Vulkan API. Incredible for squeezing out the absolute maximum raw FPS. *Requires Vulkan API 1.3.*

<details>
<summary><b>Click to expand the VulkanMod modlist</b></summary>

*   **VulkanMod:** Rewrites Minecraft's renderer to use the Vulkan API, drastically reducing CPU overhead and boosting FPS.
*   **Lithium:** General-purpose optimization for game physics, AI, and block ticking.
*   **FerriteCore:** Significantly reduces the memory footprint of the game.
*   **EntityCulling:** Skips rendering hidden entities/tiles to boost performance.
*   **Beryl:** A mod that provides shaders like Vibrant Visuals, created specifically to improve the realistic gaming experience with VulkanMod.

</details>
