# wsSysHealth

* A simple webservice for system health check.
* The access url is http://IP:8080/sysHealth
* The expected response is "good" 

# INSTALLATION

## INSTALL web.py module of python

    $ pip install web.py
    
## INSTALL this script to YOUR_ROS_PACKAGE

    $ git clone this project to folder ~/wsSysHealth
    $ roscd YOUR_ROS_PACKAGE
    $ mkdir scripts
    $ cd scripts
    $ cp ~/wsSysHealth/wsSysHealth.py .
    $ chmod 755 wsSysHealth.py
 

# Run

    $ rosrun YOUR_ROS_PACKAGE wsSysHealth.py
