# VLPR

## Prerequisite packages
### Opencv:-

For windows:
```sh
pip install opencv-python
```
For linux:
```sh
sudo apt install python3-opencv
```
### Numpy:-

For windows:
```sh
pip install numpy
```
For linux:
```sh
sudo apt install python-numpy
```
---
## Code & Files

### Our project performs the following steps:
* Liscense plate extraction - Done by [video_frame_extraction.py](video_frame_extraction.py).
* Liscense plate Recognition - Done by [detection.py](detection.py).
* Creates a folder wherein the extracted license plate number is stored.

### How to run our project:
* The test video should be added in the VLPD folder.
* Change the name of the video in [video_frame_extraction.py](video_frame_extraction.py) on line 23.
* Open the terminal.
```sh
cd VLPD
```
```python
python video_frame_extraction.py
```
* Check output in the vehicle folder
---
## In order to enhance the computational perfromance a GPU setup is preferrable as it is 500 times faster than CPU


