# This repository is synced

## OpenCV-Yolov3

### I will likely introduce some changes later. It's a pretty cool project to have fun with. I might want to add some kind of python prerequisites file, then try modifying the drawing algorithm.
## It's nothing really fancy (although, it's pretty cool) and currently more of an implementation of an article/guide I managed to stumble upon.

<I might want to implement something similar in my other projects>

## Based on 
- Nandini Bansal's medium [story](https://towardsdatascience.com/object-detection-using-yolov3-and-opencv-19ee0792a420) with [GitHub Project](https://github.com/nandinib1999/object-detection-yolo-opencv)
- My own modifications

# Changelog TO-DO/IN-PROGRESS

- configuration parameters on top of the file (IN-PROGRESS)
- configuration of the backend's target (CPU, GPU) (Done, not tested)
- quit key on 'Q' (Done)
- changeable/adjustable font/rectangle colors (TO-DO)
- FPS counter (TO-DO)
- possible split of functions into separate files (TO-DO)
- logging of detected objects (FUTURE)

### I introduced my own changes, basing on public domain resources (including Chinese websites).

I am actually not sure if I could manage to port it to use GPU instead. I believe that some frameworks offered CUDA support, but I am running on Radeon.

## Performance:

Ryzen 2600X - 60-70% CPU use at (measuring by eye) 10-15FPS

## Dependencies

- pip install opencv-python
- pip install numpy
- pip install argpars
- pip install time

## Network dependencies

- CFG file at: https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg
- Coco labels at: https://github.com/pjreddie/darknet/blob/master/data/coco.names
- Weights at: https://pjreddie.com/media/files/yolov3.weights

## Example
![Results](result.png)
