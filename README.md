# Object-Detection
Tried and tested Step-wise explanations.

Git clone https://github.com/llSourcell/YOLO_Object_Detection
1. .https://www.python.org/downloads/windows/ python 3.7.6 
2. pip install cython
3. pip install tensorflow==1.15.2
4. Download visual C++ build tools from https://go.microsoft.com/fwlink/?LinkId=691126
5. pip install -e .
6. pip install opencv-python
7. pip install nms
8. download zip from https://github.com/thtrieu/darkflow
execute pip install -e . in that directory.
9. copy the darkflow and darkflow.egg-info folder into original folder (YOLO_Object_Detection-master).
10. python flow --h
11. download weights from here : https://drive.google.com/drive/folders/0B1tW_VtY7onidEwyQ2FtQVplWEU
12. once execute any of these commands as per your wish 
For a demo that entirely runs on the CPU:
flow --model cfg/yolo-new.cfg --load bin/yolo-new.weights --demo videofile.avi
For a demo that runs 100% on the GPU:
flow --model cfg/yolo-new.cfg --load bin/yolo-new.weights --demo videofile.avi --gpu 1.0
To use your webcam/camera, simply replace videofile.avi with keyword camera.
To save a video with predicted bounding box, add --saveVideo option.

(YOU WILL GET AN ERROR SAYING NO FILES UNDER BIN)

13. Now transfer the desired weight into bin folder and check for the availability of corresponding .cfg file inside cfg folder.

14. run the command of line 12 again.
15. Wait for some time the execution will start.
