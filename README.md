# Scrap-Car-Counting-CVZone

# My deep Sort/ yolov4 implementation for counting the scrap cars

# By: Aniket Kokate

``` first of all i did this on a linux machine meaning that you may have to make a new virtual enviorment to do so you have to install venv with pip to do so it is```

``` pip install venv```
and then
``` python -m venv env ```

once you have done that you have to install the dependencies

``` 
# requirements cpu
pip install -r requirements.txt 
# requirements gpu
pip install -r requirements-gpu.txt 
```

It is also a good idea to use output mode because on most computers live output is quite laggy
``` to do so the command is 'python object_tracker.py --output ./output.mp4 --dont_show' --dont-show is optional if you want to see the live output or not! ```


Also since some files were too large like the weights I have provided them below and you have to add them to the specified location

```
# yolov4.weights, place this file in the ./data folder
https://drive.google.com/file/d/185QmmIXQrl-jyPXtQ8U1EIRQbIlGqR2T/view?usp=sharing

# variables.data-00000-of-00001, place this file in ./checkpoints/yolov4-416/variables/
https://drive.google.com/file/d/1c2MY1nYmK7Mu8EJ2fwhQnQTLEJkSSeMO/view?usp=sharing

```
