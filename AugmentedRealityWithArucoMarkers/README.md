# Augmented Reality using ArUco Markers in OpenCV (C++ / Python)

**This repository contains the code for [Augmented Reality using ArUco Markers in OpenCV (C++ / Python)](https://learnopencv.com/augmented-reality-using-aruco-markers-in-opencv-c++-python/) blog post**.

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/sh/k8mbua12pmqh4o2/AAC0N6jG7X8wtZfMUpDa9y1Ma?dl=1)

We show how to use the AruCo markers in OpenCV using an augmented reality application to replace the image inside a picture frame on a wall to display new images or videos in the frame.

### Compilation in C++

```
g++ -std=c++11 augmented_reality_with_aruco.cpp -o augmented_reality_with_aruco.out `pkg-config --cflags --libs opencv4`
```

### How to run the code

Command line usage for running the code

* Python

  * A single image:
    	
    ```
    python3 augmented_reality_with_aruco.py --image=test.jpg
    ```
    
  * A video file:

    ```
    python3 augmented_reality_with_aruco.py --video=test.mp4
    ```       

* C++:

  * A single image:
        
    ```
    ./augmented_reality_with_aruco.out --image=test.jpg
    ```

  * A video file:

    ```
     ./augmented_reality_with_aruco.out --video=test.mp4
    ```

### Results
<img src = "./augmented-reality-example.jpg" width = 1000 height = 282/>


# AI Courses by OpenCV

Want to become an expert in AI? [AI Courses by OpenCV](https://opencv.org/courses/) is a great place to start. 

<a href="https://opencv.org/courses/">
<p align="center"> 
<img src="https://learnopencv.com/wp-content/uploads/2023/01/AI-Courses-By-OpenCV-Github.png">
</p>
</a>

