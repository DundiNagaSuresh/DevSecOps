**Note- We have a wide variety of monitoring tools available in the market which best suites as per their use case in the Devops Architecture.Choosing the right tool can make a big difference in the effectiveness of your monitoring strategy.Application Architecture, Logs with specific information for better understanding of issue to trousbleshoot quickly.**
**Use Cases include Application Monitoring,Security Analytics, Troublshooting and many more.**

<img align="middle" alt="Coding" width="400" src="https://raw.githubusercontent.com/wiki/swimlane/elk-tls-docker/images/elk-tls-docker-diagram.png">

**ELK Stack - ElasticSearch Logstash Kibana - Centralized Monitoring tool**

**Logstash** Processing Pipeline. Logstash processes the collected logs through a series of filters and transformations. These filters can include:

1.Parsing: Extracting relevant fields from log messages (e.g., timestamp, severity, user ID).

2.Enrichment: Adding contextual information (e.g., geolocation, user agent) to the logs.

3.Filtering: Filtering out noise or unwanted logs.

4.Aggregation: Combining related logs (e.g., grouping logs by session ID).

*Once processed, Logstash sends the transformed data to Elasticsearch.*

**Elasticsearch** for Indexing and Search. Elasticsearch is a distributed search and analytics engine. 

1.It stores the processed logs as JSON documents in an index.

2.Elasticsearch provides powerful search capabilities, allowing you to query and retrieve specific log entries efficiently.

3.It supports full-text search, aggregations, and complex queries.

*Developers and operations teams can use Elasticsearch to gain insights into application performance, troubleshoot issues, and monitor system health*

**Kibana** for Visualization and Exploration. Kibana is the user interface for the ELK Stack. It allows you to:

1.Create visualizations (e.g., line charts, bar graphs, heat maps) based on log data.

2.Build dashboards with multiple visualizations to monitor specific aspects of your application.

3.Explore data interactively by drilling down into specific time ranges, filters, and fields.

4.Set up alerts based on specific conditions (e.g., error rate exceeding a threshold).

5.Kibana provides a unified view of your application’s health, performance, and security.

Prompts I used to search about ELK Stack:
1. Explaing the Architecture of ELK with Key Points describing the working on each tool.
2. Give me an Architecture Diagram of a Devops Architecuture where ELK is used for Monitoring.

Youtube Videos I referred.
1. DevOps Monitoring Tools for Begineer. https://youtu.be/uNsCPWYuGj4?si=aVLkUWnCpGFl7gQi ( Tech with Neha Garg )
2. Understanding ELK Stack - https://youtu.be/EKF-PCY-slo?si=lcInNcqXwg1eD99Q ( Chayan Deokar )
