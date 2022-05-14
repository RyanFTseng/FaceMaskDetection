# Face Mask Detection  
Github Link: https://github.com/RyanFTseng/FaceMaskDetection  
  
Prerequisites:  
   Python 3.9: https://www.python.org/downloads/release/python-390/  
   NVIDIA CUDA: https://developer.nvidia.com/cuda-downloads  
   PyTorch: https://pytorch.org/get-started/locally/  
  
Installation:  
Open Terminal to project directory  
Install Requirements by running: `pip install -r requirements.txt`  
Run the following commands:  
 `pip install pafy`  
 `pip install youtube_dl`  
  
Running model on webcam:
`python detect.py --source 0 --weights finalModel.pt`

Running model on image or video:
`python detect.py --source "PATH_TO_SOURCE" --weights finalModel.pt`

Running model on youtube video:
`python detect.py --source "VIDEO_URL" --weights finalModel.pt`

Results are saved in the /runs directory
