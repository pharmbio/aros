# AROS - Open Automated Robotic System for Biological Laboratories

This is the landing page for a suite of open soruce components for lab automation. The initial system was developed to automate morphological profiling according to the [Cell Painting protocol](https://www.nature.com/articles/nprot.2016.105) (high-content imaging using multiple dyes) but the componets are general and can be used in other settings as well.

Contact: Prof. Ola Spjuth. ola.spjuth@farmbio.uu.se. Research group website: https://pharmb.io

## Repos:

### Cell painting using the UR robotarm
Cell painting using the UR robot arm
<br>
https://github.com/pharmbio/robot-cellpainter

### Lab Robots http server
A unified http api to all robots in the AROS system. The http api wraps around various vendor-specific api:s for communication.
<br>
https://github.com/pharmbio/robotlab-labrobots 

### AROS DB
Database in the center of the system, managing images, projects, experiment design, data, metadata, and much more...
<br>
https://github.com/pharmbio/imagedb

### Robot Lab Cameras
Streaming cameras setup for live monitoring of the system via Grafana dashboards
<br>
https://github.com/pharmbio/robot_lab_cameras

### Robot Lab Grafana Dashboards
Grafana dashboards for monitoring of the lab sensors and robots 
<br>
https://github.com/pharmbio/robot_lab_grafana_dashboards

### Robot Lab Prometheus Exporters
Prometheus exporters for lab sensors and robot status
<br>
https://github.com/pharmbio/robot_lab_prometheus_exporters

### DIY Automated Shaker Robot
Modifications to provide Arduino nano controlled Fisherbrand plate shaker.
<br>
https://github.com/pharmbio/shaker-robot

### DIY Automated Incubator
Modifications to provide automatic door opener on existing incubator
<br>
https://github.com/pharmbio/incubator-automation

### Automation Experimental Planning + GUI
Experimental design software
<br>
https://github.com/pharmbio/lab-design
