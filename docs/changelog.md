### 0.3.2 <small>March 23, 2023</small> 

- Changed [[#50](https://github.com/roboflow/supervision/issues/50)]: Allow `Detections.class_id` to be `None`. 

### 0.3.1 <small>March 6, 2023</small> 

- Fixed [[#41](https://github.com/roboflow/supervision/issues/41)]: `PolygonZone` throws an exception when the object touches the bottom edge of the image.
- Fixed [[#42](https://github.com/roboflow/supervision/issues/42)]: `Detections.wth_nms` method throws an exception when `Detections` is empty.
- Changed [[#36](https://github.com/roboflow/supervision/pull/36)]: `Detections.wth_nms` support class agnostic and non-class agnostic case.

### 0.3.0 <small>March 6, 2023</small> 

- Changed: Allow `Detections.confidence` to be `None`.
- Added: `Detections.from_transformers` and `Detections.from_detectron2` to enable seamless integration with Transformers and Detectron2 models. 
- Added: `Detections.area` to dynamically calculate bounding box area.
- Added: `Detections.wth_nms` to filter out double detections with NMS. Initial - only class agnostic - implementation. 

### 0.2.0 <small>February 2, 2023</small> 

- Added: Advanced `Detections` filtering with pandas-like API.
- Added: `Detections.from_yolov5` and `Detections.from_yolov8` to enable seamless integration with YOLOv5 and YOLOv8 models.

### 0.1.0 <small>January 19, 2023</small> 

Say hello to Supervision 👋
