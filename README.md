# Cell-DEVS-Cadmium-Simulation-Environment

This is a parent repository containing a reference to all the Cell-DEVS Cadmium components developed by ARSLab at Carleton University.

It contains:

Cadmium Cell-DEVS: a heder only library to simulate DEVS models
DESTimes: a time class
Cell-DEVS-Models: a library with sample models
To download the whole environment clone this repository and then run:

git submodule update --init --recursive

To download an individual component (ex, Cell-DEVS-Models) clone this repository and then run:

git submodule update --init --remote --recursive -- Cell-DEVS-Models/

If it is your first time running a Cadmium model you need to setup your environment.

Cadmium user manual be found in:

http://www.sce.carleton.ca/courses/sysc-5104/lib/exe/fetch.php?media=cadmium.pdf
