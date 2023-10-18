# dj_Notebook
My Keyword Directory

3 BASIC FEATURES OF DESKTOP COMPUTING:
1. Computation: CPU, GPU, TPU etc.
                two types of processor:
                 1. CISC processors (AMD, Intel)
                 2. RISC processors (ARM) (FUTURISTIC)
2. Storage: OPERATING SYSTEM (O.S)
                 1. Windows (closed source)
                 2. Linux   (Open source)
                    It has two types of spaces: User space and Kernel space (changes can be made through and in kernel space, follows ISA: instruction set architecture)
                             2 families of Linux are:
                                       1. DEBIAN: UBUNTU, KALI LINUX etc.
                                       2. RHEL: FELONA, CENTAS, RED HAT etc.
                 3. MACOS   (closed source)
3. Network: Internet (WAN)
                     COMPONENTS:
                     1. IP addess
                     2. DNS servers
                     3. Routing etc.
            Intranet (LAN)

SEVERS:
1. DESKTOP COMPUTING:
              offers: upto 8GB, 16GB RAM and is not Sharable.
3. CLOUD COMPUTING: It is sharable
              offers: upto 2TB of RAM storage.

BARE METAL: Servers that have no information stored inside them, in other words FRESH SEVERS.
Dual Boot: Installation of two operating system on the same sevrer (DONE WITH THE HELP OF HYPERVISOR, VMWARE OR VIRTUAL BOX).
HYPERVISOR: type-1 (before installing operating system)
            type-2 (after installing operating system)


TIM BERNERS LEE: THE DEVELOPER OF WEB


LAYERS: 
there are in total 7 layers:

OSI MODEL
L1: PHYSICAL (cable, connectors etc)
L2: LINKS (mAC addrexx or NIC address, NIC = Network Interface Card)
L3: IP address
L4: Port address

TCP/IP MODEL
L5: Full/half Duplex RCP
L6: Presentation (ACSII)
L7: Application (DNS, https etc)

PORT NUMBER:
FTP: 21 OR 20
SMTP: 25
SSH: 22
TelNet: 23

TLS (Transport Lane Security) = L3 + L4

HTTPS: HYPERTEXT TRANSFER PROTOCOL SECURE SOCKET LAYER

2 types of architecture:
1. VON NUMAN ARCHITECTURE: basic concept states that program should be in the main memory.
2. HARVARD ARCHITECTURE.


CRYPTOGRAPHY: 
1. CLASSICAL CRYPTOGRAPHY
2. POST QUANTUM CRYPTOGRAPHY

GITHUB, Bitcoin, Data Structure uses Merkel tree structure

DATA STRUCTURE:

1. Primitive: int, float, char etc.
2. Non-Primitive:
       1. Linear:
            a. Quene (First in first out)
            b. Array
            c. Stack (Last in first out)
       2. Non-Linear:
            a. Tree
            b. Graph

   FORMATION OF PROGRAMMING LANGUAGE:
   1. SYNTAX: basic structure, differs language to language.
   2. OOPS: Object Oriented Programming Structure
             a. CLASS: Blueprint
             b. OBJECT: Final Structure
             c. REFRENCE: A link to object
             d. CONSTRUCTER: name of constructer = name of class
             e. NEW (Keyword): helps to create space in memory
             f. ENCAPSULATION: Combined forms
             g. ABSTRACTION: To hide
             h. POLYMORPHISM Differention of many forms
             i. INHERITENCE: same thing has different properties
   4. DATA STRUCTURE
   5. FUNCTIONS:
         1. Create a function
         2. Call a function   
   6. LOOPS:
          a. for loop
          b. while loop
   9. CONDITIONS:
          a. if statement
          b. else statement


   VON NUMAN ARCHITECTURE:

    1. IDE (Integreted Development Environment)
         eg: VS Code, Atom etc.
    2. Compiler
    3. Converts code into Assembly Language
    4. Linker (Links Libraries)
    5. Loader (transfers program to main memory)
    6. Optimisation (reduces the file size)


WHAT ARE THE MAIN ELEMENTS OF BACKEND COMPUTING?
1. Containerization
   This process bundels up all the codes and libraries it needs to run a particular infrastucture.
   Eg:DOCKER, it is just like when a musician collects all the notes in his head needed to play a particular song.

2. CI/CD Pipeline
   CI stands for continous integration and CD stands for continous deployment. It inroduces automation in building apps.
   CI brings automation to changes to code of an app on a regular basis. CD's job is to deploy it correctly and then monitor it.
   This cycle runs in a circle. EG: Jenkins or CI cirle.

3. Architectural Patterns
   For example you are facing the same problem that someone faced in past. In this case the architectural pattens would jump
   in to provide you the solution to that problem.
    I Microservices (currently used)
       Relies on a series of independently deployable services.
    II Monolithic   (outdated)
       A monolithic architecture is a traditional model of a software program, which is built as a
       unified unit that is self-contained and independent from other applications.
       This allows everything in the monolith to be released at once.
    III Serverless   (in future will move towards this)
        a way to build and run applications and services without having to manage infrastructure.
        Your application still runs on servers, but all the server management is done by AWS.

