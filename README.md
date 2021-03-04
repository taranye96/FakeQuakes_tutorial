# FakeQuakes_tutorial

Hi!  I assume you are here because you are super excited about learning how to gererate synthetic earthquake data using FakeQuakes.  FakeQuakes is the set of semistochastic forward modeling codes from https://github.com/dmelgarm/MudPy.  

The jupyter notebook in this repository goes through how to define parameters and run the FakeQuakes code using the Mentawai region as an example. 
     - The figures folder just contains a few figures used in the jupyter notebook.  

The files folder contains the various files needed to run FakeQuakes.
     __sm.gflist__ contains the full list of strong motion seismic stations in the Mentawai region
     __sm_short.gflist__ contains 2 of the strong motion stations to make computation time short for the demo
     __mentawai_fine.fault__ is the finely-discretized fault model for the Mentawai region
     __mentawai_coarse.fault__ is the coarsely-discretized fault model to make computation time short for the demo
     __mentawai.mod__ is the velocity model for the Mentawai region

The demo folder is an example FakeQuakes project folder with output rupture models and waveforms that I generated.  You can just use this project folder to follow along with the jupyter notebook, or create your own.
