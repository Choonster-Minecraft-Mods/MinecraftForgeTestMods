This is a Gradle project to run Minecraft Forge's test mods.

To use this project, clone the Minecraft Forge repository somewhere and then create the following symbolic links:
* **src/forge/java/net/minecraftforge/debug** ==\> **MinecraftForge/src/test/java/net/minecraftforge/debug**
* **src/forge/resources** ==\> **MinecraftForge/src/test/resources**

On Windows, run `mklink /D LINK TARGET` from an Administrator Command Prompt to create a directory symbolic link named **LINK** pointing to **TARGET**.
