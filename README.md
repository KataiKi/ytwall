# ytwall
Youtube Wrapper that performs seamless loops a video in fullscreen.  When used with applications such as Wallpaper Engine, WallpaperWebpage, or Plash, it can be used to make fast and easy wallpapers from any embeddable youtube page.

# Usage:
The YouTube video you are using must be embeddable.  Whether or not the video is embeddable is determined by a setting controlled by the owner of the video.

You must first obtain the Youtube Video ID from the video's source URL.  This is found after ?v= and before any & symbols.  For example, https://www.youtube.com/watch?v=jVLn-oG2NK4&list=PLgUcGCr-q2SXE01RrgPtnOm9rFBDWrLa0 has a video ID of jVLn-oG2NK4.

Then replace [YOUTUBE_ID] in the following URL with your video ID, and use this URL in your target application.
https://kataiki.github.io/ytwall/?v=[YOUTUBE_ID]

For Example: https://kataiki.github.io/ytwall/?v=jVLn-oG2NK4

## 
If you want to use part of a clip instead of the whole video, you can use the following URL instead, where [START_TIME] and [END_TIME] is the time in seconds (decimals allowed).
https://kataiki.github.io/ytwall/?v=[YOUTUBE_ID]&s=[START_TIME]&e=[END_TIME]

For Example: https://kataiki.github.io/ytwall/?v=jVLn-oG2NK4&s=65.2&e=93.4
