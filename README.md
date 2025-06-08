# TEAMR_Project_268384_269035_268449

Final project: DEEP LEARNING FOR SKIN DISEASE CLASSIFICATION

Team information:

Members: Yuxiang Jiang 268449, Pau Reig Vaqué 269035, Nil Tomàs Plans, 268384

Team code: Team R

## What this project is about?

A small project developed in 2 weeks for the final project of the Deep Learning Course 2025. Our project proposes a lightweight CNN inspired by MobileNetV2, and explores several possible improvements. The goal is to reach a test accuracy close to the best existing model on the same dataset — the VGG16 model, which achieves 89% accuracy.

## How to run the code

This project was developed entirely in Google Colaboratory. Due to the large size of the dataset, we couldn’t include it directly in the repository.

To run the notebook, you’ll first need to download the dataset manually from Kaggle:

https://www.kaggle.com/datasets/pritpal2873/multiple-skin-disease-detection-and-classification

Steps to Run:

  1.  Clone the repository and open the notebook in an environment that supports Google Colab (e.g., Google Drive or your local machine with Jupyter/Colab integration).
  2.  Download the dataset from the Kaggle link above and place it inside a folder named `data` at the root of the project.
  3.  Ensure the `results_def` folder is present in the main directory of the project. Since the original `results_def` folder exceeds GitHub’s size limits, it has been split into two parts: `results_def1` and `results_def2`.
After cloning the repository, download both folders from GitHub, merge their contents, and place everything inside a single folder named `results_def` in the main directory.
  4.  Update the paths (path, results_path, new_path) in the notebook to point to the correct location of the data and results_def folders.

After completing these steps, you should be able to run the code successfully.

## Disclaimer

This project is provided for educational and research purposes only. We do not make any guarantees about the correctness, performance, or safety of the code. By using this repository, you agree that the authors are not responsible for any issues, damages, or losses that may arise from its use.

Please use it at your own risk.
