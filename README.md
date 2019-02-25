# Welcome to my Webpage

<img style="float: left;" src="images/personalpic.jpg">

I am a Ph.D. student at [Texas A&M University](https://www.tamu.edu/), working under the supervision of [Dr. Srikanth Saripalli](https://engineering.tamu.edu/mechanical/profiles/saripalli.html) of the [Unmanned Systems Lab](https://unmanned.tamu.edu/).  My research interests are Robot State Estimation, Perception and Sensor Calibration. 

I have a Master's degree in Control Systems Engineering from [École centrale de Nantes](https://www.ec-nantes.fr/), France. I did my [MS thesis](https://github.com/SubMishMar/SubMishMar.github.io/blob/master/thesis/Master_Internship_Report_MISHRA_Subodh%5BRevised%5D.pdf) at [LAAS-CNRS](https://www.laas.fr/public/en) under the guidance of [Dr. Antonio Franchi](https://homepages.laas.fr/afranchi/robotics/?q=node/1) on the topic of [Aerial+Ground Co-Manipulation Systems](https://youtu.be/o9xmPYNPfRE).

I have a Bachelor's degree in Electrical Engineering from [NIT-Rourkela](http://www.nitrkl.ac.in/), India.

<center> <a href="https://www.linkedin.com/in/subodh-mishra/">LinkedIn</a> / <a href="https://github.com/SubMishMar">GitHub</a> / <a href="https://scholar.google.com/citations?user=4dltZR4AAAAJ&hl=en">Google Scholar</a> </center>

# Current Research
* **Augmented SLAM with Online Multi-Sensor Calibration**: I am starting to work on this project and intend to work on it for my Ph.D. The basic problem I want to address here is to add the external calibration parameters of all the sensors to the SLAM state vector. Until now much of the SLAM pipelines that have been written with the assumption that the external calibration parameters are known a-priori. But, this is far from the truth as in real world these parameters may vary with time.

* **SURVIVABLE NETWORKS OF ROBOTS FOR ADVERSITY: RECOVERABILITY AND EXPENDABILITY**: I have been involved with this project for the past 1 year. We are working on developing algorithms for cheap drones which can be used for exploring an adversarial environment. We are using [Skyviper v2450](https://www.amazon.com/Sky-Viper-v2450GPS-Streaming-Autopilot/dp/B072HH13VQ) for verifying our methods in the real world. The drone may die in the process but it's experience must help the drones which explore the same environment later. This is done by modelling the entire problem as a *Markov Decision Process*. I am working on system integration and field implementation of algorithms written by co-workers. To this end, I have gained expertise in tuning Extended Kalman Filters, ArUco Marker based Localization, programming under the ROS framework and familiarity with the ArduCopter firmware. 

# Past Experience

* **Indoor SLAM using RGB-D sensor**: During the summer of 2018, I worked in a start-up called Perceptin (now called Trifo) and I was working with the Mapping and Localization team where we used cheap RGB-D sensors to do 2D SLAM in indoor environment using state of the art open sourced software.

* **Aerial+Ground Co-Manipulation**: I worked on Aerial+Ground co-manipulation system for my master thesis at[LAAS-CNRS](https://www.laas.fr/public/en) under the guidance of [Dr. Antonio Franchi](https://homepages.laas.fr/afranchi/robotics/?q=node/1). My primary contribution was software integration of various subcomponents like The KUKA IIWA LBR14 manipulator & a [Tilted Rotor Hexcopter](https://hal.laas.fr/hal-01716845/document) and also exploring means to avoid the usage of motion capture system. To this end, I tested various visual odometry algorithms and we had concluded that during that time, ORB_SLAM seemed to be a great choice for doing SLAM on Aerial Robotic platform for Aerial Ground Co-Manipulation. Details can be found in my [MS thesis](https://github.com/SubMishMar/SubMishMar.github.io/blob/master/thesis/Master_Internship_Report_MISHRA_Subodh%5BRevised%5D.pdf).

# Other Relevant Stuff
Here I present some other not so important but relevant stuff that I have been tinkering/tinkered with in the past 1 year of grad school.

* **EKF-SLAM in MATLAB**: This is very simplistic approach to doing SLAM especially for begineers. The code can be founded [here](https://github.com/SubMishMar/EKF-SLAM). ![EKF-SLAM](https://github.com/SubMishMar/EKF-SLAM/blob/master/gif/EKF-SLAM.gif)

* **Monocular Visual Odometry**: Simple monocular visual odometry pipeline which takes the scale information from ground truth. The code can be founded [here](https://github.com/SubMishMar/movo). [image](https://github.com/SubMishMar/movo/blob/master/docs/screenshot.png)

