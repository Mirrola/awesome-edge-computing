   * [Awesome edge computing](#awesome-edge-computing)
   * [Simulators](#simulators)
   * [Frameworks](#frameworks)
      * [Engine](#engine)
      * [Networks](#networks)
   * [Test (data, benchmark)](#test-data-benchmark)
   * [Tools](#tools)
   * [Applications](#applications)
   * [Edge-AI frameworks](#edge-ai-frameworks)
   * [Prototype proposed in researches](#prototype-proposed-in-researches)
# Awesome edge computing

# Simulators
- [CloudSim](https://github.com/Cloudslab/cloudsim): CloudSim goal is to provide 
a generalized and extensible simulation framework that enables modeling, simulation,
and experimentation of emerging Cloud computing infrastructures and application 
services, allowing its users to focus on specific system design issues that they 
want to investigate, without getting concerned about the low level details related 
to Cloud-based infrastructures and services.

- [CloudSimSDN](https://github.com/Cloudslab/cloudsimsdn): An SDN extension of
CloudSim project to simulate SDN features in the context of a cloud data center.
CloudSimSDN supports calculating power consumption by both hosts and switches.
For instance, network-aware VM placement policies can be evaluated using CloudSimSDN.

- [CloudSimPy](https://github.com/FengcunLi/CloudSimPy): CloudSimPy is a data centric
task schedule framework. It is bases on [SimPy](https://simpy.readthedocs.io/),
a process-based discrete-event simulation framework based on standard Python.
The scientific computing, deep learning, and machine learning ecology of the 
Python language is more complete than other programming languages. CloudSimPy 
works well with deep learning frameworks with Python support (such as TensorFlow,
PyTorch) The combination helps to study resource management methods based on
machine learning or deep learning.

- [CFN](https://github.com/spirosmastorakis/CFN/): Computing First Networking that
based on Named Data Networking ([NDN](https://github.com/named-data-ndnSIM/ndnSIM)).

- [Cooja](https://anrg.usc.edu/contiki/index.php/Cooja_Simulator): Cooja Simulator
is a network simulator specifically designed for Wireless Sensor Networks.

- [CORE](https://github.com/coreemu/core):The Common Open Research Emulator (CORE) 
is a tool for emulating networks on one or more machines. You can connect these
emulated networks to live networks. CORE consists of a GUI for drawing topologies
of lightweight virtual machines, and Python modules for scripting network emulation.

- [EdgeCloudSim](https://github.com/CagataySonmez/EdgeCloudSim): EdgeCloudSim: An 
Environment for Performance Evaluation of Edge Computing Systems.

- [EdgeSim](https://github.com/XiaofeiTJU/SimEdgeIntel):An open-source simulator of 
edge computing and caching. This simulator system contains three models: Content,
Base Station and User.

- [EmuFog](https://github.com/emufog/emufog): EmuFog helps to test fog computing 
applications more efficiently. Instead of actual deploying large network topologies
with your application to test, EmuFog helps to generate networks that can be 
emulated easily with [MaxiNet](https://maxinet.github.io/), a distributed version
of the popular [Mininet](https://mininet.org/). This provides more realistic 
results than simulations and is cheaper and faster than real deployments. As an
input EmuFog supports generated topologies from [BRITE](https://www.cs.bu.edu/brite/)
or measured real world topologies from [Caida](https://www.caida.org). In those 
networks EmuFog places fog nodes efficiently based on user defined constrains
such as network latency thresholds or resource constraints. Applications for clients
and fog nodes can be anything shipped in a Docker container.

- [Fogbed](https://github.com/fogbed/fogbed): Fogbed is a framework that extends 
the Mininet emulator to create fog testbeds in virtualized environments. Using a 
desktop approach, Fogbed enables the deployment of virtual fog nodes as Docker
containers under different network conﬁgurations. The Fogbed API provides functionality 
to add, connect and remove containers dynamically from the network topology. These
features allow for the emulation of real world cloud and fog infrastructures in
which it is possible to start and stop compute instances at any point in time. 
Also, it is possible to change at runtime resource limitations for a container, 
such as CPU time and memory available.

- [FogNetSim\+\+](https://github.com/rtqayyum/fognetsimpp): FogNetSim\+\+ extends 
OMNeT\+\+, which is a well known framework for building network simulators, to model
all these aspects. Moreover, it includes popular communication protocols for 
simulation, such as TCP, UDP, MQTT, and CoAP. Furthermore, FogNetSim\+\+ models 
several other aspects, such as energy consumption, pricing, mobility, and handoff 
mechanisms.

- [FogTorchPI](https://github.com/di-unipi-socc/FogTorchPI): FogTorchΠ is an open
source prototype, developed in Java, based on a model for Fog computing infrastructures
and applications. 1), It takes into account non-functional parameters within the model
(i.e., hardware, software, latency and bandwidth) to determine, compare and contrast
different eligible deployments of a given application over a Fog infrastructure.
2), In the case of hardware capabilities, it considers CPU cores, RAM and storage 
available at a given node or required by a given software component. 3), Software 
capabilities are represented by a list of software names (operating system, 
programming languages, frameworks etc). 4), It considers latency, and both download
and upload bandwidths as QoS attributes. Latency is measured in milliseconds (ms),
while bandwidth is given in Megabits per second (Mbps).
**Note**: Outputs of __FogTorchPI__ can be the input of __iFogSim__.

- [IoTSim-Edge](https://github.com/DNJha/IoTSim-Edge): IoTSim captures the behavior
of heterogeneous IoT and edge computing infrastructure and allows users to test
their infrastructure and framework in an easy and configurable manner. IoTSim-Edge
extends the capability of CloudSim to incorporate the different features of edge
and IoT devices.

- [IoTSim-Osmosis](https://github.com/kalwasel/IoTSim-Osmosis): IoTSim-Osmosis 
is a simulation framework that supports the testing and validation of osmotic
computing applications. In particular, it enables a unified modelling and 
simulation of complex IoT applications over heterogeneous edge-cloud SDN-aware 
environments.[DOI:10.1016/j.sysarc.2020.101956](https://doi.org/10.1016/j.sysarc.2020.101956)

- [MobFogSim](https://github.com/diogomg/MobFogSim): An extension which can support
for Mobility of __iFogSim__. MobFogSim can model more generalised aspects related
to device mobility and VM/container migration in the fog, e.g., user position and
speed, connection handoff, migration policies and strategies, to name a few. More
details can be found in [MobFogSim: Simulation of Mobility and Migration for Fog
Computing](https://doi.org/10.1016/j.simpat.2019.102062).

- [Mini-NDN](http://minindn.memphis.edu/):Mini-NDN is a lightweight networking 
emulation tool that enables testing, experimentation, and research on the NDN 
platform. It was initially based on [Mini-CCNx](https://github.com/chesteve/mn-ccnx)
which was a fork of Mininet. Mini-NDN uses the NDN libraries, NFD, NLSR, and tools
released by the NDN project to emulate an NDN network on a single system.

- [Mininet-WiFi](https://github.com/intrig-unicamp/mininet-wifi): Emulator for 
Software-Defined Wireless Networks.

- [ndnSIM](https://ndnsim.net/): The ndnSIM 2.0 is NS-3 module that implements 
Named Data Networking (NDN) communication model, the clean slate Internet design.

- [NFaaS](https://gitlab.com/mharnen/NFaaS): Enabling to migrate functions closer
to the user in ICN environment without a global view of the network.

- [iFogSim](https://github.com/Cloudslab/iFogSim): The iFogSim Toolkit for Modeling 
and Simulation of Resource Management Techniques in Internet of Things, Edge and 
Fog Computing Environments.

- [lightMANO](https://github.com/lightmano/lightmano-core): A lightweight distributed
service orchestrator designed for resource constrained multi-access edge computing
environments.

- [Packet Tracer](https://www.netacad.com/courses/packet-tracer/introduction-packet-tracer):
Packet Tracer is a cross-platform visual simulation tool designed by Cisco Systems 
that allows users to create network topologies and imitate modern computer networks. 
The software allows users to simulate the configuration of Cisco routers and switches 
using a simulated command line interface. Packet Tracer makes use of a drag and 
drop user interface, allowing users to add and remove simulated network devices 
as they see fit.

- [pFogSim](https://github.com/jihall77/pFogSim): pFogSim (/p/-fôg-/sɪm/) is a 
play off iFogSim; A simulator made to handle large-scale FOG networks with the 
HAFA Puddle Strategy to help evaluate the potential advantages/disadvantages 
within user-customizable scenarios.

- [PureEdgeSim](https://github.com/CharafeddineMechalikh/PureEdgeSim): a new 
simulator based on [CloudSim Plus](http://Cloudsimplus.org) that is designed to
simulate Cloud, Edge, and Mist computing environments. It allows to evaluate the 
performance of resources management strategies in terms of network usage, latency,
resources utilization, energy consumption, etc. and enables the simulation of 
several scenarios such as the Internet of Things (IoT), connected vehicles/VANETs/MANET,
Mist computing environments (peer-to peer networks such as mobile devices Cloud),
and mobile Edge computing.

- [RECAP Simulator Framework](https://recap-project.eu/simulators/): The RECAP 
Simulation Framework is an open source simulation framework designed to support 
experimentation of infrastructure with different description models for workload,
user distribution, network topology, and (physical and virtual) resource placement.
It is able to simulate different use cases including Virtual Network Functions
(VNFs), Elasticsearch, smart cities, and virtual Content Delivery Networks (vCDN).
The output of the RECAP Simulation Framework depends on the use case, but in 
general, it is a set of metrics predefined by the user such as bandwidth, resource
consumption (CPU, memory, storage), network delay, energy consumption, active number
of VMs, cache hits and cache misses.

- [SimMobility](https://github.com/smart-fm/simmobility-prod): SimMobility is an
integrated mobility simulation platform that comprehensively simulates Future Mobility
scenarios by integrating long, medium, and short-term travel behavior. Various
mobility-sensitive behavioral models are integrated within the state-of-the-art 
scalable simulators to predict the impact of mobility demands on transportation 
networks, intelligent transportation services and vehicular emissions. The platform
simulates the effects of a portfolio of technology, policy and investment options
under alternative future scenarios. SimMobility encompasses the modeling of millions
of agents, including pedestrians, drivers, phones, traffic lights, GPS, cars, buses,
and trains, from second-by-second to year-by-year simulations and across countries.

- [SimpleIoTSimulator](https://www.simplesoft.com/SimpleIoTSimulator.html):
SimpleIoTSimulator® is an easy to use, IoT Sensor/device simulator that quickly 
creates test environments made up of thousands of sensors and gateways, all on 
just one computer. SimpleIoTSimulator supports many of the common IoT protocols. 
They include: MQTT, MQTT-SN, MQTT-Broker, CoAP, HTTP/s client, HTTP/s server, 
Modbus over TCP, BACnet/IP server, LoRa Gateway, LoRa Device.

- [SLEIPNIR](https://github.com/vindem/sleipnir): SLEIPNIR is a DAG scheduling
simulator focused on mobile cloud/edge/iot infrastructures.

- [Step-ONE](https://github.com/jaks6/step-one): Simulated Testbed for Edge-Fog 
Processes based on the Opportunistic Network Environment simulator.

- [Veins](https://github.com/sommer/veins): The open source vehicular network 
simulation framework.

- [Veins LTE](http://veins-lte.car2x.org/): Veins LTE is a simulator for 
heterogeneous vehicular networks. It provides fine-grained simulation of vehicular
networks based on IEEE 802.11p and TE.

- [VirtFogSim](https://github.com/mscarpiniti/VirtFogSim): VirtFogSim is a 
MATLAB-supported software toolbox that allows the dynamic joint optimization and 
tracking of the energy and delay performance of Mobile-Fog-Cloud systems for the
execution of applications described by general Directed Application Graphs (DAGs).
Check the paper [link](https://doi.org/10.3390/app9061160) for more details.

- [YAFS(Yet Another Fog Simulator)](https://github.com/acsicuib/YAFS): YAFS is a
simulator tool based on Python of architectures such as: Fog Computing ecosystems
for several analysis regarding with the placement of resources, cost deployment,
network design, ... IoT environments are the most evident fact of this type of 
architecture. The highlights points of YAFS are:
  - Dinamyc topology: entities and network links can be created or removed along
  the simulation.
  - Dinamyc creation of messages sources: sensors can generate messages from 
  different point access along the simulation.
  - And for hence, the placement allocation algorithm and the orchestration algorithm,
  that are extended by the user, can run along the simulation.
  - The topology of the network is based on Complex Network theory. Thus, the 
  algorithms can obtain more valuable indicators from topological features.
  - The results are stored in a raw format in a nosql database. The simpler the 
  format, the easier it is to perform any type of statistics.

# Frameworks

## Engine
- [Apache Edgent(incubating)](https://edgent.incubator.apache.org/): Apache Edgent
is a programming model and micro-kernel style runtime that can be embedded in 
gateways and small footprint edge devices enabling local, real-time, analytics 
on the continuous streams of data coming from equipment, vehicles, systems,
appliances, devices and sensors of all kinds (for example, Raspberry Pis or smart 
phones). Working in conjunction with centralized analytic systems, Apache Edgent 
provides efficient and timely analytics across the whole IoT ecosystem: from the
center to the edge.

- [Baetyl](https://github.com/baetyl/baetyl): Baetyl is an open edge computing 
framework of Linux Foundation Edge that extends cloud computing, data and service 
seamlessly to edge devices. It can provide temporary offline, low-latency computing 
services include device connection, message routing, remote synchronization, 
function computing, video capture, AI inference, status reporting, configuration 
ota etc.

- [Distributed Strom](http://matnar.github.io/uniroma2-storm/): Distributed Storm
is an extension of Apache Storm that supports the execution of distributed, 
adaptive, and QoS-aware scheduling algorithms. It introduces some key components
on each worker node that enhance the system with adaptation capabilities, relying 
on a MAPE (Monitor, Analyze, Plan, and Execute) feedback loop periodically executed.
Specifically, the newly introduced components are: the AdaptiveSchedulers, the 
QoSMonitors, and the WorkerMonitors. Logics of a `Bolt` can be regarded as an edge
server processes the data.

- [ENORM](https://github.com/qub-blesson/ENORM): The ENORM framework primarily
addresses the deployment and load balancing challenges on individual edge nodes. 
ENORM operates in a three-tier environment, but a master controller does not
control the edge nodes. Instead, it is assumed that they are visible to cloud 
servers that may want to make use of the edge. The framework allows for partitioning
a cloud server and offloading it to edge nodes for improving the overall QoS of 
the application.

- [EdgeMesh](https://github.com/kubeedge/edgemesh):EdgeMesh is a part of KubeEdge,
and provides a simple network solution for the inter-communications between 
services at edge scenarios.

- [FogFlow](https://github.com/smartfog/fogflow): FogFlow is an IoT edge computing
framework to automatically orchestrate dynamic data processing flows over cloud
and edges driven by context, including system context on the available system
resources from all layers, data context on the registered metadata of all available
data entities, and also usage context on the expected QoS defined by users.

- [k3OS](https://k3os.io/): k3OS is purpose-built to simplify Kubernetes operations in low-resource
computing environments. Installs fast. Boots faster. Managed through Kubernetes.

- [KubeEdge](https://github.com/kubeedge/kubeedge):KubeEdge is an open source 
system extending native containerized application orchestration and device 
management to hosts at the Edge. It is built upon Kubernetes and provides core 
infrastructure support for networking, application deployment and metadata 
synchronization between cloud and edge. It also supports MQTT and allows developers
to author custom logic and enable resource constrained device communication at
the Edge. KubeEdge consists of a cloud part and an edge part.

- [OCI](https://github.com/marckoerner/oci):  a framework that enables network 
operators with the ability to open up their edge facilities to Application Service
Providers, by offering edge computing. As an example, consider a third-party
Application Service Provider selling an IoT device (say, a home thermostat or
security camera). Whenever that device shows up at the edge of the network, the 
Open Carrier Interface framework starts the Application Service Provider implemented
edge software at the network operator’s Central Offices, which supports the IoT
device with edge processing. Thus, even an early-stage Application Service Provider, 
who has few financial or physical  resources, can offer the same level of edge 
support as giant companies, and therefore can compete with them on an even footing.
[read more](https://doi.org/10.1145/3229574.3229579).

- [OpenStack++](http://elijah.cs.cmu.edu/development.html): is a framework developed 
by Carnegie Mellon University Pittsburgh for providing VM-based cloudlet platform
on regular x86 computers for mobile application offloading. A set of new mobile 
computing applications that build upon OpenStack++ and leverage its support for 
cloudlets is also supported.

- [WSO2-IoT Server](https://wso2.com/iot): An extension of the popular open-source
enterprise service-oriented integration platform WSO2 server that consists of 
certain IoT-related mechanisms, such as connecting a broad range of common IoT
devices with the cloud using standard protocols such as MQTT and XMPP. Further,
WSO2–IoT server includes the embedded Siddhi 3.0 component that allows the system 
to deploy real-time streaming processes in embedded devices. In other words,
WSO2–IoT server provides the FEC computing capability to outer-edge devices.

- [EdgeX Foundry](https://www.edgexfoundry.org/): EdgeX Foundry is a highly flexible and 
scalable open source software framework that facilitates interoperability between 
devices and applications at the IoT Edge.

- [Akraino Edge Stack](https://www.lfedge.org/projects/akraino/): Akraino is a set of open 
infrastructures and application blueprints for the Edge, spanning a broad variety of use 
cases, including 5G, AI, Edge IaaS/PaaS, IoT, for both provider and enterprise edge 
domains.  These Blueprints have been created by the Akraino community and focus 
exclusively on the edge in all of its different forms.  What unites all of these 
blueprints is that they have been tested by the community and are ready for adoption as-is,
or used as a starting point for customizing a new edge blueprint.


## Networks
- [Awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools):A collection
of tools developed by other researchers in the Computer Science area to process 
network traces.

- [EdgeNet](https://github.com/EdgeNet-Project): edgeNet is a distributed edge
cloud, in the family of PlanetLab, GENI, Canada’s SAVI infrastructure, Japan’s 
JGN-X, Germany’s G-Lab, and PlanetLab Europe. It is a modern distributed edge 
cloud, incorporating advances in Cloud technologies over the past few years.

- [MinNet](http://mininet.org/): Mininet creates a realistic virtual network, 
running real kernel, switch and application code, on a single machine (VM, cloud
or native), in seconds, with a single command:`sudo mn`. Mininet is also a great
way to develop, share, and experiment with OpenFlow and Software-Defined Networking 
systems.

- [MobEmu](https://github.com/raduciobanu/mobemu): An opportunistic network emulator
that can run a user-created routing or dissemination algorithm on a desired mobility
trace or synthetic model.

- [Mosquitto](http://mosquitto.org/): Eclipse Mosquitto is an open source (EPL/EDL
licensed) message broker that implements the MQTT protocol versions 5.0, 3.1.1 and
3.1. Mosquitto is lightweight and is suitable for use on all devices from low power
single board computers to full servers. 
The MQTT protocol provides a lightweight method of carrying out messaging using
a publish/subscribe model. This makes it suitable for Internet of Things messaging 
such as with low power sensors or mobile devices such as phones, embedded computers 
or microcontrollers.
The Mosquitto project also provides a C library for implementing MQTT clients, 
and the very popular `mosquitto_pub` and `mosquitto_sub` command line MQTT clients.

- [Naming Data Network Platform](https://named-data.net/codebase/platform/): NDN
is an entirely new architecture, but one whose design principles are derived from 
the successes of today’s Internet, reflecting our understanding of the strengths
and limitations of the current Internet architecture, and one that can be rolled
out through incremental deployment over the current operational Internet.

- [Node-RED](https://nodered.org/): Node-RED is a programming tool for wiring 
together hardware devices, APIs and online services in new and interesting ways.
It provides a browser-based editor that makes it easy to wire together flows using
the wide range of nodes in the palette that can be deployed to its runtime in a 
single-click.

- [OMNeT++](https://github.com/omnetpp/omnetpp): OMNeT++ is a public-source, 
component-based, modular and open-architecture simulation environment with strong
GUI support and an embeddable simulation kernel. Its primary application area is
the simulation of communication networks, but it has been successfully used in 
other areas like the simulation of IT systems, queueing networks, hardware 
architectures and business processes as well.

- [Open vSwitch](https://www.openvswitch.org/):  is a production quality, multilayer 
virtual switch licensed under the open source Apache 2.0 license.  It is designed
to enable massive network automation through programmatic extension, while still 
supporting standard management interfaces and protocols (e.g. NetFlow, sFlow,
IPFIX, RSPAN, CLI, LACP, 802.1ag).  In addition, it is designed to support distribution
across multiple physical servers similar to VMware's vNetwork distributed vswitch 
or Cisco's Nexus 1000V. 

- [POX](https://github.com/noxrepo/pox): POX is a networking software platform
written in Python. POX started life as an OpenFlow controller, but can now also 
function as an OpenFlow switch, and can be useful for writing networking software
in general. An useful link of how to simulate a SDN can check the link:
http://www.brianlinkletter.com/using-the-pox-sdn-controller/

- [VerneMQ](https://vernemq.com/): VerneMQ is a high-performance, distributed 
MQTT message broker. It scales horizontally and vertically on commodity hardware
to support a high number of concurrent publishers and consumers while maintaining 
low latency and fault tolerance. VerneMQ is the reliable message hub for your IoT 
platform or smart products.

- [Wonder Shaper](https://github.com/magnific0/wondershaper): Wonder Shaper 
is a script that allows the user to limit the bandwidth of one or more network 
adapters. It does so by using iproute's tc command, but greatly simplifies its 
operation.

# Test (data, benchmark)
- [The CAIDA Anonymized Internet Traces 2015 Dataset](https://www.caida.org/data/passive/passive_2015_dataset.xml):
CAIDA's passive traces dataset contains traces collected from high-speed monitors
on a commercial backbone link. The data collection started in April 2008 and ended 
in January 2019. These data are useful for research on the characteristics of 
Internet traffic, including application breakdown, security events, geographic
and topological distribution, flow volume and duration.

- [CloudSuite](https://www.cloudsuite.ch/): CloudSuite is a benchmark suite for 
cloud services. The third release consists of eight applications that have been 
selected based on their popularity in today’s datacenters. The benchmarks are 
based on real-world software stacks and represent real-world setups.

- [DeFog](https://github.com/qub-blesson/DeFog): DeFog, a first Fog benchmarking 
suite to: (i) alleviate the burden of Fog benchmarking by using a standard 
methodology, and (ii) facilitate the understanding of the target platform by 
collecting a catalogue of relevant metrics for a set of benchmarks.

- [Edge AIBench](https://www.benchcouncil.org/EdgeAIBench/index.html): Edge AIBench 
is a benchmark suite for end-to-end edge computing including four typical application
scenarios: ICU Patient Monitor, Surveillance Camera, Smart Home, and Autonomous
Vehicle, which consider the complexity of all edge computing AI scenarios. In
addition, Edge AIBench provides an end-to-end application benchmarking framework, 
including train, validate and inference stages. 

- [EUA Datasets](https://github.com/swinedge/eua-datase): This repository maintains
a set of EUA datasets which we collected from real-world data sources. The datasets
are publicly released to facilitate research in Edge Computing. All the data is
in Australia region which contains edge server locations and user location.

- [MLPerf Inference Benchmark Suite](https://github.com/mlcommons/inference): 
MLPerf Inference is a benchmark suite for measuring how fast systems can run 
models in a variety of deployment scenarios.

- [networkX](https://networkx.github.io/): NetworkX is a Python language package 
for exploration and analysis of networks and network algorithms. The core package
provides data structures for representing many types of networks, or graphs,
including simple graphs, directed graphs, and graphs with parallel edges and 
self-loops. The nodes in NetworkX graphs can be any (hashable) Python object and
edges can contain arbitrary data; this flexibility makes NetworkX ideal for
representing networks found in many different scientific fields.

- [Neural Network Accelerator Comparison](http://nicsefc.ee.tsinghua.edu.cn/projects/neural-network-accelerator/):
A comparison of AI hardware accelerators among different platform.

- [Rocketfuel](https://research.cs.washington.edu/networking/rocketfuel/):
Traceroutes were sourced from 800 vantage points hosted by nearly 300 traceroute
web servers. They started by mapping 10 ISPs, in Europe, Australia and the United
States. In that process, they constructed a database of over 50 thousand IP
addresses representing 45 thousand routers in 537 POPs connected by 80 thousand
links.

- [tinyMLPerf Deep Learning Benchmarks for Embedded Devices](https://github.com/mlcommons/tiny):
The goal of TinyMLPerf is to provide a representative set of deep neural nets and
benchmarking code to compare performance between embedded devices. Embedded devices
include microcontrollers, DSPs, and tiny NN accelerators. These devices typically
run at between 10MHz and 250MHz, and can perform inference using less then 50mW
of power.

# Tools
- [netem](https://wiki.linuxfoundation.org/networking/netem) : netem provides
Network Emulation functionality for testing protocols by emulating the properties
of wide area networks. The current version emulates variable delay, loss,
duplication and re-ordering.

- [GeoLite2](https://dev.maxmind.com/geoip/geoip2/geolite2/): Mapping source IPv4
addresses to geo-graphical locations.

# Applications
- [Edge Courier](https://github.com/bumoslab/EdgeCourier): An application for
solving the whole-file-sync problem which needs high bandwidth in the cloud.

- [Eman's Edge Computing System For AI Applications](https://github.com/emmanuelacastillo/python-edge-computing-system):
Highly accurate AI applications, particularly for Computer Vision requires
extensive memory and computational power. Eman's Edge Computing System orchestrates
resource limited devices that requires using resource heavy AI algorithms so
that a system can still achieve ideal system performances. This is done through
Edge's monitoring modules that determines how to adjust the system so the system 
can operate efficiently based on its environments conditions.

# Edge-AI frameworks
- [Apache TVM](https://tvm.apache.org/): Apache TVM is an open source machine
learning compiler framework for CPUs, GPUs, and machine learning accelerators. 
It aims to enable machine learning engineers to optimize and run computations
efficiently on any hardware backend.

- [BerryNet](https://github.com/DT42/BerryNet): This project turns edge devices
such as Raspberry Pi into an intelligent gateway with deep learning running on it.
No internet connection is required, everything is done locally on the edge device
itself. Further, multiple edge devices can create a distributed AIoT network.

- [BranchyNet](https://github.com/kunglab/branchynet): Fast inference via early
exiting from deep neural networks. The architecture allows prediction results for
a large portion of test samples to exit the network early via these branches when
samples can already be inferred with high confidence.

- [DDNN](https://github.com/kunglab/ddnn):  distributed deep neural networks
(DDNNs) over distributed computing hierarchies, consisting of the cloud, the edge
(fog) and end devices. While being able to accommodate inference of a deep neural
network (DNN) in the cloud, a DDNN also allows fast and localized inference using
shallow portions of the neural network at the edge and end devices. Due to its
distributed nature, DDNNs enhance data privacy and system fault tolerance for
DNN applications. When supported by a scalable distributed computing hierarchy,
a DDNN can scale up in neural network size and scale out in geographical span.

- [Distiller](https://github.com/IntelLabs/distiller): Distiller is an open-source
Python package for neural network compression research.
It provides a PyTorch environment for prototyping and analyzing compression
algorithms, such as sparsity-inducing methods and low-precision arithmetic.

- [FATE](https://github.com/FederatedAI/FATE):FATE (Federated AI Technology Enabler)
is an open-source project initiated by Webank's AI Department to provide a secure
computing framework to support the federated AI ecosystem. It implements secure
computation protocols based on homomorphic encryption and multi-party computation (MPC).
It supports federated learning architectures and secure computation of various
machine learning algorithms, including logistic regression, tree-based algorithms,
deep learning and transfer learning.

- [nn-Meter](https://github.com/microsoft/nn-Meter):nn-Meter is a novel and 
efficient system to accurately predict the inference latency of DNN models on 
diverse edge devices. The key idea is dividing a whole model inference into
kernels, i.e., the execution units of fused operators on a device, and conduct
kernel-level prediction.

- [NVIDIA TensorRT](https://developer.nvidia.com/tensorrt): NVIDIA® TensorRT™ is
an SDK for high-performance deep learning inference. It includes a deep learning
inference optimizer and runtime that delivers low latency and high throughput for
deep learning inference applications.

- [Once for All](https://github.com/mit-han-lab/once-for-all): Train One Network
and Specialize it for Efficient Deployment.

- [Paddle-Lite](https://github.com/PaddlePaddle/Paddle-Lite): Paddle Lite is an
updated version of Paddle-Mobile, an open-open source deep learning framework
designed to make it easy to perform inference on mobile, embeded, and IoT devices.
It is compatible with PaddlePaddle and pre-trained models from other sources.

- [TensorFlow Lite](https://www.tensorflow.org/lite): TensorFlow Lite is an
open-source deep learning framework to run TensorFlow models on-device. If you
are new to TensorFlow Lite, we recommend that you first explore the pre-trained
models and run the example apps below on a real device to see what TensorFlow Lite
can do.

# Prototype proposed in researches
## Machine Learning
- [DeepThings](https://github.com/SLAM-Lab/DeepThings): A framework for locally
distributed and adaptive CNN inference in resource-constrained IoT edge clusters.
DeepThings mainly consists of: 1). A Fused Tile Partitioning (FTP) method for
dividing convolutional layers into independently distributable tasks. FTP fuses
layers and partitions them vertically in a grid fashion, which largely reduces 
communication and task migration overhead. 2). A distributed work stealing runtime
system for IoT clusters to adaptively distribute FTP partitions in dynamic
application scenarios.

- [FedProx](https://github.com/litian96/FedProx): FedProx aims to solve two key
challenges that differentiate it from traditional distributed optimization:
(1) significant variability in terms of the systems characteristics on each device
in the network (systems heterogeneity), and (2) non-identically distributed data
across the network (statistical heterogeneity).

- [KitNET](https://github.com/ymirsky/KitNET-py): KitNET is an online, unsupervised,
and efficient anomaly detector. A Kitsune, in Japanese folklore, is a mythical
fox-like creature that has a number of tails, can mimic different forms, and whose
strength increases with experience. Similarly, Kit-NET has an ensemble of small
neural networks (autoencoders), which are trained to mimic (reconstruct) network
traffic patterns, and whose performance incrementally improves overtime.

- [Neurosurgeon](https://github.com/njcpe/neurosurgeon):A lightweight scheduler 
to automatically partition DNN computation between mobile devices and datacenters
at the granularity of neural network layers.

- [ns3-gym](https://github.com/tkn-tub/ns3-gym): OpenAI Gym is a toolkit for
reinforcement learning (RL) widely used in research. The network simulator ns–3
is the de-facto standard for academic and industry studies in the areas of
networking protocols and communication technologies. ns3-gym is a framework that
integrates both OpenAI Gym and ns-3 in order to encourage usage of RL in
networking research.

