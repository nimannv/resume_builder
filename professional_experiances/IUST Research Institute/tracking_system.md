### Developing a Real-Time Geolocation Tracking System for Child Safety

At IUST, I contributed to a tracking system designed to provide real-time visibility into children's, pets' and patients' (alzheimer's patients) location via a tracking watch and bracelet. The project aimed to address safety concerns by enabling families to monitor their loved ones' location and receive alerts in case of unexpected movements.

My role focused on backend development, where I implemented the core services responsible for collecting, processing and delivering location data. I designed and built a scalable backend architecture with high performance that could handle frequent location updates from many devices while maintaining low latency and high reliability.

The system collected GPS coordinates from tracking devices and processed them through a backend service that maintained the current location for each user. This location data was then made available to families through a dedicated interface, allowing them to view their loved ones' location on a map and receive immediate notifications if they left predefined safe zones. The backend also supported historical location tracking, enabling families to review past movements and patterns.

**Technologies used**

* Python
* FastAPI
* PostgreSQL
* EMQX (MQTT broker)
* InfluxDB (time-series database)
* REST APIs
* Real-time messaging

**Business impact**

* Led backend development for a the tracking system that enabled real-time geolocation tracking for parents.
* Delivered low-latency location updates by designing an efficient backend architecture that processed frequent GPS data streams.
* Enabled real-time notifications and geofence alerts through an event-driven system architecture.
* Provided parents with round-the-clock visibility into their child's location, enhancing family safety and providing peace of mind.
* Enabled historical location tracking and pattern analysis through the time-series database integration.