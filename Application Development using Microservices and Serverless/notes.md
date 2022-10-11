# Notes on App dev with microservices and serverless

### learning outcomes
- Identify the twelve factors and describe how these factors map to three phases of the software delivery lifecycle.
- Explain the benefits and drawbacks of microservices
- Describe benefits and drawbacks of using microservices
- Describe how using patterns can benefit development teams
- Explain what a microservices anti-pattern is and why development teams should avoid using anti-patterns.

## intro
12-factor apps and microservices, concepts that emerged to help organizations work better and faster in a cloud-native manner. You’ll then learn about serverless computing—how it works, what value it brings, and what are specific serverless technologies.

## Twelve-Factor App

the phases of software developemnt can be though of as 
`code -> deploy -> operate`

#### code
    -   (factor 1) codebase 
    -   (factor 05) build release run 
    -   (factor 10) dev-prod parity 


#### deploy
    -   (factor 02) dependencies 
    -   (factor 03) config 
    -   (factor 04) backing services
    -   (factor 06) processes 
    -   (factor 07) port finding 
    -   (factor 09) disposability 
    -   (factor 11) logs

#### operate
    -   (factor 08) concurrency 
    -   (factor 12) admin services 

### factors again

>I. Codebase
One codebase tracked in revision control, many deploys

>II. Dependencies
Explicitly declare and isolate dependencies

>III. Config
Store config in the environment

>IV. Backing services
Treat backing services as attached resources

>V. Build, release, run
Strictly separate build and run stages

>VI. Processes
Execute the app as one or more stateless processes

>VII. Port binding
Export services via port binding

>VIII. Concurrency
Scale out via the process model

>IX. Disposability
Maximize robustness with fast startup and graceful shutdown

>X. Dev/prod parity
Keep development, staging, and production as similar as possible

>XI. Logs
Treat logs as event streams

>XII. Admin processes
Run admin/management tasks as one-off processes

## uS
![us is the best](/assets/images/us.png)



## Service Oriented Architecture and Microservices Compared.

A service has four properties according to one of many definitions of SOA:

 - It logically represents a repeatable business activity with a specified outcome.
 - It is self-contained.
 - It is a black box for its consumers, meaning the consumer does not have to be aware of the service's inner workings.
 - It may be composed of other services.

A manifesto was published for service-oriented architecture in October, 2009. This came up with six core values which are listed as follows:

 - Business value is given more importance than technical strategy.
 - Strategic goals are given more importance than project-specific benefits.
 - Intrinsic interoperability is given more importance than custom integration.
 - Shared services are given more importance than specific-purpose implementations.
 - Flexibility is given more importance than optimization.
 - Evolutionary refinement is given more importance than pursuit of initial perfection.

## Microservices patterns and anti patterns

Microservices enable single-page applications that rely on backing services to update the page dynamically, backend for frontend patterns use microservices to facilitate different user experiences more easily, apply the Strangler pattern to help break up monolithic apps into microservices, only use microservices when needed, use microservices with DevOps and Cloud services, and build microservices to the right size and not overly small.

Strangler pattern - 

![bit by bit](/assets/images/strangler.jpeg)

