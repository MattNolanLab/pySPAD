# pySPAD

Welcome to pySPAD! 

pySPAD is a python-based tool which allows users to communicate with 
SPAD camera. It has various features from recording to data visualisation. Currently
the GUI can be used for two neuroscience applications:

1.In-vivo fiber photometry for neural population imaging

2.Light microscopy(either in vivo or in vitro depending on the concept)


## Dependencies

In order to use pySPAD, we strongly recommend you to use anaconda for python 
package management. 

Once you have anaconda, create a virtual environment with python 3.7. This is 
important because pySPAD and other dependent libraries work on this version. 
Using other versions might create support issues.You can create a new
 environment by running the following line on anaconda terminal:
	
	conda create --name pySPAD python=3.7

Once you have your virtual environment,you can activate it by using 
the following line:

	conda activate pySPAD 

Also, make sure to install the following 
libraries: 

pyqtgraph

pandas
 
matplotlib

scipy 

As a last step, please make sure you have Microsoft Visual C++ Redistributable. 
You can setup this via the following link: https://www.microsoft.com/en-us/download/details.aspx?id=40784
 

## Installation

pySPAD has been tested on both linux and windows operating systems(macOS version is also coming soon!).

To install pySPAD, first clone this repository into your computer(either using
git or by using GitHub website). 

Once you copied all the files to your computer, go to file directory and start 
anaconda terminal there. 

On terminal, simply run the following:

	python run.py

This line will open the GUI and you can now start to use your camera. 

  


