THIS HYPER FIT ALGORITHM IS CONSIDERED TO BE ONE OF THE BEST (PERHAPS THE BEST) CIRCLE FITTING ALGORITHM, IN TERMS OF ACCURACY. IT IS ALSO RELATIVELY FAST.

The original algorithm fits a set of known data points (in 2D) to a circle. 
* AS A CONTRIBUTION to the original algorithm, we have added functions allowing circle fitting on complete and incomplete circular objects, in live-stream 2D-images.

THE REVISED ALGORITHM HAS THE FOLLOWING IMPLEMENTATION BLOCKS:
(1) Image acquisition-> (2) Data points (Xi,Yi) extraction, using Canny edge detection-> (3) Gathering of data points-> (4) Fitting data points to a circle, using the circle fitting algorithm-> (5) Printing the fit circle´s arc, and radius value, onto captured frames

The algorithm is explained with comments in the "Source.cpp" file

IN OUR REPOSITORY WE HAVE A VIDEO FILE, named "Circle Fitting (True radius 2 meter).webm", SHOWING AN EXAMPLE WHERE WE HAVE FIT A CIRCLE TO A LARGELY INCOMPLETE CIRCULAR ARC, USING OUR CIRCLE FITTING ALGORITHM.
In the video file, the short arc length (17 cm) we have fit to a circle corresponds to approximately 5 degree of a complete circle´s circumference. With our non-professional camera setup, the algorithm fits a circle to the arc with an accuracy of approximately 99.5%, pretty impressive for such small angle!

* As can be seen from our video example, the Hyper fit algorithm can be implemented to fit accurate circles to largely incomplete circular arcs.

HOW TO USE THE CODE:
VISUAL STUDIO:
  We have used visual studio 2013 and OpenCV version 2.4.13, download at (http://opencv.org/downloads.html)
  install OpenCV following steps below, it shows how to configure OpenCV 2.4.13 with visual studio 2010 (same for later versions)
  1. You need to configure OpenCV with visual studio, example: https://www.youtube.com/watch?v=KoJTIs-h-0g
  2. Create a new project in visual studio, add all the files (Cpp and Headerfiles) from our repository to the project 
  3. Link OpenCV libraries and additional dependencies (DLL:s) to the project, following the youtube-tutorial from step 1. 
  4. Compile and Run the application

OTHER ENVIRONMENTS OR BUILDERS:
  For other COMPILERS/BUILDERS, similar approach can be used.
  If you need help, please contact me and I might be able to help: soel1300@student.miun.se
