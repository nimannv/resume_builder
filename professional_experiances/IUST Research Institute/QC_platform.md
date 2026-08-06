### Designing and Automating an IoT Device Quality Control Platform

At IUST, one of the major operational challenges was the quality control (QC) process for IoT devices during manufacturing. Each device had to pass multiple stages of testing—including sensor validation, actuator verification, and communication testing—before it could be approved for production.

Initially, the entire QC process was performed manually. Devices were passed between multiple QC operators, each responsible for testing a subset of the device's functionality. Results were recorded manually, making the process slow, difficult to track, and susceptible to human error. The lack of centralized data also limited visibility into production quality and prevented systematic analysis of manufacturing issues.

I **designed and implemented a centralized Quality Control platform** that automated large parts of the testing workflow while providing complete visibility into the production testing process.

The platform enabled operators to connect devices directly to a workstation through a serial interface (TTL-to-USB) and execute standardized test procedures from a web-based control panel. Operators could run automated test routines, record observations, and immediately store all results in a centralized database. The platform maintained complete test histories for every device, making it possible to generate reports, trace failures, and monitor production quality over time.

Beyond improving the testing workflow, the centralized data enabled production teams to analyze failure trends, identify recurring hardware issues, detect bottlenecks in the manufacturing process, and make data-driven improvements to product quality and production efficiency.

**Technologies used**

* Python
* Django
* PostgreSQL
* JavaScript
* Docker
* Serial communication (TTL-to-USB)
* Manufacturing automation

**Business impact**

* Designed and implemented a centralized quality control platform for IoT device manufacturing.
* Reduced device testing time by **60%** through standardized and partially automated testing workflows.
* Replaced fragmented manual testing with a fully traceable and centralized QC process.
* Enabled complete visibility into production testing through centralized reporting and device-level test histories.
* Provided actionable production data that helped identify recurring failure points and manufacturing bottlenecks, improving overall production efficiency and product quality.
