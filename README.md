# 2D Object Detection | Model Comparisons

## 1) Dataset
- I took dataset from the [NuScene](https://www.nuscenes.org/), created annotation on it from the [Roboflow](https://app.roboflow.com/login), a web based 
annotations software and tried 3 different algorithms on generated dataset. Here is the information of my dataset in visual form.

![image](https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/Roboflow_Health_check.png)

- Information graphs for labels and labels-correlations.
<p float="left">
  <img src="https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/labels.jpg" width="500" /> 
  <img src="https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/labels_correlogram.jpg" width="500" />
</p>

## 2) Scaled YOLOv4
- Precision Recall Curve and result graphs for Scaled YOLOv4

<p float="left">
  <img src="https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/PR_curve_ScaledYOLOv4.png" width="500" /> 
  <img src="https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/ScaledYOLOvt_results.png" width="500" height="333"/>
</p>

## 3) YOLOv5
- Precision Recall Curve and result graphs for YOLOv5

<p float="left">
  <img src="https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/PR_curve_Yolov5.png" width="500" /> 
  <img src="https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/Yolov5_results.png" width="500" height="333"/>
</p>

## 4) Detectron2
- For this I do not have the data output but I have the COCO evaluation matrix, which is below.

![image](https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/Detectron2-1.png)
![image](https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/Detectron2-2.png)

## 5) Results
- Scaled YOLOv4

![image](https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/ScaledYOLOv4_output.jpeg)

- YOLOv5

![image](https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/YOLOv5_output.jpg)

- Detectron2

![image](https://github.com/PLEX-GR00T/2D_ObjDetection_Roboflow/blob/main/Outputs/Detectron_output.jpg)
