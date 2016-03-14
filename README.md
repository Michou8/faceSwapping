# Face Swapping
Require : 
	- wget http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
	- bzip2 -d shape_predictor_68_face_landmarks.dat.bz2

To use faceswap_test.py:
	It transform the transform first face found in these pictures
	- python faceswap_test.py <filename_1> <filename_2>
