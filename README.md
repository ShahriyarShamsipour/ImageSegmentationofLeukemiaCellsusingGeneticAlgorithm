# Image Segmentation of Leukemia Cells using Genetic Algorithm

In this project, we worked on the segmentation of leukemia cells with the genetic algorithm.
What we want to do is take an image of a leukemia cell, select three pixels from it, and replace all the pixels in that image with those three pixels to get a segmented image.
We use PSNR to find out how similar our image is to the real image.
We want to find out which three pixels get us to the closest image without trying all the different modes.
Genetic algorithm is a search algorithm that will lead us to the optimized answer quickly.
In this case and for these images, if we were to calculate all the states to get the best possible answer, we would have to do calculations for C(275*275,3) = 72042115320 different states.
While we have done this less than 50 times, and we have also reached the optimized solution, thanks to the genetic algorithm.

In the end, I have to say that for this kind of work, K-means and other clustering methods seem better. However, I did this project for the educational purpose.
