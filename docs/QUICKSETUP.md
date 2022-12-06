# Installation Guide
* [Auto Installation](#auto) (Recommend)
* [Manual Installation](#manual)

# <span id="auto">Auto Installation (audience installer)</span>
1. Select a language, then click **Next**.  
<img src="https://i.imgur.com/HfWMPKg.jpg" alt="drawing" width="400"/>

2. Make sure you have aleady installed Beat Saber and Mod Assistant, then click **Next**.
<img src="https://i.imgur.com/3Dd4HcJ.png" alt="drawing" width="400"/>

3. Select the folder where you installed Beat Saber and click **Install**. The installer will auto-detect the Beat Saber folder in your Steam or Oculus library and find the correct path.  
<img src="https://i.imgur.com/eXOc0xU.png" alt="drawing" width="400"/>

- Note that if auto-detection fails or you want to install the mod in a different 
Beat Saber location, choose your path manually using the **Custom** option, then click **Install**.
<img src="https://i.imgur.com/S1D9Q2x.png" alt="drawing" width="400"/>

4. Wait for the mod to install. 
<img src="https://i.imgur.com/cONixFk.png" alt="drawing" width="400"/>

5. Installation complete! 
<img src="https://i.imgur.com/9D0fzRF.png" alt="drawing" width="400"/>

# <span id="manual">Manual Installation</span>

1. **Please backup your Beat Saber folder first.** 
2. Find your Beat Saber folder location.
3. Download the export_rel.zip file in the latest [release](https://github.com/meta-audience/BeatSaber_audience/releases).
4. Extract the zip file to anywhere.
5. There are three .dll files in this zip file. Drag them to the following locations:
    - /Libs
        - **audience_unity.dll**
        - **audience-plugin.dll**
    - /Plugins
        - **audience.dll**
    - /Plugins/x86_64
        - **/logs/audience_log_config.json**

