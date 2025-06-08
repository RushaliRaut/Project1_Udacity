# Project1_Udacity
This repository has been created for demonstrating how to create a office like environment in Gazebo, Print a message on the console when the office file is opened &amp; how to create a model(Here in this directory i have created a humanoid robot model). 


/********************* As mentioned in the udacity project1 submission criteria we have to follow below hierarchy for the project **********/


 .Project1                          # Build My World Project 
    ├── model                          # Model files 
    │   ├── Building
    │   │   ├── model.config
    │   │   ├── model.sdf
    │   ├── HumanoidRobot
    │   │   ├── model.config
    │   │   ├── model.sdf
    ├── script                         # Gazebo World plugin C++ script      
    │   ├── welcome_message.cpp
    ├── world                          # Gazebo main World containing models 
    │   ├── UdacityOffice.world
    ├── CMakeLists.txt                 # Link libraries 
