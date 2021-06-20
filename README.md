# FakeQuakes_tutorial

Hi!  I assume you are here because you are super excited about learning how to generate synthetic earthquake data using FakeQuakes.  FakeQuakes is the set of semistochastic forward modeling codes from https://github.com/dmelgarm/MudPy.  

There are two different jupyter notebook's in this repository. 
<br>  - __FQ_walkthrough.ipynb__ explains some of the theory and goes through how to define parameters and run the FakeQuakes code using the Mentawai region as an example.
<br>  - __ROSES_FakeQuakes_lab.ipynb__ is the lab portion for the ROSES tutorial and 
has a couple exercises to practice using FakeQuakes. 

The figures folder just contains a few figures used in FQ_walkthrough.ipynb.  

The files folder contains the various files needed to run FakeQuakes.
<br>  - __sm.gflist__ is a station file and contains only 2 strong motion stations to make computation time short for the demo
<br>  - __mentawai.fault__ is a moderately-discretized fault model for the Mentawai region
<br>  - __mentawai.mod__ is the velocity model for the Mentawai region

The demo folder is an example FakeQuakes project folder with output rupture models and waveforms that I generated.  You can just use this project folder to follow along with the __FQ_walkthrough__ jupyter notebook, or create your own.

Have fun creating some earthquakes!
