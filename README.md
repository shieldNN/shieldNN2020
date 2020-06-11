# shieldNN2020
This repository contains the code for running experiments and generating results.
##Requirements
#### CARLA Simulator:
https://github.com/carla-simulator/carla/releases
We used Windows version 0.9.5 and python 3.5
This CARLA version comes with PythonAPI for python 3.5
In order to install the PythonAPI package in your python 3.5 environment, please refer to:
https://github.com/carla-simulator/carla/issues/1466

#### Python packages
Pip install pygame<br />
Pip install onnx<br />
Pip install onnx-tf<br />
pip install tensorflow-probability==0.7<br />
Pip install gym<br />
pip install scikit-image==0.16.2<br />
Pip install opencv-python<br />
Conda install pandas<br />
#### Training An Agent
Run Carla with 'Town04' command line argument. <br />
Run train.py and pass the command line arguments specified by the script.<br />
#### Testing An Agent
Run train.py with -test command line argument.
#### Pretrained Models
Pretrained models for agent 1,2 and 3 are located inside 'models' folder.
#### Paper results
To generate paper results, run plot_training_results.py and plot_histograms.py