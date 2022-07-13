# INTRODUCTION 
Mighty Brahmaputra River, is the largest river in North-East India. The average depth of the river is 30 m (100 ft) and its maximum depth is 135 m (440 ft). Containing a large number of secrets inside, It is still mysterious to people. We all are aware that it contains minerals inside it but any swimmer could rarely dare to dive beneath as the river is also home to diverse variety of aquatic species might including some dangerous species. And it becomes more dangerous during the period of the flood as other species migrate to the river. Due to urbanization and industrialization, the water body is getting more polluted day by day and the quality and quantity of water passing through it are degrading. In that context to discover the problem and survey the water body, many fishermen, divers, and local people face great challenges and also the risk of life. 
- Mighty Brahmaputra River:
![mighty brahmaputra](https://user-images.githubusercontent.com/83603244/178703135-cd8298f9-88ca-4115-9ab3-54d2f51232a6.jpg)

# ABOUT US:
The Remotely operated underwater vehicle Antahsagari project is made under 4i-Labs, IIT Guwahati. The aim of the project is to explore the underwater world. The underwater nature imposes a number of challenges for navigation like depth pressure, water leakage, stability-related issues, poor underwater lighting, etc. Our team is determined to develop cutting-edge technology to overcome these challenges. We aim to make it more versatile and adaptive to make marine research and analysis effortless and prolific in the future.
- [Click_here](https://drive.google.com/file/d/1pvHRjyKbwa5_8ssrL1nDKeLsp10tVExU/view?usp=sharing) to view the demonstration video
# AIM
-	The aim of the project is to basically explore underwater world, to explore and navigate through the bed of mighty Brahmaputra.
-	We are trying to analyse the impact of urbanisation on structure and function of river system using the chemical data extracted from the water using sensors.
- Collect data regarding water quality and mapping.
-	Periodic inspection of the river to know about water species, especially during May-June (the time in which the river is mostly flooded)
-	Inspect dams over the Brahmaputra river like Subansiri lower dam, Ranganadi dam, etc. As the dams require regular inspection to avoid any type of mishappening due to damage in it.
- We are trying to analyse the impact of urbanisation on structure and function of river system using the chemical data extracted from the water using sensors.
- It can also be used as a survey platforms to map sea floor or characterise physical, chemical, biological properties of water.
- It can be used to perform infrastructure inspections of pipeline systems so that divers are not put in harm's way.
- Surveillance and object recovery in the underwater environment.


# PHYSICAL STRUCTURE
Antahsagri is an underwater remotely operated vehicle (ROV), designed to explore the underwater world and collect data for research and analysis. It is equipped with several sensors:
- 5 Thrusters T100
- 5 Basic Esc
- 1 Bar30 pressure sensor
- 1 Temperature Sensor
- 2 Leak sensors
- 2 Lumen Subsea Lights
- 1 Raspberry Pi , used as a companion computer
- 1 camera
- 1 servo for the camera tilt
- 1 PixHawk with internal 9 DOF IMU
# METHODOLOGY
We are using ArduSub which works seamlessly with Ground Control Station software that can monitor vehicle telemetry and perform powerful mission planning activities. It also benefits from other parts of the ArduPilot platform, including simulators, log analysis tools, and higher level APIs for vehicle management and control.ArduSub is the 'brains' of the ROV. The Raspberry Pi Companion Computer runs software that relays communications between the autopilot and QGroundControl via Ethernet communications. The Companion software also streams HD video to QgroundControl. We are using SITL for simulation.SITL is a simulator that allows you to run ArduSub without any hardware.
Below is a typical diagram of hardware components on the ROV and their connections.
![68747470733a2f2f7777772e617264757375622e636f6d2f696d616765732f68617264776172652d6469616772616d2e706e67](https://user-images.githubusercontent.com/83603244/178090519-7e8ecc25-c03c-4074-ba72-74fd69026068.png)

# DESIGN 
The model of the Antahsagari 3.0 is made such that it can
withstand harsh and extreme underwater conditions while still
being on a budget. The bot is designed to be as streamlined as
possible, there are no big flat surfaces in the way of motion which
may increase the resistance in motion.
The main model is built of thick acrylic material to make sure that
the electronics can survive high underwater pressure without any
issues while at the same time giving the body strength and rigidity.
![Antah 1](https://user-images.githubusercontent.com/83603244/178090340-a78b73f3-781b-49c0-bc2f-6c3a9445f95e.png)
