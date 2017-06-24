# Face-expression-detection-and-recognition
This is small project to recognise the human emotions in a picture.
The subsequent steps involved for the same are as follows:

0 > Detection of faces in the image - Completed.

1 > Feature extraction of the faces detected and passing them to the machine learning algorithm - Completed.

2 > Training the machine learning algorithm for different faces and storing them in the database with a labeling- Ongoing.

3 > Comparing the features extracted from the image with those stored in the database and classification - Ongoing.

4 > All the above steps for a particular emotion - Yet to start.

Detailed information of every step:

0 > Detection of faces in the image:
Firstly, set up a virutal environment of OpenCV 3 with Python.
Code:
export WORKON_HOME=$HOME/.virtualenvs
source /usr/local/bin/virtualenvwrapper.sh
source ~/.profile
mkvirtualenv cv

Secondly, run the code by typing below:

python face_detect_cv3.py federer.jpg

Please check the Results file for discussion on the code and other related parameters.


