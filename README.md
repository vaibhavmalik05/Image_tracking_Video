# Image_tracking(Video)
 Object tracking in a video (Cars, bicyles, pedestrains etc)

 File motlable.csv is larger than 100 Mb and hence cannot be uploaded to git, So we have compressed it to 'mot_labels_csv_file.zip'

## Libraries used:

### cv2 (also called as openCV): 
OpenCV (Open Source Computer Vision) is a popular open-source computer vision library that provides various tools and functions for image and video processing. It is widely used in the field of computer vision and machine learning.

### IPython.display: 
IPython.display is a module in IPython (Interactive Python) that provides various utilities for displaying content in the notebook or IPython environment. One of the commonly used features is ipd.Audio, which allows you to play audio directly in the notebook. Ipd.Video is another common used feature to play video.

### tqdm: 
It is a Python library that provides a fast, extensible progress bar for loops and iterable objects. It offers a simple and intuitive way to track the progress of your iterations, making it easier to monitor the execution time and estimate the remaining time for completion. 

### subprocess: 
The subprocess module in Python allows you to spawn new processes, connect to their input/output/error pipes, and obtain their return codes. It provides a way to run external commands or programs from within your Python script.
Here we have used it for running command line scripts.

## ffmpeg framework: 
FFmpeg is a powerful open-source multimedia framework that includes a set of tools and libraries for handling multimedia data. It can be used to encode, decode, transcode, mux, demux, stream, and filter audio and video files.
We cannot use ffmpeg directly in python, so here for this project we’ll use this with the help of subprocess.
It's important to note that FFmpeg is not installed directly as a Python package but as a system-level dependency. 
Make sure to download a pre-built binary of FFmpeg (before using it in python with the help of subprocess) from the official website (https://ffmpeg.org/) or use a distribution like FFmpeg for Windows (https://ffmpeg.org/download.html#build-windows).
Also make sure to add FFmpeg to your system's PATH environment variable so that it can be accessed from the command line and from within Python.


