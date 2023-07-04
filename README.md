# PUGV-Dataset
Professional User-generated Vlog Video dataset from the paper "Two-Stream Cinematographic-aware Shot Assembly for Vlog Generation"
This repository consists of well-edited vlog videos from the BiliBili platform along with their metadata(the number of likes, shares, comments, danmu and etc.) and manual "scale type" annotations(Extreme Close shot, Close shot, Medium shot, Full shot, Long shot) for each shot.

# Structure of the repository
We upload some example data from the PUGV dataset. The file "example data" includes the information and URLs for videos in the file "video", and information of shot segmentation and shot annotations in the "annotation" file.

# video information and URLs

video URL:  https://www.bilibili.com/video/bvid/ # bvid is the unique identity number for each video
{
    {
        "bvid": ["BV1A34y157k3"],
        "title": ["白噪音美食|裹满浓郁茄汁的巴沙鱼..."],
        "description": ["一道适合夏天的菜..."],
        "video_review": [20],
        "play": [16297],
        "collect": [1012],
        "comment": [113],
        "like": [1266],
        "share": [132],
        "coin": [250],
        "danmu": [20],
        "duration": [2:34]
    },
}

# shot segmentation and annotations

{
    {
        "Shot Number": [1],
        "Start Frame": [1],
        "Start Timecode": [00:00.0],
        "Start Time (seconds)": [0],
        "End Frame": [64],
        "End Timecode": [00:02.1],
        "End Time (seconds)": [2.133],
        "Length (frames)": [64],
        "Length (timecode)": [00:02.1],
        "Length (seconds)": [2.133],
        "scale_manual": ["Extreme Close Shot"],
    },
}










