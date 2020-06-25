# Getting Started Tutorial

!!! important
    This example refers to the latest versions of CARLA (at least 0.9.5)


Download the latest release from our GitHub page and extract all the contents of
the package in a folder of your choice.


## Installing prerequisites
The current version is designed to be used with Win 64 bit, Python 3.8. 
Depending on your Python version, execute:

Note: py-trees newer than v0.8 is *NOT* supported.

#**********************************************************************************************************************
# Running scenario way 1
Start the example scenario (follow a leading vehicle) in an extra terminal:
```
python scenario_runner.py --scenario ** --reloadWorld
```

To control the ego vehicle within the scenario, open another terminal and run:
```
python manual_control.py
```

Note: If you do not wish to automatically (re-)load the CARLA world, you can
skip the command line option _--reloadWorld_

#**********************************************************************************************************************
# Running scenario way 2
double click the field RunCmd1.jar
copy the fisrt sentence from scenario list in the first cmd page and wating the environment running finish
copy the second sentence into the second cmd page

#**********************************************************************************************************************
# Scenarion list 

python scenario_runner.py --scenario ChangeLane --reloadWorld
python manual_control.py

python scenario_runner.py --scenario StationaryObjectCrossing_3 --reloadWorld
python manual_control.py

python scenario_runner.py --scenario OppositeVehicleRunningRedLight011 --reloadWorld
python manual_control.py

python scenario_runner.py --scenario DynamicObjectCrossing_1 --reloadWorld
python manual_control.py
