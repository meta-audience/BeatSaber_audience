# FAQs


### 1. How to install Mod Assistant?
1. Go to Mod Assitant(https://github.com/Assistant/ModAssistant/releases/tag/v1.1.28) and download the latest Mod Assistant
2. After executing Mod Assistant, make sure the following dependent mods are selected.
* BSIPA
* BeatSaberMarkupLanguage
* BS Utils 
3. Click "Install or Update"
4. Launch the Beat Saber game, the related folder will automatically generate by Beat Saber, then you can install your audience mod.

### 2. I can't install audience mod, what should I do?
Make sure if the Beat Saber releases upgrade recently. Whenever the Beat Saber gets upgraded, the modding feature of the Beat Saber might not upgrade at the same time. In this case, You can only wait for the modding feature to get upgraded. We will post the related information on our Discord.
  
### 3. My Beat Saber can't run after installing the audience mod
Try to launch the Beat Saber through steam platform. If that doesn't work, remove the audience mode, and re-install it. You can also ask for help in our Discord.

### 4. How many cameras can I use in Beat Saber?
At most three so far! We use NVIDIA hardware encoding, and other applications might have a chance to use the same technic, which affects the number of cameras. Consider the setting below:

### 5. I can't see the head of my Avatar in Beat Saber
This is a known issue, go to Custom Avatar → Settings → Current avatar → Ignore first person exclusions.
  
### 6. Is there a more convient way sharing the live stream to phones or Quest 1/2
You can use QR code tool to transform the URL into a QR code. or use hmd.link, click "add link" and parse your URL on it. (Note: you can only use the hmd.link in local network environment, this means you can't share this link to a friend outside the local network)

Open your phones or Quest1/2 and link to hmd.link, you'll see the link you just parse. Click the link and then you can watch the shared stream.

(You can bookmark the https://hmd.link/ for future usage)

### 7. The live stream gets frozen sometimes on the phones, what happen?
Please make sure your phone's version is higher than Android 9 or iOS 10 and under a 5G WIFI environment. 

### 8. Live stream feels laggy, too much cameras causing performance issue?
There are two reasons for live stream laggy.

1. PC hardware requirements
    - checkout our recommended requirements and see if your PC
2. Network bandwidth and speed are not enough
    - Please make sure that your network bandwidth and speed are enough for the live stream, we recommend 100M/40M for a 4K live stream.
    - Are you using a VPN? this might cause slow network speed.

### 9. How do I know that I have enough network bandwidth? How much bandwidth does audience use?
The easiest way is to open your task monitor on your PC, switch to performance → network, and you can observe "Send" to see how much bandwidth you use to upload your live stream. You can also open your router's webpage to observe the bandwidth usage.

### 10. I can find any solution from the FAQs above, what can I do?
Looks like you encounter something tricky, We'll take care from here. just a few steps to collect your log files:

1. Open a new directory (e.g. C:\audience_log)
1. Copy all the files located in the following path to "C:\audience_log"
    * %steam_install_path% \steamapps\common\Beat Saber\Logs
    * %steam_install_path% \steamapps\common\Beat Saber\Beat Saber_Data\Plugins\x86_64\logs
3. Open Command Prompt and execute the following command
`msinfo32 /nfo c:\audience_log\sys_info.nfo`

After all the steps, compress "C:\audience_log" to a compressed file and upload it to our Discord or send it to service@meta-audience.com

### 11. Is there any other contact information?
We have our Discord, feel free to join! Briefly describe your question, we'll get to you soon and do our best to help you solve the problem.

