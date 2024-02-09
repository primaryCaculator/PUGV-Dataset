# PUGV Video Dataset for Vlog Editing (ProVlog）
  Professional User-generated Vlog Video dataset from the paper "Cinematographic-aware Coherent Shot Assembly for Vlog Generation".
  
This repository consists of well-edited vlog videos from the Chinese video-sharing platform (BiliBili,https://www.bilibili.com/) and manual "scale type" annotations (Extreme Close shot, Close shot, Medium shot, Full shot, Long shot) for each shot in the videos.


* Structure of the repository

We upload all video data from the PUGV dataset. The file "cooking_videos_bvid" and "handcraft_videos_bvid" include the unique ID of each video, and each video can be access through link " https://www.bilibili.com/video/*corresponding bvid*/". Each ZIP package comprises information on shot segmentation and shot annotations about each video under the corresponding scenario(cooking or handcraft).


* Shot segmentation and annotations

```
{
    "Shot Number": [1],
    "Start Frame": [1],
    "Start Timecode": ["00:00.0"],
    "Start Time (seconds)": [0],
    "End Frame": [64],
    "End Timecode": ["00:02.1"],
    "End Time (seconds)": [2.133],
    "Length (frames)": [64],
    "Length (timecode)": ["00:02.1"],
    "Length (seconds)": [2.133],
    "scale_manual": ["Extreme Close Shot"]
  },
```


* Video downloading and processing
  
 The code about the video downloading and processing (split the video into shots), will be updated soon.










