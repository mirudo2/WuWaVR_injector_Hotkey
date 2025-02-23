# Specific Injector for WuWa Only

This injector will load UEVR only when you press the specific hotkey `CTRL + O`. It is recommended to press this hotkey only when you are already inside the map.

## Installation

1. **Create the Folder**  
   Create a folder at the exact directory:  
   `C:\WutheringWavesVR`

2. **Windows Defender Exclusions**  
   Add this folder to the Windows Defender exclusions to prevent the injector from being removed.  
   *(If you do not trust the pre-compiled files, you can compile them yourself.)*

3. **Copy Files**  
   Copy the following files into the `WutheringWavesVR` folder:  
   - `injector.exe`  
   - `main.dll`  
   - `openxr_loader.dll`  
   - `UEVRBackend.dll`  
   *(Use the DLLs from the latest stable UEVR version, not the nightly ones.)*

![Image](https://raw.githubusercontent.com/mirudo2/WuWaVR_injector_Hotkey/refs/heads/main/image.png)

## How to Inject

- Run `injector.exe` as an administrator.
- Start the game.
- Once the game has loaded and you are inside the map, press `CTRL + O` to load UEVR.
