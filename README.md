# Target Architecture
An Opinionated Target Architecture Intended For Mid-sized Insurance Companies And Companies Alike

## Definition Of Target Architecture
> The description of a future state of the architecture being developed for an organization. There may be several future states developed as a roadmap to show the evolution of the architecture to a target state.

Source: [TOGAF® Version 9.1](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap03.html#tag_03_71)

## Values
* The target architecture shall
  * Set the direction
  * Set the boundaries
  * Give guidance
  * Not be overly prescriptive
  * Be constantly evolving
* We standardize only when
  * Deemed necessary for the sake of interoperability
  * There is clearly a "better way of doing it"

## Overview
| [LEVELS](https://github.com/LarsBarkman/target-architecture/blob/master/levels.md)  | PHILOSOPHY  | [BOUNDED CONTEXT](https://github.com/LarsBarkman/target-architecture/blob/master/bounded-context.md#bounded-context)  | SOFTWARE ARCHITECTURE  | USE, BUY OR BUILD  | SHIP  | RUN  | CHANGE  |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| [***STRATEGIC***](https://github.com/LarsBarkman/target-architecture/blob/master/levels.md#strategic-level)  | From Command & Control To [Purpose And Trust](https://github.com/LarsBarkman/target-architecture/blob/master/philosophy.md#purpose-and-trust)  | Business Capabilities  | [Evolutionary Architecture](https://github.com/LarsBarkman/target-architecture/blob/master/software-architecture.md#evolutionary-architecture)  | ”Don’t Build, What Can Be Used Or Bought”  | Created And Proven By Doing  | [Cloud-only](https://github.com/LarsBarkman/target-architecture/blob/master/run.md#cloud-only)  | Lean Production  |
| [***OPERATIONAL***](https://github.com/LarsBarkman/target-architecture/blob/master/levels.md#operational-level)  | [Autonomy, Mastery And Purpose](https://github.com/LarsBarkman/target-architecture/blob/master/philosophy.md#autonomy-mastery-and-purpose)  | Business Services  | [Containerized Microservices Architecture](https://github.com/LarsBarkman/target-architecture/blob/master/software-architecture.md#containerized-microservices-architecture)  | Respect The Bounded Context  | “Optimize For Speed, Not Efficiency”  | [CaaS-only](https://github.com/LarsBarkman/target-architecture/blob/master/run.md#containers-as-a-service-caas-only)  | Fly By Instruments  |
| [***TACTICAL***](https://github.com/LarsBarkman/target-architecture/blob/master/levels.md#tactical-level)  | [Radical Agility](https://github.com/LarsBarkman/target-architecture/blob/master/philosophy.md#radical-agility)  | Microservices  | [Patterns](https://github.com/LarsBarkman/target-architecture/blob/master/patterns.md), [Principles](https://github.com/LarsBarkman/target-architecture/blob/master/principles.md) And [Standardizations](https://github.com/LarsBarkman/target-architecture/blob/master/standardizations.md)  | When And How To Use, Buy Or Build  | Continuous Deployment  | [“You Build It, You Run It.”](https://github.com/LarsBarkman/target-architecture/blob/master/run.md#you-build-it-you-run-it)  | Collect And Use Customer Metrics And Telemetry  |

## Target Architecture Anti-patterns
* [Traditional Digital Strategy](https://www.thoughtworks.com/insights/blog/digital-strategy-dead)
* [Architecture as a Recipe](http://doveltech.com/innovation/the-beginning-of-the-end-for-enterprise-architecture-frameworks/)

## How To Use The Target Architecture
1. The target architecture is the desired state
2. Evaluate every system, process, organizational structure etc.
 * For-Each, decide on and develop, one of two things
   * Decommission Strategy
    * Transformation Strategy
4. "This is your wake-up call, pal. Go to work." - [Gordon Gekko](http://www.imdb.com/title/tt0094291/quotes)

