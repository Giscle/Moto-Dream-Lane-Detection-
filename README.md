# Moto-Dream-Lane-Detection
Team leader : Olaf Placha
Other team members: Ahmet Yaylalioglu, Prashant Singh, Prashant Shukla.

This project is created by team MotoDream for Giscle Intern and for detecting lane on indidan Roads.

This project uses Canny Edge Detection, Hough Transforms, and Color thresholding to identify and mark lane lines on a road. And this repo was written with the hope that it would be easy to understand for someone not farmiliar with the project.

### Requirements 
- numpy
- matplotlib
- opencv
- python3 
- sklearn.cluster 
- collections
Insteid of installiing all these libreries individualy you can downdload and intall Anaconda with python3 inviroment it'd be helpful. 
https://conda.io/docs/user-guide/install/index.html

## How it works
We can describe this process in a straightforward way. 
- Apply gamma correction to deal with night or very less brightness in the image. 
- Define our region of interest. 
- Reduce the noise and make data smoother.
- Apply Color thresholding to identifiy road lanes clearly.
- Apply Canny Edge Detection algorithm for finding edges.
- Apply Hough transform to make lines on our data.
- Apply Clustering algorithm to draw clear line. 


There are a couple of algorithms to decide how to draw the lines, DBSCAN being the last thing I came up with. 

