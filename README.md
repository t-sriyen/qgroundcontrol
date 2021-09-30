#New add
# QGroundControl Ground Control Station

[![Releases](https://img.shields.io/github/release/mavlink/QGroundControl.svg)](https://github.com/mavlink/QGroundControl/releases)
[![Travis Build Status](https://travis-ci.org/mavlink/qgroundcontrol.svg?branch=master)](https://travis-ci.org/mavlink/qgroundcontrol)
[![Appveyor Build Status](https://ci.appveyor.com/api/projects/status/crxcm4qayejuvh6c/branch/master?svg=true)](https://ci.appveyor.com/project/mavlink/qgroundcontrol)

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/mavlink/qgroundcontrol?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


*QGroundControl* (QGC) is an intuitive and powerful ground control station (GCS) for UAVs.

The primary goal of QGC is ease of use for both first time and professional users. 
It provides full flight control and mission planning for any MAVLink enabled drone, and vehicle setup for both PX4 and ArduPilot powered UAVs. Instructions for *using QGroundControl* are provided in the [User Manual](https://docs.qgroundcontrol.com/en/) (you may not need them because the UI is very intuitive!)

All the code is open-source, so you can contribute and evolve it as you want. 
The [Developer Guide](https://dev.qgroundcontrol.com/en/) explains how to [build](https://dev.qgroundcontrol.com/en/getting_started/) and extend QGC.


Key Links: 
* [Website](http://qgroundcontrol.com) (qgroundcontrol.com)
* [User Manual](https://docs.qgroundcontrol.com/en/)
* [Developer Guide](https://dev.qgroundcontrol.com/en/)
* [Discussion/Support](https://docs.qgroundcontrol.com/en/Support/Support.html)
* [Contributing](https://dev.qgroundcontrol.com/en/contribute/)
* [License](https://github.com/mavlink/qgroundcontrol/blob/master/COPYING.md)


# SmartSurvey_QGC



**1. QGroundControl**

This work is an extension of QGroundControl that provides some additional features in QGControl to optimize the drone trajectory and energy consumption.

The list of additional features, their description and their use are mentioned on the [link](https://docs.google.com/presentation/d/1INAbxRJxul3wHkVudp6JSQHbo7yK59PzovAylaD3nAE/edit?usp=sharing).


**2. Installation and Pre-requisites**

Please refer to QgroundControl [Github page](https://github.com/mavlink/qgroundcontrol) for installation instructions


**3. How to Run**

The files that are changed for adding these features are _SurveyComplexItem.cc_, _SurveyComplexItem.h_, _Survey.SettingsGroup.json_ in the **MissionManager** folder under src and the _SurveyItemEditor.qml_ file in **PlanView** folder under src. Compile the code on Qt after replacing these four files.


# References

[1] http://qgroundcontrol.com/

[2] S. Iyengar, R.R. Saxena, J. Pal, B. Chhaglani, A. Ghosh, V.N. Padmanabhan, P.T. Venkata 2021. Holistic Energy Awareness for Intelligent Drones In Proceedings of ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation (BuildSys ’21), November 17–18, 2021, Coimbra, Portugal.ACM, New York, NY, USA, 11 pages. https://doi.org/10.1145/3486611.3486651

