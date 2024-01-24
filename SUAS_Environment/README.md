# Simulation-2024 Unreal Files

This folder contains the Unreal environment and assets for the SUAS competition

## How to Setup this Repo's Unreal Environment
1. Due to restrictions on repository file size you must first manually add the airsim plugin. To do this, copy **\<*Airsim Folder*>\Unreal\Plugins\Airsim\\**  to **SUAS_Environment\Plugins\\**. You do not need to exclude this file when adding/committing as it is already included in the repo's .gitignore.
2. After copying the airsim plugin, right click on **SUAS_Environment.uproject** and press **"Generate Visual Studio project files"**
3. Once **SUAS_Environment.sln** is generated, double click on it.
4. Finally, follow steps 9-13 from this link to finish the setup [Unreal Environment](https://microsoft.github.io/AirSim/unreal_custenv/#:~:text=Below%20are%20the%20instructions%20to%20do%20this%3A%201,chose%20%22Generate%20Visual%20Studio%20project%20files%22%20option.%20)
