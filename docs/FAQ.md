# FAQs


### 1. How do I install Mod Assistant?
1. Go to [Mod Assistant](https://github.com/Assistant/ModAssistant/releases/tag/v1.1.28) and download the latest Mod Assistant.
2. After executing Mod Assistant, make sure the following dependent mods are selected.
* BSIPA
* BeatSaberMarkupLanguage
* BS Utils 
3. Click **Install or Update**
4. Launch the Beat Saber game, and a Beat Saber folder will automatically be generated. You can then install your audience mod.

### 2. I can't install the audience mod. What should I do?
Check if a new Beat Saber update has been released recently. When Beat Saber updates, Beat Saber's modding feature might not update at the same time. In this case, you can only wait for the modding feature to update as well. We post news and information about updates on our [Discord channel](https://discord.com/invite/T2aKHMGbU2).
  
### 3. My Beat Saber won't run after installing the audience mod. What should I do?
Try to launch Beat Saber through the Steam platform. If that doesn't work, remove the audience mod, and reinstall it. You can also ask for help on our [Discord channel](https://discord.com/invite/T2aKHMGbU2).

### 4. How many cameras can I use in Beat Saber?
You can currently use a maximum of three cameras. We use NVIDIA hardware encoding, which uses GPU resources. Other applications you have open might also use GPU resources, and limit the number of cameras you're able to add. If you're using Steam as your gaming platform, try to free up GPU resources by disabling the "motion smoothing" option in your Steam VR settings.
<img src="https://imgur.com/fjA2PxY.jpg" alt="drawing" width="400"/>

### 5. I can't see the head of my avatar in Beat Saber. What should I do?
This is a known issue. Go to **Custom Avatar** → **Settings** → **Current avatar** → **Ignore first person exclusions**.
<img src="https://imgur.com/Al5D8Ow.jpg" alt="drawing" width="400"/>
  
### 6. Is there a more convenient way to share live streams to phones or Quest 1/2?
You can use a QR code tool to transform the URL into a QR code. 

Or use [hmd.link](https://hmd.link/). Click "add link" and enter your URL. (Note: you can only use the hmd.link in local network environments, which means you can't share this link to a friend outside your local network.)

On your phone or on Quest 1/2, go to [hmd.link](https://hmd.link/), and you'll see the link you just entered. Click the link to watch the shared stream.

(You can bookmark https://hmd.link/ for future use).

### 7. Why does the live stream sometimes freeze on phones?
Please make sure your phone's OS version is higher than Android 9 or iOS 10 and using 5G WiFi. 

### 8. The live stream feels laggy. Are too many cameras causing performance issue?
There are two possible reasons for a laggy live stream:

1. PC doesn't meet minimum hardware requirements
    - Check if your PC meets our recommended minimum hardware requirements.
2. Network bandwidth and speed are too low
    - Please make sure that your network bandwidth and speed are high enough for the live stream. We recommend 100M/40M for a 4K live stream.
    - Are you using a VPN? VPNs can cause slow network speeds.

### 9. How do I know that I have enough network bandwidth? How much bandwidth does audience use?
The easiest way the check network bandwidth in Windows 10 is to open your PC's Resource Monitor, expand **Network**, and observe the "Send" category to see how much bandwidth you're using for the live stream. You can also open your router's webpage to observe the bandwidth usage.

### 10. I can't find my question in the FAQs above. What can I do?
Sounds like you encountered something tricky. We'll take care of it from here. Just follow these steps to provide us with your log files:

1. Open a new directory (e.g. C:\audience_log)
1. Copy all the files located in the following paths to "C:\audience_log"
    * %steam_install_path% \steamapps\common\Beat Saber\Logs
    * %steam_install_path% \steamapps\common\Beat Saber\Beat Saber_Data\Plugins\x86_64\logs
3. Open Command Prompt and execute the following command
`msinfo32 /nfo c:\audience_log\sys_info.nfo`

After follow these steps, compress "C:\audience_log" to a compressed file and upload it to our Discord channel or send it to service@meta-audience.com

### 11. Is there any other contact information?
Feel free to join our [Discord channel](https://discord.com/invite/T2aKHMGbU2)! Briefly describe your problem, and we'll get back to you soon and do our best to help you solve the problem.
