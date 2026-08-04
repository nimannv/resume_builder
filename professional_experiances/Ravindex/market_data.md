### Designing and Building a High-Availability Market Data ETL Platform

One of Ravindex's core services was providing customers with real-time financial market data across a wide range of assets and trading platforms. A key capability of the platform was delivering accurate, up-to-date asset prices to support investment decisions and downstream financial services.

I **designed and implemented a high-availability ETL platform** responsible for collecting, transforming, validating, and distributing market price data from a variety of external sources.

The platform integrated with heterogeneous data providers using multiple ingestion methods, including web scraping, REST APIs, SOAP services, and other third-party integrations. Because each provider exposed data in different formats and with different update frequencies, I designed a flexible ETL pipeline that normalized incoming data into a consistent internal representation before making it available to downstream services.

To ensure scalability and reliability, I built an event-driven processing architecture using RabbitMQ for asynchronous message delivery, Apache Airflow for workflow orchestration and scheduling, and InfluxDB for efficient storage of high-frequency time-series market data. The platform continuously processed more than **500 market price updates per minute** while maintaining high availability and low processing latency.

The resulting system became the primary source of market pricing information for Ravindex's customer-facing services, providing real-time prices for approximately **500 financial assets** across multiple markets and trading platforms.

**Technologies used**

* Python
* Apache Airflow
* RabbitMQ
* InfluxDB
* ETL architecture
* Event-driven systems
* Time-series data processing
* Third-party system integrations

**Business impact**

* Designed and implemented the company's market data ETL platform supporting one of Ravindex's core products.
* Integrated market data from multiple external sources using web scraping, REST APIs, SOAP services, and other third-party protocols.
* Processed more than **500 market price updates per minute** with a highly available, event-driven architecture.
* Delivered real-time pricing for approximately **500 financial assets** across multiple markets and trading platforms.
* Established a scalable data ingestion pipeline capable of supporting new data providers and asset classes with minimal architectural changes.
