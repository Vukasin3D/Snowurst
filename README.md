# Snowurst

![GitHub last commit](https://img.shields.io/github/last-commit/Vukasin3D/Snowurst)
![License](https://img.shields.io/github/license/Vukasin3D/Snowurst)
![Minecraft Version](https://img.shields.io/badge/Minecraft-1.21.7-green?style=flat&logo=minecraft)
![Requires](https://img.shields.io/badge/Requires-Fabric%20API-blue?style=flat&logo=curseforge)

Snowurst is a fork of the popular Wurst Client, focusing on creating a cleaner, more performant, and aesthetically pleasing user experience.

This project began as a learning endeavor into Minecraft mod development and has evolved into a full-fledged personalization of the Wurst client, bringing new themes, features, and quality-of-life improvements.

## ✨ Key Features

* **New Visual Themes:** Features the default "Snowurst" (white) and "DarkUI" themes for a more modern interface. (RainbowUI is unchanged)
* **Streamlined Focus:** Removes non-essential features from the original client to focus on the most important and useful modules.
* **Open Source:** Inherits the original GPL-3.0 license, ensuring the project remains open and collaborative.

---

## 🚀 Installation

Snowurst can be installed just like any other Fabric mod.

1.  **Install Fabric:** Download and run the [Fabric installer](https://fabricmc.net/use/installer/) for Minecraft version **1.21.7**.
2.  **Add the Mods:** Go to the [**Releases**](https://github.com/Vukasin3D/Snowurst/releases) section of this repository and download the latest Snowurst `.jar` file.
3.  Place the Snowurst `.jar` file and the [**Fabric API**](https://www.curseforge.com/minecraft/mc-mods/fabric-api) `.jar` file into your `mods` folder.

> [!NOTE]
> You must own a licensed copy of Minecraft: Java Edition to use Snowurst.

---

## 🛠️ Development Setup

> [!IMPORTANT]
> Make sure you have **Java Development Kit (JDK) 21** installed. Other versions will not work.

### 1. Clone the Repository

```bash
git clone [https://github.com/Vukasin3D/Snowurst.git](https://github.com/Vukasin3D/Snowurst.git)
cd Snowurst
```

### 2. Generate IDE Files

Run the command corresponding to your preferred IDE:

* **For VSCode / Cursor:**
    ```bash
    gradlew genSources vscode
    ```
* **For Eclipse:**
    ```bash
    gradlew genSources eclipse
    ```
* **For IntelliJ IDEA:**
    ```bash
    gradlew genSources idea
    ```

### 3. Open the Project

Open the `Snowurst` folder in your IDE and wait for it to import the project and download the dependencies. You are now ready to start modding!

---

## 🤝 Contributing

At the moment, Snowurst is a personal project, but ideas and suggestions are always welcome! If you find a bug or have an idea for a new feature, feel free to open an [**Issue**](https://github.com/Vukasin3D/Snowurst/issues).

---

## 📜 License

This code is licensed under the **GNU General Public License v3.0**, inherited from the original Wurst Client project.

This means you are free to use, modify, and distribute this code, as long as any derivative project is also open-source and released under the same license (GPL-3.0). Using this code in closed-source or proprietary clients is **not allowed**.

(i kept everything wurst had so i can reference it more :D)
