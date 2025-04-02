Custom Object Detection using CVAT, Roboflow, and YOLOv8
1. Data Collection & Annotation
  >Collect images containing the objects to be detected.
  >Upload images to CVAT (local installation or online version).
  >Annotate images using bounding boxes or polygons and assign class labels.
  >Export annotations in YOLO format and download the dataset as a .zip file.

2. Data Processing with Roboflow
  >Create a new project on Roboflow.
  >Upload images and YOLO annotations exported from CVAT.
  >Apply augmentations (e.g., rotation, brightness, flipping).
  >Resize images to YOLOv8’s standard size (e.g., 640x640).
  >Export the dataset in YOLOv8 format and download it.

3. Model Training with YOLOv8
  >Install necessary dependencies like Ultralytics YOLOv8 and OpenCV.
  >Load the dataset into the training environment. 
  >Train the YOLOv8 model using the prepared dataset.
  >Monitor training metrics (loss, accuracy, mAP).
  >Save the best-performing model weights.

4. Model Evaluation & Inference
  >Validate the trained model on test data. 
  >Check evaluation metrics such as precision, recall, and mAP.
  >Perform inference on test images to verify detection results.

5. Deployment & GitHub Upload
  >Create a new GitHub repository.
  >Add project files, including dataset details, training scripts, and README.md.
  >Commit and push the files to GitHub.

(Optional) Convert the trained model to formats like ONNX or TensorRT for deployment.

IMPORTANT NOTE:
  #Code is avaliable in object code 
  #But images and objects are different ,same process for any object
