# wsSysHealth

* A simple webservice for system health check.
* The access url is http://IP:8080/sysHealth
* The expected response is "good" 

# INSTALLATION

## INSTALL web.py module of python

    $ sudo pip install web.py      ## Don't worry about the warning messages
    
## INSTALL this script to YOUR_ROS_PACKAGE

    $ git clone this project to folder ~/wsSysHealth
    $ roscd YOUR_ROS_PACKAGE
    $ mkdir scripts                ## Create scripts folder if it doesn't exist
    $ cd scripts
    $ cp ~/wsSysHealth/wsSysHealth.py .    ## Copy the file to the scrips folder
    $ chmod 755 wsSysHealth.py             ## Make it executable
 

# Run

    $ rosrun YOUR_ROS_PACKAGE wsSysHealth.py
