# Patient-Safety-Object-Detection
he system will use AI technology to detect and count surgical gauze in real-time, reducing the risk of retained surgical items (RSIs) and improving patient outcomes. The system will also include a human detection module to reduce the risk of human error and improve the accuracy of gauze counting.

YoloV5.ipynb is the main detection code.

As of now, there are 3 setions of the code

First: Without anomaly warning

Second: With ANomaly warning

Third: No anomaly warning but with Kalman Filter

Frame Extraction to batch extract images from videos

COCO to Yolo and Split to split to convert COCO.json annotation from CVAT into Yolo format + Splitting into Train + Test + Val combos
