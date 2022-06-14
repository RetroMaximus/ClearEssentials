# ClearEssentials 

Reffered to as (CE)

Pure Data externals written by Reg Finley aka ScriptAlias
for the Pure Data programming language

Version: 1.0-0 

Copyright © 2022 Reg Finley
This work is free. You can redistribute it and/or modify it under the terms of the The UnLicense, See https://github.com/RetroMaximus/ClearEssentials/blob/main/LICENSE for more details.

Other licenses may apply for specific objects.

About Clear Essentials
This version of Clear Essentials needs Pd 0.52-1 or above.

CE is a small library of externals that extends the performance Pure Data (Pd) - Miller S. Puckette's realtime computer music environment (download Pd from: http://msp.ucsd.edu/software.html).

CE library's repository resides at https://github.com/RetroMaximus/ClearEssentials. 

​This project is still in an experimental phase, where changes may occur and backwards compatibility is not guaranteed until a final and more stable release is available.

Download CE:
​ You can get CE from https://github.com/RetroMaximus/ClearEssentials/releases - where all releases are available, CE is currently not found via Pd's external manager. In any case, you should download the folder to a place Pd automatically searches for, and the common place is the ~/documents/pd/externals folder. Instructions on how to install CE are provided below.

Install CE:
​ 
Copy the contents of this library to pd/externals/clearessentials

About CE

CE is a collection of patches written by Reg Finley. These are not ment to re-invent the wheel
There are many other robust libraries avalible that provide solutions that do not need to be repeated.
CE primary focus will be to provide a bit more of a graphical interface with customizeable options to get closer to that end result. While most patches contained in this external library will be more gui intesive (limited to pd vanilla) the option to hide the gui will be avlaible in the case of the patch being used on a headless device.

A good example of this is the [vocadsr] object. A full gui is provided with option to set new values to all of the gui elements. While midi notes can still be recieved when [vocadsr] is not visible.

Acknowledgements
​ Special thanks the facebook group Pure Data and folks at https://forum.pdpatchrepo.info/ all of your answers over the years has given the confidence to start and compile this library.