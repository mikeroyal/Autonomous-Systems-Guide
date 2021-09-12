<h1 align="center">
 <img src="">
  <br />
  Autonomous Systems Guide
</h1>

#### A guide covering Autonomous Systems including the applications, libraries and tools that will make you a better and more efficient Autonomous Systems development.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
 <img src="">
  <br />
</p>


# Table of Contents

1. [Autonomous Systems Learning Resources](https://github.com/mikeroyal/Autonomous-Systems-Guide#Autonomous-Systems-learning-resources)

2. [Autonomous Systems Tools, Libraries, and Frameworks](https://github.com/mikeroyal/Autonomous-Systems-Guide#Autonomous-Systems-tools-libraries-and-frameworks)

3. [Computer Vision Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#computer-vision-development)

4. [Algorithms](https://github.com/mikeroyal/Autonomous-Systems-Guide#algorithms)

5. [Machine Learning](https://github.com/mikeroyal/Autonomous-Systems-Guide#machine-learning)

6. [CUDA Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#cuda-development)

7. [MATLAB Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#matlab-development)

8. [Photogrammetry Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#photogrammetry-development)

9. [Autodesk Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#autodesk-development)

10. [LiDAR Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#lidar-development)

11. [Robotics Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#robotics-development)

12. [Linear Algebra](https://github.com/mikeroyal/Autonomous-Systems-Guide#linear-algebra)

13. [C/C++ Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#cc-development)

14. [Python Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#python-development)

15. [R Development](https://github.com/mikeroyal/Autonomous-Systems/-Guide#r-development)

16. [Julia Development](https://github.com/mikeroyal/Autonomous-Systems-Guide#julia-development)

# Autonomous Systems Learning Resources
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

[Autonomous Systems (AS)](https://www.microsoft.com/en-us/ai/autonomous-systems-project-bonsai) is a branch of artificial intelligence that provides a solution for system automation(Robotics, Cars, and Smart devices) that works alongside people for decision support or a system that works independently on its own. It can be deployed on-premises, in the cloud, IoT Edge, or in embedded devices.

[Autonomous Systems - Microsoft AI](https://www.microsoft.com/en-us/ai/autonomous-systems)

[Introduction to Microsoft Project Bonsai](https://docs.microsoft.com/en-us/learn/autonomous-systems/intro-to-project-bonsai/)

[Machine teaching with the Microsoft Autonomous Systems platform](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/autonomous-systems)

[Autonomous Maritime Systems Training | AMC Search](https://www.amcsearch.com.au/ams-training)

[Top Autonomous Cars Courses Online | Udemy](https://www.udemy.com/topic/autonomous-cars/)

[Applied Control Systems 1: autonomous cars: Math + PID + MPC | Udemy](https://www.udemy.com/course/applied-systems-control-for-engineers-modelling-pid-mpc/)

[Learn Autonomous Robotics with Online Courses and Lessons | edX](https://www.edx.org/learn/autonomous-robotics)

[Artificial Intelligence Nanodegree program](https://www.udacity.com/course/ai-artificial-intelligence-nanodegree--nd898)

[Autonomous Systems Online Courses & Programs | Udacity](https://www.udacity.com/school-of-autonomous-systems)

[Edge AI for IoT Developers Course | Udacity](https://www.udacity.com/course/intel-edge-ai-for-iot-developers-nanodegree--nd131)

[Autonomous Systems MOOC and Free Online Courses | MOOC List](https://www.mooc-list.com/tags/autonomous-systems)

[Robotics and Autonomous Systems Graduate Program | Standford Online](https://online.stanford.edu/programs/robotics-and-autonomous-systems-graduate-program)

[Mobile Autonomous Systems Laboratory | MIT OpenCourseWare](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-186-mobile-autonomous-systems-laboratory-january-iap-2005/lecture-notes/)

# Autonomous Systems Tools, Libraries, and Frameworks
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

[Microsoft Project Bonsai](https://azure.microsoft.com/en-us/services/project-bonsai/) is a low-code AI platform that speeds AI-powered automation development and part of the Autonomous Systems suite from Microsoft. Bonsai is used to build AI components that can provide operator guidance or make independent decisions to optimize process variables, improve production efficiency, and reduce downtime.

[Microsoft AirSim](https://microsoft.github.io/AirSim/lidar.html) is a simulator for drones, cars and more, built on Unreal Engine (with an experimental Unity release). AirSim is open-source, cross platform, and supports [software-in-the-loop simulation](https://www.mathworks.com/help///ecoder/software-in-the-loop-sil-simulation.html) with popular flight controllers such as PX4 & ArduPilot and [hardware-in-loop](https://www.ni.com/en-us/innovations/white-papers/17/what-is-hardware-in-the-loop-.html) with PX4 for physically and visually realistic simulations. It is developed as an Unreal plugin that can simply be dropped into any Unreal environment. AirSim is being developed  as a platform for AI research to experiment with deep learning, computer vision and reinforcement learning algorithms for autonomous vehicles.

[CARLA](https://github.com/carla-simulator/carla) is an open-source simulator for autonomous driving research. CARLA has been developed from the ground up to support development, training, and validation of autonomous driving systems. In addition to open-source code and protocols, CARLA provides open digital assets (urban layouts, buildings, vehicles) that were created for this purpose and can be used freely.

[ROS/ROS2 bridge for CARLA(package)](https://github.com/carla-simulator/ros-bridge) is a bridge that enables two-way communication between ROS and CARLA. The information from the CARLA server is translated to ROS topics. In the same way, the messages sent between nodes in ROS get translated to commands to be applied in CARLA.

[XGBoost](https://xgboost.readthedocs.io/) is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework. XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems in a fast and accurate way. It supports distributed training on multiple machines, including AWS, GCE, Azure, and Yarn clusters. Also, it can be integrated with Flink, Spark and other cloud dataflow systems.

[LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) is an integrated software for support vector classification, (C-SVC, nu-SVC), regression (epsilon-SVR, nu-SVR) and distribution estimation (one-class SVM). It supports multi-class classification.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.

[Automated Driving Toolbox™](https://www.mathworks.com/products/automated-driving.html) is a MATLAB tool that provides algorithms and tools for designing, simulating, and testing ADAS and autonomous driving systems. You can design and test vision and lidar perception systems, as well as sensor fusion, path planning, and vehicle controllers. Visualization tools include a bird’s-eye-view plot and scope for sensor coverage, detections and tracks, and displays for video, lidar, and maps. The toolbox lets you import and work with HERE HD Live Map data and OpenDRIVE® road networks. It also provides reference application examples for common ADAS and automated driving features, including FCW, AEB, ACC, LKA, and parking valet. The toolbox supports C/C++ code generation for rapid prototyping and HIL testing, with support for sensor fusion, tracking, path planning, and vehicle controller algorithms.

[Navigation Toolbox™](https://www.mathworks.com/products/navigation.html) is a tool that provides algorithms and analysis tools for motion planning, simultaneous localization and mapping (SLAM), and inertial navigation. The toolbox includes customizable search and sampling-based path planners, as well as metrics for validating and comparing paths. You can create 2D and 3D map representations, generate maps using SLAM algorithms, and interactively visualize and debug map generation with the SLAM map builder app.

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Mapping Toolbox™](https://www.mathworks.com/products/mapping.html) is a tool that provides algorithms and functions for transforming geographic data and creating map displays. You can visualize your data in a geographic context, build map displays from more than 60 map projections, and transform data from a variety of sources into a consistent geographic coordinate system.

[UAV Toolbox](https://www.mathworks.com/products/uav.html) is an application that provides tools and reference applications for designing, simulating, testing, and deploying unmanned aerial vehicle (UAV) and drone applications. You can design autonomous flight algorithms, UAV missions, and flight controllers. The Flight Log Analyzer app lets you interactively analyze 3D flight paths, telemetry information, and sensor readings from common flight log formats.

[Parallel Computing Toolbox™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you solve computationally and data-intensive problems using multicore processors, GPUs, and computer clusters. High-level constructs such as parallel for-loops, special array types, and parallelized numerical algorithms enable you to parallelize MATLAB® applications without CUDA or MPI programming. The toolbox lets you use parallel-enabled functions in MATLAB and other toolboxes. You can use the toolbox with Simulink® to run multiple simulations of a model in parallel. Programs and models can run in both interactive and batch modes.

[ROS Toolbox](https://www.mathworks.com/products/ros.html) is a tool that provides an interface connecting MATLAB® and Simulink® with the Robot Operating System (ROS and ROS 2), enabling you to create a network of ROS nodes. The toolbox includes MATLAB functions and Simulink blocks to import, analyze, and play back ROS data recorded in rosbag files. You can also connect to a live ROS network to access ROS messages.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Image Processing Toolbox™](https://www.mathworks.com/products/image.html) is a tool that provides a comprehensive set of reference-standard algorithms and workflow apps for image processing, analysis, visualization, and algorithm development. You can perform image segmentation, image enhancement, noise reduction, geometric transformations, image registration, and 3D image processing.

[Computer Vision Toolbox™](https://www.mathworks.com/products/computer-vision.html) is a tool that provides algorithms, functions, and apps for designing and testing computer vision, 3D vision, and video processing systems. You can perform object detection and tracking, as well as feature detection, extraction, and matching. You can automate calibration workflows for single, stereo, and fisheye cameras. For 3D vision, the toolbox supports visual and point cloud SLAM, stereo vision, structure from motion, and point cloud processing.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) is a tool that provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Deep Learning Toolbox™](https://www.mathworks.com/products/deep-learning.html) is a tool that provides a framework for designing and implementing deep neural networks with algorithms, pretrained models, and apps. You can use convolutional neural networks (ConvNets, CNNs) and long short-term memory (LSTM) networks to perform classification and regression on image, time-series, and text data. You can build network architectures such as generative adversarial networks (GANs) and Siamese networks using automatic differentiation, custom training loops, and shared weights. With the Deep Network Designer app, you can design, analyze, and train networks graphically. It can exchange models with TensorFlow™ and PyTorch through the ONNX format and import models from TensorFlow-Keras and Caffe. The toolbox supports transfer learning with DarkNet-53, ResNet-50, NASNet, SqueezeNet and many other pretrained models.

[Reinforcement Learning Toolbox™](https://www.mathworks.com/products/reinforcement-learning.html) is a tool that provides an app, functions, and a Simulink® block for training policies using reinforcement learning algorithms, including DQN, PPO, SAC, and DDPG. You can use these policies to implement controllers and decision-making algorithms for complex applications such as resource allocation, robotics, and autonomous systems.

[Deep Learning HDL Toolbox™](https://www.mathworks.com/products/deep-learning-hdl.html) is a tool that provides functions and tools to prototype and implement deep learning networks on FPGAs and SoCs. It provides pre-built bitstreams for running a variety of deep learning networks on supported Xilinx® and Intel® FPGA and SoC devices. Profiling and estimation tools let you customize a deep learning network by exploring design, performance, and resource utilization tradeoffs.

[Model Predictive Control Toolbox™](https://www.mathworks.com/products/model-predictive-control.html) is a tool that provides functions, an app, and Simulink® blocks for designing and simulating controllers using linear and nonlinear model predictive control (MPC). The toolbox lets you specify plant and disturbance models, horizons, constraints, and weights. By running closed-loop simulations, you can evaluate controller performance.

[Predictive Maintenance Toolbox™](https://www.mathworks.com/products/predictive-maintenance.html)  is a tool that lets you manage sensor data, design condition indicators, and estimate the remaining useful life (RUL) of a machine. The toolbox provides functions and an interactive app for exploring, extracting, and ranking features using data-based and model-based techniques, including statistical, spectral, and time-series analysis.

[Vision HDL Toolbox™](https://www.mathworks.com/products/vision-hdl.html) is a tool that provides pixel-streaming algorithms for the design and implementation of vision systems on FPGAs and ASICs. It provides a design framework that supports a diverse set of interface types, frame sizes, and frame rates. The image processing, video, and computer vision algorithms in the toolbox use an architecture appropriate for HDL implementations.

# Computer Vision Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129494417-b0ee8192-ac41-4a6d-8e1d-4761ffc8bab1.png">
  <br />
</p>

## Computer Vision Learning Resources

[Computer Vision](https://azure.microsoft.com/en-us/overview/what-is-computer-vision/) is a field of Artificial Intelligence (AI) that focuses on enabling computers to identify and understand objects and people in images and videos.

[OpenCV Courses](https://opencv.org/courses/)

[Exploring Computer Vision in Microsoft Azure](https://docs.microsoft.com/en-us/learn/paths/explore-computer-vision-microsoft-azure/)

[Top Computer Vision Courses Online | Coursera](https://www.coursera.org/courses?languages=en&query=computer%20vision)

[Top Computer Vision Courses Online | Udemy](https://www.udemy.com/topic/computer-vision/)

[Learn Computer Vision with Online Courses and Lessons | edX](https://www.edx.org/learn/computer-vision)

[Computer Vision and Image Processing Fundamentals | edX](https://www.edx.org/course/computer-vision-and-image-processing-fundamentals)

[Introduction to Computer Vision Courses | Udacity](https://www.udacity.com/course/introduction-to-computer-vision--ud810)

[Computer Vision Nanodegree program | Udacity](https://www.udacity.com/course/computer-vision-nanodegree--nd891)

[Machine Vision Course |MIT Open Courseware ](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-801-machine-vision-fall-2004/)

[Computer Vision Training Courses | NobleProg](https://www.nobleprog.com/computer-vision-training)

[Visual Computing Graduate Program | Stanford Online](https://online.stanford.edu/programs/visual-computing-graduate-program)

## Computer Vision Tools, Libraries, and Frameworks

[OpenCV](https://opencv.org) is a highly optimized library with focus on real-time computer vision applications. The C++, Python, and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Microsoft Cognitive Toolkit (CNTK)](https://docs.microsoft.com/en-us/cognitive-toolkit/) is an open-source toolkit for commercial-grade distributed deep learning. It describes neural networks as a series of computational steps via a directed graph. CNTK allows the user to easily realize and combine popular model types such as feed-forward DNNs, convolutional neural networks (CNNs) and recurrent neural networks (RNNs/LSTMs). CNTK implements stochastic gradient descent (SGD, error backpropagation) learning with automatic differentiation and parallelization across multiple GPUs and servers.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a Python module for machine learning built on top of SciPy, NumPy, and matplotlib, making it easier to apply robust and simple implementations of many popular machine learning algorithms.

[NVIDIA cuDNN](https://developer.nvidia.com/cudnn) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers. cuDNN accelerates widely used deep learning frameworks, including [Caffe2](https://caffe2.ai/), [Chainer](https://chainer.org/), [Keras](https://keras.io/), [MATLAB](https://www.mathworks.com/solutions/deep-learning.html), [MxNet](https://mxnet.incubator.apache.org/), [PyTorch](https://pytorch.org/), and [TensorFlow](https://www.tensorflow.org/).

[Automated Driving Toolbox™](https://www.mathworks.com/products/automated-driving.html) is a MATLAB tool that provides algorithms and tools for designing, simulating, and testing ADAS and autonomous driving systems. You can design and test vision and lidar perception systems, as well as sensor fusion, path planning, and vehicle controllers. Visualization tools include a bird’s-eye-view plot and scope for sensor coverage, detections and tracks, and displays for video, lidar, and maps. The toolbox lets you import and work with HERE HD Live Map data and OpenDRIVE® road networks. It also provides reference application examples for common ADAS and automated driving features, including FCW, AEB, ACC, LKA, and parking valet. The toolbox supports C/C++ code generation for rapid prototyping and HIL testing, with support for sensor fusion, tracking, path planning, and vehicle controller algorithms.

[LRSLibrary](https://github.com/andrewssobral/lrslibrary) is a Low-Rank and Sparse Tools for Background Modeling and Subtraction in Videos. The library was designed for moving object detection in videos, but it can be also used for other computer vision and machine learning problems.

[Image Processing Toolbox™](https://www.mathworks.com/products/image.html) is a tool that provides a comprehensive set of reference-standard algorithms and workflow apps for image processing, analysis, visualization, and algorithm development. You can perform image segmentation, image enhancement, noise reduction, geometric transformations, image registration, and 3D image processing.

[Computer Vision Toolbox™](https://www.mathworks.com/products/computer-vision.html) is a tool that provides algorithms, functions, and apps for designing and testing computer vision, 3D vision, and video processing systems. You can perform object detection and tracking, as well as feature detection, extraction, and matching. You can automate calibration workflows for single, stereo, and fisheye cameras. For 3D vision, the toolbox supports visual and point cloud SLAM, stereo vision, structure from motion, and point cloud processing.

[Statistics and Machine Learning Toolbox™](https://www.mathworks.com/products/statistics.html) is a tool that provides functions and apps to describe, analyze, and model data. You can use descriptive statistics, visualizations, and clustering for exploratory data analysis; fit probability distributions to data; generate random numbers for Monte Carlo simulations, and perform hypothesis tests. Regression and classification algorithms let you draw inferences from data and build predictive models either interactively, using the Classification and Regression Learner apps, or programmatically, using AutoML.

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Mapping Toolbox™](https://www.mathworks.com/products/mapping.html) is a tool that provides algorithms and functions for transforming geographic data and creating map displays. You can visualize your data in a geographic context, build map displays from more than 60 map projections, and transform data from a variety of sources into a consistent geographic coordinate system.

[UAV Toolbox](https://www.mathworks.com/products/uav.html) is an application that provides tools and reference applications for designing, simulating, testing, and deploying unmanned aerial vehicle (UAV) and drone applications. You can design autonomous flight algorithms, UAV missions, and flight controllers. The Flight Log Analyzer app lets you interactively analyze 3D flight paths, telemetry information, and sensor readings from common flight log formats.

[Parallel Computing Toolbox™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you solve computationally and data-intensive problems using multicore processors, GPUs, and computer clusters. High-level constructs such as parallel for-loops, special array types, and parallelized numerical algorithms enable you to parallelize MATLAB® applications without CUDA or MPI programming. The toolbox lets you use parallel-enabled functions in MATLAB and other toolboxes. You can use the toolbox with Simulink® to run multiple simulations of a model in parallel. Programs and models can run in both interactive and batch modes.

[Partial Differential Equation Toolbox™](https://www.mathworks.com/products/pde.html) is a tool that provides functions for solving structural mechanics, heat transfer, and general partial differential equations (PDEs) using finite element analysis.

[ROS Toolbox](https://www.mathworks.com/products/ros.html) is a tool that provides an interface connecting MATLAB® and Simulink® with the Robot Operating System (ROS and ROS 2), enabling you to create a network of ROS nodes. The toolbox includes MATLAB functions and Simulink blocks to import, analyze, and play back ROS data recorded in rosbag files. You can also connect to a live ROS network to access ROS messages.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Deep Learning Toolbox™](https://www.mathworks.com/products/deep-learning.html) is a tool that provides a framework for designing and implementing deep neural networks with algorithms, pretrained models, and apps. You can use convolutional neural networks (ConvNets, CNNs) and long short-term memory (LSTM) networks to perform classification and regression on image, time-series, and text data. You can build network architectures such as generative adversarial networks (GANs) and Siamese networks using automatic differentiation, custom training loops, and shared weights. With the Deep Network Designer app, you can design, analyze, and train networks graphically. It can exchange models with TensorFlow™ and PyTorch through the ONNX format and import models from TensorFlow-Keras and Caffe. The toolbox supports transfer learning with DarkNet-53, ResNet-50, NASNet, SqueezeNet and many other pretrained models.

[Reinforcement Learning Toolbox™](https://www.mathworks.com/products/reinforcement-learning.html) is a tool that provides an app, functions, and a Simulink® block for training policies using reinforcement learning algorithms, including DQN, PPO, SAC, and DDPG. You can use these policies to implement controllers and decision-making algorithms for complex applications such as resource allocation, robotics, and autonomous systems.

[Deep Learning HDL Toolbox™](https://www.mathworks.com/products/deep-learning-hdl.html) is a tool that provides functions and tools to prototype and implement deep learning networks on FPGAs and SoCs. It provides pre-built bitstreams for running a variety of deep learning networks on supported Xilinx® and Intel® FPGA and SoC devices. Profiling and estimation tools let you customize a deep learning network by exploring design, performance, and resource utilization tradeoffs.

[Model Predictive Control Toolbox™](https://www.mathworks.com/products/model-predictive-control.html) is a tool that provides functions, an app, and Simulink® blocks for designing and simulating controllers using linear and nonlinear model predictive control (MPC). The toolbox lets you specify plant and disturbance models, horizons, constraints, and weights. By running closed-loop simulations, you can evaluate controller performance.

[Vision HDL Toolbox™](https://www.mathworks.com/products/vision-hdl.html) is a tool that provides pixel-streaming algorithms for the design and implementation of vision systems on FPGAs and ASICs. It provides a design framework that supports a diverse set of interface types, frame sizes, and frame rates. The image processing, video, and computer vision algorithms in the toolbox use an architecture appropriate for HDL implementations.

[Data Acquisition Toolbox™](https://www.mathworks.com/products/data-acquisition.html) is a tool that provides apps and functions for configuring data acquisition hardware, reading data into MATLAB® and Simulink®, and writing data to DAQ analog and digital output channels. The toolbox supports a variety of DAQ hardware, including USB, PCI, PCI Express®, PXI®, and PXI Express® devices, from National Instruments® and other vendors.

[Microsoft AirSim](https://microsoft.github.io/AirSim/lidar.html) is a simulator for drones, cars and more, built on Unreal Engine (with an experimental Unity release). AirSim is open-source, cross platform, and supports [software-in-the-loop simulation](https://www.mathworks.com/help///ecoder/software-in-the-loop-sil-simulation.html) with popular flight controllers such as PX4 & ArduPilot and [hardware-in-loop](https://www.ni.com/en-us/innovations/white-papers/17/what-is-hardware-in-the-loop-.html) with PX4 for physically and visually realistic simulations. It is developed as an Unreal plugin that can simply be dropped into any Unreal environment. AirSim is being developed  as a platform for AI research to experiment with deep learning, computer vision and reinforcement learning algorithms for autonomous vehicles.

# Algorithms
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

**[NIST Fingerprint Image Quality algorithms](https://www.nist.gov/services-resources/software/nist-biometric-image-software-nbis#NFIQ)**

[Fuzzy logic](https://www.investopedia.com/terms/f/fuzzy-logic.asp) is a heuristic approach that allows for more advanced decision-tree processing and better integration with rules-based programming.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123861872-858dce80-d8dc-11eb-9a2c-51205d1541e9.png">
  <br />
</p>

**Architecture of a Fuzzy Logic System. Source: [ResearchGate](https://www.researchgate.net/figure/Architecture-of-a-fuzzy-logic-system_fig2_309452475)**

[Support Vector Machine (SVM)](https://web.stanford.edu/~hastie/MOOC-Slides/svm.pdf) is a supervised machine learning model that uses classification algorithms for two-group classification problems.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858065-ec5cb900-d8d7-11eb-81c5-c6a8feefa84f.png">
  <br />
</p>

**Support Vector Machine (SVM). Source:[OpenClipArt](https://openclipart.org/detail/182977/svm-support-vector-machines)**

[Neural networks](https://www.ibm.com/cloud/learn/neural-networks) are a subset of machine learning and are at the heart of deep learning algorithms. The name/structure is inspired by the human brain copying the process that biological neurons/nodes signal to one another.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858036-e5ce4180-d8d7-11eb-8c52-43d7c7e6e3c4.png">
  <br />
</p>

**Deep neural network. Source: [IBM](https://www.ibm.com/cloud/learn/neural-networks)**

[Convolutional Neural Networks (R-CNN)](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-convolutional-neural-networks) is an object detection algorithm that first segments the image to find potential relevant bounding boxes and then run the detection algorithm to find most probable objects in those bounding boxes.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858026-e36be780-d8d7-11eb-9034-8859d6f09490.png">
  <br />
</p>

**Convolutional Neural Networks. Source:[CS231n](https://cs231n.github.io/convolutional-networks/#conv)**

[Recurrent neural networks (RNNs)](https://www.ibm.com/cloud/learn/recurrent-neural-networks) is a type of artificial neural network which uses sequential data or time series data.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858062-ebc42280-d8d7-11eb-9252-97e058bda8bd.png">
  <br />
</p>

**Recurrent Neural Networks. Source: [Slideteam](https://www.slideteam.net/recurrent-neural-networks-rnns-ppt-powerpoint-presentation-file-templates.html)**

[Multilayer Perceptrons (MLPs)](https://deepai.org/machine-learning-glossary-and-terms/multilayer-perceptron) is multi-layer neural networks composed of multiple layers of [perceptrons](https://en.wikipedia.org/wiki/Perceptron) with a threshold activation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858053-e8c93200-d8d7-11eb-844c-60463ecf662c.png">
  <br />
</p>

**Multilayer Perceptrons. Source: [DeepAI](https://deepai.org/machine-learning-glossary-and-terms/multilayer-perceptron)**

[Random forest](https://www.ibm.com/cloud/learn/random-forest) is a commonly-used machine learning algorithm, which combines the output of multiple decision trees to reach a single result. A decision tree in a forest cannot be pruned for sampling and therefore, prediction selection. Its ease of use and flexibility have fueled its adoption, as it handles both classification and regression problems.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398881-fe21d000-dccc-11eb-8f5f-0a0730d85d55.png">
  <br />
</p>

**Random forest. Source: [wikimedia](https://community.tibco.com/wiki/random-forest-template-tibco-spotfirer-wiki-page)**

[Decision trees](https://www.cs.cmu.edu/~bhiksha/courses/10-601/decisiontrees/) are tree-structured models for classification and regression.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398883-ffeb9380-dccc-11eb-9adb-66729a353132.png">
  <br />
</p>

***Decision Trees. Source: [CMU](http://www.cs.cmu.edu/~bhiksha/courses/10-601/decisiontrees/)*

[Naive Bayes](https://en.wikipedia.org/wiki/Naive_Bayes_classifier) is a machine learning algorithm that is used solved calssification problems. It's based on applying [Bayes' theorem](https://www.mathsisfun.com/data/bayes-theorem.html) with strong independence assumptions between the features.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398885-00842a00-dccd-11eb-89c1-bd4c1adbf305.png">
  <br />
</p>

**Bayes' theorem. Source:[mathisfun](https://www.mathsisfun.com/data/bayes-theorem.html)**


# Machine Learning
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/96352527-ad077880-1078-11eb-98b7-da1c0586cf0e.png">
  <br />
</p>

<img src="https://user-images.githubusercontent.com/45159366/105645196-dccfd480-5e4e-11eb-95d1-c5eb560b72fd.jpeg">

**Machine Learning/Deep Learning Frameworks.**

## Learning Resources for ML

[Machine Learning](https://www.ibm.com/cloud/learn/machine-learning) is a branch of artificial intelligence (AI) focused on building apps using algorithms that learn from data models and improve their accuracy over time without needing to be programmed.

[Machine Learning by Stanford University from Coursera](https://www.coursera.org/learn/machine-learning)

[AWS Training and Certification for Machine Learning (ML) Courses](https://aws.amazon.com/training/learning-paths/machine-learning/)

[Machine Learning Scholarship Program for Microsoft Azure from Udacity](https://www.udacity.com/scholarships/machine-learning-scholarship-microsoft-azure)

[Microsoft Certified: Azure Data Scientist Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-data-scientist)

[Microsoft Certified: Azure AI Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-ai-engineer)

[Azure Machine Learning training and deployment](https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/azure-machine-learning)

[Learning Machine learning and artificial intelligence from Google Cloud Training](https://cloud.google.com/training/machinelearning-ai)

[Machine Learning Crash Course for Google Cloud](https://developers.google.com/machine-learning/crash-course/)

[JupyterLab](https://jupyterlab.readthedocs.io/)

[Scheduling Jupyter notebooks on Amazon SageMaker ephemeral instances](https://aws.amazon.com/blogs/machine-learning/scheduling-jupyter-notebooks-on-sagemaker-ephemeral-instances/)

[How to run Jupyter Notebooks in your Azure Machine Learning workspace](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-run-jupyter-notebooks)

[Machine Learning Courses Online from Udemy](https://www.udemy.com/topic/machine-learning/)

[Machine Learning Courses Online from Coursera](https://www.coursera.org/courses?query=machine%20learning&)

[Learn Machine Learning with Online Courses and Classes from edX](https://www.edx.org/learn/machine-learning)

## ML Frameworks, Libraries, and Tools

[TensorFlow](https://www.tensorflow.org) is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

[Keras](https://keras.io) is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.It was developed with a focus on enabling fast experimentation. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML.

[PyTorch](https://pytorch.org) is a library for deep learning on irregular input data such as graphs, point clouds, and manifolds. Primarily developed by Facebook's AI Research lab.

[Amazon SageMaker](https://aws.amazon.com/sagemaker/) is a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high quality models.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a fast and collaborative Apache Spark-based big data analytics service designed for data science and data engineering. Azure Databricks, sets up your Apache Spark environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Microsoft Cognitive Toolkit (CNTK)](https://docs.microsoft.com/en-us/cognitive-toolkit/) is an open-source toolkit for commercial-grade distributed deep learning. It describes neural networks as a series of computational steps via a directed graph. CNTK allows the user to easily realize and combine popular model types such as feed-forward DNNs, convolutional neural networks (CNNs) and recurrent neural networks (RNNs/LSTMs). CNTK implements stochastic gradient descent (SGD, error backpropagation) learning with automatic differentiation and parallelization across multiple GPUs and servers.

[Apple CoreML](https://developer.apple.com/documentation/coreml) is a framework that helps integrate machine learning models into your app. Core ML provides a unified representation for all models. Your app uses Core ML APIs and user data to make predictions, and to train or fine-tune models, all on the user's device. A model is the result of applying a machine learning algorithm to a set of training data. You use a model to make predictions based on new input data.

[Tensorflow_macOS](https://github.com/apple/tensorflow_macos) is a Mac-optimized version of TensorFlow and TensorFlow Addons for macOS 11.0+ accelerated using Apple's ML Compute framework.

[Apache OpenNLP](https://opennlp.apache.org/) is an open-source library for a machine learning based toolkit used in the processing of natural language text. It features an API for use cases like [Named Entity Recognition](https://en.wikipedia.org/wiki/Named-entity_recognition), [Sentence Detection](), [POS(Part-Of-Speech) tagging](https://en.wikipedia.org/wiki/Part-of-speech_tagging), [Tokenization](https://en.wikipedia.org/wiki/Tokenization_(data_security)) [Feature extraction](https://en.wikipedia.org/wiki/Feature_extraction), [Chunking](https://en.wikipedia.org/wiki/Chunking_(psychology)), [Parsing](https://en.wikipedia.org/wiki/Parsing), and [Coreference resolution](https://en.wikipedia.org/wiki/Coreference).

[Apache Airflow](https://airflow.apache.org) is an open-source workflow management platform created by the community to programmatically author, schedule and monitor workflows. Install. Principles. Scalable. Airflow has a modular architecture and uses a message queue to orchestrate an arbitrary number of workers. Airflow is ready to scale to infinity.

[Open Neural Network Exchange(ONNX)](https://github.com/onnx) is an open ecosystem that empowers AI developers to choose the right tools as their project evolves. ONNX provides an open source format for AI models, both deep learning and traditional ML. It defines an extensible computation graph model, as well as definitions of built-in operators and standard data types.

[Apache MXNet](https://mxnet.apache.org/) is a deep learning framework designed for both efficiency and flexibility. It allows you to mix symbolic and imperative programming to maximize efficiency and productivity. At its core, MXNet contains a dynamic dependency scheduler that automatically parallelizes both symbolic and imperative operations on the fly. A graph optimization layer on top of that makes symbolic execution fast and memory efficient. MXNet is portable and lightweight, scaling effectively to multiple GPUs and multiple machines. Support for Python, R, Julia, Scala, Go, Javascript and more.

[AutoGluon](https://autogluon.mxnet.io/index.html) is toolkit for Deep learning that automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy deep learning models on tabular, image, and text data.

[Anaconda](https://www.anaconda.com/) is a very popular Data Science platform for machine learning and deep learning that enables users to develop models, train them, and deploy them.

[PlaidML](https://github.com/plaidml/plaidml) is an advanced and portable tensor compiler for enabling deep learning on laptops, embedded devices, or other devices where the available computing hardware is not well supported or the available software stack contains unpalatable license restrictions.

[OpenCV](https://opencv.org) is a highly optimized library with focus on real-time computer vision applications. The C++, Python, and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a Python module for machine learning built on top of SciPy, NumPy, and matplotlib, making it easier to apply robust and simple implementations of many popular machine learning algorithms.

[Weka](https://www.cs.waikato.ac.nz/ml/weka/) is an open source machine learning software that can be accessed through a graphical user interface, standard terminal applications, or a Java API. It is widely used for teaching, research, and industrial applications, contains a plethora of built-in tools for standard machine learning tasks, and additionally gives transparent access to well-known toolboxes such as scikit-learn, R, and Deeplearning4j.

[Caffe](https://github.com/BVLC/caffe) is a deep learning framework made with expression, speed, and modularity in mind. It is developed by Berkeley AI Research (BAIR)/The Berkeley Vision and Learning Center (BVLC) and community contributors.

[Theano](https://github.com/Theano/Theano) is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently including tight integration with NumPy.

[nGraph](https://github.com/NervanaSystems/ngraph) is an open source C++ library, compiler and runtime for Deep Learning. The nGraph Compiler aims to accelerate developing AI workloads using any deep learning framework and deploying to a variety of hardware targets.It provides the freedom, performance, and ease-of-use to AI developers.

[NVIDIA cuDNN](https://developer.nvidia.com/cudnn) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers. cuDNN accelerates widely used deep learning frameworks, including [Caffe2](https://caffe2.ai/), [Chainer](https://chainer.org/), [Keras](https://keras.io/), [MATLAB](https://www.mathworks.com/solutions/deep-learning.html), [MxNet](https://mxnet.incubator.apache.org/), [PyTorch](https://pytorch.org/), and [TensorFlow](https://www.tensorflow.org/).

[Jupyter Notebook](https://jupyter.org/) is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Jupyter is used widely in industries that do data cleaning and transformation, numerical simulation, statistical modeling, data visualization, data science, and machine learning.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for large-scale data processing. It provides high-level APIs in Scala, Java, Python, and R, and an optimized engine that supports general computation graphs for data analysis. It also supports a rich set of higher-level tools including Spark SQL for SQL and DataFrames, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for stream processing.

[Apache Spark Connector for SQL Server and Azure SQL](https://github.com/microsoft/sql-spark-connector) is a high-performance connector that enables you to use transactional data in big data analytics and persists results for ad-hoc queries or reporting. The connector allows you to use any SQL database, on-premises or in the cloud, as an input data source or output data sink for Spark jobs.

[Apache PredictionIO](https://predictionio.apache.org/) is an open source machine learning framework for developers, data scientists, and end users. It supports event collection, deployment of algorithms, evaluation, querying predictive results via REST APIs. It is based on scalable open source services like Hadoop, HBase (and other DBs), Elasticsearch, Spark and implements what is called a Lambda Architecture.

[Cluster Manager for Apache Kafka(CMAK)](https://github.com/yahoo/CMAK) is a tool for managing [Apache Kafka](https://kafka.apache.org/) clusters.

[BigDL](https://bigdl-project.github.io/) is a distributed deep learning library for Apache Spark. With BigDL, users can write their deep learning applications as standard Spark programs, which can directly run on top of existing Spark or Hadoop clusters.

[Eclipse Deeplearning4J (DL4J)](https://deeplearning4j.konduit.ai/) is a set of projects intended to support all the needs of a JVM-based(Scala, Kotlin, Clojure, and Groovy) deep learning application. This means starting with the raw data, loading and preprocessing it from wherever and whatever format it is in to building and tuning a wide variety of simple and complex deep learning networks.

[Tensorman](https://github.com/pop-os/tensorman) is a utility for easy management of Tensorflow containers by developed by [System76]( https://system76.com).Tensorman allows Tensorflow to operate in an isolated environment that is contained from the rest of the system. This virtual environment can operate independent of the base system, allowing you to use any version of Tensorflow on any version of a Linux distribution that supports the Docker runtime.

[Numba](https://github.com/numba/numba) is an open source, NumPy-aware optimizing compiler for Python sponsored by Anaconda, Inc. It uses the LLVM compiler project to generate machine code from Python syntax. Numba can compile a large subset of numerically-focused Python, including many NumPy functions. Additionally, Numba has support for automatic parallelization of loops, generation of GPU-accelerated code, and creation of ufuncs and C callbacks.

[Chainer](https://chainer.org/) is a Python-based deep learning framework aiming at flexibility. It provides automatic differentiation APIs based on the define-by-run approach (dynamic computational graphs) as well as object-oriented high-level APIs to build and train neural networks. It also supports CUDA/cuDNN using [CuPy](https://github.com/cupy/cupy) for high performance training and inference.

[XGBoost](https://xgboost.readthedocs.io/) is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework. XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems in a fast and accurate way. It supports distributed training on multiple machines, including AWS, GCE, Azure, and Yarn clusters. Also, it can be integrated with Flink, Spark and other cloud dataflow systems.

[cuML](https://github.com/rapidsai/cuml) is a suite of libraries that implement machine learning algorithms and mathematical primitives functions that share compatible APIs with other RAPIDS projects. cuML enables data scientists, researchers, and software engineers to run traditional tabular ML tasks on GPUs without going into the details of CUDA programming. In most cases, cuML's Python API matches the API from scikit-learn.

# CUDA Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306481-e17b8f00-ff27-11ea-832f-c85374acb3b1.png">
  <br />
</p>


<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/117718735-55a23480-b191-11eb-874d-e690d09cd490.png">
  <br />
</p>

**CUDA Toolkit. Source: [NVIDIA Developer CUDA](https://developer.nvidia.com/cuda-zone)**

## CUDA Learning Resources

[CUDA](https://developer.nvidia.com/cuda-zone) is a parallel computing platform and programming model developed by NVIDIA for general computing on graphical processing units (GPUs). With CUDA, developers are able to dramatically speed up computing applications by harnessing the power of GPUs. In GPU-accelerated applications, the sequential part of the workload runs on the CPU, which is optimized for single-threaded. The compute intensive portion of the application runs on thousands of GPU cores in parallel. When using CUDA, developers can program in popular languages such as C, C++, Fortran, Python and MATLAB.

[CUDA Toolkit Documentation](https://docs.nvidia.com/cuda/index.html)

[CUDA Quick Start Guide](https://docs.nvidia.com/cuda/cuda-quick-start-guide/index.html)

[CUDA on WSL](https://docs.nvidia.com/cuda/wsl-user-guide/index.html)

[CUDA GPU support for TensorFlow](https://www.tensorflow.org/install/gpu)

[NVIDIA Deep Learning cuDNN Documentation](https://docs.nvidia.com/deeplearning/cudnn/api/index.html)

[NVIDIA GPU Cloud Documentation](https://docs.nvidia.com/ngc/ngc-introduction/index.html)

[NVIDIA NGC](https://ngc.nvidia.com/) is a hub for GPU-optimized software for deep learning, machine learning, and high-performance computing (HPC) workloads.

[NVIDIA NGC Containers](https://www.nvidia.com/en-us/gpu-cloud/containers/) is a registry that provides researchers, data scientists, and developers with simple access to a comprehensive catalog of GPU-accelerated software for AI, machine learning and HPC. These containers take full advantage of NVIDIA GPUs on-premises and in the cloud.

## CUDA Tools Libraries, and Frameworks

[CUDA Toolkit](https://developer.nvidia.com/cuda-downloads) is a collection of tools & libraries that provide a development environment for creating high performance GPU-accelerated applications. The CUDA Toolkit allows you can develop, optimize, and deploy your applications on GPU-accelerated embedded systems, desktop workstations, enterprise data centers, cloud-based platforms and HPC supercomputers. The toolkit includes GPU-accelerated libraries, debugging and optimization tools, a C/C++ compiler, and a runtime library to build and deploy your application on major architectures including x86, Arm and POWER.

[NVIDIA cuDNN](https://developer.nvidia.com/cudnn) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers. cuDNN accelerates widely used deep learning frameworks, including [Caffe2](https://caffe2.ai/), [Chainer](https://chainer.org/), [Keras](https://keras.io/), [MATLAB](https://www.mathworks.com/solutions/deep-learning.html), [MxNet](https://mxnet.incubator.apache.org/), [PyTorch](https://pytorch.org/), and [TensorFlow](https://www.tensorflow.org/).

[CUDA-X HPC](https://www.nvidia.com/en-us/technologies/cuda-x/) is a collection of libraries, tools, compilers and APIs that help developers solve the world's most challenging problems. CUDA-X HPC includes highly tuned kernels essential for high-performance computing (HPC).

[NVIDIA Container Toolkit](https://github.com/NVIDIA/nvidia-docker) is a collection of tools & libraries that allows users to build and run GPU accelerated Docker containers. The toolkit includes a container runtime [library](https://github.com/NVIDIA/libnvidia-container) and utilities to automatically configure containers to leverage NVIDIA GPUs.

[Minkowski Engine](https://nvidia.github.io/MinkowskiEngine) is an auto-differentiation library for sparse tensors. It supports all standard neural network layers such as convolution, pooling, unpooling, and broadcasting operations for sparse tensors.

[CUTLASS](https://github.com/NVIDIA/cutlass) is a collection of CUDA C++ template abstractions for implementing high-performance matrix-multiplication (GEMM) at all levels and scales within CUDA. It incorporates strategies for hierarchical decomposition and data movement similar to those used to implement cuBLAS.

[CUB](https://github.com/NVIDIA/cub) is a cooperative primitives for CUDA C++ kernel authors.

[Tensorman](https://github.com/pop-os/tensorman) is a utility for easy management of Tensorflow containers by developed by [System76]( https://system76.com).Tensorman allows Tensorflow to operate in an isolated environment that is contained from the rest of the system. This virtual environment can operate independent of the base system, allowing you to use any version of Tensorflow on any version of a Linux distribution that supports the Docker runtime.

[Numba](https://github.com/numba/numba) is an open source, NumPy-aware optimizing compiler for Python sponsored by Anaconda, Inc. It uses the LLVM compiler project to generate machine code from Python syntax. Numba can compile a large subset of numerically-focused Python, including many NumPy functions. Additionally, Numba has support for automatic parallelization of loops, generation of GPU-accelerated code, and creation of ufuncs and C callbacks.

[Chainer](https://chainer.org/) is a Python-based deep learning framework aiming at flexibility. It provides automatic differentiation APIs based on the define-by-run approach (dynamic computational graphs) as well as object-oriented high-level APIs to build and train neural networks. It also supports CUDA/cuDNN using [CuPy](https://github.com/cupy/cupy) for high performance training and inference.

[CuPy](https://cupy.dev/) is an implementation of NumPy-compatible multi-dimensional array on CUDA. CuPy consists of the core multi-dimensional array class, cupy.ndarray, and many functions on it. It supports a subset of numpy.ndarray interface.

[CatBoost](https://catboost.ai/) is a fast, scalable, high performance [Gradient Boosting](https://en.wikipedia.org/wiki/Gradient_boosting) on Decision Trees library, used for ranking, classification, regression and other machine learning tasks for Python, R, Java, C++. Supports computation on CPU and GPU.

[cuDF](https://rapids.ai/) is a GPU DataFrame library for loading, joining, aggregating, filtering, and otherwise manipulating data. cuDF provides a pandas-like API that will be familiar to data engineers & data scientists, so they can use it to easily accelerate their workflows without going into the details of CUDA programming.

[cuML](https://github.com/rapidsai/cuml) is a suite of libraries that implement machine learning algorithms and mathematical primitives functions that share compatible APIs with other RAPIDS projects. cuML enables data scientists, researchers, and software engineers to run traditional tabular ML tasks on GPUs without going into the details of CUDA programming. In most cases, cuML's Python API matches the API from scikit-learn.

[ArrayFire](https://arrayfire.com/) is a general-purpose library that simplifies the process of developing software that targets parallel and massively-parallel architectures including CPUs, GPUs, and other hardware acceleration devices.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs.

[AresDB](https://eng.uber.com/aresdb/) is a GPU-powered real-time analytics storage and query engine. It features low query latency, high data freshness and highly efficient in-memory and on disk storage management.

[Arraymancer](https://mratsim.github.io/Arraymancer/) is a tensor (N-dimensional array) project in Nim. The main focus is providing a fast and ergonomic CPU, Cuda and OpenCL ndarray library on which to build a scientific computing ecosystem.

[Kintinuous](https://github.com/mp3guy/Kintinuous) is a real-time dense visual SLAM system capable of producing high quality globally consistent point and mesh reconstructions over hundreds of metres in real-time with only a low-cost commodity RGB-D sensor.

[GraphVite](https://graphvite.io/) is a general graph embedding engine, dedicated to high-speed and large-scale embedding learning in various applications.

# MATLAB Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306473-de809e80-ff27-11ea-924b-0a6947ae38bc.png">
  <br />
</p>

## MATLAB Learning Resources

[MATLAB](https://www.mathworks.com/products/matlab.html) is a programming language that does numerical computing such as expressing matrix and array mathematics directly.

[MATLAB Documentation](https://www.mathworks.com/help/matlab/)

[Getting Started with MATLAB ](https://www.mathworks.com/help/matlab/getting-started-with-matlab.html)

[MATLAB and Simulink Training from MATLAB Academy](https://matlabacademy.mathworks.com)

[MathWorks Certification Program](https://www.mathworks.com/services/training/certification.html)

[MATLAB Online Courses from Udemy](https://www.udemy.com/topic/matlab/)

[MATLAB Online Courses from Coursera](https://www.coursera.org/courses?query=matlab)

[MATLAB Online Courses from edX](https://www.edx.org/learn/matlab)

[Building a MATLAB GUI](https://www.mathworks.com/discovery/matlab-gui.html)

[MATLAB Style Guidelines 2.0](https://www.mathworks.com/matlabcentral/fileexchange/46056-matlab-style-guidelines-2-0)

[Setting Up Git Source Control with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/set-up-git-source-control.html)

[Pull, Push and Fetch Files with Git with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/push-and-fetch-with-git.html)

[Create New Repository with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/add-folder-to-source-control.html)

[PRMLT](http://prml.github.io/) is Matlab code for machine learning algorithms in the PRML book.

## MATLAB Tools, Libraries, Frameworks

**[MATLAB and Simulink Services & Applications List](https://www.mathworks.com/products.html)**

[MATLAB in the Cloud](https://www.mathworks.com/solutions/cloud.html) is a service that allows you to run in cloud environments from [MathWorks Cloud](https://www.mathworks.com/solutions/cloud.html#browser) to [Public Clouds](https://www.mathworks.com/solutions/cloud.html#public-cloud) including [AWS](https://aws.amazon.com/) and [Azure](https://azure.microsoft.com/).

[MATLAB Online™](https://matlab.mathworks.com) is a service that allows to users to uilitize MATLAB and Simulink through a web browser such as Google Chrome.

[Simulink](https://www.mathworks.com/products/simulink.html) is a block diagram environment for Model-Based Design. It supports simulation, automatic code generation, and continuous testing of embedded systems.

[Simulink Online™](https://www.mathworks.com/products/simulink-online.html) is a service that provides access to Simulink through your web browser.

[MATLAB Drive™](https://www.mathworks.com/products/matlab-drive.html) is a service that gives you the ability to store, access, and work with your files from anywhere.

[MATLAB Parallel Server™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you scale MATLAB® programs and Simulink® simulations to clusters and clouds. You can prototype your programs and simulations on the desktop and then run them on clusters and clouds without recoding. MATLAB Parallel Server supports batch jobs, interactive parallel computations, and distributed computations with large matrices.

[MATLAB Schemer](https://github.com/scottclowe/matlab-schemer) is a MATLAB package makes it easy to change the color scheme (theme) of the MATLAB display and GUI.

[LRSLibrary](https://github.com/andrewssobral/lrslibrary) is a Low-Rank and Sparse Tools for Background Modeling and Subtraction in Videos. The library was designed for moving object detection in videos, but it can be also used for other computer vision and machine learning problems.

[Image Processing Toolbox™](https://www.mathworks.com/products/image.html) is a tool that provides a comprehensive set of reference-standard algorithms and workflow apps for image processing, analysis, visualization, and algorithm development. You can perform image segmentation, image enhancement, noise reduction, geometric transformations, image registration, and 3D image processing.

[Computer Vision Toolbox™](https://www.mathworks.com/products/computer-vision.html) is a tool that provides algorithms, functions, and apps for designing and testing computer vision, 3D vision, and video processing systems. You can perform object detection and tracking, as well as feature detection, extraction, and matching. You can automate calibration workflows for single, stereo, and fisheye cameras. For 3D vision, the toolbox supports visual and point cloud SLAM, stereo vision, structure from motion, and point cloud processing.

[Statistics and Machine Learning Toolbox™](https://www.mathworks.com/products/statistics.html) is a tool that provides functions and apps to describe, analyze, and model data. You can use descriptive statistics, visualizations, and clustering for exploratory data analysis; fit probability distributions to data; generate random numbers for Monte Carlo simulations, and perform hypothesis tests. Regression and classification algorithms let you draw inferences from data and build predictive models either interactively, using the Classification and Regression Learner apps, or programmatically, using AutoML.

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Mapping Toolbox™](https://www.mathworks.com/products/mapping.html) is a tool that provides algorithms and functions for transforming geographic data and creating map displays. You can visualize your data in a geographic context, build map displays from more than 60 map projections, and transform data from a variety of sources into a consistent geographic coordinate system.

[UAV Toolbox](https://www.mathworks.com/products/uav.html) is an application that provides tools and reference applications for designing, simulating, testing, and deploying unmanned aerial vehicle (UAV) and drone applications. You can design autonomous flight algorithms, UAV missions, and flight controllers. The Flight Log Analyzer app lets you interactively analyze 3D flight paths, telemetry information, and sensor readings from common flight log formats.

[Parallel Computing Toolbox™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you solve computationally and data-intensive problems using multicore processors, GPUs, and computer clusters. High-level constructs such as parallel for-loops, special array types, and parallelized numerical algorithms enable you to parallelize MATLAB® applications without CUDA or MPI programming. The toolbox lets you use parallel-enabled functions in MATLAB and other toolboxes. You can use the toolbox with Simulink® to run multiple simulations of a model in parallel. Programs and models can run in both interactive and batch modes.

[Partial Differential Equation Toolbox™](https://www.mathworks.com/products/pde.html) is a tool that provides functions for solving structural mechanics, heat transfer, and general partial differential equations (PDEs) using finite element analysis.

[ROS Toolbox](https://www.mathworks.com/products/ros.html) is a tool that provides an interface connecting MATLAB® and Simulink® with the Robot Operating System (ROS and ROS 2), enabling you to create a network of ROS nodes. The toolbox includes MATLAB functions and Simulink blocks to import, analyze, and play back ROS data recorded in rosbag files. You can also connect to a live ROS network to access ROS messages.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Deep Learning Toolbox™](https://www.mathworks.com/products/deep-learning.html) is a tool that provides a framework for designing and implementing deep neural networks with algorithms, pretrained models, and apps. You can use convolutional neural networks (ConvNets, CNNs) and long short-term memory (LSTM) networks to perform classification and regression on image, time-series, and text data. You can build network architectures such as generative adversarial networks (GANs) and Siamese networks using automatic differentiation, custom training loops, and shared weights. With the Deep Network Designer app, you can design, analyze, and train networks graphically. It can exchange models with TensorFlow™ and PyTorch through the ONNX format and import models from TensorFlow-Keras and Caffe. The toolbox supports transfer learning with DarkNet-53, ResNet-50, NASNet, SqueezeNet and many other pretrained models.

[Reinforcement Learning Toolbox™](https://www.mathworks.com/products/reinforcement-learning.html) is a tool that provides an app, functions, and a Simulink® block for training policies using reinforcement learning algorithms, including DQN, PPO, SAC, and DDPG. You can use these policies to implement controllers and decision-making algorithms for complex applications such as resource allocation, robotics, and autonomous systems.

[Deep Learning HDL Toolbox™](https://www.mathworks.com/products/deep-learning-hdl.html) is a tool that provides functions and tools to prototype and implement deep learning networks on FPGAs and SoCs. It provides pre-built bitstreams for running a variety of deep learning networks on supported Xilinx® and Intel® FPGA and SoC devices. Profiling and estimation tools let you customize a deep learning network by exploring design, performance, and resource utilization tradeoffs.

[Model Predictive Control Toolbox™](https://www.mathworks.com/products/model-predictive-control.html) is a tool that provides functions, an app, and Simulink® blocks for designing and simulating controllers using linear and nonlinear model predictive control (MPC). The toolbox lets you specify plant and disturbance models, horizons, constraints, and weights. By running closed-loop simulations, you can evaluate controller performance.

[Vision HDL Toolbox™](https://www.mathworks.com/products/vision-hdl.html) is a tool that provides pixel-streaming algorithms for the design and implementation of vision systems on FPGAs and ASICs. It provides a design framework that supports a diverse set of interface types, frame sizes, and frame rates. The image processing, video, and computer vision algorithms in the toolbox use an architecture appropriate for HDL implementations.

[SoC Blockset™](https://www.mathworks.com/products/soc.html) is a tool that provides Simulink® blocks and visualization tools for modeling, simulating, and analyzing hardware and software architectures for ASICs, FPGAs, and systems on a chip (SoC). You can build your system architecture using memory models, bus models, and I/O models, and simulate the architecture together with the algorithms.

[Wireless HDL Toolbox™](https://www.mathworks.com/products/wireless-hdl.html) is a tool that provides pre-verified, hardware-ready Simulink® blocks and subsystems for developing 5G, LTE, and custom OFDM-based wireless communication applications. It includes reference applications, IP blocks, and gateways between frame and sample-based processing.

[ThingSpeak™](https://www.mathworks.com/products/thingspeak.html) is an IoT analytics service that allows you to aggregate, visualize, and analyze live data streams in the cloud. ThingSpeak provides instant visualizations of data posted by your devices to ThingSpeak. With the ability to execute MATLAB® code in ThingSpeak, you can perform online analysis and process data as it comes in. ThingSpeak is often used for prototyping and proof-of-concept IoT systems that require analytics.

[SEA-MAT](https://sea-mat.github.io/sea-mat/) is a collaborative effort to organize and distribute Matlab tools for the Oceanographic Community.

[Gramm](https://github.com/piermorel/gramm) is a complete data visualization toolbox for Matlab. It provides an easy to use and high-level interface to produce publication-quality plots of complex data with varied statistical visualizations. Gramm is inspired by R's ggplot2 library.

[hctsa](https://hctsa-users.gitbook.io/hctsa-manual) is a software package for running highly comparative time-series analysis using Matlab.

[Plotly](https://plot.ly/matlab/) is a Graphing Library for MATLAB.

[YALMIP](https://yalmip.github.io/) is a MATLAB toolbox for optimization modeling.

[GNU Octave](https://www.gnu.org/software/octave/) is a high-level interpreted language, primarily intended for numerical computations. It provides capabilities for the numerical solution of linear and nonlinear problems, and for performing other numerical experiments. It also provides extensive graphics capabilities for data visualization and manipulation.

# Photogrammetry Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129494677-0341843b-c78c-4027-8a2c-43e98a995f6f.png">
  <br />
</p>

## Photogrammetry Learning Resources

[Photogrammetry](https://www.autodesk.com/solutions/photogrammetry-software) is the art and science of extracting 3D information from photographs. The process involves taking overlapping photographs of an object, structure, or space, and converting them into 2D or 3D digital models. Photogrammetry is often used by surveyors, architects, engineers, and contractors to create topographic maps, meshes, point clouds, or drawings based on the real-world.

[Aerial photogrammetry](https://www.autodesk.com/solutions/photogrammetry-software) is process of utilizing aircrafts to produce aerial photography that can be turned into a 3D model or mapped digitally. Now, it is possible to do the same work with a drone.

[Terrestrial(Close-range) photogrammetry](https://www.autodesk.com/solutions/photogrammetry-software) is when images are captured using a handheld camera or with a camera mounted to a tripod. The output of this method is not to create topographic maps, but rather to make 3D models of a smaller object.

[Top Photogrammetry Courses Online | Udemy](https://www.udemy.com/topic/photogrammetry/)

[Photogrammetry With Drones: In Mapping Technology | Udemy](https://www.udemy.com/course/essentials-of-photogrammetry/)

[Introduction to Photogrammetry Course | Coursera](https://www.coursera.org/lecture/aerial-photography-with-uav/introduction-to-photogrammetry-KyP30)

[Photogrammetry Online Classes and Training | Linkedin Learning](https://www.linkedin.com/learning/search?keywords=Photogrammetry&upsellOrderOrigin=default_guest_learning&trk=learning-course_learning-search-bar_search-submit)

[Pix4D training and certification for mapping professionals](https://training.pix4d.com/)

[Drone mapping and photogrammetry workshops with Pix4D](https://training.pix4d.com/pages/workshops)

[Digital Photogrammetric Systems Course | Purdue Online Learning](https://engineering.purdue.edu/online/courses/digital-photogrammetric-systems)

[Photogrammetry Training | Deep3D Photogrammetry](https://deep3d.co.uk/photogrammetry-training/)

[ASPRS Certification Program](https://www.asprs.org/certification)

## Photogrammetry Tools, Libraries, and Frameworks

[Autodesk® ReCap™](https://www.autodesk.com/products/recap/free-trial) is a software tool that converts reality captured from laser scans or photos into a 3D model or 2D drawing that's ready to be used in your design built for UAV and drone processes.

[Autodesk® ReCap™ Photo](http://blogs.autodesk.com/recap/introducing-recap-photo/) is a cloud-connected solution tailored for drone/UAV photo capturing workflows. Using ReCap Photo, you can create textured meshes, point clouds with geolocation, and high-resolution orthographic views with elevation maps.

[Pix4D](https://www.pix4d.com/) is a unique suite of photogrammetry software for drone mapping. Capture images with our app, process on desktop or cloud and create maps and 3D models.

[PIX4Dmapper](https://www.pix4d.com/product/pix4dmapper-photogrammetry-software) is the leading photogrammetry software for professional drone mapping.

[RealityCapture](https://www.capturingreality.com/) is a state-of-the-art photogrammetry software solution that creates virtual reality scenes, textured 3D meshes, orthographic projections, geo-referenced maps and much more from images and/or laser scans completely automatically.

[Adobe Scantastic](https://labs.adobe.com/projects/scantastic/) is a tool that makes the creation of 3D assets accessible to everyone. It can be used with just a mobile device (combined with Adobe's server-based photogrammetry pipeline), users can easily scan objects in their physical environment and turn them into 3D models which can then be imported into tools like [Adobe Dimension](https://www.adobe.com/products/dimension.html)  and [Adobe Aero](https://www.adobe.com/products/aero.html).

[Adobe Aero](https://www.adobe.com/products/aero.html) is a tool that helps you build, view, and share immersive AR experiences. Simply build a scene by bringing in 2D images from Adobe Photoshop and Illustrator, or 3D models from Adobe Dimension, Substance, third-party apps like Cinema 4D, or asset libraries like Adobe Stock and TurboSquid. Aero optimizes a wide array of assets, including OBJ, GLB, and glTF files, for AR, so you can visualize them in real time.

[Agisoft Metashape](https://www.agisoft.com/) is a stand-alone software product that performs photogrammetric processing of digital images and generates 3D spatial data to be used in GIS applications, cultural heritage documentation, and visual effects production as well as for indirect measurements of objects of various scales.

[MicroStation](https://www.bentley.com/en/products/brands/microstation) is a CAD software platform for 2D and 3D dimensional design and drafting, developed and sold by Bentley Systems. It generates 2D/3D vector graphics objects and elements and includes building information modeling (BIM) features.

[Leica Photogrammetry Suite (LPS)](https://support.hexagonsafetyinfrastructure.com/infocenter/index?page=product&facRef=LPS&facDisp=Leica%20Photogrammetry%20Suite%20(LPS)&landing=1) is a powerful photogrammetry system that delivers full analytical triangulation, the generation of digital terrain models, orthophoto production, mosaicking, and 3D feature extraction in a user-friendly environment that guarantees results even for photogrammetry novices.

[Terramodel](https://heavyindustry.trimble.com/products/terramodel) is a powerful software package for the surveyor, civil engineer or contractor who requires a CAD and design package with integrated support for raw survey data.

[MicMac](https://github.com/micmacIGN/micmac) is a free and  open-source photogrammetry software tools for 3D reconstruction.

[3DF Zephyr] (https://www.3dflow.net/3df-zephyr-photogrammetry-software/) is a photogrammetry software solution by 3Dflow. It allows you automatically reconstruct 3D models from photos and deal with any 3D reconstruction and scanning challenge. No matter what camera sensor, drone or laser scanner device you are going to use.

[COLMAP](https://colmap.github.io/) is a general-purpose Structure-from-Motion (SfM) and Multi-View Stereo (MVS) pipeline with a graphical and command-line interface. It offers a wide range of features for reconstruction of ordered and unordered image collections.

[Multi-View Environment (MVE)](https://www.gcc.tu-darmstadt.de/home/proj/mve/) is an effort to ease the work with multi-view datasets and to support the development of algorithms based on multiple views. It features Structure from Motion, Multi-View Stereo and Surface Reconstruction. MVE is developed at the TU Darmstadt.

[AliceVision](https://github.com/alicevision/AliceVision) is a Photogrammetric Computer Vision Framework which provides 3D Reconstruction and Camera Tracking algorithms. AliceVision comes up with strong software basis and state-of-the-art computer vision algorithms that can be tested, analyzed and reused.

[Meshroom](https://github.com/alicevision/meshroom) is a free, open-source 3D Reconstruction Software based on the AliceVision framework.

[PhotoModeler](https://www.photomodeler.com/) is a software extracts Measurements and Models from photographs taken with an ordinary camera. A cost-effective way for accurate 2D or 3D measurement, photo-digitizing, surveying, 3D scanning, and reality capture.

[ODM](https://www.opendronemap.org/odm/) is an open source command line toolkit to generate maps, point clouds, 3D models and DEMs from drone, balloon or kite images.

[WebODM](https://www.opendronemap.org/webodm/) is a user-friendly, commercial grade software for drone image processing. Generate georeferenced maps, point clouds, elevation models and textured 3D models from aerial images. It supports multiple engines for processing, currently [ODM](https://github.com/OpenDroneMap/ODM) and [MicMac](https://github.com/dronemapper-io/NodeMICMAC/).

[NodeODM](https://www.opendronemap.org/nodeodm/) is a [standard API specification](https://github.com/OpenDroneMap/NodeODM/blob/master/docs/index.adoc) for processing aerial images with engines such as [ODM](https://github.com/OpenDroneMap/ODM). The API is used by clients such as [WebODM](https://github.com/OpenDroneMap/WebODM), [CloudODM](https://github.com/OpenDroneMap/CloudODM) and [PyODM](https://github.com/OpenDroneMap/PyODM).

[ClusterODM]https://www.opendronemap.org/clusterodm/) is a reverse proxy, load balancer and task tracker with optional cloud autoscaling capabilities for NodeODM API compatible nodes. In a nutshell, it's a program to link together multiple NodeODM API compatible nodes under a single network address.

[FIELDimageR](https://www.opendronemap.org/fieldimager/) is an R package to analyze orthomosaic images from agricultural field trials.

[Regard3D](https://www.regard3d.org/) is a free and open source structure-from-motion program. It converts photos of an object, taken from different angles, into a 3D model of this object.

# Autodesk Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687186-060c4b00-d1ca-11eb-9e90-f51a3ebf4e43.png">
  <br />
</p>

## Autodesk Learning Resources

[Autodesk](https://www.autodesk.com/) is a global leader in design and make technology, with expertise across architecture, engineering, construction, design, manufacturing, and entertainment.

[CNC programming (Computer Numerical Control Programming)](https://www.autodesk.com/solutions/cnc-programming) is utilized by manufacturers to create program instructions for computers to control a machine tool. CNC is highly involved in the manufacturing process and improves automation as well as flexibility.

[AutoDesk Learning & Training](https://www.autodesk.com/training)

[Autodesk Certification](https://www.autodesk.com/certification/overview)

[Autodesk University](https://www.autodesk.com/autodesk-university/)

[Autodesk Design Academy](https://academy.autodesk.com/)

[Autodesk Customer Success Hub](https://customersuccess.autodesk.com)

[Software and Services for Education | Autodesk Education](https://www.autodesk.com/education/home)

[AutoDesk Forums](https://forums.autodesk.com)

[AutoDesk Developer Network](https://www.autodesk.com/developer-network/overview)

[Learning Civil 3D on Autodesk Knowledge Network](https://knowledge.autodesk.com/support/civil-3d/learn)

[Top Autodesk Courses on Udemy](https://www.udemy.com/topic/autodesk/)

[Top Autodesk Courses on Coursera](https://www.coursera.org/autodesk)

[Top Autodesk Fusion 360 Courses on Coursera](https://www.coursera.org/courses?query=autodesk%20fusion%20360&page=1)


## Autodesk Tools and Frameworks

[AutoCAD®](https://www.autodesk.com/products/autocad/overview) is computer-aided design (CAD) software that architects, engineers, and construction professionals rely on to create precise 2D and 3D drawings. It also automates tasks such as comparing drawings, counting, adding blocks, creating schedules.

[AutoCAD LT®](https://www.autodesk.com/products/autocad-lt/overview) is a powerful 2D computer-aided design (CAD) software that architects, engineers, construction professionals, and designers rely on to design, draft, and document with precise 2D geometry.

[AutoCAD® Mobile App](https://www.autodesk.com/products/autocad-mobile/overview) is a mobile(smartphone or tablet) version of AutoCAD that has the core design and drafting tools. Work on your CAD drawings anytime, anywhere—even offline.

[AutoCAD® Web App](https://www.autodesk.com/products/autocad-web-app/overview) is a web version of AutoCAD that can edit, create, share, and view CAD drawings in a web browser on any computer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687196-0ad0ff00-d1ca-11eb-87d8-6a1e806dcd4c.png">
  <br />
</p>

**AutoCAD® with Architecture toolset. Source: [Autodesk](https://www.autodesk.com/products/autocad/overview)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687204-13293a00-d1ca-11eb-806b-57a3526b0b75.png">
  <br />
</p>

**AutoCAD® with  Mechanical toolset. Source: [Autodesk](https://www.autodesk.com/products/autocad/overview)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687201-10c6e000-d1ca-11eb-99b4-90dec581f163.png">
  <br />
</p>

**AutoCAD® with Electrical toolset. Source: [Autodesk](https://www.autodesk.com/products/autocad/overview)**

[Tinkercad®](https://www.tinkercad.com) is a free, easy-to-use app for 3D design, electronics, and coding. It's used by teachers, kids, hobbyists, and designers to imagine, design, and make anything.

[Revit®](https://www.autodesk.com/products/revit/overview) is a  BIM (Building Information Modeling) software to drive efficiency and accuracy across the project lifecycle, from conceptual design, visualization, and analysis to fabrication and construction.

[AEC(Architecture, Engineering & Construction) Collection®](https://www.autodesk.com/collections/architecture-engineering-construction/overview) is a set of BIM and CAD tools for designers, engineers, and contractors that is supported by a cloud-based common data environment that facilitates project delivery from early-stage design through to construction.

[Fusion 360®](https://www.autodesk.com/products/fusion-360/overview) is an integrated CAD, CAM, CAE, and PCB software application. It unifies design, engineering, electronics, and manufacturing into a single software platform.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687501-98f9b500-d1cb-11eb-807b-20d24da14fc1.png">
  <br />
</p>

**Autodesk® Fusion 360. Source: [Autodesk](https://www.autodesk.com/products/fusion-360/features#)**

[Fusion 360 with FeatureCAM®](https://www.autodesk.com/products/featurecam/overview) is a tool that gives you access to FeatureCAM Ultimate, PartMaker, Fusion 360, Fusion Team, and HSMWorks. With FeatureCAM CNC programming software uses manufacturing knowledge to intelligently make decisions, produce results, and remove repetitive processes.

[Fusion 360 with Netfabb®](https://www.autodesk.com/products/netfabb/overview) is a software that offers a complete toolset for design and implementation for additive manufacturing. It streamlines workflows and automates processes around 3D print preparation. The software also includes access to Fusion 360, Fusion 360 Team, and additional capabilities through Fusion 360 Additive Extensions.

[Fusion 360 Manage](https://www.autodesk.com/products/fusion-360-manage/overview) is a product lifecycle management platform that connects your people, processes, and data across departments and geographies. It gives you the flexibility to start today and expand tomorrow with PLM that adapts to your business.

[Fusion Team](https://fusionteam.autodesk.com/) is a cloud-based coll tool that helps eliminate the inefficiencies that disparate tools create when working with your internal and external teams.

[Fusion 360 with PowerInspect®](https://www.autodesk.com/products/powerinspect/overview) is a 3D measurement software offers a powerful way to inspect, validate, and manage quality for all measurement equipment. Now includes access to Fusion 360, Fusion 360 Team, and Fusion 360 – Machining Extension. PowerInspect includes comprehensive inspection tools that measure parts while they’re still in On Machine Verification (OMV). Machine tool probing helps you make informed scrap or rework decisions quickly.

[Fusion 360 with PowerMill® CAM](https://www.autodesk.com/products/powermill/overview) is a software provides expert CNC programming strategies for complex 3 and 5-axis manufacturing. This includes access to Fusion 360 and advanced manufacturing capabilities through Fusion 360 extensions.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687213-1f14fc00-d1ca-11eb-931e-79c7c5c58ce9.png">
  <br />
</p>

**CNC machining with Fusion 360 with PowerMill® CAM. Source: [Autodesk](https://www.autodesk.com/products/powermill/overview)**

[Fusion 360 with PowerShape®](https://www.autodesk.com/products/powershape/overview) is a  manufacturing CAD software combines surface, solid, and mesh modeling to help prepare molds, dies, and other complex parts for manufacture. This includes access to Fusion 360 and Fusion 360 Team.

[Autodesk PartMaker®](https://www.autodesk.com/solutions/manufacturing-software/swiss-machining) is a software that can produce CNC programs that drive main and sub-spindle machining operations. These can be used for turning, indexed and interpolated C-axis milling, Y-axis, and B-axis milling.

[Robot Structural Analysis Professional](https://www.autodesk.com/products/robot-structural-analysis/overview) is a structural load analysis software that verifies code compliance and uses BIM-integrated workflows to exchange data with Revit. It can help you to create more resilient, constructible designs that are accurate, coordinated, and connected to BIM.

[Revit LT™](https://www.autodesk.com/products/revit-lt/overview) is a software that provides the most cost-effective BIM (Building Information Modeling) solution, you can produce high-quality 3D architectural designs and documentation.

[Maya®](https://www.autodesk.com/products/maya/overview) is a 3D computer animation, modeling, simulation, and rendering software that can create realistic effects from explosions to cloth simulation.

[Maya LT™](https://www.autodesk.com/products/maya-lt/overview) is a game design software for indie game makers that can create and animate realistic-looking characters, props, and environments using the sophisticated 3D modeling and animation tools.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687226-2a682780-d1ca-11eb-9408-4b32ddc7d493.png">
  <br />
</p>

**Autodesk® Maya. Source:[Autodesk](https://www.autodesk.com/products/maya/overview)**

[3DS Max®](https://www.autodesk.com/products/3ds-max/overview) is a 3D modeling and rendering software for design visualization, games, and animation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687233-3358f900-d1ca-11eb-8e9c-0cb68b16db0e.png">
  <br />
</p>

**Autodesk® 3DS Max. Source:[Autodesk](https://www.autodesk.com/products/3ds-max/overview)**

[Arnold](https://www.autodesk.com/products/arnold/overview) is an advanced Monte Carlo ray tracing(Global illumination) renderer that helps you work more efficiently.

[ReCap™](https://www.autodesk.com/products/recap/overview) is a Pro 3D scanning software to transform the physical world into a digital asset. With reality capture data you can better understand and verify existing and as-built conditions to gain insights and make better decisions.

[Flame®](https://www.autodesk.com/products/flame/overview) is a 3D VFX and finishing software provides powerful tools for 3D compositing, visual effects, and editorial finishing. An integrated, creative environment means faster compositing, advanced graphics, color correction, and more.

[Mudbox®](https://www.autodesk.com/products/mudbox/overview) is a 3D digital painting and sculpting software that let's you sculpt and paint highly detailed 3D geometry and textures.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687228-2e944500-d1ca-11eb-894e-b55e15c35620.png">
  <br />
</p>

**Autodesk® Mudbox. Source:[Autodesk](https://www.autodesk.com/products/mudbox/overview)**

[Character Generator®](https://www.autodesk.com/products/character-generator/overview) is a powerful 3D design and animation tools, Character Generator offers artists a web-based laboratory to create fully rigged 3D characters for animation packages and game engines.

[Smoke®](https://www.autodesk.com/products/smoke/overview) is a  video effects software helps production studios increase productivity by combining editing workflows with node-based compositing tools in a timeline-centered editing environment.

[ShotGrid](https://www.autodesk.com/products/shotgrid/overview) formerly Shotgun Software, is software for creative project management software and review tools for film, TV, and games that streamlines workflows for creative studios.

[Advance Steel®](https://www.autodesk.com/products/advance-steel/overview) is a 3D modeling software for steel detailing, design, fabrication, and construction. it connects engineers and detailers through a seamless design and detailing workflow between Advance Steel and Revit, you can reduce the time required to move from design to fabrication while simultaneously reducing errors along the way.

[Media & Entertainment Collection®](https://www.autodesk.com/collections/media-entertainment/overview) is a collection that includes all of the tools you need to build a powerful and scalable 3D animation pipeline for complex simulations, effects, and rendering.

[Civil 3D®](https://www.autodesk.com/products/civil-3d/overview) is a  civil engineering design software supports BIM (Building Information Modeling) with integrated features to improve drafting, design, and construction documentation.

[Inventor®](https://www.autodesk.com/products/inventor/overview) is a  CAD software that provides professional-grade 3D mechanical design, documentation, and product simulation tools. Work efficiently with a powerful blend of parametric, direct, freeform, and rules-based design capabilities.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687217-24724680-d1ca-11eb-9768-0fbcba5a0d41.png">
  <br />
</p>

**Autodesk® Inventor. Source:[Autodesk](https://www.autodesk.com/products/inventor/overview)**

[Inventor® CAM](https://www.autodesk.com/products/inventor-cam/overview) is an integrated CAM software for Inventor that simplifies CNC programming processes. Such as the machining workflow with CAD-embedded 2.5-axis to 5-axis milling, turning, and mill-turn capabilities.

[Inventor Nastran®](https://www.autodesk.com/products/inventor-nastran/overview) is a CAD-embedded finite element analysis software that delivers finite element analysis (FEA) tools for engineers and analysts. Simulation covers multiple analysis types, such as linear and nonlinear stress, dynamics, and heat transfer.

[Inventor® Nesting](https://www.autodesk.com/products/inventor-nesting/overview) is a CAD-embedded, true-shape nesting tools for Inventor that helps you optimize yield from flat raw material. Easily compare nesting studies to optimize efficiency and reduce costs, and export 3D models or DXF™ files of the completed nest for cutting path generation.

[Inventor Tolerance Analysis®](https://www.autodesk.com/products/inventor-tolerance-analysis/overview) is an CAD-embedded tolerance stackup analysis software that is designed to help Inventor users make more informed decisions while specifying manufacturing tolerances.

[Product Design & Manufacturing Collection](https://www.autodesk.com/collections/product-design-manufacturing/overview) is an integrated set of professional-grade applications that connect everyone, from concept to production, with shared tools to streamline your product development process.

[Navisworks®](https://www.autodesk.com/products/navisworks/overview) is a project review software to improve BIM (Building Information Modeling) coordination. That can combine design and construction data into a single model.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687230-2f2cdb80-d1ca-11eb-9bcf-5dc2fb858d7d.png">
  <br />
</p>

**Autodesk® Navisworks. Source:[Autodesk](https://www.autodesk.com/products/navisworks/overview)**

[BIM Collaborate](https://www.autodesk.com/products/bim-collaborate/overview) is cloud-based design collaboration and coordination software that connects AEC teams, helping you execute on design intent and deliver high-quality constructible models on a single platform.

[BIM Collaborate Pro](https://www.autodesk.com/products/bim-collaborate/overview) is cloud-based design collaboration and coordination software that connects AEC teams, helping you execute on design intent and deliver high-quality constructible models on a single platform.

[InfraWorks®](https://www.autodesk.com/products/infraworks/overview) is a conceptual design software lets architecture, engineering, and construction professionals model, analyze, and visualize infrastructure design concepts within the context of the built and natural environment—improving decision making and accelerating project approvals.

[SketchBook®](https://www.autodesk.com/products/sketchbook/overview) is a drawing and painting software lets designers, architects, and concept artists sketch ideas quickly and create stunning illustrations.

[Alias®](https://www.autodesk.com/products/alias-products/overview) is a product design software for sketching, concept modeling, surfacing, visualization. It can create and reuse templates across design and surfacing teams sharing surfacing language.

[Assemble BIM Data](https://construction.autodesk.com/products/assemble/) is a tool that helps keep projects on track. Along with condition and connect BIM data to design reviews, estimating, change management, scheduling, work-in-place tracking, and more.

[Autodesk® Forge](https://forge.autodesk.com) is a cloud-based developer platform from Autodesk. That let's you access design and engineering data in the cloud with the Forge platform. Whether you want to automate processes, connect teams and workflows, or visualize your data using Forge APIs.

[Autodesk® Rendering](https://www.autodesk.com/products/rendering/overview) is a fast, high-resolution cloud rendering software that let's you produce stunning, high-quality renderings from designs and models with cloud rendering. This service uses cloud credits, which is a universal measure across Autodesk consumption-based cloud services to perform certain tasks in the cloud.

[Autodesk® CFD](https://www.autodesk.com/products/cfd/overview) is a computational fluid dynamics simulation software that engineers and analysts use to intelligently predict how liquids and gases will perform. It helps to minimize the need for physical prototypes while providing deeper insight into fluid flow design performance.

[Autodesk® Drive](https://www.autodesk.com/subscription/drive) is a way to securely store, preview, and share your 2D and 3D design data.

[Autodesk® Viewer](https://www.autodesk.com/viewers) is a tool that supports most 2D and 3D files, including DWG, STEP, DWF, RVT, and Solidworks, and works with over 80 file types on any device. Get the feedback you need with Autodesk Viewer’s annotation and drawing tools for easy online collaboration.

[Autodesk BIM 360®](https://www.autodesk.com/bim-360/) is a tool is part of the Autodesk Construction Cloud, connecting workflows, teams, and data to help you build better.

[Autodesk® Build](https://construction.autodesk.com/products/autodesk-build/) is a construction management software for field execution and project management that empowers you to seamlessly collaborate and deliver construction projects on time, on budget.

[Autodesk® Takeoff](https://construction.autodesk.com/products/autodesk-takeoff/) is a tool that helps you work with competitive bids that are generated from accurate estimates produced from integrated 2D takeoffs and 3D quantities.

[BuildingConnected](https://www.buildingconnected.com) is the argest real-time construction network that connects owners and builders through an easy-to-use platform to streamline the bid and risk management process.

[Bid Board Pro](https://www.buildingconnected.com/bid-board/) is a tool that helps you see all bid invites across your entire office or division from one place. Know what needs to get done, who’s responsible for it and when it’s due. Track project files, deadlines and more during each stage of the bidding process.

[TradeTapp](https://www.buildingconnected.com/tradetapp/) is a tool that helps you significantly decrease the time it takes to analyze subcontractor risk, annually or for a specific project. Advanced risk profiles enable a streamlined process and offer financial benchmarking, key metric calculations, capacity recommendations and safety performance history.

[Design Review](https://www.autodesk.com/products/design-review/overview) is a CAD viewer software lets you view, mark up, print, and track changes to 2D and 3D files for free—without the original design software. Work with a variety of file formats, including: DWF, DWFx, DWG, and DXF (requires installation of [free DWG TrueView software](https://www.autodesk.com/products/dwg/viewers)); Adobe PDF; as well as image file types such as.bmp, .jpg, .gif, .pcx, .pct, .png, .rlc, .tga, .tif, .mil, .cal, and more.

[EAGLE](https://www.autodesk.com/products/eagle/overview) is electronic design automation (EDA) software that lets printed circuit board (PCB) designers seamlessly connect schematic diagrams, component placement, PCB routing, and comprehensive library content.

[Fabrication ESTmep™, CADmep™, and CAMduct™](https://www.autodesk.com/products/fabrication/overview) is a software that provides an integrated set of tools for MEP specialty contractors to estimate, detail, and drive fabrication of mechanical building systems. Also, create high LOD models of piping, plumbing, or ductwork systems in AutoCAD using CADmep. Content libraries used in ESTmep, CADmep, and CAMduct can also be used in Revit to support BIM workflows. Available stand-alone or in the Architecture, Engineering & Construction Collection..

[Formit](https://www.autodesk.com/products/formit/overview) is an architectural modeling software for BIM-based 3D sketching. The pro version of FormIt includes the tools in the FormIt app, plus Dynamo computation, and collaboration and analysis features.

[Helius Composite](https://www.autodesk.com/products/helius-composite/overview) is a tool that can help you simulate the material behavior of compound components. Built-in solvers minimize the need to have secondary finite element analysis (FEA) software to analyze material characteristics more quickly.

[Helius PFA](https://www.autodesk.com/products/helius-pfa/overview) is a progressive failure analysis software that predicts failure stages of composite materials. Helius PFA enables you to integrate composite and elastomeric material properties into your finite element analysis (FEA) program.

[HSMWorks](https://www.autodesk.com/products/hsmworks/overview) is an ambedded CAM software for [SOLIDWORKS®](https://www.solidworks.com/) to design and generate CAM toolpaths without the hassle of changing software. Reduce cycle time and rework with CAD-embedded 2.5 to 5-axis milling, turning, and mill-turn capabilities. HSMWorks is included with your Fusion 360 subscription.

[Insight](https://www.autodesk.com/products/insight/overview) is a building performance analysis software that empowers architects and engineers to design more energy-efficient buildings with advanced simulation engines and building performance analysis data integrated in Revit.

[Moldflow®](https://www.autodesk.com/products/moldflow/overview) is a software tool that lets you troubleshoot problems with plastic injection and compression molding for design and manufacturing. Advanced tools and a simplified user interface help you address manufacturing challenges, such as part warpage, cooling channel efficiency, and cycle time reduction.

[MotionBuilder®](https://www.autodesk.com/products/motionbuilder/overview) is a 3D character animation software. Work in an interactive environment optimized to help you work faster and more efficiently without compromising creativity.

[PlanGrid Build](https://construction.autodesk.com/products/autodesk-plangrid-build/?pgr=1) is a Construction app built for the field. It allows you to complete tasks from anywhere on the jobsite with seamless access to Autodesk Build data, even when you’re offline.

[Point Layout](https://www.autodesk.com/products/point-layout/overview) is a  construction layout software helps contractors and subcontractors bring model accuracy to the field and back. Connect models to layout and quality workflows. Get direct file format compatibility with robotic total station hardware, including Leica, Topcon, and Trimble.

[Structural Bridge Design®](https://www.autodesk.com/products/structural-bridge-design/overview) is a bridge analysis software for small to medium-span bridges used by engineers to deliver design reports faster.

[Vault®](https://www.autodesk.com/products/vault/overview) is a product data management (PDM) software helps streamline workflows. Everyone works from a central source of organized data—collaborating, reducing errors, and saving time.

[Vehicle Tracking®](https://www.autodesk.com/products/vehicle-tracking/overview) is a swept path analysis and design software to facilitate parking lot layout, roundabout design, and other design challenges impacted by vehicle movement.

[VRED®](https://www.autodesk.com/products/vred/overview) is a 3D visualization software helps automotive designers and engineers create product presentations, design reviews, and virtual prototypes using interactive GPU raytracing and both analytic and cloud-rendering modes.

[Within Medical®](https://www.autodesk.com/products/within-medical/overview) is a 3D printing orthopedic implant design software that enables designers to create medical implants to aid osseointegration.

[Pype](https://construction.autodesk.com/products/pype/) is a tool that helps you reduce project risk and strengthen client relationships by automating processes that are critical for owner satisfaction and contract compliance.

[Pype Closeout](https://pype.io/closeout/) is a tool provides a single portal for closeout documentation management, with digital document collection from subcontractors and powerful reporting dashboards. With subcontractor outreach automated, the Closeout platform ensures contract compliance and helps you get paid faster.

[Pype SmartPlans](https://pype.io/smartplans/) is a tool that locates and extracts all submittals from your uploaded plans automatically. Export product, equipment, and finish schedules into excel with a single click. SmartPlans’ powerful automation uses cutting edge artificial intelligence and machine learning to intelligently read your drawings to extract submittals and schedules.

[CAMplete](https://www.autodesk.com/products/camplete/overview) is a software tool that  provides G-code post-processing, verification, and simulation for different kinds of CNC machinery. Import data from leading CAM software then use proven post-processors and highly accurate 3D machine models, developed in partnership with machine tool builders, to rapidly produce high-quality, collision free NC machining code.

[Vault PLM](https://www.autodesk.com/products/vault-plm/overview) is a tool that combines Vault Professional with Fusion Lifecycle for enterprise-wide collaboration and product lifecycle management.

# LiDAR Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950812-f5ae2900-cd0e-11eb-8989-9188bd18a68c.png">
  <br />
</p>

## LiDAR Learning Resources
[Back to the Top](https://github.com/mikeroyal/LiDAR-Guide#table-of-contents)

[Introduction to Lidar Course - NOAA](https://coast.noaa.gov/digitalcoast/training/intro-lidar.html)

[Lidar 101:An Introduction to Lidar Technology, Data, and Applications(PDF) - NOAA](https://coast.noaa.gov/data/digitalcoast/pdf/lidar-101.pdf)

[Understanding LiDAR Technologies - GIS Lounge](https://www.gislounge.com/understanding-lidar-technologies/)

[LiDAR University Free Lidar Training Courses on MODUS AI](https://www.modus-ai.com/lidar-university-2/)

[LiDAR | Learning Plan on ERSI](https://www.esri.com/training/catalog/5bccd52a6e9c0f01fb49e85d/lidar/#!)

[Light Detection and Ranging Sensors Course on Coursera](https://www.coursera.org/lecture/state-estimation-localization-self-driving-cars/lesson-1-light-detection-and-ranging-sensors-3NXgp)

[Quick Introduction to Lidar and Basic Lidar Tools(PDF)](https://training.fws.gov/courses/references/tutorials/geospatial/CSP7304/documents/Lidar.pdf)

[LIDAR - GIS Wiki](http://wiki.gis.com/wiki/index.php/Lidar)

[OpenStreetMap Wiki](https://wiki.openstreetmap.org/wiki/Main_Page)

[OpenStreetMap Frameworks](https://wiki.openstreetmap.org/wiki/Frameworks)

## LiDAR Tools & Frameworks

[Light Detection and Ranging (lidar)](https://www.usgs.gov/news/earthword-lidar) is a technology used to create high-resolution models of ground elevation with a vertical accuracy of 10 centimeters (4 inches). Lidar equipment, which includes a laser scanner, a Global Positioning System (GPS), and an Inertial Navigation System (INS), is typically mounted on a small aircraft. The laser scanner transmits brief pulses of light to the ground surface. Those pulses are reflected or scattered back and their travel time is used to calculate the distance between the laser scanner and the ground.  Lidar data is initially collected as a “point cloud” of individual points reflected from everything on the surface, including structures and vegetation. To produce a “bare earth” Digital Elevation Model (DEM), structures and vegetation are stripped away.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950840-fe9efa80-cd0e-11eb-9a12-57c4799d63b5.png">
  <br />
</p>

**3D Data Visualization of Golden Gate Bridge. Source: [USGS](https://www.usgs.gov/core-science-systems/ngp/tnm-delivery)**

[Mola](https://docs.mola-slam.org/latest/) is a Modular Optimization framework for Localization and mApping (MOLA).

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950850-01015480-cd0f-11eb-9fa6-1f93d6d87cd1.gif">
  <br />
</p>

**3D LiDAR SLAM from KITTI dataset. Source: [MOLA](https://docs.mola-slam.org/latest/demo-kitti-lidar-slam.html)**

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a MATLAB tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Automated Driving Toolbox™](https://www.mathworks.com/products/automated-driving.html) is a MATLAB tool that provides algorithms and tools for designing, simulating, and testing ADAS and autonomous driving systems. You can design and test vision and lidar perception systems, as well as sensor fusion, path planning, and vehicle controllers. Visualization tools include a bird’s-eye-view plot and scope for sensor coverage, detections and tracks, and displays for video, lidar, and maps. The toolbox lets you import and work with HERE HD Live Map data and OpenDRIVE® road networks. It also provides reference application examples for common ADAS and automated driving features, including FCW, AEB, ACC, LKA, and parking valet. The toolbox supports C/C++ code generation for rapid prototyping and HIL testing, with support for sensor fusion, tracking, path planning, and vehicle controller algorithms.

[Microsoft AirSim](https://microsoft.github.io/AirSim/lidar.html) is a simulator for drones, cars and more, built on Unreal Engine (with an experimental Unity release). AirSim is open-source, cross platform, and supports [software-in-the-loop simulation](https://www.mathworks.com/help///ecoder/software-in-the-loop-sil-simulation.html) with popular flight controllers such as PX4 & ArduPilot and [hardware-in-loop](https://www.ni.com/en-us/innovations/white-papers/17/what-is-hardware-in-the-loop-.html) with PX4 for physically and visually realistic simulations. It is developed as an Unreal plugin that can simply be dropped into any Unreal environment. AirSim is being developed  as a platform for AI research to experiment with deep learning, computer vision and reinforcement learning algorithms for autonomous vehicles.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950853-02328180-cd0f-11eb-9459-1b31d084bd3f.png">
  <br />
</p>

**3D Autonomous Vehicle Simulation in AirSim. Source: [Microsoft](https://microsoft.github.io/AirSim)**

[LASer(LAS)](https://www.asprs.org/divisions-committees/lidar-division/laser-las-file-format-exchange-activities) is a public file format for the interchange of 3-dimensional point cloud data data between data users. Although developed primarily for exchange of lidar point cloud data, this format supports the exchange of any 3-dimensional x,y,z tuplet. This binary file format is an alternative to proprietary systems or a generic ASCII file interchange system used by many companies. The problem with proprietary systems is obvious in that data cannot be easily taken from one system to another. There are two major problems with the ASCII file interchange. The first problem is performance because the reading and interpretation of ASCII elevation data can be very slow and the file size can be extremely large even for small amounts of data. The second problem is that all information specific to the lidar data is lost. The LAS file format is a binary file format that maintains information specific to the lidar nature of the data while not being overly complex.

[3D point cloud](https://www.onyxscan-lidar.com/point-cloud/) is a set of data points defined in a given three-dimensional coordinates system.. Point clouds can be produced directly by 3D scanner which records a large number of points returned from the external surfaces of objects or earth surface. These data are exchanged between LiDAR users mainly through LAS format files (.las).

[ArcGIS Desktop](https://www.esri.com/en-us/arcgis/products/arcgis-desktop/overview) is powerful and cost-effective desktop geographic information system (GIS) software. It is the essential software package for GIS professionals. ArcGIS Desktop users can create, analyze, manage, and share geographic information so decision-makers can make intelligent, informed decisions.

[USGS 3DEP Lidar Point Cloud Now Available as Amazon Public Dataset](https://www.usgs.gov/news/usgs-3dep-lidar-point-cloud-now-available-amazon-public-dataset)

[National Geospatial Program](https://www.usgs.gov/core-science-systems/national-geospatial-program)

[National Map Data Download and Visualization Services](https://www.usgs.gov/core-science-systems/ngp/tnm-delivery)

[USGS Lidar Base Specification(LBS) online edition](https://www.usgs.gov/core-science-systems/ngp/ss/lidar-base-specification-online)


# Robotics Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/96352533-b55fb380-1078-11eb-874c-f165cbcce899.png">
  <br />
</p>

## Robotic Arms & Dev Kits

[Eva](https://automata.tech/about-eva/) is a 6-axis of freedom and ease of use, the lab robot arm easily automates the loading and unloading of samples into lab machines, precision balances and more. Eva can handle a range of common lab items  including microplates, PCR tube strips, eppendorf tubes, petri dishes and microscope slides to automating repetitive and strenuous sample handling processes. Common manufacturing machine tending applications with Eva include start/end of line loading and unloading of machines such as CNC machines, CMMs, metal presses and chemical etching machines.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122688384-cac14a80-d1d0-11eb-874c-a523a0c654ad.png">
  <br />
</p>

**Eva lab robot arm from Automata. Source: [Automata](https://automata.tech/about-eva/)**

**AWS DeepRacer autonomous Car Kit**
<img src="https://user-images.githubusercontent.com/45159366/105645201-e35e4c00-5e4e-11eb-9df8-2cc91705b496.png">

[Checkout the AWS DeepRacer autonomous Car Kit](https://www.amazon.com/AWS-DeepRacer-Fully-autonomous-developers/dp/B07JMHRKQG)

**AWS DeepRacer autonomous Car Kit Hardware Specifications**

 - CAR:	18th scale 4WD with monster truck chassis
 - CPU:	Intel Atom™ Processor
 - MEMORY:	4GB RAM
 - STORAGE: 32GB (expandable)
 - WI-FI:	802.11ac
 - CAMERA:	 4 MP cameras with MJPEG
 - SOFTWARE:	Ubuntu OS 16.04 LTS, Intel® OpenVINO™ toolkit, ROS Kinetic
 - DRIVE BATTERY:	7.4V/1100mAh lithium polymer
 - COMPUTE BATTERY:	13600mAh USB-C PD
 - PORTS:	4x USB-A, 1x USB-C, 1x Micro-USB, 1x HDMI
 - SENSORS:	Integrated accelerometer and gyroscope

 [Checkout the SunFounder PiCar-V Kit V2.0 for Raspberry Pi](https://www.sunfounder.com/products/smart-video-car)

<img src="https://user-images.githubusercontent.com/45159366/105645908-84e69d00-5e51-11eb-85a7-29b8074337ed.png">


## Robotics Learning Resources

[Robotics courses from Coursera](https://www.edx.org/learn/robotics)

[Learn Robotics with Online Courses and Classes from edX](https://www.edx.org/learn/robotics)

[Top Robotics Courses Online from Udemy](https://www.udemy.com/topic/robotics/)

[Free Online AI & Robotics Courses](https://www.futurelearn.com/subjects/it-and-computer-science-courses/ai-and-robotics)

[REC Foundation Robotics Industry Certification](https://www.roboticseducation.org/industry-certifications/)

[Carnegie Mellon Robotics Academy](https://www.cmu.edu/roboticsacademy/Training/Certifications.html)

[RIA Robotic Integrator Certification Program](https://www.robotics.org/robotics/integrator-certification)

[AWS RoboMaker – Develop, Test, Deploy, and Manage Intelligent Robotics Apps](https://aws.amazon.com/blogs/aws/aws-robomaker-develop-test-deploy-and-manage-intelligent-robotics-apps/)

[Microsoft AI School](https://aischool.microsoft.com/en-us/home)

[Language Understanding (LUIS) for Azure Cognitive Services](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/what-is-luis)

[ROS on Windows 10](https://ms-iot.github.io/ROSOnWindows/)

[Windows ML ROS Node](https://ms-iot.github.io/ROSOnWindows/ROSAtMS/WinML.html)

[Azure VM templates to bootstrap ROS and ROS 2 environments](https://ms-iot.github.io/ROSOnWindows/ROSAtMS/AzureVM.html)

[Google Robotics Research](https://research.google/teams/brain/robotics/)

## Robotics Tools and Frameworks

[Robot Framework](https://robotframework.org/) is a generic open source automation framework. It can be used for test automation and robotic process automation. It has easy syntax, utilizing human-readable keywords. Its capabilities can be extended by libraries implemented with Python or Java.

[The Robotics Library (RL)](https://github.com/roboticslibrary/rl) is a self-contained C++ library for robot kinematics, motion planning and control. It covers mathematics, kinematics and dynamics, hardware abstraction, motion planning, collision detection, and visualization.RL runs on many different systems, including Linux, macOS, and Windows. It uses CMake as a build system and can be compiled with Clang, GCC, and Visual Studio.

[Robot Structural Analysis Professional](https://www.autodesk.com/products/robot-structural-analysis/overview?term=1-YEAR) is structural load analysis software developed by Autodesk that verifies code compliance and uses BIM-integrated workflows to exchange data with Revit. It can help you to create more resilient, constructible designs that are accurate, coordinated, and connected to BIM.

[PowerMill](https://www.autodesk.com/products/powermill/overview) is a software developed by Autodesk that provides powerful, flexible, easy-to-use tools for offline programming of robots. Get tools to help you optimize robotic paths and simulate virtual mock-ups of manufacturing cells and systems.

[ROS](https://www.ros.org/) is robotics middleware. Although ROS is not an operating system, it provides services designed for a heterogeneous computer cluster such as hardware abstraction, low-level device control, implementation of commonly used functionality, message-passing between processes, and package management.

[ROS2](https://index.ros.org/doc/ros2/) is a set of [software libraries and tools](https://github.com/ros2) that help you build robot applications. From drivers to state-of-the-art algorithms, and with powerful developer tools, ROS has what you need for your next robotics project. And it’s all open source.

[MoveIt](https://moveit.ros.org/) is the most widely used software for manipulation and has been used on over 100 robots. It provides an easy-to-use robotics platform for developing advanced applications, evaluating new designs and building integrated products for industrial, commercial, R&D, and other domains.

[AutoGluon](https://autogluon.mxnet.io/index.html) is toolkit for [Deep learning](https://gitlab.com/maos20008/intro-to-machine-learning) that automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy deep learning models on tabular, image, and text data.

[Gazebo](http://gazebosim.org/) accurately and efficiently simulates indoor and outdoor robots. You get a robust physics engine, high-quality graphics, and programmatic and graphical interfaces.

[Robotics System Toolbox](https://www.mathworks.com/products/robotics.html) provides tools and algorithms for designing, simulating, and testing manipulators, mobile robots, and humanoid robots. For manipulators and humanoid robots, the toolbox includes algorithms for collision checking, trajectory generation, forward and inverse kinematics, and dynamics using a rigid body tree representation.
For mobile robots, it includes algorithms for mapping, localization, path planning, path following, and motion control. The toolbox provides reference examples of common industrial robot applications. It also includes a library of
commercially available industrial robot models that you can import, visualize, and simulate.

[Intel Robot DevKit](https://github.com/intel/robot_devkit) is the tool to generate Robotics Software Development Kit (RDK) designed for autonomous devices, including the ROS2 core and capacibilities packages like perception, planning, control driver etc. It provides flexible build/runtime configurations to meet different autonomous requirement on top of diversity hardware choices, for example use different hareware engine CPU/GPU/VPU to accelerate AI related features.

[Arduino](https://www.arduino.cc/) is an open-source platform used for building electronics projects. Arduino consists of both a physical programmable circuit board (often referred to as a microcontroller) and a piece of software, or IDE (Integrated Development Environment) that runs on your computer, used to write and upload computer code to the physical board.

[ArduPilot](https://ardupilot.org/ardupilot/index.html) enables the creation and use of trusted, autonomous, unmanned vehicle systems for the peaceful benefit of all. ArduPilot provides a comprehensive suite of tools suitable for almost any vehicle and application.

[AirSim](https://github.com/Microsoft/AirSim) is a simulator for drones, cars and more, built on Unreal Engine (we now also have an experimental Unity release). It is open-source, cross platform, and supports hardware-in-loop with popular flight controllers such as PX4 for physically and visually realistic simulations.

[The JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover) is an open source, build it yourself, scaled down version of the 6 wheel rover design that JPL uses to explore the surface of Mars. The Open Source Rover is designed almost entirely out of consumer off the shelf (COTS) parts. This project is intended to be a teaching and learning experience for those who want to get involved in mechanical engineering, software, electronics, or robotics.

[Light Detection and Ranging(LiDAR)](https://en.wikipedia.org/wiki/Lidar) is a remote sensing method that uses light in the form of a pulsed laser at an object, and uses the time and wavelength of the reflected beam of light to estimate the distance and in some applications ([Laser Imaging](https://en.wikipedia.org/wiki/Laser_scanning)), to create a 3D representation of the object and its surface characteristics. This technology is commonly used in aircraft and self-driving vehicles.

[AliceVision](https://github.com/alicevision/AliceVision) is a Photogrammetric Computer Vision Framework which provides a 3D Reconstruction and Camera Tracking algorithms. AliceVision aims to provide strong software basis with state-of-the-art computer vision algorithms that can be tested, analyzed and reused. The project is a result of collaboration between academia and industry to provide cutting-edge algorithms with the robustness and the quality required for production usage.

[CARLA](https://github.com/carla-simulator/carla) is an open-source simulator for autonomous driving research. CARLA has been developed from the ground up to support development, training, and validation of autonomous driving systems. In addition to open-source code and protocols, CARLA provides open digital assets (urban layouts, buildings, vehicles) that were created for this purpose and can be used freely. The simulation platform supports flexible specification of sensor suites and environmental conditions.

[ROS bridge](https://github.com/carla-simulator/ros-bridge) is a package to bridge ROS for CARLA Simulator.

[ROS-Industrial](https://rosindustrial.org/) is an open source project that extends the advanced capabilities of ROS software to manufacturing.

[AWS RoboMaker](https://aws.amazon.com/robomaker/) is the most complete cloud solution for robotic developers to simulate, test and securely deploy robotic applications at scale. RoboMaker provides a fully-managed, scalable infrastructure for simulation that customers use for multi-robot simulation and CI/CD integration with regression testing in simulation.

[Microsoft Robotics Developer Studio](https://www.microsoft.com/en-us/download/details.aspx?id=29081)  is a free .NET-based programming environment for building robotics applications.

[Visual Studio Code Extension for ROS](https://github.com/ms-iot/vscode-ros) is an extension provides support for Robot Operating System (ROS) development.

[Azure Kinect ROS Driver](https://github.com/microsoft/azure_kinect_ros_driver) is a node which publishes sensor data from the [Azure Kinect Developer Kit](https://azure.microsoft.com/en-us/services/kinect-dk/) to the [Robot Operating System (ROS)](http://www.ros.org/). Developers working with ROS can use this node to connect an Azure Kinect Developer Kit to an existing ROS installation.

[Azure IoT Hub for ROS](https://github.com/microsoft/ros_azure_iothub) is a ROS package works with the Microsoft Azure IoT Hub service to relay telemetry messages from the Robot to Azure IoT Hub or reflect properties from the Digital Twin to the robot using dynamic reconfigure.

[ROS 2 with ONNX Runtime](https://github.com/ms-iot/ros_msft_onnx) is a program that uses ROS 2 to run on different hardware platforms using their respective AI acceleration libraries for optimized execution of the ONNX model.

[Azure Cognitive Services LUIS ROS Node](https://github.com/ms-iot/ros_msft_luis) is a ROS node that bridges between ROS and the Azure Language Understanding Service. it can be configured to process audio directly from a microphone, or can subscribe to a ROS audio topic, then processes speech and generates "intent" ROS messages which can be processed by another ROS node to generate ROS commands.

# Linear Algebra
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124998626-9a1b4680-e001-11eb-9a49-1e97604e8a10.png">
  <br />
</p>

# Linear Algebra Learning Resources

[Linear algebra](https://en.wikipedia.org/wiki/Linear_algebra) is the math of vectors and matrices. The only prerequisite for this guide is a basic understanding of high school math concepts like numbers, variables, equations, and the fundamental arithmetic operations on real numbers: addition (denoted +), subtraction (denoted −), multiplication (denoted implicitly), and division (fractions). Also, you should also be familiar with functions that take real numbers as inputs and give real numbers as outputs, f : R → R.

[Linear Algebra - Online Courses | Harvard University](https://online-learning.harvard.edu/course/linear-algebra)

[Linear Algebra | MIT Open Learning Library](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+18.06SC+2T2019/about)

[Linear Algebra - Khan Academy](https://www.khanacademy.org/math/linear-algebra)

[Top Linear Algebra Courses on Coursera](https://www.coursera.org/courses?query=linear%20algebra)

[Mathematics for Machine Learning: Linear Algebra on Coursera](https://www.coursera.org/learn/linear-algebra-machine-learning)

[Top Linear Algebra Courses on Udemy](https://www.udemy.com/topic/linear-algebra/)

[Learn Linear Algebra with Online Courses and Classes on edX](https://www.edx.org/learn/linear-algebra)

[The Math of Data Science: Linear Algebra Course on edX](https://www.edx.org/course/math-of-data-science-linear-algebra)

[Linear Algebra in Twenty Five Lectures | UC Davis](https://www.math.ucdavis.edu/~linear/linear.pdf)

[Linear Algebra | UC San Diego Extension](https://extension.ucsd.edu/courses-and-programs/linear-algebra-1)

[Linear Algebra for Machine Learning | UC San Diego Extension](https://extension.ucsd.edu/courses-and-programs/linear-algebra-for-machine-learning)

[Introduction to Linear Algebra, Interactive Online Video | Wolfram](http://www.wolfram.com/wolfram-u/introduction-to-linear-algebra/)

[Linear Algebra Resources | Dartmouth](https://math.dartmouth.edu/~trs/linear-algebra-resources.php)

#  Defintions

### i. Vector operations

We now define the math operations for vectors. The operations we can perform on vectors ~u = (u1, u2, u3) and ~v = (v1, v2, v3) are: addition, subtraction, scaling, norm (length), dot product, and cross product:

The dot product and the cross product of two vectors can also be described in terms of the angle θ between the two vectors.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398163-26a7cb00-dcc9-11eb-9b70-3452d50762c5.png">
  <br />
</p>

**Vector Operations. Source: [slideserve](https://www.slideserve.com/krystal/streaming-simd-extension-sse)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124399554-fbc17500-dcd0-11eb-96b0-c31df664425a.png">
  <br />
</p>

**Vector Operations. Source: [pinterest](https://www.pinterest.com/pin/41799102767414798/)**

### ii. Matrix operations

We denote by A the matrix as a whole and refer to its entries as aij .The mathematical operations defined for matrices are the following:

• determinant (denoted det(A) or |A|)
Note that the matrix product is not a commutative operation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398167-2ad3e880-dcc9-11eb-9455-9b0c3c6171cd.png">
  <br />
</p>

**Matrix Operations. Source: [SDSU Physics](https://sdsu-physics.org/math/pages/435_LA_ch2.html)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398169-2c051580-dcc9-11eb-934a-71c691325062.png">
  <br />
</p>

**Check for modules that allow Matrix Operations. Source: [DPS Concepts](https://dspconcepts.com/forums/audio-weaver-designer/347-check-modules-allow-matrix-operations)**

### iii. Matrix-vector product

The matrix-vector product is an important special case of the matrix product.

There are two fundamentally different yet equivalent ways to interpret the matrix-vector product. In the column picture, (C), the multiplication of the
matrix A by the vector ~x produces a linear combination of the columns of the matrix: ~y = A~x = x1A[:,1] + x2A[:,2], where A[:,1] and A[:,2] are the first and second columns of the matrix A. In the row picture, (R), multiplication of the matrix A by the vector ~x produces a column vector with coefficients equal to the dot products of rows of the matrix with the vector ~x.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398176-36bfaa80-dcc9-11eb-82c9-641f9ddd8563.png">
  <br />
</p>

**Matrix-vector product. Source: [wikimedia](https://commons.wikimedia.org/wiki/File:Matrix_vector_product_qtl1.svg)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398178-38896e00-dcc9-11eb-94c4-2b2fa7499989.png">
  <br />
</p>

**Matrix-vector Product. Source: [mathisfun](https://www.mathsisfun.com/algebra/scalar-vector-matrix.html)**

### iv. Linear transformations

The matrix-vector product is used to define the notion of a linear transformation, which is one of the key notions in the study of linear algebra. Multiplication by a matrix A ∈ R m×n can be thought of as computing a linear transformation TA that takes n-vectors as inputs and produces m-vectors as outputs:

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398182-3fb07c00-dcc9-11eb-815a-d31e591fe218.png">
  <br />
</p>

**Linear Transformations. Source: [slideserve](https://www.slideserve.com/hall-cobb/chap-6-linear-transformations)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398184-40e1a900-dcc9-11eb-90e9-36031124610f.png">
  <br />
</p>

**Elementary matrices for linear transformations in R^2. Source:[Quora](https://www.quora.com/What-is-a-linear-transformation)**

### v. Fundamental vector spaces

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398197-4fc85b80-dcc9-11eb-9abc-3741bda9b63e.png">
  <br />
</p>

**Fundamental theorem of linear algebra for Vector Spaces. Source: [wikimedia](https://en.wikipedia.org/wiki/Fundamental_theorem_of_linear_algebra)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398199-50f98880-dcc9-11eb-8fd0-994dc48f62d6.png">
  <br />
</p>

**Fundamental theorem of linear algebra. Source: [wolfram](https://mathworld.wolfram.com/FundamentalTheoremofLinearAlgebra.html)**

# Computational Linear Algebra

### i. Solving systems of equations

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398355-307dfe00-dcca-11eb-8668-ba037de5aca5.png">
  <br />
</p>

**System of Linear Equations by Graphing. Source: [slideshare](https://www.slideshare.net/JITENDRATHAKOR/systems-of-linear-equations-43550732)**

### ii. Systems of equations as matrix equations

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398360-34118500-dcca-11eb-94eb-81ee66a9dc8a.png">
  <br />
</p>

**Systems of equations as matrix equations. Source: [mathisfun](https://www.mathsisfun.com/algebra/systems-linear-equations-matrices.html?ref=binfind.com%2Fweb)**

# Computing the Inverse of a Matrix

In this section we’ll look at several different approaches for computing the inverse of a matrix. The matrix inverse is unique so no matter which
method we use to find the inverse, we’ll always obtain the same answer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398409-71761280-dcca-11eb-9add-d105af886569.png">
  <br />
</p>

**Inverse of 2x2 Matrix. Source: [pinterest](https://www.pinterest.com/pin/375276581446966518/)**

### i. Using row operations

One approach for computing the inverse is to use the Gauss–Jordan elimination procedure.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398532-0c6eec80-dccb-11eb-9c82-6a65916fa43a.png">
  <br />
</p>

**Elementray row operations. Source: [YouTube](http://www.youtube.com/watch?v=DH2JSYx52nk)**

### ii. Using elementary matrices

Every row operation we perform on a matrix is equivalent to a leftmultiplication by an elementary matrix.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398426-83f04c00-dcca-11eb-8dde-54deedff30f7.png">
  <br />
</p>

**Elementary Matrices. Source: [SDSU Physics](http://sdsu-physics.org/math/pages/435_LA_ch2.html)**

### iii. Transpose of a Matrix

Finding the inverse of a matrix is to use the Transpose method.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398574-34f6e680-dccb-11eb-8112-ca77aad96004.png">
  <br />
</p>

**Transpose of a Matrix. Source: [slideserve](https://www.slideserve.com/jaimin/matrix-inverse-and-transpose)**

# Other Linear Topics

In this section discuss a number of other important topics of linear algebra.

### i. Basis

Intuitively, a basis is any set of vectors that can be used as a coordinate system for a vector space. You are certainly familiar with the standard basis for the xy-plane that is made up of two orthogonal axes: the x-axis and the y-axis.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398635-a040b880-dccb-11eb-8d5f-0e6ec65b742d.png">
  <br />
</p>

**Basis. Source: [wikimedia](https://en.wikipedia.org/wiki/Basis_(linear_algebra))**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398636-a171e580-dccb-11eb-8a40-8e6a9e24b6af.png">
  <br />
</p>

**Change of Basis. Source: [wikimedia](https://en.wikipedia.org/wiki/Change_of_basis)**

### ii. Matrix representations of linear transformations

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398653-b9e20000-dccb-11eb-8985-1d203f52f131.png">
  <br />
</p>

**Matrix representations of linear transformations. Source: [slideserve](https://www.slideserve.com/sylvie/two-dimensional-geometric-transformations)**

### iii. Dimension and Basis for Vector Spaces

The dimension of a vector space is defined as the number of vectors in a basis for that vector space. Consider the following vector space S = span{(1, 0, 0),(0, 1, 0),(1, 1, 0)}. Seeing that the space is described by three vectors, we might think that S is 3-dimensional. This is not the case, however, since the three vectors are not linearly independent so they don’t form a basis for S. Two vectors are sufficient to describe any vector in S; we can write S = span{(1, 0, 0),(0, 1, 0)}, and we see these two vectors are linearly independent so they form a basis and dim(S) = 2. There is a general procedure for finding a basis for a vector space. Suppose you are given a description of a vector space in terms of m vectors V = span{~v1, ~v2, . . . , ~vm} and you are asked to find a basis for V and the dimension of V. To find a basis for V, you must find a set of linearly independent vectors that span V. We can use the Gauss–Jordan elimination procedure to accomplish this task. Write the vectors ~vi as the rows of a matrix M. The vector space V corresponds to the row space of the matrix M. Next, use row operations to find the reduced row echelon form (RREF) of the matrix M. Since row operations do not change the row space of the matrix, the row space of reduced row echelon form of the matrix M is the same as the row space of the original set of vectors. The nonzero rows in the RREF of the matrix form a basis for vector space V and the numbers of nonzero rows is the dimension of V.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398664-c5352b80-dccb-11eb-866e-61808bcf953d.png">
  <br />
</p>

**Basis and Dimension. Source: [sliderserve](https://www.slideserve.com/kalil/chapter-3-vector-space)**

### iv. Row space, columns space, and rank of a matrix

Recall the fundamental vector spaces for matrices that we defined in Section II-E: the column space C(A), the null space N (A), and the row space R(A). A standard linear algebra exam question is to give you a certain matrix A and ask you to find the dimension and a basis for each of its fundamental spaces. In the previous section we described a procedure based on Gauss–Jordan elimination which can be used “distill” a set of linearly independent vectors which form a basis for the row space R(A). We will now illustrate this procedure with an example, and also show how to use the RREF of the matrix A to find bases for C(A) and N (A).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398677-d67e3800-dccb-11eb-8052-dfd1b01920fd.png">
  <br />
</p>

**Row space and Column space. Source: [slideshare](https://www.slideshare.net/VishveshJasani/row-space-column-space-null-space-rank-nullity)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398679-d8e09200-dccb-11eb-8707-e340933063d4.png">
  <br />
</p>

**Row space and Column space. Source: [slideshare](http://www.slideshare.net/RonakMachhi/null-space-rank-and-nullity-theorem)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398681-d9792880-dccb-11eb-8c6f-0c483cf860a4.png">
  <br />
</p>

**Rank and Nullity. Source: [slideshare](https://www.slideshare.net/VishveshJasani/row-space-column-space-null-space-rank-nullity)**

### v. Invertible matrix theorem

There is an important distinction between matrices that are invertible and those that are not as formalized by the following theorem. Theorem. For an n×n matrix A, the following statements are equivalent:

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398692-e6961780-dccb-11eb-98d9-dae7199a6365.png">
  <br />
</p>

**Invertible Matrix theorem. Source: [SDSU Physics](https://sdsu-physics.org/math/pages/435_LA_ch2.html)**

### vi. Determinants

The determinant of a matrix, denoted det(A) or |A|, is a special way to combine the entries of a matrix that serves to check if a matrix is invertible or not.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398703-f9105100-dccb-11eb-8d4e-e6db343304ec.png">
  <br />
</p>

**Determinant of a Square Matrix. Source: [stackexchange](https://math.stackexchange.com/questions/1354148/proving-the-formula-for-finding-the-determinant-of-a-square-matrix)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398705-fa417e00-dccb-11eb-8d1f-0cbf01d77f3d.png">
  <br />
</p>

**Determinant of matrix. Source: [onlinemathlearning](https://www.onlinemathlearning.com/matrix-determinants.html)**

### vii. Eigenvalues and eigenvectors

The set of eigenvectors of a matrix is a special set of input vectors for which the action of the matrix is described as a simple scaling. When a matrix is multiplied by one of its eigenvectors the output is the same eigenvector multiplied by a constant A~eλ = λ~eλ. The constant λ is called an eigenvalue of A.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398717-03cae600-dccc-11eb-86f2-72a816b9231a.png">
  <br />
</p>

**Generalized EigenVectors. Source: [YouTube](https://www.youtube.com/watch?v=xyhaYHGZN-w)**

### viii. Linear Regression

[Linear regression](https://en.wikipedia.org/wiki/Linear_regression) is an approach to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered to be an explanatory variable, and the other is considered to be a dependent variable.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398722-0af1f400-dccc-11eb-9ac7-1de7c6e43ff5.png">
  <br />
</p>

**Multiple Linear Regression. Source: [Medium](https://medium.com/@subarna.lamsal1/multiple-linear-regression-sklearn-and-statsmodels-798750747755)**

# C/C++ Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297894-961e0d80-a111-11eb-81c3-e2bd2ac9a7cd.png">
  <br />
</p>

## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[Basics of Embedded C Programming for Beginners on Udemy](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)


## C/C++ Tools and Frameworks

[AWS SDK for C++](https://aws.amazon.com/sdk-for-cpp/)

[Azure SDK for C++](https://github.com/Azure/azure-sdk-for-cpp)

[Azure SDK for C](https://github.com/Azure/azure-sdk-for-c)

[C++ Client Libraries for Google Cloud Services](https://github.com/googleapis/google-cloud-cpp)

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems.

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed.

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language.

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library.

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).


# Python Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93133273-ce490380-f68b-11ea-81d0-7f6a3debe6c0.png">
  <br />
</p>

## Python Learning Resources

[Python](https://www.python.org) is an interpreted, high-level programming language. Python is used heavily in the fields of Data Science and Machine Learning.

[Python Developer’s Guide](https://devguide.python.org) is a comprehensive resource for contributing to Python – for both new and experienced contributors. It is maintained by the same community that maintains Python.

[Azure Functions Python developer guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference-python) is an introduction to developing Azure Functions using Python. The content below assumes that you've already read the [Azure Functions developers guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference).

[CheckiO](https://checkio.org/) is a programming learning platform and a gamified website that teaches Python through solving code challenges and competing for the most elegant and creative solutions.

[Python Institute](https://pythoninstitute.org)

[PCEP – Certified Entry-Level Python Programmer certification](https://pythoninstitute.org/pcep-certification-entry-level/)

[PCAP – Certified Associate in Python Programming certification](https://pythoninstitute.org/pcap-certification-associate/)

[PCPP – Certified Professional in Python Programming 1 certification](https://pythoninstitute.org/pcpp-certification-professional/)

[PCPP – Certified Professional in Python Programming 2](https://pythoninstitute.org/pcpp-certification-professional/)

[MTA: Introduction to Programming Using Python Certification](https://docs.microsoft.com/en-us/learn/certifications/mta-introduction-to-programming-using-python)

[Getting Started with Python in Visual Studio Code](https://code.visualstudio.com/docs/python/python-tutorial)

[Google's Python Style Guide](https://google.github.io/styleguide/pyguide.html)

[Google's Python Education Class](https://developers.google.com/edu/python/)

[Real Python](https://realpython.com)

[The Python Open Source Computer Science Degree by Forrest Knight](https://github.com/ForrestKnight/open-source-cs-python)

[Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science)

[Intro to Python by W3schools](https://www.w3schools.com/python/python_intro.asp)

[Codecademy's Python 3 course](https://www.codecademy.com/learn/learn-python-3)

[Learn Python with Online Courses and Classes from edX](https://www.edx.org/learn/python)

[Python Courses Online from Coursera](https://www.coursera.org/courses?query=python)

## Python Frameworks, Libraries, and Tools

[Python Package Index (PyPI)](https://pypi.org/) is a repository of software for the Python programming language. PyPI helps you find and install software developed and shared by the Python community.

[PyCharm](https://www.jetbrains.com/pycharm/) is the best IDE I've ever used. With PyCharm, you can access the command line, connect to a database, create a virtual environment, and manage your version control system all in one place, saving time by avoiding constantly switching between windows.

[Python Tools for Visual Studio(PTVS)](https://microsoft.github.io/PTVS/) is a free, open source plugin that turns Visual Studio into a Python IDE. It supports editing, browsing, IntelliSense, mixed Python/C++ debugging, remote Linux/MacOS debugging, profiling, IPython, and web development with Django and other frameworks.

[Django](https://www.djangoproject.com/) is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.

[Flask](https://flask.palletsprojects.com/) is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries.

[Web2py](http://web2py.com/) is an open-source web application framework written in Python allowing allows web developers to program dynamic web content. One web2py instance can run multiple web sites using different databases.

[AWS Chalice](https://github.com/aws/chalice) is a framework for writing serverless apps in python. It allows you to quickly create and deploy applications that use AWS Lambda.

[Tornado](https://www.tornadoweb.org/) is a Python web framework and asynchronous networking library. Tornado uses a non-blocking network I/O, which can scale to tens of thousands of open connections.

[HTTPie](https://github.com/httpie/httpie) is a command line HTTP client that makes CLI interaction with web services as easy as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers.

[Scrapy](https://scrapy.org/) is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages. It can be used for a wide range of purposes, from data mining to monitoring and automated testing.

[Sentry](https://sentry.io/) is a service that helps you monitor and fix crashes in realtime. The server is in Python, but it contains a full API for sending events from any language, in any application.

[Pipenv](https://github.com/pypa/pipenv) is a tool that aims to bring the best of all packaging worlds (bundler, composer, npm, cargo, yarn, etc.) to the Python world.

[Python Fire](https://github.com/google/python-fire) is a library for automatically generating command line interfaces (CLIs) from absolutely any Python object.

[Bottle](https://github.com/bottlepy/bottle) is a fast, simple and lightweight [WSGI](https://www.wsgi.org/) micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the [Python Standard Library](https://docs.python.org/library/).

[CherryPy](https://cherrypy.org) is a minimalist Python object-oriented HTTP web framework.

[Sanic](https://github.com/huge-success/sanic) is a Python 3.6+ web server and web framework that's written to go fast.

[Pyramid](https://trypyramid.com) is a small and fast open source Python web framework. It makes real-world web application development and deployment more fun and more productive.

[TurboGears](https://turbogears.org) is a hybrid web framework able to act both as a Full Stack framework or as a Microframework.

[Falcon](https://falconframework.org/) is a reliable, high-performance Python web framework for building large-scale app backends and microservices with support for MongoDB, Pluggable Applications and autogenerated Admin.

[Neural Network Intelligence(NNI)](https://github.com/microsoft/nni) is an open source AutoML toolkit for automate machine learning lifecycle, including [Feature Engineering](https://github.com/microsoft/nni/blob/master/docs/en_US/FeatureEngineering/Overview.md), [Neural Architecture Search](https://github.com/microsoft/nni/blob/master/docs/en_US/NAS/Overview.md), [Model Compression](https://github.com/microsoft/nni/blob/master/docs/en_US/Compressor/Overview.md) and [Hyperparameter Tuning](https://github.com/microsoft/nni/blob/master/docs/en_US/Tuner/BuiltinTuner.md).

[Dash](https://plotly.com/dash) is a popular Python framework for building ML & data science web apps for Python, R, Julia, and Jupyter.

[Luigi](https://github.com/spotify/luigi) is a Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built-in.

[Locust](https://github.com/locustio/locust) is an easy to use, scriptable and scalable performance testing tool.

[spaCy](https://github.com/explosion/spaCy) is a library for advanced Natural Language Processing in Python and Cython.

[NumPy](https://www.numpy.org/) is the fundamental package needed for scientific computing with Python.

[Pillow](https://python-pillow.org/) is a friendly PIL(Python Imaging Library) fork.

[IPython](https://ipython.org/) is a command shell for interactive computing in multiple programming languages, originally developed for the Python programming language, that offers enhanced introspection, rich media, additional shell syntax, tab completion, and rich history.

[GraphLab Create](https://turi.com/) is a Python library, backed by a C++ engine, for quickly building large-scale, high-performance machine learning models.

[Pandas](https://pandas.pydata.org/) is a fast, powerful, and easy to use open source data structrures, data analysis and manipulation tool, built on top of the Python programming language.

[PuLP](https://coin-or.github.io/pulp/) is an Linear Programming modeler written in python. PuLP can generate LP files and call on use highly optimized solvers, GLPK, COIN CLP/CBC, CPLEX, and GUROBI, to solve these linear problems.

[Matplotlib](https://matplotlib.org/) is a 2D plotting library for creating static, animated, and interactive visualizations in Python. Matplotlib produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.

# R Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/126396985-130c91c7-9db4-4b74-90f8-d11c1876fdd4.png">
  <br />
</p>

## R Learning Resources

[R](https://www.r-project.org/) is an open source software environment for statistical computing and graphics. It compiles and runs on a wide variety of  platforms such as Windows and MacOS.

[An Introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf)

[Google's R Style Guide](https://google.github.io/styleguide/Rguide.html)

[R developer's guide to Azure](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/r-developers-guide)

[Running R at Scale on Google Compute Engine](https://cloud.google.com/solutions/running-r-at-scale)

[Running R on AWS](https://aws.amazon.com/blogs/big-data/running-r-on-aws/)

[RStudio Server Pro for AWS](https://aws.amazon.com/marketplace/pp/RStudio-RStudio-Server-Pro-for-AWS/B06W2G9PRY)

[Learn R by Codecademy](https://www.codecademy.com/learn/learn-r)

[Learn R Programming with Online Courses and Lessons by edX](https://www.edx.org/learn/r-programming)

[R Language Courses by Coursera](https://www.coursera.org/courses?query=r%20language)

[Learn R For Data Science by Udacity](https://www.udacity.com/course/programming-for-data-science-nanodegree-with-R--nd118)

## R Tools, Libraries, and Frameworks

[RStudio](https://rstudio.com/) is an integrated development environment for R and Python, with a console, syntax-highlighting editor that supports direct code execution, and tools for plotting, history, debugging and workspace management.

[Shiny](https://shiny.rstudio.com/) is a newer package from RStudio that makes it incredibly easy to build interactive web applications with R.

[Rmarkdown ](https://rmarkdown.rstudio.com/) is a package helps you create dynamic analysis documents that combine code, rendered output (such as figures), and prose.

[Rplugin](https://github.com/JetBrains/Rplugin) is R Language supported plugin for the IntelliJ IDE.

[Plotly](https://plotly-r.com/) is an R package for creating interactive web graphics via the open source JavaScript graphing library [plotly.js](https://github.com/plotly/plotly.js).

[Metaflow](https://metaflow.org/) is a Python/R library that helps scientists and engineers build and manage real-life data science projects. Metaflow was originally developed at Netflix to boost productivity of data scientists who work on a wide variety of projects from classical statistics to state-of-the-art deep learning.

[Prophet](https://facebook.github.io/prophet) is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data.

[LightGBM](https://lightgbm.readthedocs.io/) is a gradient boosting framework that uses tree based learning algorithms, used for ranking, classification and many other machine learning tasks.

[Dash](https://plotly.com/dash) is a Python framework for building analytical web applications in Python, R, Julia, and Jupyter.

[MLR](https://mlr.mlr-org.com/) is Machine Learning in R.

[ML workspace](https://github.com/ml-tooling/ml-workspace) is an all-in-one web-based IDE specialized for machine learning and data science. It is simple to deploy and gets you started within minutes to productively built ML solutions on your own machines. ML workspace is the ultimate tool for developers preloaded with a variety of popular data science libraries (Tensorflow, PyTorch, Keras, and MXnet) and dev tools (Jupyter, VS Code, and Tensorboard) perfectly configured, optimized, and integrated.

[CatBoost](https://catboost.ai/) is a fast, scalable, high performance Gradient Boosting on Decision Trees library, used for ranking, classification, regression and other machine learning tasks for Python, R, Java, C++. Supports computation on CPU and GPU.

[Plumber](https://www.rplumber.io/) is a tool that allows you to create a web API by merely decorating your existing R source code with special comments.

[Drake](https://docs.ropensci.org/drake) is an R-focused pipeline toolkit for reproducibility and high-performance computing.

[DiagrammeR](https://visualizers.co/diagrammer/) is a package you can create, modify, analyze, and visualize network graph diagrams. The output can be incorporated into R Markdown documents, integrated with Shiny web apps, converted to other graph formats, or exported as image files.

[Knitr](https://yihui.org/knitr/) is a general-purpose literate programming engine in R, with lightweight API's designed to give users full control of the output without heavy coding work.

[Broom](https://broom.tidymodels.org/) is a tool that converts statistical analysis objects from R into tidy format.

# Julia Development
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94961900-6e839280-04aa-11eb-84c6-2fb3f83e2b90.png">
  <br />
</p>


## Julia Learning Resources

[Julia](https://julialang.org) is a high-level, [high-performance](https://julialang.org/benchmarks/) dynamic language for technical computing. Julia programs compile to efficient native code for [multiple platforms](https://julialang.org/downloads/#support_tiers) via LLVM.

[JuliaHub](https://juliahub.com/) contains over 4,000 Julia packages for use by the community.

[Julia Observer](https://www.juliaobserver.com)

[Julia Manual](https://docs.julialang.org/en/v1/manual/getting-started/)

[JuliaLang Essentials](https://docs.julialang.org/en/v1/base/base/)

[Julia Style Guide](https://docs.julialang.org/en/v1/manual/style-guide/)

[Julia By Example](https://juliabyexample.helpmanual.io/)

[JuliaLang Gitter](https://gitter.im/JuliaLang/julia)

[DataFrames Tutorial using Jupyter Notebooks](https://github.com/bkamins/Julia-DataFrames-Tutorial/)

[Julia Academy](https://juliaacademy.com/courses?preview=logged_out)

[Julia Meetup groups](https://www.meetup.com/topics/julia/)

[Julia on Microsoft Azure](https://juliacomputing.com/media/2017/02/08/azure.html)

## Julia Tools, Libraries and Frameworks

[JuliaPro](https://juliacomputing.com/products/juliapro.html) is a free and fast way to setup Julia for individual researchers, engineers, scientists, quants, traders, economists, students and others. Julia developers can build better software quicker and easier while benefiting from Julia's unparalleled high performance. It includes 2600+ open source packages or from a curated list of 250+ JuliaPro packages. Curated packages are tested, documented and supported by Julia Computing.

[Juno](https://junolab.org) is a powerful, free IDE based on [Atom](https://atom.io/) for the Julia language.

[Debugger.jl](https://github.com/JuliaDebug/Debugger.jl) is the Julia debuggin tool.

[Profile (Stdlib)](https://docs.julialang.org/en/v1/manual/profile/) is a module provides tools to help developers improve the performance of their code. When used, it takes measurements on running code, and produces output that helps you understand how much time is spent on individual line's.

[Revise.jl](https://github.com/timholy/Revise.jl) allows you to modify code and use the changes without restarting Julia. With Revise, you can be in the middle of a session and then update packages, switch git branches, and/or edit the source code in the editor of your choice; any changes will typically be incorporated into the very next command you issue from the REPL. This can save you the overhead of restarting Julia, loading packages, and waiting for code to JIT-compile.

[JuliaGPU](https://juliagpu.org/) is a Github organization created to unify the many packages for programming GPUs in Julia. With its high-level syntax and flexible compiler, Julia is well positioned to productively program hardware accelerators like GPUs without sacrificing performance.

[IJulia.jl](https://github.com/JuliaLang/IJulia.jl) is the Julia kernel for Jupyter.

[AWS.jl](https://github.com/JuliaCloud/AWS.jl) is a Julia interface for [Amazon Web Services](https://aws.amazon.com/).

[CUDA.jl](https://juliagpu.gitlab.io/CUDA.jl) is a package for the main programming interface for working with NVIDIA CUDA GPUs using Julia. It features a user-friendly array abstraction, a compiler for writing CUDA kernels in Julia, and wrappers for various CUDA libraries.

[XLA.jl](https://github.com/JuliaTPU/XLA.jl) is a package for compiling Julia to XLA for [Tensor Processing Unit(TPU)](https://cloud.google.com/tpu/).

[Nanosoldier.jl](https://github.com/JuliaCI/Nanosoldier.jl) is a package for running JuliaCI services on MIT's Nanosoldier cluster.

[Julia for VSCode](https://www.julia-vscode.org) is a powerful extension for the Julia language.

[JuMP.jl](https://jump.dev/) is a domain-specific modeling language for [mathematical optimization](https://en.wikipedia.org/wiki/Mathematical_optimization) embedded in Julia.

[Optim.jl](https://github.com/JuliaNLSolvers/Optim.jl) is a univariate and multivariate optimization in Julia.

[RCall.jl](https://github.com/JuliaInterop/RCall.jl) is a package that allows you to call R functions from Julia.

[JavaCall.jl](http://juliainterop.github.io/JavaCall.jl) is a package that allows you to call Java functions from Julia.

[PyCall.jl](https://github.com/JuliaPy/PyCall.jl) is a package that allows you to call Python functions from Julia.

[MXNet.jl](https://github.com/dmlc/MXNet.jl) is the Apache MXNet Julia package. MXNet.jl brings flexible and efficient GPU computing and state-of-art deep learning to Julia.

[Knet](https://denizyuret.github.io/Knet.jl/latest) is the [Koç University deep](http://www.ku.edu.tr/en) learning framework implemented in Julia by [Deniz Yuret](https://www.denizyuret.com/) and collaborators. It supports GPU operation and automatic differentiation using dynamic computational graphs for models defined in plain Julia.

[Distributions.jl](https://github.com/JuliaStats/Distributions.jl) is a Julia package for probability distributions and associated functions.

[DataFrames.jl](http://juliadata.github.io/DataFrames.jl/stable/) is a tool for working with tabular data in Julia.

[Flux.jl](https://fluxml.ai/) is an elegant approach to machine learning. It's a 100% pure-Julia stack, and provides lightweight abstractions on top of Julia's native GPU and AD support.

[IRTools.jl](https://github.com/FluxML/IRTools.jl) is a simple and flexible IR format, expressive enough to work with both lowered and typed Julia code, as well as external IRs.

[Cassette.jl](https://github.com/jrevels/Cassette.jl) is a Julia package that provides a mechanism for dynamically injecting code transformation passes into Julia’s just-in-time (JIT) compilation cycle, enabling post hoc analysis and modification of "Cassette-unaware" Julia programs without requiring manual source annotation or refactoring of the target code.


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Autonomous-Systems-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Autonomous-Systems-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
