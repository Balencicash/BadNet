# **BadNet: Badminton Match Player Tracking and Court Boundary Line Detection System**

This project leverages [YOLOv8](https://github.com/ultralytics/ultralytics) to enable **player tracking** and **boundary line detection** in badminton match footage/frame.  
The system is designed to assist in match analysis and statistical data collection by efficiently detecting players' positions and court boundaries.

---

## **Features**

1. **Player Tracking**  
   - Real-time detection and marking of player positions on the court.  
   - Visualization of players' movement trajectories.  

2. **Line Detection**  
   - Accurate detection of court boundary lines to assist in out-of-bounds judgment.

3. **Optimized Model**  
   - Utilizes YOLOv8 for enhanced detection speed and accuracy, suitable for real-time applications.

---

## **Project Structure**

```plaintext
├── data/                   # Dataset directory
│   ├── images/             # Raw images or videos
│   ├── labels/             # Annotation files
├── models/                 # YOLOv8 trained weights
├── scripts/                # Core scripts
│   ├── track_players.py    # Player tracking module
│   ├── line_detection.py   # Line detection module
│   ├── visualize.py        # Visualization of results
├── results/                # Output directory for results (videos/images)
├── README.md               # Project description
└── requirements.txt        # Environment dependencies
