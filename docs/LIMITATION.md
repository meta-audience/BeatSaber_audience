# Limitations

### GPU Limitations
- **We only support NVIDIA graphics cards**
- If the computer is running other applications that use up GPU resources, the streamer may experience live streaming problems
- If you experience problems, check for error messages in your Beat Saber folder:
  - Navigate to the path /Logs/_latest.txt
  - If you see `streaming session error`, your GPU may be occupied by other apps
  - Close other apps or try restarting your computer

### Browser VR Mode Streaming Support
- **Viewing VR 3D streaming is only supported by the latest Google Chrome version**
- The first time you enter VR mode in Chrome using the WebXR API Emulator extension, your SteamVR status will change from <br>`SteamVR Home` -> `Chrome 106`,  indicating you have successfully entered VR mode
- If you try to re-enter VR mode in Chrome but are unable to, and `Chrome 106` doesn't appear as your SteamVR status, this may be due to a bug in the extension. Follow these steps:
  - Refresh your live stream browser 
  - Restart your SteamVR
  - Enter VR mode again (the SteamVR status should show as `Chrome 106`)
 > In "Chrome XXX" XXX is your Chrome version
  
### Viewer Limitations
 Resolution | Viewer limit  
 ----- | ----- 
| 3840×2160 (4K) |  16 viewers
| 2560x1440 (2K) |   20 viewers
| 1920x1080 (1080P)| 40 viewers

> (2D & 3D cameras have the same limitations)
> 
> Example scenario: 
> - Streamer adds 3 source cameras with resolutions of 3D/2K, 2D/2K, and 2D/1080P
> - Streamer then adds 3 viewers to Scene Settings and links them to the 3 source cameras 
> - Streamer starts streaming in Beat Saber and clicks **Share the Stream** to show 3 different share URLs (one for each viewer)
> - Each URL has an individual audience limit
>   - 3D/2K  limit is 20 viewers
>   - 2D/2K  limit is 20 viewers
>   - 2D/1080P limit is 40 viewers
