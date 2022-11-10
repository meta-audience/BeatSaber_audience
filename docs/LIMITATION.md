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
- it only can support about 10 viewers watch streaming through SFU url
