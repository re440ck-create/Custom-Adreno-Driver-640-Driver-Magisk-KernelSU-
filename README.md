
<img width="1080" height="2400" alt="1000024987" src="https://github.com/user-attachments/assets/af9022b9-d278-47ea-892a-e8d516bccdaf" />
<img width="1079" height="1763" alt="1000024988" src="https://github.com/user-attachments/assets/2177c365-0dbd-4222-b2a4-cfcc8d2a7cab" />

# ⚡ Custom Adreno 600 GPU Driver

> **Special Build & Optimized by AMINE** 🛠️

A high-performance custom Adreno 640 GPU driver tailored for **Snapdragon 855 / 860 / 865** devices. This module is engineered with strict SELinux rules to maximize gaming performance while ensuring rock-solid system stability.

## 🚀 Key Features

* **⚙️ Updated Graphics APIs:** Powered by **Vulkan 1.1.295**, **OpenGL ES 3.2**, and **OpenCL 3.0** for superior 3D rendering and compute performance.
* **🛡️ Stable & Safe Integration:** Built-in bootloop prevention and strict SELinux patching to avoid System UI crashes.
* **🧹 Smart Shader Cache Cleaner:** Automatically detects and clears outdated GPU/Graphite caches during installation to prevent visual glitches.
* **🎮 Gaming Optimized:** Reduces input lag and stabilizes frame-pacing for emulators and heavy 3D titles.

---

## 📦 Compatibility & Installation

This module features a universal installer script that automatically adapts to your root environment. 

**Fully Supported Root Managers:**
* ✅ **Magisk** 
* ✅ **KernelSU (KSU)**
* ✅ **APatch**

### 🛠️ Flashing Instructions:
1. Open your preferred root manager app (**Magisk**, **KernelSU**, or **APatch**).
2. Navigate to the **Modules** tab.
3. Tap on **Install from storage** (or the **+** button).
4. Select the downloaded `Custom-Adreno-640-Driver.zip` file.
5. Wait for the automated flashing process to finish (The *Smart Shader Cleaner* will run automatically).
6. **Reboot** your device to apply the new drivers. Enjoy!

---

## 🧪 How to Verify the Update

To ensure the new drivers are successfully applied, you can use the following tools from the Google Play Store to check your GPU APIs version:

* 📱 **[DevCheck Device & System Info](https://play.google.com/store/apps/details?id=flar2.devcheck):** Navigate to the **Hardware** tab to verify the current **OpenGL ES** version and general GPU details.
* 🌋 **[Vulkan Hardware Capability Viewer](https://play.google.com/store/apps/details?id=de.saschawillems.vulkancapsviewer):** Use this to confirm the updated **Vulkan** API version (e.g., 1.1.295) and supported extensions.
* ⚡ **[OpenCL Hardware Capability Viewer](https://play.google.com/store/search?q=OpenCL+Hardware+Capability+Viewer&c=apps):** Run this to check the active **OpenCL 3.0** profile and compute unit metrics.
