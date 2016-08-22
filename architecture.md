# ARCHITECTURE
> IT architecture is the art and science of designing and delivering valuable technology strategy.

Source: [What is Architecture?](http://iasaglobal.org/itabok/what-is-it-architecture/)

## Evolutionary Architecture

> Common wisdom in software once held that architectural elements are "difficult to change later." An evolutionary architecture designs for incremental change in an architecture as a first principle. Evolutionary architectures are appealing because change has historically been difficult to anticipate and expensive to retrofit. If evolutionary change is built into the architecture, change becomes easier and cheaper, allowing changes to development practices, release practices, and overall agility.

Source: [Microservices as an Evolutionary Architecture](https://www.thoughtworks.com/insights/blog/microservices-evolutionary-architecture)

### A Comprehensive Presentation of Evolutionary Architecture, Presented by [Neal Ford](http://nealford.com/).

[![Evolutionary Software Architectures](http://img.youtube.com/vi/SzSZpZI02Jg/0.jpg)](https://www.youtube.com/watch?v=SzSZpZI02Jg)

## Containerized Microservices Architecture
### Microservices Architecture
>In short, the microservice architectural style is an approach to developing a single application as a suite of small services, each running in its own process and communicating with lightweight mechanisms, often an HTTP resource API. These services are built around business capabilities and independently deployable by fully automated deployment machinery. There is a bare minimum of centralized management of these services, which may be written in different programming languages and use different data storage technologies.

> -- James Lewis and Martin Fowler

Source: [Microservices Resource Guide](http://martinfowler.com/microservices/#what)

### Containerized
> Containers are a solution to the problem of how to get software to run reliably when moved from one computing environment to another. This could be from a developer's laptop to a test environment, from a staging environment into production and perhaps from a physical machine in a data center to a virtual machine in a private or public cloud.

> Put simply, a container consists of an entire runtime environment: an application, plus all its dependencies, libraries and other binaries, and configuration files needed to run it, bundled into one package. By containerizing the application platform and its dependencies, differences in OS distributions and underlying infrastructure are abstracted away.

Source: [What are containers and why do you need them?](http://www.cio.com/article/2924995/enterprise-software/what-are-containers-and-why-do-you-need-them.html)


## PATTERNS

### STABILITY PATTERNS (INTEGRATION) PATTERNS
> Reliability in distributed systems is determined by the weakest component, so even a minor internal function could bring your entire system down. Learn how stability patterns anticipate the hot spots of distributed network behavior

* 'Use Timeouts' pattern
* 'Circuit Breaker' pattern
* 'Handshaking' pattern
* 'Bulkheads' pattern

Source: [Stability patterns applied in a RESTful architecture](http://www.javaworld.com/article/2824163/application-performance/stability-patterns-applied-in-a-restful-architecture.html)

## PRINCIPLES

## STANDARDIZATIONS

### REVISION CONTROL AND SOURCE CODE MANAGEMENT
#### [GitHub](https://github.com)
> GitHub is a web-based Git repository hosting service. It offers all of the distributed revision control and source code management(SCM) functionality of Git as well as adding its own features. Unlike Git, which is strictly acommand-line tool, GitHub provides a Web-based graphical interface and desktop as well as mobile integration. It also provides access control and several collaboration features such as bug tracking, feature requests,task management, and wikis for every project.

Source: [Wikipedia](https://en.wikipedia.org/wiki/GitHub)

### BUG TRACKING, FEATURE REQUESTS, TASK MANAGEMENT AND DOCUMENTATION
#### [GitHub](https://github.com)
> GitHub is a web-based Git repository hosting service. It offers all of the distributed revision control and source code management(SCM) functionality of Git as well as adding its own features. Unlike Git, which is strictly acommand-line tool, GitHub provides a Web-based graphical interface and desktop as well as mobile integration. It also provides access control and several collaboration features such as bug tracking, feature requests,task management, and wikis for every project.

Source: [Wikipedia](https://en.wikipedia.org/wiki/GitHub)

### CONTAINER TECHNOLOGY
#### [DOCKER CONTAINERS](https://www.docker.com/what-docker)
Docker containers wrap a piece of software in a complete filesystem that contains everything needed to run: code, runtime, system tools, system libraries – anything that can be installed on a server. This guarantees that the software will always run the same, regardless of its environment.


### CONTAINER ORCHESTRATION
#### [KUBERNETES](http://kubernetes.io/)
Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications.


### CAAS (CONTAINER AS A SERVICE
#### [GOOGLE CONTAINER ENGINE](https://cloud.google.com/container-engine/)
Google Container Engine is a powerful cluster manager and orchestration system for running your Docker containers. Container Engine schedules your containers into the cluster and manages them automatically based on requirements you define (such as CPU and memory). It's built on the open source Kubernetes system, giving you the flexibility to take advantage of on-premises, hybrid, or public cloud infrastructure.


### CONTAINER WORKFLOW
#### [DEIS WORKFLOW](https://deis.com/workflow/)
Deis Workflow is an open source Platform as a Service (PaaS) that adds a developer-friendly layer to any Kubernetes cluster, making it easy to deploy and manage applications.


### CONTAINER REGISTRY 
#### [GOOGLE CONTAINER REGISTRY](https://cloud.google.com/container-registry/)
Fast, private Docker image storage on Google Cloud Platform


### INTEGRATION BETWEEN SERVICES
#### REQUEST-RESPONSE
##### RESTFUL: [JSON API](http://jsonapi.org/)
> If you’ve ever argued with your team about the way your JSON responses should be formatted, JSON API can be your anti-bikeshedding tool.

> By following shared conventions, you can increase productivity, take advantage of generalized tooling, and focus on what matters: your application.

> Clients built around JSON API are able to take advantage of its features around efficiently caching responses, sometimes eliminating network requests entirely.

##### RPC: [GRPC](http://www.grpc.io/)
A high performance, open source, general RPC framework that puts mobile and HTTP/2 first.

#### PUBLISH-SUBSCRIBE
##### MESSAGING SYSTEM: [APACHE KAFKA](http://kafka.apache.org/)
Apache Kafka is publish-subscribe messaging rethought as a distributed commit log

##### INTERMEDIATE DATA FORMAT: [APACHE AVRO](https://avro.apache.org/docs/current/)
Apache Avro™ is a data serialization system.
Avro provides:
* Rich data structures.
* A compact, fast, binary data format.
* A container file, to store persistent data.


### VERSIONING
#### [SEMANTIC VERSIONING 2.0.0](http://semver.org/spec/v2.0.0.html)
> In systems with many dependencies, releasing new package versions can quickly become a nightmare. If the dependency specifications are too tight, you are in danger of version lock (the inability to upgrade a package without having to release new versions of every dependent package). If dependencies are specified too loosely, you will inevitably be bitten by version promiscuity (assuming compatibility with more future versions than is reasonable). Dependency hell is where you are when version lock and/or version promiscuity prevent you from easily and safely moving your project forward.

Given a version number MAJOR.MINOR.PATCH, increment the:
* MAJOR version when you make incompatible API changes,
* MINOR version when you add functionality in a backwards-compatible manner, and
* PATCH version when you make backwards-compatible bug fixes.

### ACCESSIBILITY 
#### [WEB CONTENT ACCESSIBILITY GUIDELINES (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)
> Web Content Accessibility Guidelines (WCAG) 2.0 covers a wide range of recommendations for making Web content more accessible. Following these guidelines will make content accessible to a wider range of people with disabilities, including blindness and low vision, deafness and hearing loss, learning disabilities, cognitive limitations, limited movement, speech disabilities, photosensitivity and combinations of these. Following these guidelines will also often make your Web content more usable to users in general.


## Further Reading
* [Microservices as an Evolutionary Architecture](https://www.thoughtworks.com/insights/blog/microservices-evolutionary-architecture)
* [Microservices Resource Guide](http://martinfowler.com/microservices/)
* [What are containers and why do you need them?](http://www.cio.com/article/2924995/enterprise-software/what-are-containers-and-why-do-you-need-them.html)