4. API's (Application Programming Interface)
    APIs are mechanisms that enable two software components to communicate with each other using a set of definitions and protocols.
    For eg: in a weather app the sender of information is a server, the reciever of information, your mobile app
    is the client. It shows communication between these two parties.
    TYPES:
     Private APIs
     These are internal to an enterprise and only used for connecting systems and data within the business.
     Public APIs 
     These are open to the public and may be used by anyone. There may or not be some authorization and cost associated with these types of APIs.
     Partner APIs 
     These are only accessible by authorized external developers to aid business-to-business partnerships.
     Composite APIs 
     These combine two or more different APIs to address complex system requirements or behaviors. 

    EXAMPLES:
      SOAP APIs 
      These APIs use Simple Object Access Protocol. Client and server exchange messages using XML.
      This is a less flexible API that was more popular in the past.
      REST API's
      REST stands for Representational State Transfer. REST defines a set of functions like GET, PUT, DELETE, etc. that clients can use to access server data. Clients and 
      servers exchange data using HTTP.The main feature of REST API is statelessness. Statelessness means that servers do not save client data between requests. Client 
      requests to the server are similar to URLs you type in your browser to visit a website.

   WHAT ARE API Gateways:
     An API gateway is a component of the app-delivery infrastructure that sits between clients and services and provides centralized handling of API communication between 
     them. It also delivers multi-cloud, and hybrid environments.

   5. VCS (Version Control System)
      A version control system (VCS) tracks changes to a file or set of files over time. The most common type is a centralized VCS, which uses a server to store all the 
      versions of a file.
      Example: GitHub

   6. Testing:
      Integration testing: a type of software testing in which the different units, modules or components of a software application are tested as a combined entity.
      Unit testing:  a software development process in which the smallest testable parts of an application, called units, are individually scrutinized for proper operation.
      Functional testing: The purpose of Functional tests is to test each function of the software application, by providing appropriate input, verifying the output 
      against the Functional requirements.
      
   7. Cashing
      The data in a cache is generally stored in fast access hardware such as RAM (Random-access memory)
       and may also be used in correlation with a software component.
      A cache's primary purpose is to increase data retrieval performance by reducing the need to access the underlying slower storage layer.
      For example when RAM stores data in a PC.
  
       HOW DOES CDN (Content Delivery Network) WORK??
     CDNs cache content like web pages, images, and video in proxy servers near to your physical location. This allows you to do things like watch a movie, download 
     software, check your bank balance, post on social media, or make purchases, without having to wait for content to load. Just like an ATM, it functions on the
     model of POP's, points of presence.

     REDIS: Redis is an open source, in-memory, key-value data store most commonly used as a primary database, cache, message broker, and queue.
     Redis Enterprise is the only true datastore built for hybrid and multicloud applications.

   9. Database:
        I. A relational database is one that stores data in tables. The relationship between each data point is
        clear and searching through those relationships is relatively easy.
        Eg: PostgreSQL, MySQLetc.
        II. A non-relational database is any database that does not use the tabular schema of rows and columns
        like in relational databases. Rather, its storage model is optimized for the type of data it’s storing.
        Eg: MongoDB, Redis etc.

      

  Difference between virtual machines and containers:

  1. Virtual Machine: A virtual machine is a virtual representation, or emulation, of a physical computer.
      They are often referred to as a guest while the physical machine they run on is referred to as the host.

     Hypervisors:
     Type 1:Type 1 hypervisors run directly on the physical hardware (usually a server), taking the place of the OS.
            Typically, you use a separate software product to create and manipulate VMs on the hypervisor.
     Type 2:Type 2 hypervisors run as an application within a host OS and usually target single-user desktop or notebook platforms.
            With a Type 2 hypervisor, you manually create a VM and then install a guest OS in it.

  2. Containers: Instead of virtualizing the underlying hardware, containers virtualize the operating system (typically Linux)
 so each individual container contains only the application and its libraries and dependencies.
The absence of the guest OS is why containers are so lightweight and, thus, fast and portable.Containers,
 and the orchestration engine that manages them, Kubernetes.

  DOCKER: This application manages containers.Containers are made in docker. For eg: When a orchestra is playing music, the musicians (Containers) can be termed a docker.
  
  KUBERNETES: This application orchestrates containers. After creating containers in docker they can be uploaded in kubernetes. For eg: when a orchestra is playing
  music the orchestrator maintaining the symphony among the musicians (Containers) can be termed as Kubernetes.

  ![image](https://github.com/devanshi-j/dj_Notebook/assets/89416589/4829e2c7-112f-4cfb-aaf2-1c80ca73f792)

  Kubevirt: KubeVirt is an addon that enables creation of virtual machine on Kubernetes.

  WHAT ARE NAMESPACES and CGROUPS?
  NAMESPACES: It is a feature of LINUX kernes, the key feature of namespaces is that they isolate processes from each other.
  On a server where you are running many different services

  CGROUPS: So basically you use cgroups to control how much of a given key resource (CPU, memory, network, and disk I/O) can be accessed or used by a process or set of 
  processes. Cgroups are a key component of containers because there are often multiple processes running in a container that you need to control together. In a Kubernetes 
  environment, cgroups can be used to implement resource requests and limits at the pod level.

  What is a POD?
  A Kubernetes pod is a collection of one or more Linux® containers, and is the smallest unit of a Kubernetes application. 
  
  WHAT ARE BORGS?
  A task manager by google, it runs 1000's of application and machines of a cluster at the same time.

  WHAT IS A HCI (hyper convered infrastructure):
  Hyperconverged infrastructure (HCI) is a type of data center infrastructure that virtualizes computing, storage and networking elements in a single system through a 
  hypervisor. virtualized abstractions managed by a hypervisor replaces all physical hardware components.

  KERNEL BYPASS:

  CNI (container network interface):
  it configures network interfaces in Linux containers. And it is concerned mainly with adding, 
  connecting and deleting disconnecting containers to networks.

  CNI FLANNEL TUNNEL:

  OVERLAY NETWORK: 
  An overlay network is a virtual or logical network that is created on top of an existing physical network. 
  The overlay creates a new layer where traffic can be programmatically directed through new virtual network routes or paths instead of requiring physical links.

  eth0 = physical link.
  
  enh = states fiber net for fast internet.

  TUN/TAP: 

  
  

     

   
