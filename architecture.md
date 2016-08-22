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
## PRINCIPLES

## STANDARDIZATIONS

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
