### Designing and Building a Configurable Digital Lending Platform

At Ravindex, I **designed and implemented a new lending platform from the ground up**, enabling the company to launch digital lending as a new service within its hedge fund offerings.

Rather than implementing a fixed loan workflow, I designed a configurable lending engine that allowed operators and managers to define loan products without requiring software changes. Each loan product could be configured with its own base asset (the asset provided to the customer), repayment asset, interest model, repayment schedule, number of installments, and additional lending rules. This flexible architecture enabled the business to introduce new lending products quickly while keeping the platform maintainable and extensible.

Based on these configurable loan definitions, customers could apply for and receive loans through the platform. The system managed the complete loan lifecycle, including loan origination, installment scheduling, repayment processing, outstanding balances, loan status tracking, and settlement.

To support operational and financial decision-making, I also implemented reporting capabilities that provided managers with visibility into loan portfolios, repayment performance, asset exposure, and other key metrics used to monitor lending operations and manage risk.

The platform was designed to support rapid business growth while minimizing the engineering effort required to introduce new lending products, allowing the business team to manage product configuration through the application.

**Technologies used**

* Python
* FastAPI
* PostgreSQL
* Backend API development
* Financial systems architecture

**Business impact**

* Designed and implemented the company's first digital lending platform as a new service offering within its hedge fund business.
* Built a configurable lending engine that enabled new loan products to be created through configuration rather than software development.
* Automated the complete loan lifecycle, including origination, repayments, installment management, reporting, and portfolio tracking.
* Enabled the platform to scale rapidly, managing more than **$2 million** in loans within the first **six months** after launch.
* Established the technical foundation for the company's expansion into digital lending services.
