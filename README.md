## Tracking Players by Unique IDs

To execute:
```
```
python object tracker.py -v <video_path>
```
OR
```
python object tracker.py --video <video_path>
```
```

Folder Structure:

    ├── config (consists of yolov3 models and coco class names
    ├── utils (yolov3 utils functions)
        ├── datasets.py
        ├── parse_config.py
        └── utils.py
    ├── models.py (yolov3)
    ├── object_tracker.py (main script to get unique ID of players)
    ├── object_tracker_optical_flow.py 
    ├── sort.py (deepsort pre-defined implementation)
    └── README.md


![Output Video](video.gif)
