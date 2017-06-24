#This file is for results and discussions.

0 > Detection of faces in the image.

The task of face detection in the image is completed using the algorithm that was suggested by Viola & Jones in 2001.
(http://cgit.nutn.edu.tw:8080/cgit/PaperDL/uang_09032621564947.pdf)

This algorithm is very fast and most of the times accurate for detecting the faces. In the recent times, many other face detection techniues have been eveolved.

> Histogram of Oriented Techniques & Local Binary Pattern -- popular recent face detection techniques.

The results discussed here will be that of the technique suggested by Viola & Jones.

Couple of parameters to play around with in the file "face_detect_cv3.py":

1 > Scale size
2 > Minimum neighbors

The above two parameters affect the result of face detection.

Scale factor will affect the results when the images are captured at avarying distance and thus you will need to adjust this parameter to get the best result.

Minimum neighbors is an important parameter where you want to set a threshold to the number of minimum neighbors for a robust face detection.

For example > Image of Federer holding the Wimbledon Trophy (federer1.jpg).

If minimum neighbors is set to 5 (less), you will notice you have three faces detected in the image (federerfdwrong).

If the minimum neighbors is set to say 30 (high), the result of face detection will be accurate and will detect only one face in the image (federerfdcorrect).
