# squat counter in Python based on YOLOv7 model with Keypoint extraction in JSON format. 

The "yolov7-w6-pose.pt" petrained dataset (https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7-w6-pose.pt) is still needed to run this application.
</p>
running pose detection model by using webcam:
</P>
python squat_counter.py --weights yolov7-w6-pose.pt --source 0 --device 0 --kpt-label --view-img
