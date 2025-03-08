# wild-animal-detection
The Wild Animal Detection and Alert System uses AI cameras to detect wildlife in real-time. It sends instant alerts via sirens to prevent conflicts, protect livestock, and reduce accidents, ensuring safety in wildlife-prone areas.

The `wild_animal_detection.ipynb` notebook is designed to detect animals using a pre-trained YOLOv8 model. Below are the steps to run it:

1. **Install Required Packages**:
   - `!pip install ultralytics`
   - `!pip install roboflow`

2. **Load the YOLOv8 Model**:
   - Download and load the pre-trained model.

3. **Run the Detection**:
   - Use a webcam for real-time detection.
   - The script processes video frames and detects animals with confidence scores.
   - If an animal is detected, it plays an alert sound.

4. **Execute the Notebook**:
   - Open the notebook in Jupyter or Google Colab.
   - Run each cell sequentially to install dependencies, load the model, and start detection.

You can find the full notebook [here](https://github.com/Thrishok/wild-animal-detection/blob/65f7125e2619be3baaa3bbcb571c2d9eac45b56a/wild_animal_detection.ipynb).
