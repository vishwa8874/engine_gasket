# Engine Gasket Defect Detection using YOLO

This project utilizes YOLO (You Only Look Once) for detecting defects in engine gaskets through image inspection.

## Project Structure
├── data.yaml
├── index.py
├── model.pt
├── output.jpg
├── train_file.ipynb
├── test
│ ├── images
│ └── labels
└── train
├── images
└── labels


- **data.yaml**: Configuration file for the YOLO model.
- **index.py**: Python script for running defect detection using YOLO.
- **model.pt**: Pre-trained YOLO model file.
- **output.jpg**: Sample output image showing detected defects.
- **train_file.ipynb**: Jupyter notebook for training the YOLO model.
- **test/**: Directory containing test images and labels.
- **train/**: Directory containing training images and labels.

## Getting Started

### Running the Program

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
   ```

2. **Install dependencies:**

Ensure you have Python and pip installed. Install required packages:

```bash
pip install ultralytics opencv-python
```

3. **Detect defects using pre-trained model:**

Run the index.py script to perform defect detection using the pre-trained YOLO model:

```bash
python index.py
```
By default, the script uses the webcam (source="0"). Modify source parameter in index.py if using images or videos.

4. **Training the YOLO model:**

Use the train_file.ipynb notebook to train the YOLO model. Make sure to follow the instructions within the notebook to specify the correct paths and configurations.
