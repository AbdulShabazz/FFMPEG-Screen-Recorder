# FFMPEG-Screen-Recorder
FFMPEG screen recorder command line configuration on Windows.

```shell
ffmpeg -f gdigrab -framerate 120 -offset_x 0 -offset_y 0 -video_size 3840x2048 -show_region 1 -i desktop -c:v libx264 -crf 0 output.mp4
```
