Structural Health Monitoring (SHM) defined as a process that involves sensing, computing and
decision making to assess the integrity of infrastructure, has been plagued by the lack of efficient
data management to enable actual data-driven decision-making. The Internet of Things (IoT)
provides a way to decisively address key deficiencies of current SHM practices.
We propose a user-friendly Plug and Play (PnP) IoT device which fits in with existing data
acquisition networks and is capable of performing large scale real-time data analytics. The device
is built to work within an IoT framework that composes three layers, namely the Edge, Fog and
Cloud.
The Edge is composed of either commercial data acquisition systems or by sensors without any
commercial system being involved. The Edge layer is connected to the Fog which is a
decentralized computing layer that consists of the proposed IoT Device. Within the Fog, real-time
data is aggregated, parsed, filtered and passed through a layer of user-defined algorithms. The
main goal of the algorithms used at the Fog, is to reduce the incoming data and classify it into
known classes. This process allows a real-time data flow to the Cloud, as only important decisionmaking components of the data are propagated. The algorithms on the PnP device are trained in
the Cloud layer using historical data. The Cloud is also responsible for hosting a user interface
(UI) to interact with the Edge and Fog Layers. The UI enables users to control their data acquisition
and visualize their analytics in (near) real-time.

To solve the problems stated in the introduction, we proposed a user-friendly Plug and Play (PnP)
IoT device which fits in with existing data acquisition networks and is capable of performing large scale
real-time data analytics. The device is built to work within an IoT framework consisting of three layers,
namely the Edge, Fog and Cloud. The Edge is composed of either commercial data acquisition systems
(DAQ) or by sensors without any commercial system being involved. The Edge layer is connected to the
Fog - a decentralized computing layer - and consists of the proposed IoT Device. Within the Fog, real-time
data is aggregated, parsed, filtered and passed through a layer of user-defined algorithms. The main goal of
the algorithms used at the Fog, is to reduce the incoming data and classify it into known classes. This
process allows a real-time data flow to the Cloud, as only important decision-making components of the
data are propagated. The algorithms on the PnP device are trained in the Cloud layer using historical data.
The Cloud is also responsible for hosting a user interface (UI) to interact with the Edge and Fog Layers.
The UI enables users to control their data acquisition and visualize their analytics in (near) real-time. 

The user interface is one of the major components in creating a user-friendly environment for our
clients. It has been developed using Javascript, python, Ajax, CSS, HTML and Nodejs. A wide range of
actions have been embedded in each of the tabs to control the settings of the PnP IoT Device and the
algorithms being run. The dashboard tab allows users to select individual DAQ systems and check their
status in real-time. The data format settings tab can be used to adjust the type and formatting of the incoming
data from each individual DAQ. The algorithm selection tab includes preset algorithms to be run in our
device. Currently, the create algorithm and data setting tabs are inactive and require backend adjustments.
Lastly, a LED panel has been placed to notify the user about the overall health of their structure. Users will
receive an immediate notification about the status of their system via mail or text if the light turns red.
Figure 6 in the results section shows the developed online user interface.
