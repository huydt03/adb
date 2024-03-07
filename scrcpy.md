scrcpy --max-size=1280 --disable-screensaver --stay-awake --video-codec=h265 --video-bit-rate=6M --audio-bit-rate=192K --max-fps=30

alt + f = full screen

"set devices size"
adb shell wm size 1080x1920
adb shell wm density 420
"reset"
adb shell wm size reset
adb shell wm density reset

"obs"
  setting -> video: 1280x720
