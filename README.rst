#######################################################
Node-RED Integrated Monitoring Dashboard
#######################################################

This repository contains the source code and flow configurations for a comprehensive monitoring system. Built on **Node-RED**, this dashboard integrates multiple industrial and facility management functions into a single event-driven application.

*******************
Key Features
*******************

- **Fuel Management System:** Real-time tracking of fuel levels, consumption rates, and refilling logs.
- **Cleanliness Online Monitoring:** Digital checklist and scheduling system for facility hygiene management.
- **Filtration Monitoring:** Live status updates and pressure/flow tracking for filtration units.
- **Multi-Protocol Integration:** Seamless communication using MQTT for IoT and Modbus for industrial PLC/Sensors.
- **Database Logging:** Automated data storage using MySQL for historical analysis and reporting.

**************************
Technical Specifications
**************************

- **Platform:** Node-RED (Low-code programming)
- **Protocols:** MQTT, Modbus RTU/TCP, HTTP
- **Database:** MySQL / MariaDB
- **Dashboard:** Node-RED Dashboard (UI Nodes)
- **Runtime:** Node.js

*******************
Installation Guide
*******************

1. **Clone the Project**
   .. code-block:: bash

      git clone https://github.com/afafirmansyah/node-red-dashboard.git

2. **Prerequisites**
   - Install **Node.js** and **Node-RED** on your system or server.
   - Set up a **MySQL** database and import the required tables.

3. **Install Nodes**
   - Open your Node-RED instance.
   - Install necessary nodes via "Manage Palette":
     - ``node-red-dashboard``
     - ``node-red-node-mysql``
     - ``node-red-contrib-modbus``
     - ``node-red-contrib-mqtt-broker`` (optional)

4. **Import Flow**
   - Copy the JSON content from the ``/flows`` or source folder.
   - In Node-RED, go to **Import** > **Clipboard** and paste the JSON.

5. **Configuration**
   - Update the MQTT Broker and MySQL nodes with your specific server credentials.
   - Deploy the flow and access the UI at ``http://localhost:1880/ui``.

*******
License
*******

This project is licensed under the MIT License - see the `license.txt` file for details.

*********
Contact
*********

**Ahmad Fauzi Firmansyah**
- **GitHub:** `afafirmansyah <https://github.com/afafirmansyah>`_
- **LinkedIn:** `ahmad-fauzi-firmansyah <https://linkedin.com/in/ahmad-fauzi-firmansyah/>`_
