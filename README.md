`Dependencies`
1. Install docker https://docs.docker.com/get-docker/
2. Install Nvidia Container Toolkit https://developer.nvidia.com/cuda-downloads to run the docker container with your GPU.

`Yolov3 model inference with trained weights using docker.`

1. Add video of interest to Assignment3/Data directory.
2. Add frames to infer json to Assignment3/JSON directory.
3. Add trained weights to Assignment3/Weights directory.
4. In the root folder run the command `bash run.sh`
5. Once the yolov3 model has done its inference, it will copy the results to Assignment/Results directory.
6. The frames of interest will be saved into a csv file ie frames_of_interest.csv in Assignment/Results directory.
7. The video of interest with bounding box will be saved into Assignment/Results/Video directory.

`Yolov3 model inference with trained weights without using docker.`

1. Add video of interest to Assignment3/Data directory.
2. Add frames to infer json to Assignment3/JSON directory.
3. Add trained weights to Assignment3/Weights directory.
4. In the root folder run the command `python detect_new.py`
5. Once the yolov3 model has done its inference, it will copy the results to Assignment/Results directory.
6. The frames of interest will be saved into a csv file ie frames_of_interest.csv in Assignment/Results directory.
7. The video of interest with bounding box will be saved into Assignment/Results/Video directory.


```
Project Structure

yolov3
├─ Assignment3
│  ├─ Data
│  │  ├─ README.md
│  │  └─ Videos
│  ├─ JSON
│  │  └─ README.md
│  ├─ README.md
│  ├─ Results
│  │  ├─ README.md
│  │  ├─ Video
│  │  │  └─ README.md
│  │  └─ Results.csv
│  └─ Weights
│     └─ README.md
├─ run.sh
├─ detect_new.py
```
