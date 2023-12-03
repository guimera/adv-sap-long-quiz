## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- is a software development approach that allows services to be reused and communicate across platforms and languages to create new applications.

2. List and discuss the characteristics of SOA. A service-oriented architecture consists of four main components:
- Service, which contains the basic service-oriented architecture(SOA) building blocks. It can be open source and accessible to the public or private, available only to authorized users. Each service has three main features, a Service Implementation, Service Contract, and Service Interface. Where in Service Implementation, is the code that creates the logic for filling the specific service function. While in the Service Contract, defines the parameters of a service as well as its cost and quality. Lastly is the Service Interface, which describes how to interface handles communication with other services and systems.
- Service provider, it creates, handles, and provides one or more services that others can use.
- Service consumer, is an individual, system, application, or other service that seeks services from the service provider. Also specifies the terms and conditions under which a service provider and a service requester get involved.
- Service registry, additionally known as a service repository, is a listing of available services. It is in charge of keeping service descriptions as well as additional relevant data on how to use a service provider's services.

3. Define Microservices.
- is a different approach to software development that focuses on creating single-function modules with well-defined interfaces and operations.

4. List and discuss the benefits of using Microservices.
- Improved productivity, it improves creation and maintenance of software applications by breaking them down into smaller autonomous fragments.
- Scalability improvements, since each cloud microservice runs independently, it is simpler to add, remove, update, or scale them. Where the developers can complete these tasks without affecting with any other microservices in the system.
- Improved Data Security, when the components of a computer system's design are broken down into smaller pieces, sensitive data is protected from outside invaders.

5. List and discuss the similarities and differences of SOA and Microservices. 

The similarities of SOA and Microservices are:
- both require designing and operating apps in a cloud or hybrid cloud environment.
- it is designed to organize multiple services required for the creation and use of apps.
- each efficiently divides huge, complex applications into smaller components that are easier to design and deploy. Because both microservices and SOA operate in cloud environments, they can grow to meet modern needs for big data capacity and speed.

While their differences are:
- Microservices architecture is based on smaller, tiny services that are focused on a particular purpose and can operate independently of one another while supporting the same application. While the SOA contains larger, more modular services that are not self-contained, it is designed to share resources as much as feasible.
- An individual microservices are frequently utilize their own data storage. While in SOA, almost all services share the same data storage units.
- Microservices is based on Bounded Context, while SOA is centered on the concept of sharing components.

6. Define Web Services.
- is a software system that supports interoperable machine-to-machine interaction over a network. It is also fulfilling a specific task or a set of tasks.

7. List and discuss the benefits of using Web Services.
- Quality
  It allows the construction of services by assembling existing services. Where it is reasonable to expect that such services have undergone testing and possess known performance characteristics. 

- Cost
  Assembling such systems from ready-made web services significantly reduces the expense of developing new frameworks. The clients may receive the benefits resulting from these cost decreases. The clients remain to win from cost cuts and proficiency got by web administration.

- Interoperability 
  It has highest Interoperability priority. Its objectives are to allow programming applications to communicate with each other and exchange data or services among themselves. For instance, .NET applications can communicate with Java web services and the other way around. It is used to ensure the independence of the technology and application platforms.

8. List and discuss the characteristics of Web Services.
- XML-based
  a web service uses XML at information representation and record transportation layer. 

- Coarse-grained
  few objects hold a lot of related data. It wraps one or more fine-grained services together into a coarse-grained service. Has a broader functionality in comparison to fine-grained service.

- Loosely Coupled
  it communicates by passing XML message to each other via a web API. Web API adds a layer of abstraction to the environment that makes the connection adaptable and flexible. A web service supports connections between systems.

- Capability to be Synchronous and Asynchronous
  Synchronous Web services is served by RPC-oriented messaging. Which invoked over existing Web protocols by a client who waits for a response. 
  Asynchronous Web services is a crucial factor in enabling loosely coupled system. Which invoked over existing Web protocols by a client who does not wait for a response. Also, it is often used for document-oriented messaging.

- Remote Procedure Calls (RPCs) 
  is a software communication protocol that one program can use to request a service from a program located in another computer on a network without having to understand the network's details. Which is used to call other processes on the remote systems like a local system.

9. List and discuss the distinct roles in Web Services Architecture.
- Provider 
  makes the web service and builds it obtainable to client application who wants to use it.

- Requestor 
  is the client application that requires contacting a web service. 

- Broker 
  the application offers a contact to the UDDI.

10. List and discuss the Web Services Components.
- SOAP (Simple Object Access Protocol)
  an XML based protocol for accessing web services and platform independent and language independent. It can be used with Java, .Net or PHP language on any platform. A W3C recommendation for communication between applications.

- UDDI (Universal Description, Discovery, and Integration)
  an XML based standard for describing, publishing, and finding webservices. Can communicate via SOAP and uses WSDL to describe interfaces to webservices.

- WSDL (Web Services Description Language)
  an XML based language for describing webservices and how to access them and exchange in decentralized and distributed environments. An integral part of UDDI. It allows people and other companies to access the service.
