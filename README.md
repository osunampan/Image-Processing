# Image-Processing
Semester project image processing - human faces

Here i have implemented the following image processing tasks:
1. Detecting human faces and extracting faces from any picture using mtcnn face detector.
2. Face Analysis - Predicting age, gender, race and emotion of a human face picture using facebook's deepface.
3. Face Analysis model comparisions - OpenCV, OpenFace and Dlib, if 2 pictures belong to the same people.
4. Recognising celebrities using Facenet


Please Note that Most Image processing uses keras for the implementation in that case You need to make new virtual environment in conda and have the correct versions of keras and tensorflow installed inside that environment. Also, while running make sure to install the perticular kernel for the virtual machine.

For running the above notebook please make sure you have the following libraries installed by running the following command:
General:

python -m pip install -U matplotlib or conda install matplotlib
pip install numpy or conda install numpy
pip install opencv-python

1. Detecting human faces and extracting faces from any picture using mtcnn face detector:
    pip install mtcnn
    conda install -c conda-forge mtcnn
    
2. Face Analysis - Predicting age, gender, race and emotion of a human face picture using facebook's deepface.
    pip install deepface
    conda install -c conda-forge deepface
    

Others, not mentioned here will be included in the notebook.
