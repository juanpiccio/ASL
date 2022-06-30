# ASL Detection
 This project was done together with my friend and colleague Iván Aguilar.
 
 Its goal is to detect American Sign Language employing the famous You Only Look Once framework, a simple NN and a CNN.

We pre-train YOLO with a dataset of labelled images downloaded from the internet, and then we further train it with a set we created ourselves using some python code to capture ourselves via our webcams and an annotation app.

We then employ the model to detect ASL in our test sets.

As part of the project, we also train both a simple NN and a CNN and compare the classifying power of each model.