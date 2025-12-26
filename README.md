Cricket Ball Tracking System using YOLOv8
This repository contains an automated system to detect and track a cricket ball from video footage. The project was developed as part of a technical assessment to demonstrate skills in computer vision and deep learning deployment.

🚀 Features
Ball Detection: Uses a fine-tuned YOLOv8s model.

Trajectory Visualization: Draws a smooth path of the ball's movement.

Data Export: Generates frame-by-frame coordinates (visible vs non-visible) in CSV format.

Optimized Pipeline: Includes ROI (Region of Interest) filtering to reduce background noise.

📂 Project Structure
code/: Contains the Jupyter Notebook (.ipynb) and Python script for inference.

model/: Stores the trained weights (best.pt).

annotations/: Frame-by-frame tracking data in CSV files.

results/: Final output videos with overlaid tracking trajectories.

requirements.txt: List of necessary Python libraries.

🛠️ Installation & Setup
Clone the repository:
git clone https://github.com/Pallavigalgale/cricket_ball_trajectory/tree/main
Install dependencies:

pip install -r requirements.txt
Model Performance
Architecture: YOLOv8s

Epochs: 50

mAP@50: ~0.95 (95% accuracy in ball detection)

Inference Speed: Real-time performance on NVIDIA Tesla T4 GPU.

📝 Technical Report
A detailed analysis of the training process, challenges faced, and post-processing techniques used can be found in the Report.pdf file in the main directory.
