# Object Detection — YOLOv5

### AI-Powered Object Detection from Drone Imagery

A commercial application developed at **[SKAITECH](https://skaitech.al/)** for analyzing images captured by drones. Users can upload regular aerial images or georeferenced TIFF files, select a trained YOLOv5 model, and review the objects that the model is designed to detect.

Large images are divided into smaller sections for analysis, allowing detailed areas to be processed and then presented as a complete result. When suitable geospatial information is available, detected objects can also be associated with map locations.

## Project Showcase

### Detection Overview

Detected objects are presented across the processed aerial image, with a total count and class legend available in the interface.

![Object detection results across drone imagery](assets/images/detection-results.jfif)

### Detection Detail

Users can inspect individual detection locations and view the class associated with each result.

![Detailed object detection result](assets/images/detection-detail.jfif)

### Geospatial Visualization

For supported georeferenced imagery, detections can be displayed within their wider geographical context.

![Geospatial overview of detected objects](assets/images/geospatial-overview.jfif)

## Key Capabilities

- Drone imagery analysis
- Object detection with YOLOv5
- Support for different trained detection models
- Large aerial image processing
- Geospatial visualization for supported imagery

The detected categories depend on the selected model. For example, one trained model could detect cars, while another could distinguish specific vehicle types or support a different object-detection task.

## Built With

Python · Django · YOLOv5 · PyTorch · OpenCV · GeoPandas · GDAL · Mapbox

## Project Attribution

Developed at **SKAITECH**.

This is a private commercial project showcased as part of my professional portfolio. Source code and trained models are not publicly available.

[Visit the SKAITECH website](https://skaitech.al/)
