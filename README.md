# helmet-detection-yolo
Using the YOLO architecture to detect helmetted and non-helmetted motorbikers. Training and testing done on custom data by manual annotation, using different versions of YOLO.

This is an experimental approach at using YOLO architecture in detecting motorbike riders with and without helmet. Different versions of YOLO like yolov2, tiny-yolo, and its variants in darknet/darkflow were experimented with.
The data was collected from various websites and manually annotated using the LabelImg software. Training was done on this custom data and testing done on unseen custom data.
Inputs where images, but trial was done on video input as well, by capturing them frame-by-frame.

The (presentation)[https://github.com/naveena-as/helmet-detection-yolo/blob/main/Presentation.pdf] gives a summary of the whole work and links to necessary files, and the step-by-step experimentation can be seen in the (code)[https://github.com/naveena-as/helmet-detection-yolo/blob/main/YOLO_helmet_detection_code.ipynb].
