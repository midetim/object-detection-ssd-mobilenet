
# Object Detection with SSD MobileNet

This project demonstrates object detection using a pre-trained SSD MobileNet model. It includes a Jupyter Notebook to run inference on images or video feeds and visualize detected objects.

## Files
- **frozen_inference_graph.pb**: The pre-trained SSD MobileNet model file.
- **labels.txt**: The list of object classes that the model can detect. It includes common objects like "person," "car," "bicycle," etc.
- **object_detection_demo.ipynb**: Jupyter Notebook for running the object detection demo.
- **ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt**: Configuration file that maps model outputs to label names for visualization.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/object-detection-ssd-mobilenet.git
   ```
2. Navigate to the project directory:
   ```bash
   cd object-detection-ssd-mobilenet
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook:
   ```bash
   jupyter notebook object_detection_demo.ipynb
   ```

## Usage
1. Run each cell in the Jupyter Notebook to load the model and perform inference.
2. Upload images or video feeds for real-time object detection and visualize the results.

## Model and Labels
- The **frozen_inference_graph.pb** model is trained on the COCO dataset, which includes 90 common objects.
- The list of classes is provided in `labels.txt`, which you can modify for custom classes if using a different model.

## License
MIT License
