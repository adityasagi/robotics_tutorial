## Setup

To install Anaconda follow the instructions in the following webpage:  
https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart

Create a conda environment for the PyBullet tutorial:  
$ conda create --name pyb_env  

Switch to the newly create environment (you will notice the name of the environment on the command line in the extreme left):  
$ conda activate pyb_env  


Once in the desired environment install the following packages:  
$ conda install nb_conda_kernels  

Install PyBullet (while in the environment):  
$ pip install pybullet  


To check the installation launch:  
$ python  

Inside the python environment import the pybullet library:  
>> import pybullet

If this command executes without any error then the pybullet installation is successful.  


Check the Jupyter notebook by running the following command in the bash shell:  
$ jupyter notebook  

This command will provide a URL. Run the URL in a browser (Firefox). If a web page opens up, then the Jupyter software is successfully installed.  



## Agenda 

1) Kinematics of a serial-2R manipulator  
1a) Forward kinematics  
1b) Inverse kinematics  
1c) Verification of the FK and IK modules against each other  


2) Introduction to PyBullet  
2a) How to start a PyBullet session  
2b) Settings the simulation parameters in PyBullet  
2c) Loading URDF files in PyBullet  


3) Torque control of robot state in PyBullet  
3a) Obtaining joint information  
3b) Setting the control mode (and enabling the motors)  
3c) Control of joint torque  


4) PID control of robot  
4a) Reading the joint state  
4b) Determining the control action  
4c) Setting the required control torque  


5) Point-to-point tracking of end-effector  
5a) Obtaining the required joint angles to reach the desired end-effector position  
5b) Simulating a PID position control loop to reach the desired end-effector position  


6) Simulating an industrial robot (KUKA KR120)  
6a) Obtaining the URDF models for the robots  
6b) Loading the URDF model  
6c) Obtaining the joint information  
6d) Controlling the robot joints  



## References
1) PyBullet Quick start guide  
https://usermanual.wiki/Document/pybullet20quickstart20guide.479068914/html

2) Introduction to PyBullet  
https://alexanderfabisch.github.io/pybullet.html

2) Kinematics of serial-2R manipulators  
https://ed.iitm.ac.in/~sandipan/files/serialkinematicsv2.pdf

