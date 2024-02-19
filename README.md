   * [Awesome edge computing](#awesome-edge-computing)
   * [Simulators](#simulators)
   * [Frameworks](#frameworks)
      * [Engine](#engine)
      * [Networks](#networks)
   * [Test (data, benchmark)](#test-data-benchmark)
   * [Tools](#tools)
   * [Applications](#applications)
   * [Edge-AI frameworks](#edge-ai-frameworks)
   * [Academic institution](#academic-institution)
   * [Other awesome list](#other-awesome-list)
   * [Star History](#star-history)
# Awesome edge computing

# Simulators

- [Artery](http://artery.v2x-research.eu/): Artery enables V2X simulations based
  on ETSI ITS-G5 protocols like GeoNetworking and BTP. Single vehicles can be
  equipped with multiple ITS-G5 services through Artery's middleware, which also
  provides common Facilities for these services. Some basic services, such as
  Cooperative Awareness (CAMs) and Decentralized Notification (DENMs), are
  already included.

- [CausalSim](https://github.com/CausalSim/Unbiased-Trace-Driven-Simulation): CausalSim
  is a causal framework for unbiased trace-driven simulation. Current
  trace-driven simulators assume that the interventions being simulated (e.g., a
  new algorithm) would not affect the validity of the traces. However,
  real-world traces are often biased by the choices algorithms make during trace
  collection, and hence replaying traces under an intervention may lead to
  incorrect results. CausalSim addresses this challenge by learning a causal
  model of the system dynamics and latent factors capturing the underlying
  system conditions during trace collection. It learns these models using an
  initial randomized control trial (RCT) under a fixed set of algorithms, and
  then applies them to remove biases from trace data when simulating new
  algorithms.

- [CloudSim](https://github.com/Cloudslab/cloudsim): CloudSim goal is to provide
  a generalized and extensible simulation framework that enables modeling,
  simulation, and experimentation of emerging Cloud computing infrastructures
  and application services, allowing its users to focus on specific system
  design issues that they want to investigate, without getting concerned about
  the low level details related to Cloud-based infrastructures and services.

- [CloudSim Express](https://github.com/Cloudslab/cloudsim-express):
  CloudSim Express introduces a human-readable scripting approach to define
  simulation scenarios, a standard way of writing extensions, and a simplified
  deployment approach. The script-based approach significantly reduces
  code-based implementations. In the cases of simple examples, it completely
  eliminates the need to implement Java code.

- [CloudSim Plus
  Automation](https://github.com/manoelcampos/cloudsimplus-automation): CloudSim
  Plus Automation is a Java 17+ command line tool based on CloudSim Plus (and some
  CloudReports classes) which is able to read specifications of CloudSim Plus
  simulation scenarios from a YAML file, a very human-readable data format.
  Simulation scenarios can be written inside a YAML file and CloudSim Plus
  Automation reads these simulation scenarios, creates and runs them on CloudSim
  Plus.

- [CloudSim+ - Py4j gateway](https://github.com/pkoperek/cloudsimplus-gateway):
  py4j gateway for Cloud Sim Plus framework.

- [CloudSimSDN](https://github.com/Cloudslab/cloudsimsdn): An SDN extension of
  CloudSim project to simulate SDN features in the context of a cloud data
  center. CloudSimSDN supports calculating power consumption by both hosts and
  switches. For instance, network-aware VM placement policies can be evaluated
  using CloudSimSDN.

- [CloudSimPy](https://github.com/FengcunLi/CloudSimPy): CloudSimPy is a data
  centric task schedule framework. It is bases on
  [SimPy](https://simpy.readthedocs.io/), a process-based discrete-event
  simulation framework based on standard Python. The scientific computing, deep
  learning, and machine learning ecology of the Python language is more complete
  than other programming languages. CloudSimPy works well with deep learning
  frameworks with Python support (such as TensorFlow, PyTorch) The combination
  helps to study resource management methods based on machine learning or deep
  learning.

- [CFN](https://github.com/spirosmastorakis/CFN/): Computing First Networking
  that based on Named Data Networking
  ([NDN](https://github.com/named-data-ndnSIM/ndnSIM)).

- [Cooja](https://anrg.usc.edu/contiki/index.php/Cooja_Simulator): Cooja
  Simulator is a network simulator specifically designed for Wireless Sensor
  Networks.

- [CORE](https://github.com/coreemu/core):The Common Open Research Emulator
  (CORE) is a tool for emulating networks on one or more machines. You can
  connect these emulated networks to live networks. CORE consists of a GUI for
  drawing topologies of lightweight virtual machines, and Python modules for
  scripting network emulation.

- [DFaaS](https://github.com/UNIMIBInside/dfaas): A novel decentralized
  FaaS-based architecture designed to automatically and autonomously balance the
  traffic load across edge nodes belonging to federated Edge Computing
  ecosystems. Its implementation relies on an overlay peer-to-peer network and a
  distributed control algorithm that takes decisions on load redistribution.

- [EasiEI](https://gitlab.com/Mirrola/ns-3-dev): EasiEI simulates various
  computing, communication, and storage resources in edge computing, and
  provides basic task scheduling algorithms to support the simulation of edge
  computing scenarios.

- [ECSNeT++](https://github.com/sedgecloud/ECSNeTpp): ECSNeT++ is a simulation
  toolkit for simulating the execution of Distributed Stream Processing
  applications on Edge anc Cloud Computing environments. ECSNeT++ is implemented
  using the OMNeT++ and the INET framework.

- [EdgeCloudSim](https://github.com/CagataySonmez/EdgeCloudSim): EdgeCloudSim:
  An Environment for Performance Evaluation of Edge Computing Systems.

- [EdgeSim](https://github.com/XiaofeiTJU/SimEdgeIntel):An open-source simulator
  of edge computing and caching. This simulator system contains three models:
  Content, Base Station and User.

- [EmuFog](https://github.com/emufog/emufog): EmuFog helps to test fog computing
  applications more efficiently. Instead of actual deploying large network
  topologies with your application to test, EmuFog helps to generate networks
  that can be emulated easily with [MaxiNet](https://maxinet.github.io/), a
  distributed version of the popular [Mininet](https://mininet.org/). This
  provides more realistic results than simulations and is cheaper and faster
  than real deployments. As an input EmuFog supports generated topologies from
  [BRITE](https://www.cs.bu.edu/brite/) or measured real world topologies from
  [Caida](https://www.caida.org). In those networks EmuFog places fog nodes
  efficiently based on user defined constrains such as network latency
  thresholds or resource constraints. Applications for clients and fog nodes can
  be anything shipped in a Docker container.

- [EnvisEdge](https://github.com/NimbleEdge/EnvisEdge): EnvisEdge allows users
  to simulate an edge computing environment to test their ideas and models
  before putting them in place on the edge. It takes care of all the complex
  stuff such as diversity across operating systems, computation power and
  communication mediums, allowing you to focus on the idea rather than the
  setup. EnvisEdge allows researchers, developers and data scientists to
  experiment and test their hypotheses, and produce production-ready code
  without having direct access to the edge devices. Creating a path for global
  research and growth in the domains of federated learning and edge computing.

- [EPCSAC](https://github.com/TNanukem/EPCSAC): The EPCSAC (Extensible Platform
  for Cloud Scheduling Algorithm Comparison) is an online open-source platform
  developed to help researchers compare scheduling algorithms to allocate tasks
  into virtual machines inside cloud infrastructures.

- [FAAP-Simulator](https://github.com/MSuter6/faap-simulator):  Application
  allocation in the area of fog computing and targets fog networks in industrial
  environments. With the simulator, it is possible to generate, run and evaluate
  instances of the Fog Application Allocation Problem denoted as FAAP. The
  simulator is completely implemented in the scala programming language.

- [faas-sim](https://github.com/edgerun/faas-sim): Faas-sim is a powerful
  trace-driven simulation framework to simulate container-based
  function-as-a-service platforms. It can be used to develop, and evaluate the
  performance of operational strategies for such systems, like scheduling,
  autoscaling, load balancing, and others. faas-sim was developed at the
  Distributed Systems Group at TU Wien as part of a larger research effort
  surrounding serverless edge computing systems.

- [Fogbed](https://github.com/fogbed/fogbed): Fogbed is a framework that extends
  the Mininet emulator to create fog testbeds in virtualized environments. Using
  a desktop approach, Fogbed enables the deployment of virtual fog nodes as
  Docker containers under different network conﬁgurations. The Fogbed API
  provides functionality to add, connect and remove containers dynamically from
  the network topology. These features allow for the emulation of real world
  cloud and fog infrastructures in which it is possible to start and stop
  compute instances at any point in time. Also, it is possible to change at
  runtime resource limitations for a container, such as CPU time and memory
  available.

- [Fogify](https://ucy-linc-lab.github.io/fogify/): Fogify is an emulation
  Framework easing the modeling, deployment and experimentation of fog testbeds.
  Fogify provides a toolset to: model complex fog topologies comprised of
  heterogeneous resources, network capabilities and QoS criteria; deploy the
  modelled configuration and services using popular containerized
  infrastructure-as-code descriptions to a cloud or local environment;
  experiment, measure and evaluate the deployment by injecting faults and
  adapting the configuration at runtime to test different "what-if" scenarios
  that reveal the limitations of a service before introduced to the public.

- [FogNetSim\+\+](https://github.com/rtqayyum/fognetsimpp): FogNetSim\+\+
  extends OMNeT\+\+, which is a well known framework for building network
  simulators, to model all these aspects. Moreover, it includes popular
  communication protocols for simulation, such as TCP, UDP, MQTT, and CoAP.
  Furthermore, FogNetSim\+\+ models several other aspects, such as energy
  consumption, pricing, mobility, and handoff mechanisms.

- [FogTorchPI](https://github.com/di-unipi-socc/FogTorchPI): FogTorchΠ is an
  open source prototype, developed in Java, based on a model for Fog computing
  infrastructures and applications. 1), It takes into account non-functional
  parameters within the model (i.e., hardware, software, latency and bandwidth)
  to determine, compare and contrast different eligible deployments of a given
  application over a Fog infrastructure. 2), In the case of hardware
  capabilities, it considers CPU cores, RAM and storage available at a given
  node or required by a given software component. 3), Software capabilities are
  represented by a list of software names (operating system, programming
  languages, frameworks etc). 4), It considers latency, and both download and
  upload bandwidths as QoS attributes. Latency is measured in milliseconds (ms),
  while bandwidth is given in Megabits per second (Mbps). **Note**: Outputs of
  __FogTorchPI__ can be the input of __iFogSim__.

- [gem5](https://www.gem5.org/): The gem5 simulator is a modular platform for
  computer-system architecture research, encompassing system-level architecture
  as well as processor microarchitecture.

- [Ianvs](https://github.com/kubeedge/ianvs): Ianvs is a distributed synergy AI
  benchmarking project incubated in KubeEdge SIG AI. Ianvs aims to test the
  performance of distributed synergy AI solutions following recognized
  standards, in order to facilitate more efficient and effective development.
  More detailedly, Ianvs prepares not only test cases with datasets and
  corresponding algorithms, but also benchmarking tools including simulation and
  hyper-parameter searching. Ianvs also reveals best practices for developers
  and end users with presentation tools including leaderboards and test reports.

- [iFogSim](https://github.com/Cloudslab/iFogSim): The iFogSim Toolkit for
  Modeling and Simulation of Resource Management Techniques in Internet of
  Things, Edge and Fog Computing Environments.

- [IoTSim-Edge](https://github.com/DNJha/IoTSim-Edge): IoTSim captures the
  behavior of heterogeneous IoT and edge computing infrastructure and allows
  users to test their infrastructure and framework in an easy and configurable
  manner. IoTSim-Edge extends the capability of CloudSim to incorporate the
  different features of edge and IoT devices.

- [IoTSim-Osmosis](https://github.com/kalwasel/IoTSim-Osmosis): IoTSim-Osmosis
  is a simulation framework that supports the testing and validation of osmotic
  computing applications. In particular, it enables a unified modelling and
  simulation of complex IoT applications over heterogeneous edge-cloud SDN-aware
  environments.[DOI:10.1016/j.sysarc.2020.101956](https://doi.org/10.1016/j.sysarc.2020.101956)

- [iTETRIS](http://www.ict-itetris.eu/simulator/test_beds.htm): iTETRIS is
  aligned with the communication architecture defined by ETSI for Intelligent
  Transport Systems (ITS). The standard specifications concern a communication
  system designed for various types of traffic applications which can use
  several coexistent communication technologies. The architecture assumes three
  different actors communicating in an ITS scenario, each representing a given
  subsystem: vehicle, roadside and central subsystems.

- [Kathará](https://github.com/KatharaFramework/Kathara): Kathará (from the
  Greek Καθαρά, purely) is a lightweight network emulation system based on
  Docker containers. It can be really helpful in showing interactive
  demos/lessons, testing production networks in a sandbox environment, or
  developing new network protocols.

- [LEAF](https://github.com/dos-group/leaf-java): A simulator for Large
  Energy-Aware Fog computing environments, based on CloudSim Plus. LEAF enables
  energy consumption modeling of distributed, heterogeneous, and
  resource-constrained infrastructure that executes complex application graphs.

- [lightMANO](https://github.com/lightmano/lightmano-core): A lightweight
  distributed service orchestrator designed for resource constrained
  multi-access edge computing environments.

- [MARSSx86](http://www.marss86.org/~marss86/index.php/Home): MARSSx86 (MARSS
  for short) is a tool for cycle accurate full system simulation of the x86-64
  architecture, specifically multicore implementations.
  
- [MaxiNet](https://github.com/MaxiNet/MaxiNet): MaxiNet extends the famous
  Mininet emulation environment to span the emulation across several physical
  machines. This allows to emulate very large SDN networks.

- [MobFogSim](https://github.com/diogomg/MobFogSim): An extension which can
  support for Mobility of __iFogSim__. MobFogSim can model more generalised
  aspects related to device mobility and VM/container migration in the fog,
  e.g., user position and speed, connection handoff, migration policies and
  strategies, to name a few. More details can be found in [MobFogSim: Simulation
  of Mobility and Migration for Fog
  Computing](https://doi.org/10.1016/j.simpat.2019.102062).

- [Mini-NDN](http://minindn.memphis.edu/):Mini-NDN is a lightweight networking
  emulation tool that enables testing, experimentation, and research on the NDN
  platform. It was initially based on
  [Mini-CCNx](https://github.com/chesteve/mn-ccnx) which was a fork of Mininet.
  Mini-NDN uses the NDN libraries, NFD, NLSR, and tools released by the NDN
  project to emulate an NDN network on a single system.

- [MinNet](http://mininet.org/): Mininet creates a realistic virtual network,
  running real kernel, switch and application code, on a single machine (VM,
  cloud or native), in seconds, with a single command:`sudo mn`. Mininet is also
  a great way to develop, share, and experiment with OpenFlow and
  Software-Defined Networking systems.

- [Mininet-WiFi](https://github.com/intrig-unicamp/mininet-wifi): Emulator for 
Software-Defined Wireless Networks.

- [MobEmu](https://github.com/raduciobanu/mobemu): An opportunistic network
  emulator that can run a user-created routing or dissemination algorithm on a
  desired mobility trace or synthetic model.

- [NDN4IVC](https://github.com/insert-lab/ndn4ivc): An open-source
  simulator/framework that facilitates testing of more realistic VANET
  applications via the NDN stack. This project utilizes two popular simulators
  for VANET simulation: the NS3 network simulator with the ndnSIM module and
  SUMO, a simulator of urban mobility. NDN4IVC allows real-time bidirectional
  communication between SUMO and NS3 to support more data about road traffic and
  vehicular mobility. The framework can model the impact of vehicular networks
  on road traffic and investigate complex interactions between the two domains.

- [ndnSIM](https://ndnsim.net/): The ndnSIM 2.0 is NS-3 module that implements
  Named Data Networking (NDN) communication model, the clean slate Internet
  design.

- [NFaaS](https://gitlab.com/mharnen/NFaaS): Enabling to migrate functions
  closer to the user in ICN environment without a global view of the network.

- [NS-3](https://www.nsnam.org): ns-3 is a discrete-event network simulator for
  Internet systems, targeted primarily for research and educational use. ns-3 is
  free, open-source software, licensed under the GNU GPLv2 license, and
  maintained by a worldwide community.

- [OMNeT++](https://github.com/omnetpp/omnetpp): OMNeT++ is a public-source,
  component-based, modular and open-architecture simulation environment with
  strong GUI support and an embeddable simulation kernel. Its primary
  application area is the simulation of communication networks, but it has been
  successfully used in other areas like the simulation of IT systems, queueing
  networks, hardware architectures and business processes as well.

- [Open-Simulator](https://github.com/alibaba/open-simulator): Open-simulator is
  a cluster simulator for Kubernetes. With the simulation capability of
  Open-Simulator, users can create a fake Kubernetes cluster and deploy
  workloads on it. Open-Simulator will simulate the kube-controller-manager to
  create pods for the workloads, and simulate the kube-scheduler to assign pods
  to the appropriate nodes.

- [Packet
  Tracer](https://www.netacad.com/courses/packet-tracer/introduction-packet-tracer):
  Packet Tracer is a cross-platform visual simulation tool designed by Cisco
  Systems that allows users to create network topologies and imitate modern
  computer networks. The software allows users to simulate the configuration of
  Cisco routers and switches using a simulated command line interface. Packet
  Tracer makes use of a drag and drop user interface, allowing users to add and
  remove simulated network devices as they see fit.

- [PeerSim](http://peersim.sourceforge.net/): PeerSim is a simulation
  environment for P2P protocols in java. Its features include easy
  configuration, extendability and high performance.

- [pFogSim](https://github.com/jihall77/pFogSim): pFogSim (/p/-fôg-/sɪm/) is a
  play off iFogSim; A simulator made to handle large-scale FOG networks with the
  HAFA Puddle Strategy to help evaluate the potential advantages/disadvantages
  within user-customizable scenarios.

- [PureEdgeSim](https://github.com/CharafeddineMechalikh/PureEdgeSim): a new
  simulator based on [CloudSim Plus](http://Cloudsimplus.org) that is designed
  to simulate Cloud, Edge, and Mist computing environments. It allows to
  evaluate the performance of resources management strategies in terms of
  network usage, latency, resources utilization, energy consumption, etc. and
  enables the simulation of several scenarios such as the Internet of Things
  (IoT), connected vehicles/VANETs/MANET, Mist computing environments (peer-to
  peer networks such as mobile devices Cloud), and mobile Edge computing.

- [RECAP-DES](https://bitbucket.org/RECAP-DES/recap-des/src/master/): RECAP
  Discrete Event Simulation Framework an extension for CloudSimPlus

- [RECAP Simulator Framework](https://recap-project.eu/simulators/): The RECAP
  Simulation Framework is an open source simulation framework designed to
  support experimentation of infrastructure with different description models
  for workload, user distribution, network topology, and (physical and virtual)
  resource placement. It is able to simulate different use cases including
  Virtual Network Functions (VNFs), Elasticsearch, smart cities, and virtual
  Content Delivery Networks (vCDN). The output of the RECAP Simulation Framework
  depends on the use case, but in general, it is a set of metrics predefined by
  the user such as bandwidth, resource consumption (CPU, memory, storage),
  network delay, energy consumption, active number of VMs, cache hits and cache
  misses.

- [SatEdgeSim](https://github.com/wjy491156866/SatEdgeSim):  A Toolkit for
  Modeling and Simulation of Performance Evaluation in Satellite Edge Computing
  Environments, which uses CloudSim Plus and PureEdgeSim as the underlying
  simulation framework.

- [Shadow](https://github.com/shadow/shadow): Shadow is a discrete-event network
  simulator that directly executes real application code, enabling you to
  simulate distributed systems with thousands of network-connected processes in
  realistic and scalable private network experiments using your laptop, desktop,
  or server running Linux.

- [SUMO - ITS](https://sumo.dlr.de/docs/SUMO_at_a_Glance.html): "Simulation of
  Urban MObility", or "SUMO" for short, is an open source, microscopic,
  multi-modal traffic simulation. It allows to simulate how a given traffic
  demand which consists of single vehicles moves through a given road network.
  The simulation allows to address a large set of traffic management topics. It
  is purely microscopic: each vehicle is modelled explicitly, has an own route,
  and moves individually through the network. Simulations are deterministic by
  default but there are various options for introducing randomness.

- [SimFaaS](https://github.com/pacslab/simfaas): This is a project done in PACS
  Lab aiming to develop a performance simulator for serverless computing
  platforms. Using this simulator, we can calculate Quality of Service (QoS)
  metrics like average response time, the average probability of cold start,
  average running servers (directly reflecting average cost), a histogram of
  different events, distribution of the number of servers throughout time, and
  many other characteristics.

- [SimFlex](https://parsa.epfl.ch/simflex/): SimFlex is proceeding along two
  synergistic fronts: (1) Flexus is a powerful and flexible simulator framework
  that allows full-system simulation that relies heavily on well-defined
  component interface models to facilitate both model integration and
  compile-time simulator optimization. (2) SMARTS applies rigorous statistical
  sampling the­ory to reduce simulation turnaround by several orders of
  magnitude, while achieving high accuracy and confidence in estimates.

- [SimGrid](https://github.com/simgrid/simgrid): SimGrid is a scientific
  instrument to study the behavior of large-scale distributed systems such as
  Grids, Clouds, HPC or P2P systems. It can be used to evaluate heuristics,
  prototype applications or even assess legacy MPI applications.
 
- [SimMobility](https://github.com/smart-fm/simmobility-prod): SimMobility is an
  integrated mobility simulation platform that comprehensively simulates Future
  Mobility scenarios by integrating long, medium, and short-term travel
  behavior. Various mobility-sensitive behavioral models are integrated within
  the state-of-the-art scalable simulators to predict the impact of mobility
  demands on transportation networks, intelligent transportation services and
  vehicular emissions. The platform simulates the effects of a portfolio of
  technology, policy and investment options under alternative future scenarios.
  SimMobility encompasses the modeling of millions of agents, including
  pedestrians, drivers, phones, traffic lights, GPS, cars, buses, and trains,
  from second-by-second to year-by-year simulations and across countries.

- [SimpleIoTSimulator](https://www.simplesoft.com/SimpleIoTSimulator.html):
  SimpleIoTSimulator® is an easy to use, IoT Sensor/device simulator that
  quickly creates test environments made up of thousands of sensors and
  gateways, all on just one computer. SimpleIoTSimulator supports many of the
  common IoT protocols. They include: MQTT, MQTT-SN, MQTT-Broker, CoAP, HTTP/s
  client, HTTP/s server, Modbus over TCP, BACnet/IP server, LoRa Gateway, LoRa
  Device.

- [Simu5G](https://github.com/Unipisa/Simu5G): Simu5G is the evolution of the
  popular [SimuLTE 4G network simulator](https://simulte.com/) that incorporates
  5G New Radio access.

- [SimuLTE](https://simulte.com/): SimuLTE is an innovative simulation tool
  enabling complex system level performance-evaluation of LTE and LTE Advanced
  networks (3GPP Release 8 and beyond) for the OMNeT++ framework.

- [SLEIPNIR](https://github.com/vindem/sleipnir): SLEIPNIR is a DAG scheduling
simulator focused on mobile cloud/edge/iot infrastructures.

- [StarryNet](https://github.com/SpaceNetLab/StarryNet): A novel experimentation
  framework that enables researchers to conveniently build credible and flexible
  experimental network environments (ENE) mimicking satellite dynamics and
  network behaviors of large-scale integrated space and terrestrial networks
  (ISTNs) [paper](https://www.usenix.org/conference/nsdi23/presentation/lai-zeqi).

- [Step-ONE](https://github.com/jaks6/step-one): Simulated Testbed for Edge-Fog
  Processes based on the Opportunistic Network Environment simulator.

- [SVL Simulator](https://github.com/lgsvl/simulator): An end-to-end autonomous
  vehicle simulation platform.

- [The ONE](https://akeranen.github.io/the-one/): The ONE is a simulation
  environment that is capable of: 1) generating node movement using different
  movement models. 2) routing messages between nodes with various DTN routing
  algorithms and sender and receiver types. 3) visualizing both mobility and
  message passing in real time in its graphical user interface. ONE can import
  mobility data from real-world traces or other mobility generators. It can
  also produce a variety of reports from node movement to message passing and
  general statistics.

- [Veins - ITS](https://github.com/sommer/veins): Veins is an open source
  framework for running vehicular network simulations. It is based on two
  well-established simulators: OMNeT++, an event-based network simulator, and
  SUMO, a road traffic simulator. It extends these to offer a comprehensive
  suite of models for IVC simulation.

- [Veins LTE - ITS](http://veins-lte.car2x.org/): Veins LTE is a simulator for
  heterogeneous vehicular networks. It provides fine-grained simulation of
  vehicular networks based on IEEE 802.11p and TE.

- [VENTOS](https://maniam.github.io/VENTOS/#about): VENTOS is an integrated C++
  simulator for studying vehicular traffic flows, collaborative driving, and
  interactions between vehicles and infrastructure through DSRC-enabled wireless
  communication capability. 

- [VirtFogSim](https://github.com/mscarpiniti/VirtFogSim): VirtFogSim is a
  MATLAB-supported software toolbox that allows the dynamic joint optimization
  and tracking of the energy and delay performance of Mobile-Fog-Cloud systems
  for the execution of applications described by general Directed Application
  Graphs (DAGs). Check the paper [link](https://doi.org/10.3390/app9061160) for
  more details.

- [VNS](https://omnetpp.org/download-items/VNS.html): VNS is a simulation
  framework that completely integrates the mobility and network components in a
  transparent and efficient way, reducing the overhead of communication and
  synchronization between different simulators. VNS provides bi-directionally
  interaction between a microscopic mobility model and network simulators such
  as OMNeT++.

- [YAFS(Yet Another Fog Simulator)](https://github.com/acsicuib/YAFS): YAFS is a
  simulator tool based on Python of architectures such as: Fog Computing
  ecosystems for several analysis regarding with the placement of resources,
  cost deployment, network design, ... IoT environments are the most evident
  fact of this type of architecture. The highlights points of YAFS are:
  - Dinamyc topology: entities and network links can be created or removed along
    the simulation.
  - Dinamyc creation of messages sources: sensors can generate messages from
    different point access along the simulation.
  - And for hence, the placement allocation algorithm and the orchestration
    algorithm, that are extended by the user, can run along the simulation.
  - The topology of the network is based on Complex Network theory. Thus, the
    algorithms can obtain more valuable indicators from topological features.
  - The results are stored in a raw format in a nosql database. The simpler the
    format, the easier it is to perform any type of statistics.

# Frameworks

## Engine
- [Akraino Edge Stack](https://www.lfedge.org/projects/akraino/): Akraino is a
  set of open infrastructures and application blueprints for the Edge, spanning
  a broad variety of use cases, including 5G, AI, Edge IaaS/PaaS, IoT, for both
  provider and enterprise edge domains.  These Blueprints have been created by
  the Akraino community and focus exclusively on the edge in all of its
  different forms.  What unites all of these blueprints is that they have been
  tested by the community and are ready for adoption as-is, or used as a
  starting point for customizing a new edge blueprint.

- [Apache Edgent(incubating)](https://edgent.incubator.apache.org/): Apache
  Edgent is a programming model and micro-kernel style runtime that can be
  embedded in gateways and small footprint edge devices enabling local,
  real-time, analytics on the continuous streams of data coming from equipment,
  vehicles, systems, appliances, devices and sensors of all kinds (for example,
  Raspberry Pis or smart phones). Working in conjunction with centralized
  analytic systems, Apache Edgent provides efficient and timely analytics across
  the whole IoT ecosystem: from the center to the edge.

- [Apache OpenWhisk](https://openwhisk.apache.org/): Apache OpenWhisk is an open
  source, distributed Serverless platform that executes functions (fx) in
  response to events at any scale. OpenWhisk manages the infrastructure, servers
  and scaling using Docker containers so you can focus on building amazing and
  efficient applications.

- [AREG SDK](https://github.com/aregtech/areg-sdk): **AREG SDK** is an
  interface-centric real-time asynchronous communication engine to enable
  distributed- and
  [mist-](https://csrc.nist.gov/publications/detail/sp/500-325/final)computing,
  where connected Things interact and provide services as if they act like thin
  distributed servers. The communication engine of AREG SDK is based on Object
  Remote Procedure Call (ORPC) protocol.

- [Baetyl](https://github.com/baetyl/baetyl): Baetyl is an open edge computing
  framework of Linux Foundation Edge that extends cloud computing, data and
  service seamlessly to edge devices. It can provide temporary offline,
  low-latency computing services include device connection, message routing,
  remote synchronization, function computing, video capture, AI inference,
  status reporting, configuration ota etc.

- [Bochs](https://bochs.sourceforge.io/): Bochs is a highly portable open source
  IA-32 (x86) PC emulator written in C++, that runs on most popular platforms.
  It includes emulation of the Intel x86 CPU, common I/O devices, and a custom
  BIOS. Bochs can be compiled to emulate many different x86 CPUs, from early 386
  to the most recent x86-64 Intel and AMD processors which may even not reached
  the market yet.

- [BOINC](https://boinc.berkeley.edu/): BOINC lets you help cutting-edge science
  research using your computer. The BOINC app, running on your computer,
  downloads scientific computing jobs and runs them invisibly in the background.

- [Chameleon](https://www.chameleoncloud.org/): Chameleon is a large-scale,
  deeply reconfigurable experimental platform built to support Computer Sciences
  systems research. Community projects range from systems research developing
  new operating systems, virtualization methods, performance variability
  studies, and power management research to projects in software defined
  networking, artificial intelligence, and resource management. 

- [Distributed Strom](http://matnar.github.io/uniroma2-storm/): Distributed
  Storm is an extension of Apache Storm that supports the execution of
  distributed, adaptive, and QoS-aware scheduling algorithms. It introduces some
  key components on each worker node that enhance the system with adaptation
  capabilities, relying on a MAPE (Monitor, Analyze, Plan, and Execute) feedback
  loop periodically executed. Specifically, the newly introduced components are:
  the AdaptiveSchedulers, the QoSMonitors, and the WorkerMonitors. Logics of a
  `Bolt` can be regarded as an edge server processes the data.

- [ENORM](https://github.com/qub-blesson/ENORM): The ENORM framework primarily
  addresses the deployment and load balancing challenges on individual edge
  nodes. ENORM operates in a three-tier environment, but a master controller
  does not control the edge nodes. Instead, it is assumed that they are visible
  to cloud servers that may want to make use of the edge. The framework allows
  for partitioning a cloud server and offloading it to edge nodes for improving
  the overall QoS of the application.

- [EdgeGallery (Documents maintained in
  Chinese)](https://gitee.com/edgegallery): EdgeGallery is a 5G edge computing
  open source project supported by device vendors, operators, vertical industry
  partners, etc. Its goal is to create a public platform for edge computing that
  meets the characteristics of 5G MEC "connectivity and computation",
  standardize open network capabilities (especially for 5G networks), and
  generalize the lifecycle-management process of MEC application development
  (testing, migration, and operation).

- [EdgeMesh](https://github.com/kubeedge/edgemesh):EdgeMesh is a part of
  KubeEdge, and provides a simple network solution for the inter-communications
  between services at edge scenarios.

- [EdgeX Foundry](https://www.edgexfoundry.org/): EdgeX Foundry is a highly
  flexible and scalable open source software framework that facilitates
  interoperability between devices and applications at the IoT Edge.

- [Folding@home](https://foldingathome.org/): Folding@home (FAH or F@h) is a
  distributed computing project for simulating protein dynamics, including the
  process of protein folding and the movements of proteins implicated in a
  variety of diseases. It brings together citizen scientists who volunteer to
  run simulations of protein dynamics on their personal computers and scientific
  researchers. Insights from these data are helping scientists to better
  understand biology and providing new opportunities for developing
  therapeutics.

- [FogAtlas](https://fogatlas.fbk.eu/): FogAtlas (evolution of the former Foggy
  platform) is a software framework aiming to manage a geographically
  distributed and decentralized Cloud Computing infrastructure that provides
  computational, storage and network services close to the data sources and the
  users, embracing the Fog Computing paradigm. FogAtlas is able to manage the so
  called Cloud-to-Thing Continuum offering service-aware workload placement and
  zero-touch deployment. It is an evolution of the well known paradigms of IaaS
  and PaaS adding the concept of “locality” to the traditional Cloud Computing
  model and easing the operations of a Fog Computing infrastructure.

- [FogFlow](https://github.com/smartfog/fogflow): FogFlow is an IoT edge
  computing framework to automatically orchestrate dynamic data processing flows
  over cloud and edges driven by context, including system context on the
  available system resources from all layers, data context on the registered
  metadata of all available data entities, and also usage context on the
  expected QoS defined by users.

- [k3OS](https://k3os.io/): k3OS is purpose-built to simplify Kubernetes
  operations in low-resource computing environments. Installs fast. Boots
  faster. Managed through Kubernetes.

- [K3s](https://k3s.io/): Lightweight Kubernetes. Production ready, easy to
  install, half the memory, all in a binary less than 100 MB. Great for Edge,
  IoT, CI, Development, ARM, Embedding k8s, and Situations where a PhD in k8s
  clusterology is infeasible

- [Krustlet](https://krustlet.dev/): Krustlet: Kubernetes Kubelet in Rust for
  running WASM Krustlet acts as a Kubelet by listening on the event stream for
  new pods that the scheduler assigns to it based on specific Kubernetes
  tolerations. The default implementation of Krustlet listens for the
  architecture wasm32-wasi and schedules those workloads to run in a
  wasmtime-based runtime instead of a container runtime.

- [KubeEdge](https://github.com/kubeedge/kubeedge):KubeEdge is an open source
  system extending native containerized application orchestration and device
  management to hosts at the Edge. It is built upon Kubernetes and provides core
  infrastructure support for networking, application deployment and metadata
  synchronization between cloud and edge. It also supports MQTT and allows
  developers to author custom logic and enable resource constrained device
  communication at the Edge. KubeEdge consists of a cloud part and an edge part.

- [OCI](https://github.com/marckoerner/oci):  a framework that enables network
  operators with the ability to open up their edge facilities to Application
  Service Providers, by offering edge computing. As an example, consider a
  third-party Application Service Provider selling an IoT device (say, a home
  thermostat or security camera). Whenever that device shows up at the edge of
  the network, the Open Carrier Interface framework starts the Application
  Service Provider implemented edge software at the network operator’s Central
  Offices, which supports the IoT device with edge processing. Thus, even an
  early-stage Application Service Provider, who has few financial or physical
  resources, can offer the same level of edge support as giant companies, and
  therefore can compete with them on an even footing. [read
  more](https://doi.org/10.1145/3229574.3229579).

- [OpenStack++](http://elijah.cs.cmu.edu/development.html): is a framework
  developed by Carnegie Mellon University Pittsburgh for providing VM-based
  cloudlet platform on regular x86 computers for mobile application offloading.
  A set of new mobile computing applications that build upon OpenStack++ and
  leverage its support for cloudlets is also supported.

- [OpenYurt](https://github.com/openyurtio/openyurt): OpenYurt has been designed
  to meet various DevOps requirements against typical edge infrastructures. It
  provides the same user experience for managing the edge applications as if
  they were running in the cloud infrastructure. It addresses specific
  challenges for cloud-edge orchestration in Kubernetes such as unreliable or
  disconnected cloud-edge networking, edge node autonomy, edge device
  management, region-aware deployment and so on. OpenYurt preserves intact
  Kubernetes API compatibility, is vendor agnostic, and more importantly, is
  SIMPLE to use.

- [PhoneSploit Pro](https://github.com/AzeemIdrisi/PhoneSploit-Pro): An
  all-in-one hacking tool to remotely exploit Android devices using ADB and
  Metasploit-Framework to get a Meterpreter session.

- [SuperEdge](https://github.com/superedge/superedge): SuperEdge is an open
  source container management system for edge computing to manage compute
  resources and container applications in multiple edge regions. These resources
  and applications, in the current approach, are managed as one single
  Kubernetes cluster. A native Kubernetes cluster can be easily converted to a
  SuperEdge cluster.

- [WebAssembly: Curated list of awesome things regarding WebAssembly (wasm)
  ecosystem.](https://github.com/mbasso/awesome-wasm)

- [WebAssembly Micro
  Runtime](https://github.com/bytecodealliance/wasm-micro-runtime): WebAssembly
  Micro Runtime (WAMR) is a standalone WebAssembly (WASM) runtime with a small
  footprint. It includes a few parts as below: 1, The "iwasm" VM core,
  supporting WebAssembly interpreter, ahead of time compilation (AoT) and
  Just-in-Time compilation (JIT). 2, The application framework and the
  supporting API's for the WASM applications. 3, The dynamic management of the
  WASM applications

- [wasmCloud](https://wasmcloud.dev/): wasmCloud is a distributed platform for
  writing portable business logic that can run anywhere from the edge to the
  cloud. Secure by default, wasmCloud aims to strip wasteful boilerplate from
  the developer experience and return joy to the act of building distributed
  applications.

- [WasmEdge Runtime](https://wasmedge.org/): WasmEdge (previously known as SSVM)
  is a lightweight, high-performance, and extensible WebAssembly runtime for
  cloud native, edge, and decentralized applications. It is the fastest Wasm VM
  today. WasmEdge is an official sandbox project hosted by the CNCF. Its use
  cases include serverless apps, embedded functions, microservices, smart
  contracts, and IoT devices.

- [Wasmer](https://wasmer.io/): Wasmer is a fast and secure WebAssembly runtime
  that enables super lightweight containers to run anywhere: from Desktop to the
  Cloud, Edge and IoT devices.

- [Wasmtime](https://wasmtime.dev/): Wasmtime is a Bytecode Alliance project
  that is a standalone wasm-only optimizing runtime for WebAssembly and WASI. It
  runs WebAssembly code outside of the Web, and can be used both as a
  command-line utility or as a library embedded in a larger application.

- [WSO2-IoT Server](https://wso2.com/iot): An extension of the popular
  open-source enterprise service-oriented integration platform WSO2 server that
  consists of certain IoT-related mechanisms, such as connecting a broad range
  of common IoT devices with the cloud using standard protocols such as MQTT and
  XMPP. Further, WSO2–IoT server includes the embedded Siddhi 3.0 component that
  allows the system to deploy real-time streaming processes in embedded devices.
  In other words, WSO2–IoT server provides the FEC computing capability to
  outer-edge devices.


## Networks
- [Awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools):A
  collection of tools developed by other researchers in the Computer Science
  area to process network traces.

- [EdgeNet](https://github.com/EdgeNet-Project): edgeNet is a distributed edge
  cloud, in the family of PlanetLab, GENI, Canada’s SAVI infrastructure, Japan’s
  JGN-X, Germany’s G-Lab, and PlanetLab Europe. It is a modern distributed edge
  cloud, incorporating advances in Cloud technologies over the past few years.

- [Komondor](https://github.com/wn-upf/Komondor): Komondor is a wireless network
  simulator that includes novel mechanisms for next-generation WLANs, such as
  dynamic channel bonding or enhanced spatial reuse. One of the main purposes of
  Komondor is to simulate the behavior of IEEE 802.11ax-2019 networks, an
  amendment designed to boost spectral efficiency in dense deployments.

- [Mosquitto](http://mosquitto.org/): Eclipse Mosquitto is an open source
  (EPL/EDL licensed) message broker that implements the MQTT protocol versions
  5.0, 3.1.1 and 3.1. Mosquitto is lightweight and is suitable for use on all
  devices from low power single board computers to full servers. The MQTT
  protocol provides a lightweight method of carrying out messaging using a
  publish/subscribe model. This makes it suitable for Internet of Things
  messaging such as with low power sensors or mobile devices such as phones,
  embedded computers or microcontrollers. The Mosquitto project also provides a
  C library for implementing MQTT clients, and the very popular `mosquitto_pub`
  and `mosquitto_sub` command line MQTT clients.

- [Naming Data Network Platform](https://named-data.net/codebase/platform/): NDN
  is an entirely new architecture, but one whose design principles are derived
  from the successes of today’s Internet, reflecting our understanding of the
  strengths and limitations of the current Internet architecture, and one that
  can be rolled out through incremental deployment over the current operational
  Internet.

- [Node-RED](https://nodered.org/): Node-RED is a programming tool for wiring
  together hardware devices, APIs and online services in new and interesting
  ways. It provides a browser-based editor that makes it easy to wire together
  flows using the wide range of nodes in the palette that can be deployed to its
  runtime in a single-click.

- [Open vSwitch](https://www.openvswitch.org/):  is a production quality,
  multilayer virtual switch licensed under the open source Apache 2.0 license.
  It is designed to enable massive network automation through programmatic
  extension, while still supporting standard management interfaces and protocols
  (e.g. NetFlow, sFlow, IPFIX, RSPAN, CLI, LACP, 802.1ag).  In addition, it is
  designed to support distribution across multiple physical servers similar to
  VMware's vNetwork distributed vswitch or Cisco's Nexus 1000V.

- [POX](https://github.com/noxrepo/pox): POX is a networking software platform
  written in Python. POX started life as an OpenFlow controller, but can now
  also function as an OpenFlow switch, and can be useful for writing networking
  software in general. An useful link of how to simulate a SDN can check the
  link: http://www.brianlinkletter.com/using-the-pox-sdn-controller/

- [RICE](https://github.com/harnen/timers): A unified approach to remote
  function invocation in ICN([Naming Data Network
  Platform](https://named-data.net/codebase/platform/)) that exploits the
  attractive ICN properties of name-based routing, receiver-driven low and
  congestion control, low balance, and object-oriented security while presenting
  a natural programming model to the application developer.

- [VerneMQ](https://vernemq.com/): VerneMQ is a high-performance, distributed
  MQTT message broker. It scales horizontally and vertically on commodity
  hardware to support a high number of concurrent publishers and consumers while
  maintaining low latency and fault tolerance. VerneMQ is the reliable message
  hub for your IoT platform or smart products.

- [Wonder Shaper](https://github.com/magnific0/wondershaper): Wonder Shaper is a
  script that allows the user to limit the bandwidth of one or more network
  adapters. It does so by using iproute's tc command, but greatly simplifies its
  operation.

# Test (data, benchmark)
- [aBeacon Data](https://people.cs.rutgers.edu/~dz220/Data.html): A large-scale
  repository composed of BLE sensing, location trace, and manual report data,
  including 31,131 couriers at 2,466 merchant locations in one month.

- [AI Benchmark](https://ai-benchmark.com/): The performance and comparison of
  all chipsets from Qualcomm, HiSilicon, Samsung, MediaTek and Unisoc that are
  providing hardware acceleration for AI inference. 

- [CloudSuite](https://www.cloudsuite.ch/): CloudSuite is a benchmark suite for
  cloud services. The third release consists of eight applications that have
  been selected based on their popularity in today’s datacenters. The benchmarks
  are based on real-world software stacks and represent real-world setups.

- [DeFog](https://github.com/qub-blesson/DeFog): DeFog, a first Fog benchmarking
  suite to: (i) alleviate the burden of Fog benchmarking by using a standard
  methodology, and (ii) facilitate the understanding of the target platform by
  collecting a catalogue of relevant metrics for a set of benchmarks.

- [Edge AIBench](https://www.benchcouncil.org/EdgeAIBench/index.html): Edge
  AIBench is a benchmark suite for end-to-end edge computing including four
  typical application scenarios: ICU Patient Monitor, Surveillance Camera, Smart
  Home, and Autonomous Vehicle, which consider the complexity of all edge
  computing AI scenarios. In addition, Edge AIBench provides an end-to-end
  application benchmarking framework, including train, validate and inference
  stages. 

- [EUA Datasets](https://github.com/swinedge/eua-datase): This repository
  maintains a set of EUA datasets which we collected from real-world data
  sources. The datasets are publicly released to facilitate research in Edge
  Computing. All the data is in Australia region which contains edge server
  locations and user location.

- [GT-ITM: Georgia Tech Internetwork Topology
  Models](https://www.cc.gatech.edu/projects/gtitm/): This is a collection of
  routines to generate and analyze graphs using a wide variety of models for
  internetwork topology. The graphs are generated in Don Knuth's SGB format; a
  routine is provided to convert to an alternative format that may be easier to
  parse.

- [Huawei - Dataset for Network AI Scheduling Technology
  Research (in Chinese)](https://res-static.hc-cdn.cn/cloudbu-site/china/zh-cn/6gana/1681784385302642219.zip):
  Modeling computational service scenarios for Network AI, providing users with
  strategy algorithms for task scheduling research.

- [MLPerf Inference Benchmark Suite](https://github.com/mlcommons/inference):
  MLPerf Inference is a benchmark suite for measuring how fast systems can run
  models in a variety of deployment scenarios.

- [networkX](https://networkx.github.io/): NetworkX is a Python language package
  for exploration and analysis of networks and network algorithms. The core
  package provides data structures for representing many types of networks, or
  graphs, including simple graphs, directed graphs, and graphs with parallel
  edges and self-loops. The nodes in NetworkX graphs can be any (hashable)
  Python object and edges can contain arbitrary data; this flexibility makes
  NetworkX ideal for representing networks found in many different scientific
  fields.

- [Neural Network Accelerator
  Comparison](http://nicsefc.ee.tsinghua.edu.cn/projects/neural-network-accelerator/):
  A comparison of AI hardware accelerators among different platform.

- [Rocketfuel](https://research.cs.washington.edu/networking/rocketfuel/):
  Traceroutes were sourced from 800 vantage points hosted by nearly 300
  traceroute web servers. They started by mapping 10 ISPs, in Europe, Australia
  and the United States. In that process, they constructed a database of over 50
  thousand IP addresses representing 45 thousand routers in 537 POPs connected
  by 80 thousand links.

- [The CAIDA Anonymized Internet Traces 2015
  Dataset](https://www.caida.org/data/passive/passive_2015_dataset.xml): CAIDA's
  passive traces dataset contains traces collected from high-speed monitors on a
  commercial backbone link. The data collection started in April 2008 and ended
  in January 2019. These data are useful for research on the characteristics of
  Internet traffic, including application breakdown, security events, geographic
  and topological distribution, flow volume and duration.

- [tinyMLPerf Deep Learning Benchmarks for Embedded
  Devices](https://github.com/mlcommons/tiny): The goal of TinyMLPerf is to
  provide a representative set of deep neural nets and benchmarking code to
  compare performance between embedded devices. Embedded devices include
  microcontrollers, DSPs, and tiny NN accelerators. These devices typically run
  at between 10MHz and 250MHz, and can perform inference using less then 50mW of
  power.

- vivo —— Dataset for Wireless Resource Scheduling in Cell-Free Scenarios  (in
  Chinese) : Aims to research AI-based scheduling strategies for Cell-Free
  systems. 
  - Dataset: https://commonbox.vivo.xyz/s/rUeNxBRZfKL 
  - Codes: https://commonbox.vivo.xyz/s/dHMSmyouTeC

# Tools
- [ASSOLO](http://netlab-mn.unipv.it/assolo/): ASSOLO is a new active probing
  tool for estimating available bandwidth based on the concept of "self-induced
  congestion". ASSOLO features a new probing traffic profile called REACH
  (Reflected ExponentiAl Chirp), which tests a wide range of rates being more
  accurate in the center of the probing interval. Moreover, the tool runs inside
  a real-time operating system and uses some de-noising techniques to improve
  the measurement process.

- [netem](https://wiki.linuxfoundation.org/networking/netem) : netem provides
  Network Emulation functionality for testing protocols by emulating the
  properties of wide area networks. The current version emulates variable delay,
  loss, duplication and re-ordering.

- [nmon](http://nmon.sourceforge.net/pmwiki.php): This systems administrator,
  tuner, benchmark tool gives you a huge amount of important performance
  information in one go. Many helpful tools for data analysis can be also found
  on section [Data
  Analysis](http://nmon.sourceforge.net/pmwiki.php?n=Main.HomePage).

- [GeoLite2](https://dev.maxmind.com/geoip/geoip2/geolite2/): Mapping source
  IPv4 addresses to geo-graphical locations.

- [Sigar](https://github.com/hyperic/sigar/wiki/overview): The Sigar API
  provides a portable interface for gathering system information such as:

  - System memory, swap, cpu, load average, uptime, logins
  - Per-process memory, cpu, credential info, state, arguments, environment, open
    files
  - File system detection and metrics
  - Network interface detection, configuration info and metrics
  - TCP and UDP connection tables Network route table 
  
  This information is available in most operating systems, but each OS has their
  own way(s) providing it. SIGAR provides developers with API to access this
  information regardless of the underlying platform. one The core API is
  implemented in pure C with bindings currently implemented for Java, Perl,
  Ruby, Python, Erlang, PHP and C#.


# Applications
- [Edge Courier](https://github.com/bumoslab/EdgeCourier): An application for
  solving the whole-file-sync problem which needs high bandwidth in the cloud.

- [Eman's Edge Computing System For AI Applications](https://github.com/emmanuelacastillo/python-edge-computing-system):
  Highly accurate AI applications, particularly for Computer Vision requires
  extensive memory and computational power. Eman's Edge Computing System
  orchestrates resource limited devices that requires using resource heavy AI
  algorithms so that a system can still achieve ideal system performances. This
  is done through Edge's monitoring modules that determines how to adjust the
  system so the system can operate efficiently based on its environments
  conditions.

# Edge-AI frameworks
- [Adlik](https://github.com/Adlik/Adlik): Adlik [ædlik] is an end-to-end
  optimizing framework for deep learning models. The goal of Adlik is to
  accelerate deep learning inference process both on cloud and embedded
  environment.

- [AI Model Efficiency Toolkit (AIMET)](https://github.com/quic/aimet):AIMET is
  a library that provides advanced model quantization and compression techniques
  for trained neural network models. It provides features that have been proven
  to improve run-time performance of deep learning neural network models with
  lower compute and memory requirements and minimal impact to task accuracy.

- [Apache TVM](https://tvm.apache.org/): Apache TVM is an open source machine
  learning compiler framework for CPUs, GPUs, and machine learning accelerators.
  It aims to enable machine learning engineers to optimize and run computations
  efficiently on any hardware backend.

- [BerryNet](https://github.com/DT42/BerryNet): This project turns edge devices
  such as Raspberry Pi into an intelligent gateway with deep learning running on
  it. No internet connection is required, everything is done locally on the edge
  device itself. Further, multiple edge devices can create a distributed AIoT
  network.

- [Bi-Real Net](https://github.com/liuzechun/Bi-Real-net): Compared with the
  standard 1-bit CNNs, Bi-Real net utilizes a simple short-cut to significantly
  enhance the representational capability. Further, an advanced training
  algorithm is specifically designed for training 1-bit CNNs (including Bi-Real
  net), including a tighter approximation of the derivative of the sign function
  with respect the activation, the magnitude-aware gradient with respect to the
  weight, as well as a novel initialization.

- [BMXNet](https://github.com/hpi-xnor/BMXNet): Apache MXNet is a deep learning
  framework designed for both efficiency and flexibility. It allows you to mix
  symbolic and imperative programming to maximize efficiency and productivity.
  At its core, MXNet contains a dynamic dependency scheduler that automatically
  parallelizes both symbolic and imperative operations on the fly. A graph
  optimization layer on top of that makes symbolic execution fast and memory
  efficient. MXNet is portable and lightweight, scalable to many GPUs and
  machines.

- [BranchyNet](https://github.com/kunglab/branchynet): Fast inference via early
  exiting from deep neural networks. The architecture allows prediction results
  for a large portion of test samples to exit the network early via these
  branches when samples can already be inferred with high confidence.

- [Caffe2](https://github.com/pytorch/pytorch/tree/master/caffe2):Caffe2 is a
  lightweight, modular, and scalable deep learning framework. Building on the
  original Caffe, Caffe2 is designed with expression, speed, and modularity in
  mind.

- [CMSIS-NN](https://www.keil.com/pack/doc/CMSIS/NN/html/index.html): Collection
  of efficient neural network kernels developed to maximize the performance and
  minimize the memory footprint on Cortex-M processor cores.

- [Communication-Aware DNN Pruning (CaP)](https://github.com/neu-spiral/CaP): A
  novel distributed inference framework for distributing DNN computations across
  a physical network. Departing from conventional pruning methods, CaP takes the
  physical network topology into consideration and produces DNNs that are
  communication-aware, designed for both accurate and fast execution over such a
  distributed deployment.

- [Compute Library](https://github.com/ARM-software/ComputeLibrary): The Compute
  Library is a collection of low-level machine learning functions optimized for
  Arm® Cortex®-A and Arm® Mali™ GPUs architectures.

- [Condensa](https://github.com/NVlabs/condensa): CONDENSA allows developers to
  design strategies for compressing DL models, resulting significant reduction
  in both the memory footprint and execution time. It uses a Bayesian
  optimization-based method to find compression hyperparameters automatically by
  exploiting an L-C optimizer to recover the accuracy loss during compression.
  They reported a 2.22 times runtime improvement over an uncompressed VGG-19 on
  the CIFAR-10 dataset with up to 65 times memory reduction. [src from: 10.1145/3469029](https://doi.org/10.1145/3469029)

- [Core ML](https://developer.apple.com/documentation/coreml): Core ML optimizes
  on-device performance by leveraging the CPU, GPU, and Neural Engine while
  minimizing its memory footprint and power consumption. Running a model
  strictly on the user’s device removes any need for a network connection, which
  helps keep the user’s data private and your app responsive.

- [daBNN](https://github.com/JDAI-CV/dabnn): daBNN is an open-source fast
  inference framework developed by Zhang et al., which can implement Binary
  Neural Networks on ARM devices [161]. An upgraded bit-packing scheme and
  binary direct convolution have been used in this framework to shrink the cost
  of convolution and speed up inference. This framework is written in C++ and
  ARM assembly and has Java support for the Android package. This fast framework
  can be 6 times faster than [BMXNet](https://github.com/hpi-xnor/BMXNet) on
  [Bi-Real Net](https://github.com/liuzechun/Bi-Real-net). [src from: 10.1145/3469029](https://doi.org/10.1145/3469029)

- [DDNN](https://github.com/kunglab/ddnn):  distributed deep neural networks
  (DDNNs) over distributed computing hierarchies, consisting of the cloud, the
  edge (fog) and end devices. While being able to accommodate inference of a
  deep neural network (DNN) in the cloud, a DDNN also allows fast and localized
  inference using shallow portions of the neural network at the edge and end
  devices. Due to its distributed nature, DDNNs enhance data privacy and system
  fault tolerance for DNN applications. When supported by a scalable distributed
  computing hierarchy, a DDNN can scale up in neural network size and scale out
  in geographical span.

- [DeepIoT](https://github.com/yscacaca/DeepIoT): DeepIoT is a framework that
  shrinks a neural network into smaller dense matrices but keeps the performance
  of the algorithm almost the same. This framework finds the minimum
  number of filters and dimensions required by each layer and reduces the
  redundancy of that layer. [src from: 10.1145/3469029](https://doi.org/10.1145/3469029)

- [DeepStack](https://www.deepstack.cc/): DeepStack is an Open-Source AI API
  engine that serves pre-built models and custom models on multiple edge devices
  locally or on your private cloud.

- [DeepThings](https://github.com/SLAM-Lab/DeepThings): A framework for locally
  distributed and adaptive CNN inference in resource-constrained IoT edge
  clusters. DeepThings mainly consists of: 1). A Fused Tile Partitioning (FTP)
  method for dividing convolutional layers into independently distributable
  tasks. FTP fuses layers and partitions them vertically in a grid fashion,
  which largely reduces communication and task migration overhead. 2). A
  distributed work stealing runtime system for IoT clusters to adaptively
  distribute FTP partitions in dynamic application scenarios.

- [Distiller](https://github.com/IntelLabs/distiller): Distiller is an
  open-source Python package for neural network compression research. It
  provides a PyTorch environment for prototyping and analyzing compression
  algorithms, such as sparsity-inducing methods and low-precision arithmetic.

- [FATE](https://github.com/FederatedAI/FATE):FATE (Federated AI Technology
  Enabler) is an open-source project initiated by Webank's AI Department to
  provide a secure computing framework to support the federated AI ecosystem. It
  implements secure computation protocols based on homomorphic encryption and
  multi-party computation (MPC). It supports federated learning architectures
  and secure computation of various machine learning algorithms, including
  logistic regression, tree-based algorithms, deep learning and transfer
  learning.

- [FedProx](https://github.com/litian96/FedProx): FedProx aims to solve two key
  challenges that differentiate it from traditional distributed optimization:
  (1) significant variability in terms of the systems characteristics on each
  device in the network (systems heterogeneity), and (2) non-identically
  distributed data across the network (statistical heterogeneity).

- [GNN-RL pipleline](https://gnn-rl.readthedocs.io/en/latest/): GNN-RL pipleline is a
  toolkit to help users extract topology information through reinforcement
  learning task (e.g., topology-aware neural network compression and job
  scheduling). GNN-RL contains two major part -- graph neural network (GNN) and
  reinforcement learning (RL). It requires your research object is a graph or
  been modeled as a graph, the reinforcement learning take the graph as
  environment states and produces actions by using a GNN-based policy network.

- [KitNET](https://github.com/ymirsky/KitNET-py): KitNET is an online,
  unsupervised, and efficient anomaly detector. A Kitsune, in Japanese folklore,
  is a mythical fox-like creature that has a number of tails, can mimic
  different forms, and whose strength increases with experience. Similarly,
  Kit-NET has an ensemble of small neural networks (autoencoders), which are
  trained to mimic (reconstruct) network traffic patterns, and whose performance
  incrementally improves overtime.

- [MACE](https://github.com/XiaoMi/mace): MACE (Mobile AI Compute Engine) is a
  deep learning inference framework optimized for mobile heterogeneous computing
  platforms. MACE provides tools and documents to help users to deploy deep
  learning models to mobile phones, tablets, personal computers and IoT devices.

- [MegEngine](https://github.com/MegEngine/MegEngine): MegEngine is a fast,
  scalable and easy-to-use deep learning framework, with auto-differentiation.

- [MindSpore Lite](https://www.mindspore.cn/lite/en): MindSpore Lite is an
  ultra-fast, intelligent, and simplified AI engine that enables intelligent
  applications in all scenarios, provides E2E solutions for users, and helps
  users enable AI capabilities.

- [ML Kit](https://developers.google.com/ml-kit): ML Kit 19 is a mobile SDK
  framework introduced by Google. It uses Google's cloud vision APIs, mobile
  vision APIs, and TensorFlow Lite to perform tasks like text recognition, image
  labeling, and smart reply. Curukogluall et al. tested ML Kit APIs for image
  recognition, bar-code scanning, and text recognition on an Android device and
  reported that these APIs recognize different types of test objects such as tea
  cup, water glass, remote controller, and computer mouse successfully. [src
  from: 10.1145/3469029](https://doi.org/10.1145/3469029)

- [MLC LLM](https://github.com/mlc-ai/mlc-llm): In recent years, there has been
  remarkable progress in generative artificial intelligence (AI) and large
  language models (LLMs), which are becoming increasingly prevalent. Thanks to
  open-source initiatives, it is now possible to develop personal AI assistants
  using open-sourced models. However, LLMs tend to be resource-intensive and
  computationally demanding. To create a scalable service, developers may need
  to rely on powerful clusters and expensive hardware to run model inference.
  Additionally, deploying LLMs presents several challenges, such as their
  ever-evolving model innovation, memory constraints, and the need for potential
  optimization techniques.

- [MNN](https://github.com/alibaba/MNN): MNN is a highly efficient and
  lightweight deep learning framework. It supports inference and training of
  deep learning models, and has industry leading performance for inference and
  training on-device. At present, MNN has been integrated in more than 20 apps
  of Alibaba Inc, such as Taobao, Tmall, Youku, Dingtalk, Xianyu and etc.,
  covering more than 70 usage scenarios such as live broadcast, short video
  capture, search recommendation, product searching by image, interactive
  marketing, equity distribution, security risk control. In addition, MNN is
  also used on embedded devices, such as IoT.

- [Model Compression Toolkit (MCT)](https://github.com/sony/model_optimization):
  Model Compression Toolkit (MCT) is an open source project for neural network
  model optimization under efficient, constrained hardware. This project
  provides researchers, developers, and engineers advanced quantization and
  compression tools for deploying state-of-the-art neural networks.

- [MQBench](https://github.com/ModelTC/MQBench): MQBench is an open-source model
  quantization toolkit based on PyTorch fx. The envision of MQBench is to
  provide: 1) SOTA Algorithms. With MQBench, the hardware vendors and
  researchers can benefit from the latest research progress in academia. 2)
  Powerful Toolkits. With the toolkit, quantization node can be inserted to the
  original PyTorch module automatically with respect to the specific hardware.
  After training, the quantized model can be smoothly converted to the format
  that can inference on the real device.

- [ncnn](https://github.com/Tencent/ncnn): ncnn is a high-performance neural
  network inference computing framework optimized for mobile platforms. ncnn is
  deeply considerate about deployment and uses on mobile phones from the
  beginning of design. ncnn does not have third party dependencies. it is
  cross-platform, and runs faster than all known open source frameworks on
  mobile phone cpu. Developers can easily deploy deep learning algorithm models
  to the mobile platform by using efficient ncnn implementation, create
  intelligent APPs, and bring the artificial intelligence to your fingertips.
  ncnn is currently being used in many Tencent applications, such as QQ, Qzone,
  WeChat, Pitu and so on.

- [Neurosurgeon](https://github.com/njcpe/neurosurgeon):A lightweight scheduler
  to automatically partition DNN computation between mobile devices and
  datacenters at the granularity of neural network layers.

- [nn-Meter](https://github.com/microsoft/nn-Meter):nn-Meter is a novel and
  efficient system to accurately predict the inference latency of DNN models on
  diverse edge devices. The key idea is dividing a whole model inference into
  kernels, i.e., the execution units of fused operators on a device, and conduct
  kernel-level prediction.

- [ns3-ai](https://github.com/hust-diangroup/ns3-ai):This module does not
  provide any AI algorithms or rely on any frameworks   but instead is providing
  a Python module that enables AI interconnect, so the AI framework needs to be
  separately installed.   You only need to clone or download this work, then
  import the Python modules, you could use this work to exchange data
  between ns-3 and your AI algorithms.

- [ns3-gym](https://github.com/tkn-tub/ns3-gym): OpenAI Gym is a toolkit for
  reinforcement learning (RL) widely used in research. The network simulator
  ns–3 is the de-facto standard for academic and industry studies in the areas
  of networking protocols and communication technologies. ns3-gym is a framework
  that integrates both OpenAI Gym and ns-3 in order to encourage usage of RL in
  networking research.
  
- [NVIDIA TensorRT](https://developer.nvidia.com/tensorrt): NVIDIA® TensorRT™ is
  an SDK for high-performance deep learning inference. It includes a deep
  learning inference optimizer and runtime that delivers low latency and high
  throughput for deep learning inference applications.

- [Once for All](https://github.com/mit-han-lab/once-for-all): Train One Network
  and Specialize it for Efficient Deployment.

- [ONNX Runtime](https://github.com/microsoft/onnxruntime): ONNX Runtime is a
  cross-platform inference and training machine-learning accelerator. It can
  enable faster customer experiences and lower costs, supporting models from
  deep learning frameworks such as PyTorch and TensorFlow/Keras as well as
  classical machine learning libraries such as scikit-learn, LightGBM, XGBoost,
  etc. ONNX Runtime is compatible with different hardware, drivers, and
  operating systems, and provides optimal performance by leveraging hardware
  accelerators where applicable alongside graph optimizations and transforms.

- [OpenVINO](): OpenVINO™ is an open-source toolkit for optimizing and deploying
  AI inference.
  - Boost deep learning performance in computer vision, automatic speech
    recognition, natural language processing and other common tasks
  - Use models trained with popular frameworks like TensorFlow, PyTorch and more
  - Reduce resource demands and efficiently deploy on a range of Intel®
    platforms from edge to cloud


- [Paddle-Lite](https://github.com/PaddlePaddle/Paddle-Lite): Paddle Lite is an
  updated version of Paddle-Mobile, an open-open source deep learning framework
  designed to make it easy to perform inference on mobile, embeded, and IoT
  devices. It is compatible with PaddlePaddle and pre-trained models from other
  sources.

- [Pocket](https://github.com/GTkernel/Pocket): A new approach for serving ML
  applications in settings like the edge, based on a shared ML runtime backend
  as a service and lightweight ML application pocket containers. Key to
  realizing Pocket is use of lightweight IPC, support for cross-client
  isolation, and a novel resource amplification method which inlines resource
  reallocation with IPC. The latter ensures just-in-time assignment of the
  limited edge resources where they're most needed, thereby reducing contention
  effects and boosting overall performance and efficiency. [Pocket: ML Serving
  from the Edge](https://dl.acm.org/doi/10.1145/3552326.3587459)

- [PyTorch Mobile](https://pytorch.org/mobile/home/): The PyTorch Mobile runtime
  beta release allows you to seamlessly go from training a model to deploying
  it, while staying entirely within the PyTorch ecosystem. It provides an
  end-to-end workflow that simplifies the research to production environment for
  mobile devices. In addition, it paves the way for privacy-preserving features
  via federated learning techniques.

- [SparseML](https://github.com/neuralmagic/sparseml): SparseML is an
  open-source model optimization toolkit that enables you to create
  inference-optimized sparse models using pruning, quantization, and
  distillation algorithms. Models optimized with SparseML can then be exported
  to the ONNX and deployed with DeepSparse for GPU-class performance on CPU
  hardware.

- [SparseZoo](https://github.com/neuralmagic/sparsezoo): SparseZoo is a
  constantly-growing repository of sparsified (pruned and pruned-quantized)
  models with matching sparsification recipes for neural networks. It simplifies
  and accelerates your time-to-value in building performant deep learning models
  with a collection of inference-optimized models and recipes to prototype from.

- [SNPE](https://developer.qualcomm.com/sites/default/files/docs/snpe/index.html):
  The Snapdragon Neural Processing Engine (SNPE) is a Qualcomm Snapdragon
  software accelerated runtime for the execution of deep neural networks. With
  SNPE, users can:
    - Execute an arbitrarily deep neural network
    - Execute the network on the SnapdragonTM CPU, the AdrenoTM GPU or the
      HexagonTM DSP.
    - Debug the network execution on x86 Ubuntu Linux
    - Convert Caffe, Caffe2, ONNXTM and TensorFlowTM models to a SNPE Deep
      Learning Container (DLC) file
    - Quantize DLC files to 8 bit fixed point for running on the Hexagon DSP
    - Debug and analyze the performance of the network with SNPE tools
    - Integrate a network into applications and other code via C++ or Java

- [Tengine](https://github.com/OAID/Tengine): Tengine is developed by OPEN AI
  LAB. This project meet the demand of fast and efficient deployment of deep
  learning neural network models on embedded devices. In order to achieve
  cross-platform deployment in many AIoT applications, this project is based on
  the original Tengine project using C language for reconstruction, and deep
  frame tailoring for the characteristics of limited embedded device resources.
  Also, it adopts a completely separated front-end/back-end design, which makes
  it possible to be transplanted and deployed onto CPU, GPU, NPU and other
  heterogeneous computing units rapidly, conveniently.

- [TensorFlow Lite](https://www.tensorflow.org/lite): TensorFlow Lite is an
  open-source deep learning framework to run TensorFlow models on-device. If you
  are new to TensorFlow Lite, we recommend that you first explore the
  pre-trained models and run the example apps below on a real device to see what
  TensorFlow Lite can do.


# Academic institutions
- [Cloud Computing and Distributed Systems (CLOUDS)
  Laboratory](http://www.cloudbus.org/intro.html): The Cloud Computing and
  Distributed Systems (CLOUDS) Laboratory, formerly GRIDS Lab, is a software
  research and development group within the School of Computing and Information
  Systems at the University of Melbourne, Australia. The CLOUDS Lab is actively
  engaged in the design and development of next-generation computing systems and
  applications that aggregate or lease services of distributed resources
  depending on their availability, capability, performance, cost , and users'
  quality-of-service requirements. The lab is working towards realising this
  vision through its two flagship projects: Gridbus and Cloudbus.

# Other awesome list
- [AI at the edge](https://github.com/crespum/edge-ai): A curated list of
  resources for embedded AI.
- [Edge Computing & Internet Of
  Things](https://github.com/yarncraft/awesome-edge): A qualitative compilation
  of production-ready edge computing projects with a focus on IoT based Data
  Engineering.
- [Explore Edge Computing](https://kandi.openweaver.com/explore/edge-computing):
  Discover & find a curated list of popular & new libraries, top authors,
  trending project kits, discussions, tutorials & learning resources on kandi.

# Star History

<a href="https://github.com/qijianpeng/awesome-edge-computing/stargazers">
        <img width="500" alt="Star History Chart" src="https://api.star-history.com/svg?repos=qijianpeng/awesome-edge-computing&type=Date">
</a>
