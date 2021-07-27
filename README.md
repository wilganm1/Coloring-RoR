# Project to color the Record of Ragnarok manga

This respository is to house a project to color in the manga of Record of Ragnarok (Shūmatsu no Walküre (終末のワルキューレ, Shūmatsu no Warukyūre, lit. "Valkyrie of the End") with object detection and auotmated coloring. The purpose of this project is to train an object detection model that will scan images of characters, recognize them, and color them in with colors from offical sources. OpenCV can be used do the coloring. Since this is a manga all the images are in black & white, so that makes it easier. We will have to extract the grayscale values of every pixel for each image, and save them for later. The same thing will be done for the reference colored image. All the unique colors will also be obtained in a list. Detection of characters will be done using an object detection program like Roboflow or Tensorflow I can either use LabelImg on my computer or use Roboflow to annotate images. If Roboflow is used then  their Yolov5/4 Google Colab notebook with their code to train models to recognize characters can be used. Since this is a manga and the design, shape, angle of the characters can alter slightly annotation will probably get hyper-specific. I'm talking about labeling their left and right arm, their head and roso, etc. Colorization of black-and-white images has already been tried: https://www.pyimagesearch.com/2019/02/25/black-and-white-image-colorization-with-opencv-and-deep-learning/, https://techvidvan.com/tutorials/deep-learning-project-colorize-black-white-images-with-python/, https://github.com/PySimpleGUI/PySimpleGUI-Photo-Colorizer/blob/master/PySimpleGUI_Colorizer.py.

This is just a fun project I want to try out. But if it works it will give me experience using openCV and object detection. I can use Roboflow or install my own Tensorflow object detection program and use that.
