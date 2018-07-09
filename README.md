  ## facerecognition using Haar-Cascade Classifier, OpenCV,python and sqlite3 databse.
 ### requirement
- Python 2.7
- OpenCV 
- Sqlite3
- Numpy
 ### Outline
 This project consist of 3 parts, which are:
* Creating datasets (datasetCreator.py)
* Train the model (trainnner.py)
* Face Recognition (detector.py)
## How to Execute?
* Please make sure that you have folders called 'dataset',recognizer and 'trainer' in the same directory.
* Run datasetCreator.py enter user id and show some face images for the respective user I fixed 100 images for one user.After scaning of
100 images the camera window will destroy.Now go to sqlite studio and fill the descriptions about user that you want like name ,designation etc.
* If you want more faces to be include, change the ID and run the program again.
* Now run trainner.pt to train your dataset.
* At last,Run detector.py to recognize the faces.
* for the strangers algorithm shows unknown to user.
