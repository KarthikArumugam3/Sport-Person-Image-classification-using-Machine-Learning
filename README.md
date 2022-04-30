# Sportsperson-Image-classification-Webapp-using-Machine-Learning

## Webapp demonstration
https://user-images.githubusercontent.com/69972911/166058916-bc4fb2c4-bd37-4780-905b-58aa3cc6afb6.mp4

## Project Description
### Working on Image dataset - 

* This dataset contains images of the Sports personalities on which the ML model is built. 
* It has 5 image classes & the model is only trained on these 5 classes.
* Each data point is a 3D image one of the 5 classes.
* The images from the dataset are downsized to 32*32 before training the model to avoid issues.

The 5 classes of images are of the following personalities:- 
* Virat Kohli
* Maria Sharapova
* Lionel Messi
* Serena Williams
* Roger Federer

## Tech
The project uses the following technologies/packages :- 

- ![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=Python)
- ![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
- ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
- ![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
- ![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
- ![Pandas](https://img.shields.io/badge/-Pandas-black?style=flat-square&logo=Pandas)
- ![Numpy](https://img.shields.io/badge/-Numpy-black?style=flat-square&logo=Numpy)
- ![Matplotlib](https://img.shields.io/badge/-Matplotlib-black?style=flat-square&logo=Matplotlib)
- ![Seaborn](https://img.shields.io/badge/-Seaborn-black?logo=seaborn&logoColor=white)
- [![Editor](https://img.shields.io/badge/Editor-VSCode-blue?style=flat-square&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)
- ![PyCharm](https://img.shields.io/badge/-PyCharm-000000?logo=pycharm&logoColor=white)


## Installation:-

All the packages related to this project have been listed down in the requirements.txt file.

* Install the packages in active environment using:-
```
pip install requirements.txt
```
------------
* For working in isolated conda environments:-
1. Create a virtual environment in conda at the default location in windows:
```
conda create -n env_name
```
-----------
2. To create a virtual env in the current working directory:-
```
conda create --prefix ./envs
```
-----------
* To run the main Ml web app of the project you need to start the server:-
```
cd /server
```
```
python server.py
```

* To run the Streamlit webapp associated with this project :-
```
Launch the "app.html" present in UI folder
```
# Project Development 

#### What?
* I have created this Machine learning project that aims at classifying different sports personalities when the image is provided.
* After running the main script the server will start and would be ready to be tested on unknown data of images of the respective 5 people.
* I have created a hassle free webapp using Flask where simply the images the person can be fed and the ML model associated with the webapp would take in the photo and process it and give out the result.


## Author:-
[Karthik Arumugam](https://github.com/KarthikArumugam3)
