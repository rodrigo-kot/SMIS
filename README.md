# SMIS - Smart Microgreen Irrigation System
Smart Microgreen Irrigation System project with IoT using ThingSpeak server

This project seeks to develop an automated system to use in a DIY microgreen farm. It will be developed for an ESP32 DevKit in the C programming language. 
The farm will consist of 5 shelves, with each being able to hold up to 3 trays (88 x 39 cm). One main pump and reservoir will supply water for the system, with valves on each shelf to control which trays receive irrigation. The user shall receive an alert on cases like low water level, these could be local or remote. 
It could be possible that, due to the number of analog inputs required by the system, more than one module will be needed. For this case, the system could be split into a main module that monitors the general and ambient variables, and a module responsible for the shelf monitoring part.

The goals are:
  - maintenance of soil moisture at desired target:
    - automatic irrigation of microgreen trays;
  - independent monitoring of each shelf's parameters (soil moisture and valve status:
    - local (display);
    - remote (ThingSpeak server);
  - wireless parameter configuration (bluetooth);
