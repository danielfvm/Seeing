# Seeing
This project uses an ASI-Camera for capturing video of the Polarstar. The video is then beeing processed using OpenCV to calculate the starprofile, mass and the centroid. The algorithms are from the [PHD2](https://github.com/OpenPHDGuiding/phd2) project and were taken from [star_profile.cpp](https://github.com/OpenPHDGuiding/phd2/blob/master/star_profile.cpp) and [star.cpp](https://github.com/OpenPHDGuiding/phd2/blob/master/star.cpp).

## Installation
```
$ pip install -r requirements.txt
$ export ZWO_ASI_LIB=/PATH/TO/libASICamera2.so
$ python <SCRIPT_NAME>.py
```

## Results

