### End-to-End Integration with the aFRR Energy Market

One of Spectral's core products enables energy producers to participate in electricity markets by integrating their assets with grid operators and market platforms, including Day-Ahead, aFRR (Automatic Frequency Restoration Reserve), FCR, and other ancillary service markets.

I **designed and implemented the aFRR market integration end-to-end**, delivering the complete software platform required for customers to participate in the market.

The solution included the full operational lifecycle of aFRR participation:

* A bidding system for submitting market offers.
* Energy activation management to process activation requests from the grid operator and coordinate asset responses.
* Reporting services for operational and market compliance.
* Reliable integrations with multiple external systems and market operators using industry-standard communication protocols.

The project required designing reliable backend services capable of interacting with external market infrastructure, processing time-sensitive events, and ensuring the correctness of market operations. I integrated with multiple third-party systems using REST APIs, SOAP services, SMTP, and AMQP-based messaging while building resilient workflows to support continuous market participation.

**Technologies used**

- Go (Golang)
- PostgreSQL
- TimescaleDB
- REST APIs
- SOAP
- SMTP
- AMQP
- Distributed backend services
- Energy market integrations

**Business impact**

- Delivered Spectral's end-to-end integration with the **aFRR (Automatic Frequency Restoration Reserve)** market.
- Enabled **four major energy producers** to participate in the aFRR market through Spectral's platform.
- Supported the management of approximately **100 MW** of energy assets in production.
- Expanded Spectral's market capabilities by delivering a new customer-facing service and strengthening its position in ancillary energy markets.
