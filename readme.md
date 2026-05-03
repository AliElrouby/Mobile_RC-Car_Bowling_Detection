Mobile_RC-Car_Bowling_Detection/
│
├── data/
│   ├── raw_videos/
│   │   └── Vid_1.mp4
│   │
│   ├── extracted_frames/
│   │   └── video1
│   │       ├── frame_00000.jpg
│   │       ├── frame_00001.jpg
│   │       └── labels/
│   │           ├── frame_00000.txt
│   │           └── frame_00001.txt
│   │   └──video2
│   │       ├── frame_00000.jpg
│   │       ├── frame_00001.jpg
│   │       └── labels/
│   │           ├── frame_00000.txt
│   │           └── frame_00001.txt
│   └── yolo_dataset/
│       ├── images/
│       │   ├── train/
│       │   ├── val/
│       │   └── test/
│       ├── labels/
│       │   ├── train/
│       │   ├── val/
│       │   └── test/
│       └── data.yaml
│
├── models/
│   ├── yolov8n.pt
│   ├── best.pt
│   └── best.tflite
│
├── runs/
│   └── detect/
│
├── src/
│   ├── 01_extract_frames.py
│   ├── 02_prepare_dataset.py
│   ├── 03_train.py
│   ├── 04_predict.py
│   ├── 05_track.py
│   └── code.ipynb
│
├── classes.txt
├── requirements.txt
├── .gitignore
└── README.md