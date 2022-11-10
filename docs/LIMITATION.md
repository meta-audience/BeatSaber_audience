### GPU Session Problem
- we only support nvdia graphic card
- if you have any application occupied the gpu session, streamer maynot create streaming success
- you can check messages in BeatSaber folder
  - path is /Logs/_latest.txt
  - if find `streaming session error`, your gpu may be occupied by some apps
  - try to close other apps or restart your computer

### Browser VR mode streaming support
- we only support latest Chrome to watch VR 3D streaming
- if your steamVR cannot open Chrome XR extension, try restart your steamVR
  -  when you click the VR mode button through our streaming url, and see your steamVR status `Chrome 106` -> `SteamVR Home` -> `Chrome 106` -> ... (loop)
    - ChromeXXX, XXX is the number of Chrome edition
  -  then you should restart steamVR
### Viewer limitation
 Resolution | Limit viewers 
 ----- | ----- 
| 3840×2160 (4K) |  16 viewers
| 2560x1440 (2K) |   20 viewers
| 1920x1080 (1080P)| 40 viewers

> 2D & 3D cameras have same limitation  
> 
> Example: 
> - streamer builds 3 source cameras with resolutions of 3D/2K, 2D/2K, and 2D/1080P
> - then build 3 viewers in scene setting and link with 3 source cameras 
> - start streaming in BeatSaber and share link will get 3 share urls
> - each URL has an individual audience limit
> - So 3D/2K has 20 viewers limit
> - 2D/2K has 20 viewers limit
> - 2D/1080P has 40 viewers limit
