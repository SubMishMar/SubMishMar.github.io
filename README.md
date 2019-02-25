# Welcome to my Webpage

<img style="float: left;" src="images/personalpic.jpg">

<div style="text-align: justify"> I am a Ph.D. student at the Department of Mechanical Engineering, <a href="https://www.tamu.edu/">Texas A&M University</a>, working under the supervision of <a href="https://engineering.tamu.edu/mechanical/profiles/saripalli.html">Dr. Srikanth Saripalli</a> of the <a href="https://unmanned.tamu.edu/">Unmanned Systems Lab</a>. My research interests are focused on Mobile Robot Localization and Mapping. I have a MS in Control Systems Engineering from <a href="https://www.ec-nantes.fr/">École centrale de Nantes</a>, France and I did my <a href="https://github.com/SubMishMar/SubMishMar.github.io/blob/master/thesis/Master_Internship_Report_MISHRA_Subodh%5BRevised%5D.pdf">MS Thesis</a> at <a href="https://www.laas.fr/public/">LAAS-CNRS</a>, Toulouse, under the guidance of <a href="http://homepages.laas.fr/afranchi/robotics/?q=node/1">Dr. Antonio Franchi</a> on <a href="https://youtu.be/o9xmPYNPfRE">Aerial+Ground Co-Manipulation</a>. I have a B.Tech. in Electrical Engineering from <a href="http://www.nitrkl.ac.in/">National Institute of Technology-Rourkela</a>, India.</div>

<center> <a href="https://www.linkedin.com/in/subodh-mishra/">LinkedIn</a> / <a href="https://github.com/SubMishMar">GitHub</a> / <a href="https://scholar.google.com/citations?user=4dltZR4AAAAJ&hl=en">Google Scholar</a> </center>

# Current Research
* **Augmented SLAM with Online Multi-Sensor Calibration**: I am starting to work on this project and intend to work on it for my Ph.D. The basic problem I want to address here is to add the external calibration parameters of all the sensors to the SLAM state vector. Until now much of the SLAM pipelines that have been written with the assumption that the external calibration parameters are known a-priori. But, this is far from the truth as in real world these parameters may vary with time.

* **SURVIVABLE NETWORKS OF ROBOTS FOR ADVERSITY: RECOVERABILITY AND EXPENDABILITY**: I have been involved with this project for the past 1 year. We are working on developing algorithms for cheap drones which can be used for exploring an adversarial environment. We are using [Skyviper v2450](https://www.amazon.com/Sky-Viper-v2450GPS-Streaming-Autopilot/dp/B072HH13VQ) for verifying our methods in the real world. The drone may die in the process but it's experience must help the drones which explore the same environment later. This is done by modelling the entire problem as a *Markov Decision Process*. I am working on system integration and field implementation of algorithms written by co-workers. To this end, I have gained expertise in tuning Extended Kalman Filters, ArUco Marker based Localization, programming under the ROS framework and familiarity with the ArduCopter firmware. 

# Past Experience

* **Indoor SLAM using RGB-D sensor**: During the summer of 2018, I worked in a start-up called Perceptin (now called Trifo) and I was working with the Mapping and Localization team where we used cheap RGB-D sensors to do 2D SLAM in indoor environment using state of the art open sourced software.

* **Aerial+Ground Co-Manipulation**: I worked on Aerial+Ground co-manipulation system for my master thesis at[LAAS-CNRS](https://www.laas.fr/public/en) under the guidance of [Dr. Antonio Franchi](https://homepages.laas.fr/afranchi/robotics/?q=node/1). My primary contribution was software integration of various subcomponents like The KUKA IIWA LBR14 manipulator & a [Tilted Rotor Hexcopter](https://hal.laas.fr/hal-01716845/document) and also exploring means to avoid the usage of motion capture system. To this end, I tested various visual odometry algorithms and we had concluded that during that time, ORB_SLAM seemed to be a great choice for doing SLAM on Aerial Robotic platform for Aerial Ground Co-Manipulation. Details can be found in my [MS thesis](https://github.com/SubMishMar/SubMishMar.github.io/blob/master/thesis/Master_Internship_Report_MISHRA_Subodh%5BRevised%5D.pdf).

# Other Relevant Stuff
Here I present some other not so important but relevant stuff that I have been tinkering/tinkered with in the past 1 year of grad school.

* **EKF-SLAM in MATLAB**: This is very simplistic EKF based approach to do SLAM using MATLAB, especially for begineers. The code can be founded [here](https://github.com/SubMishMar/EKF-SLAM).

* **Monocular Visual Odometry**: Simple monocular visual odometry pipeline which takes the scale information from ground truth. The code can be founded [here](https://github.com/SubMishMar/movo).
