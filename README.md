# Self-Driving-Car-using-Deep-Q-Learnning
Self Driving car using Deep Q learning : A course project for the course ENPM 808F Robot Learning

To start the simulation run the Simulation file. 
Obstacle or road can be created using right click of the mouse.
To save the training data , press save button on the graphical interface.
Press load button to load the last saved training data.

Requirement :
#Anaconda 
https://www.continuum.io/downloads

Download the right installer of python 3.6 (64-bit if you are on a 64-bit machine and 32-bit if you are on a 32-bit machine)

#Kivy
https://www.dropbox.com/s/wso12fmfd55ysus/Kivy-1.10.1.dev0-cp36-cp36m-win_amd64.whl?dl=0

Then , Open Anaconda Prompt as Admin
once the Anaconda Prompt is open, type in these commands in the order specified
Enter y to proceed when prompted.

1. conda install -c anaconda python=3.6.1
2. conda install -c peterjc123 pytorch=0.1.12

 Change the directory in the Anaconda Prompt to the known path where the kivy wheel was downloaded. ( For me this path is C:\Users\Indushekhar\Downloads, so change the below command accordingly for your system)
 cd C:\Users\Indushekhar\Downloads
 
Once the path has been changed succesfully, you should now enter these commands in the Anaconda prompt to install Kivy

1. pip install docutils pygments pypiwin32 kivy.deps.sdl2 kivy.deps.glew
2. pip install kivy.deps.gstreamer
3. pip install Kivy-1.10.1.dev0-cp36-cp36m-win_amd64.whl
