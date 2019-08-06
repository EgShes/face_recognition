# face_detection
Some expirements on face recognition

5 celebrity dataset was taken from [here](https://www.kaggle.com/dansbecker/5-celebrity-faces-dataset)

Face recognition can be devided in three steps:
1. locate face
1. ectract vector from face image
1. compare vector with precomputed vectors

For the first step comparison of two face detection models [faced](https://github.com/iitzco/faced) and [mtcnn](https://github.com/TropComplique/mtcnn-pytorch) were made.

Later I found a great library [facenet-pytorch](https://github.com/timesler/facenet-pytorch) and used it for experiments.

Comparison of vectors were first made by cosine similarity and then with SVM model.
