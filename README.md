# CSC245-Helmet-Detection-Test

Helmet detection test for the third project for CSC245

# Tutorials

## Building the project
Creating virtual environments:
https://docs.python.org/3/tutorial/venv.html

Creating and running a virtual environment:
python -m venv env
env/Scripts/activate

Downloading requirements
pip install -r requirements.txt

Remember to install CUDA (12.1) and cuDNN from Nvidia if you want to use GPU


## Downloading the dataset
Kaggle: Test dataset:
https://www.kaggle.com/datasets/npk7264/helmet-dataset/

After downloading the dataset, put the contents in a folder named "datasets".

 
## Using YOLO
YOLO quickstart:
https://github.com/ultralytics/ultralytics

YOLO training on custom datasets
https://docs.ultralytics.com/modes/train/


## Adding samples
Create a folder named 'samples' and put all the photos you want to detect into it.

# Things to do:
* Resolving bugs with GPU (must run on GPU! Docker might be a solution...)
* Create a custom dataset and train with it (Roboflow might be good)
* Change the final result from detecting with images to detecting with videos (target: 20fps, at least 85% accuracy)