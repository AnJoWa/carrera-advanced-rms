# Advanced Race Management System for Carrera Digital

This is an advanced race management system (RMS) for Carrera Digital implemented in python and forked from https://github.com/wachjose88/carrera-advanced-rms. This Version directly supports Fullscreen Mode via command line option and is subject to active development to add more features.

## Install and Run

To install the RMS at first the requirements have to be installed:

    pip install -r requirements.txt

Now you can run the RMS by changing into the rms directory and executing it with the following commands: 

    cd rms
    python main.py -cu CUADDRESS

CUADDRESS should be replaced by the adress of your Carrera Control Unit. This could be a bluetooth address, a serial port or "dummy" for debugging.
Add the option "-f" to directly run in fullscreen mode.
    
    python main.py -cu CUADDRESS -f

## Screenshots

![Homescreen](/screenshots/home.png)

![Racemode](/screenshots/race.png)

## Web Statistic

It is possible to upload the data to a web app in order to view different types of
statistics online. 

Source code of the web app: https://github.com/wachjose88/carrera-advanced-rms-statistic
