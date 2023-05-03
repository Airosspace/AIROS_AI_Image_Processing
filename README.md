
# AIROS Image Processor

This project aims to develop a foreign object detection system using YOLOV5 (You Only Look Once Version 5) object detection algorithm for detecting foreign objects on the runway. The system detects foreign objects in the runway image or video stream and highlights them for easy identification. This project is developed in Python.

## Installation

To use this project, you will need to have Python 3.7 or higher installed on your machine. You can install Python from the official website: `https://www.python.org/downloads/.`

- Next, clone this repository to your local machine using the following command:

```bash
  git clone https://github.com/airos-software-dev/airos-mission-control.git
```

- Then, install the required Python packages using the following command:

```bash
    pip install -r requirements.txt
```

## Usage 

To use the foreign object detection system, run the following command:

```bash
    python detect.py --source <path_to_input_file> --weights <path_to_model_weights>

```
This will run the detection algorithm on the input file and display the output image or video with foreign objects highlighted in red.



## Features

- Real-time detection of foreign objects on the runway.
- High accuracy detection using YOLOV5 object detection algorithm.
- Easy to use command-line interface.
- Ability to detect multiple foreign objects in a single image or video stream.
- Customizable detection threshold for tuning the sensitivity of the algorithm.## Contributing

We welcome contributions to AIROS Image Processor Github! To contribute, please fork this repository, make your changes, and submit a pull request. Please ensure that your changes are well-documented and tested, and follow the `AIROS Image Processor` coding guidelines.


## License

AIROS Image Processor is released under the `GNU General Public License v3.0.` Please see the LICENSE file for more information.

[AIROSSPACE](https://airosspace.com/)

![Logo](https://github.com/Airosspace/ROS_PX4_Installation/blob/main/images/logo.png)
## Credits

AIROS Image Processor is developed by the AIROS Software Development Team, a group of passionate software engineers dedicated to providing cutting-edge solutions for drone-based applications.

