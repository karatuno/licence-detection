# licence-detection
20 FPS on Intel® Core™ i3-1005G1
> object_detection_yolo.py (Inference scripts)

Usage : python3 object_detection_yolo.py PATH_TO_IMAGES

Example: python3 object_detection_yolo.py --dir /home/ayush/Downloads/inference_images/

> test_images : folder containing test images.

> output_images: folder containing output images from neural network with inference time and bounding box with confidence.

> chart_yolov3-tiny.png: chart showing mAP>70

> weights, names and cfg for yolo inference.

I've trained yolov3-tiny using darknet and I'm using OpenCV DNN for inference.
I'm getting an average inference time of 50ms making average FPS around 20.
My CPU is Intel® Core™ i3-1005G1 CPU @ 1.20GHz × 4 
