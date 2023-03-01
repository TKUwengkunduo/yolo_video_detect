# yolo_video_detect

This program is used for YOLO model detection video, you can use the Realsense camera to view the recognition results in real time



## Building
```bash
git clone https://github.com/TKUwengkunduo/yolo_video_detect.git

cd yolo_video_detect
```

## Install weights
Please download `.weights` yourself and put it in the `/cfg/weights` folder

## Get file
Please put the following two files in your darknet folder into this folder to replace the original files
`darknet`
`libdarknet.so`

## Run
```bash
python3 YOLO_Detect.py
```

## other
`.data` may need to be changed according to the situation
