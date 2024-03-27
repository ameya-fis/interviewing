## Billing system
Design a system that determines API usage by customers and generates billing reports based
on the usage. Requirements:
* Customers must be able to view billing reports on a web browser on desktop /
mobile. 
* Billing reports must be current up to 2 hours ago. 
* Granularity can be on a daily basis, don’t need to go lower.

### Reports: Usage by API, usage by day, etc.
* Shows customer usage by API (day-over-day, ...)
* Shows customer usage by day (broken down by API)


### Rubric
* Problem understanding and scoping
* High level design: Architectural patterns, components used, overall approach
* Low level design: Components, data storage systems w/ tradeoffs and schema
definitions, bottlenecks, ensuring correctness of operations
* API design, schema transformations as required
* Operational parameters: Reliability, scalability, resiliency, availability
* UX approaches for mobile v/s desktop web browser (display area constraints, resizable UI components, etc.)