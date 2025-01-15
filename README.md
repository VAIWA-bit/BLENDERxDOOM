# BLENDERxDOOM
![prev](https://raw.githubusercontent.com/VAIWA-bit/BLENDERxDOOM/refs/heads/main/prev.jpg)
## Info
- Tested only on Windows 10
- Tested with Blender 4.1, 4.2
- If you want to play Doom - **GZDoom** and **Doom Enhanced** won't work, use **Crispy Doom** instead
- The launcher is built using **Microsoft Edge WebView2**. If you don't have it installed, you will need to install it. However, it comes pre-installed by default on Windows 10 and later
- You can play any game, but keep in mind that higher resolutions require a more powerful CPU. I recommend sticking to a resolution of around 300x300
- By default Blender will open in fullscreen mode
- If you want to modify the code or shader of the project’s blend file, you can find it in the installation folder. When you open it, press **Ctrl+Alt+Tab** and remember to press **Ctrl+Alt+Tab** again before saving your changes
## 1. Download BLENDERxDOOM.zip and install it
## 2. Setup
- **Required:** Ensure the game is set to run in windowed mode, modify its resolution, and verify that it is using OpenGL or Vulkan
## 3. Play
- Open the launcher, click the edit button and specify the game path
- Do the same and specify the blender path
- **Required:** The path must not include non-English characters. The path must include executable name.
**Ex:**
```
C:\gog games\Braid\braid.exe
```
```
C:\Program Files\Blender Foundation\Blender 4.1\blender.exe
```
## 4. Custom Window Size (**Optional**)
If a game cannot change its resolution, you can force a resize. However, be aware that each game manages resize events differently. Click on the edit icon and enter a custom resolution, e.g., 320x180. Check the box to use the custom window size
## 5. Custom Window Title (**Optional**)
If the game crashes immediately after launching, you can specify its title. Click on the edit icon and enter a custom title, for example, 'Braid.' Check the box to use the custom window title. To obtain the window title, you can use the PowerShell code provided below (launch your game and execute the following code)
```
Get-Process | Where-Object { $_.MainWindowTitle } | Select-Object Id, ProcessName, MainWindowTitle
```
## 6. Custom Client Area (**Optional**)
If you launch a game and see black bars on the right or bottom of the game frame, it indicates that you need to specify a custom client area resolution. Click on the edit icon and enter a custom resolution, such as 312x172. Check the box to use the custom client area
## 7. Launch with Arguments (**Optional**)
If you want to play an emulator, and it supports this feature, you can specify the game path for it to load. Ensure that the arguments do not contain non-English characters. Click on the edit icon and enter the custom arguments. Check the box to use the custom arguments
## If you believe this project deserves your contribution, it would be greatly appreciated
## **Bitcoin**
![Bitcoin](https://raw.githubusercontent.com/VAIWA-bit/PaintPlay/refs/heads/main/img/bitcoin.png)
### bc1qtjvtktp5hkspzehaaaw6827crawhqkwgn7sf7u
## **Ethereum / Tether**
![Ethereum](https://raw.githubusercontent.com/VAIWA-bit/PaintPlay/refs/heads/main/img/Tether.png)
### 0xf516751FD82c942aA10430Cb52A12B10333E6BdE
## **Toncoin**
![Toncoin](https://raw.githubusercontent.com/VAIWA-bit/PaintPlay/refs/heads/main/img/toncoin.png)
### EQA3OYCxwhDVstIcIaquAeLvFR_PknhuB4WH-jpvMKpdRgeV
