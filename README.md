# About this project

The goal of the project was to detect aggregates in cornea cells images and to get some metrics about those aggregate (area, perimeter, etc.). 
For this image processing project, I chose to test the `SegmentAnythingModel` from Meta. However, I also preprocessed my images by hand before that, and this notebook might serve as an introduction to image masking and for other image processing concepts. 

# How to read it

Well, as often, I store all my code in notbeooks. In this particular project, I worked on Google Colab (you can find [my working notebook here](https://colab.research.google.com/drive/1KgvWUjOMLnAkkqiG5Cl2sLE7b2-o00P5?usp=drive_link)) because I needed strong RAM and performance to use the `SAM` model. 

I am not providing the `SAM` weights file nor the checkpoints I had created with the `pickle` library because those files were too heavy. 

However, don't hesitate to contact me if you have any question about my work. You can contact me via Github if so.
