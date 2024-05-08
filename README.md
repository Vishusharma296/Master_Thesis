# Master_Thesis
**Thesis Title:** Design and Implementation of Wireless Sensor Networks Using LoRaWAN, MQTT and Cloud Computing

**Abstract** 

The objective of this thesis is to create small-scale Wireless Sensor Networks (WSNs) that leverage LoRaWAN technology, MQTT protocol, and cloud computing as a proof of concept for an IoT platform. These WSNs are intended to be long-range, low-power networks that are scalable, cost-effective, and relatively easy to deploy. The work begins with a literature review of the current state-of-the-art Wireless Sensor Networks (WSNs) based on technologies like WiFi, Bluetooth, ZigBee, and Low Power Wide Area Networks (LPWANs). LPWAN technologies are commonly used for long-range networks. This review revealed that LoRaWAN technology has several advantages over other LPWAN technologies such as SigFox and Narrow Band IoT (NB-IoT) in terms of cost-effectiveness and ease of network deployment. MQTT protocol was chosen for its lightweight and data-centric
approach in comparison to HTTP’s document-centric approach. Cloud computing was chosen for its scalability, security, and easy integration with existing infrastructure.
The research work investigates a number of important issues concerning the challenges involved in integrating and optimizing the WSNs based on LoRaWAN, MQTT, and cloud
computing systems. One of the key issues explored during the research was where to perform certain tasks related to LoRaWAN-based wireless sensor networks, such as decoding
sensor data using a decoding script. This can be done either in the LoRaWAN gateway, in resource-constrained Single Board Computers (SBCs) at the edge, or in cloud/local servers.

The research also explores the optimal MQTT architecture for sensor applications running in LoRaWAN gateways such that it’s compatible with the back-end computing infrastructure. Additionally, the research examines the current limitations of LoRaWAN-compatible network devices, particularly with regard to ease of network deployment, configuration tools, and systems integration.

Key Words: WSN, LoRaWAN, MQTT, Sensors, Cloud computing, IoT, Edge computing, system integration, LPWAN, Industry 4.0.

**Technologies used**

LoRaWAN based wireless networks solves two most important problems of the IoT applications: 
- They provide very long range communication (2-15 Km) at very low power consumption rate.
- LoraWAN based sensor nodes can run upto 10 years on AA sized batteries with very little maintenance.

MQTT is a light weight message transport protocol suitable for Machine to Machine communication (M2M) and Internet of Things (IoT).
- It uses a publish/subscribe model for communication. Clients can publish (publishing clients like sensors) on topics to a central broker (MQTT Server)
and subscribing clients (say a smart phone or a PC) can subscribe to the topics of their interest to see the messages.
- MQTT allows to establish secure connections with a large variety of devices even with unreliable network connections. 
- MQTT is far more suitable for IoT application compared to REST based protocols like HTTP.

Cloud computing enables to build the scalable infrastructure without having too much technical expertise in the database management.
It also enable data analytics and creating application servers for data consumption via dashboards.

**Research Goal**

The research in this report mainly focuses on the combined use of LoRaWAN technology, MQTT protocol and use of cloud
servers as well as local servers in creating long range, low power wireless sensor networks. The most significant research questions that were explore:
- Scalability of network with number and variety of devices (LoRaWAN compatible)
- Exploring complexity of the system integration with existing MQTT and cloud infrastructure
- Where to do the packet decoding and data structure modification of incoming messages from sensors --- Gateway or Back-end servers?
This is subjected to the constraints of costs associated with Cloud service providers, complexity of the network, ease of making configuration changes


Note: The contents of this repositorly is private and not open source. Contents of this repository can only be used by the permission of the principal author Vishu Sharma.
For research collaboration and commercialization of the technologies related to this research, please contact vishusharma296@gmail.com
