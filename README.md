# CST8917 - Assignment 2

## Azure Event Grid

| Category                   | Azure Event Grid                                                                 | Amazon EventBridge                                                                 | Cloud IoT Core                                                                 |
|----------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| **Overview**               | Azure Event Grid is a fully managed, publish-subscribe event routing service designed for near real-time delivery. | A serverless service that uses events to connect application components together, making it easier to build scalable event-driven applications. | A fully managed service that allows you to easily and securely connect, manage, and ingest data from millions of globally dispersed devices. |
| **Core Features**          | Triggers, Bindings, Messaging, Eventing                                          | Triggers, Messaging, Eventing                                                        | Messaging                                                                      |
| **Native Integrations**    | Azure Functions, Logic Apps, Event Hubs                                          | Lambda, Amazon SQS, Amazon SNS                                                      | Cloud Dataflow, Cloud Pub/Sub                                                  |
| **Third-party Integrations** | Datadog, MongoDB                                                               | Datadog, MongoDB, Salesforce                                                        | Telegraf, Prometheus, Grafana                                                  |
| **Monitoring & Observability** | Built-in monitoring                                                        | CloudWatch                                                                          | Cloud Logging                                                                  |
| **Pricing Model**          | Price per unit per hour; No additional fees for MQTT operations until 1 million operations; Pay-per-use option | Cost per million events                                                             | Discontinued; Previously price per MB used                                     |
| **Strengths**              | Low latency; Flexible pricing options (pay-as-you-go or time-based)              | High customization; Excellent documentation                                         | SDK support across platforms; Easy data integration with caching systems       |
| **Weaknesses**             | Limited regional availability; More costly than some alternatives                | No event replay feature; Stability issues with triggering                           | Limited monitoring and dashboards; Occasional server instability; Discontinued |
### Analysis

## Azure Event Hubs

| Category                   | Azure Event Hubs                                                                 | Amazon Kinesis                                                                 | Google Cloud Pub/Sub                                                                 |
|----------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| **Overview**               | A a fully managed, real-time data streaming platform that can ingest millions of events per second with low latency to build data pipelines for IoT telemetry, application logging, clickstream analytics, financial transaction processing, and other scenarios that require high-throughput, reliable event ingestion. | Amazon's service for managing real-time data streams to collect streaming data such as IoT device data with low latency, providing insights in minutes. | An asynchronous and scalable messaging service that decouples services producing messages from services processing those messages. |
| **Core Features**          | Triggers, Binding, Messaging, Eventing                                           | Triggers, Messaging, Eventing                                                   | Triggers, Subscription-based bindings, Messaging, Eventing                           |
| **Native Integrations**    | Azure Stream Analytics, Azure Data Explorer, Azure Function Apps                 | AWS Lambda, Amazon Redshift, Amazon CloudWatch                                  | Dataflow, BigQuery, Cloud Functions                                                  |
| **Third-party Integrations** | Apache Kafka, Apache Spark                                                     | Kafka Connector, Apache Flink, Debezium                                         | Apache Kafka Connector, Datadog, Grafana                                             |
| **Monitoring & Observability** | Azure Monitor                                                             | CloudWatch                                                                      | Google Cloud Monitoring, Google Logging                                              |
| **Pricing Model**          | Price per hour; Price per million events; Storage costs; Retention period costs  | Per stream; Per hour; Data storage costs                                         | Throughput-based costs; Data transfer costs; Storage costs; Pay-as-you-go            |
| **Strengths**              | Strong for IoT devices and application monitoring                               | High scalability and throughput; Supports replay; Flexible and accessible       | Pay-as-you-go model; Easy integration                                                |
| **Weaknesses**             | Less flexible pricing; Integration improvements needed                          | Pricing can be expensive at scale; Throughput limits; No FIFO queuing            | Slower processing for large messages; Potential message duplication issues           |
### Analysis

## References

## Azure Functions
### Azure Functions 
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses
### AWS Lambda
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses
### Google Cloud Functions
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses

## Azure Logic Apps
### Azure Logic Apps
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses
### AWS Step Functions
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses
### Google Cloud Workflows
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses

## Durable Functions
### Durable Functions
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses
### AWS Step Functions
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses
### Google Cloud Functions
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses

## Azure Service Bus
### Azure Service Bus
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses
### Amazon Simple Notification Service
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses
### Cloud Pub/Sub
#### Overview
#### Core Features
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses


## Azure Event Grid
### Azure Event Grid
#### Overview
"Azure Event Grid is a fully managed, publish-subscribe event routing service designed for near real-time delivery." (https://prashantbiztalkblogs.wordpress.com/2025/06/21/event-grid-vs-service-bus-vs-event-hubs-vs-storage-queues-choosing-the-right-messaging-backbone-in-azure/)
#### Core Features
- Triggers (https://learn.microsoft.com/en-us/azure/event-grid/overview)
- Bindings (https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-event-grid-trigger?tabs=python-v2%2Cisolated-process%2Cnodejs-v4%2Cextensionv3&pivots=programming-language-python)
- Messaging (https://learn.microsoft.com/en-us/azure/event-grid/overview)
- Eventing (https://learn.microsoft.com/en-us/azure/event-grid/overview)
#### Integration Options

##### Native
- Azure Functions
- Logic Apps
- Events Hubs
- (https://medium.com/walmartglobaltech/azure-messaging-services-how-to-choose-the-right-messaging-technology-in-azure-eab610b5e986)
##### Third-party
- Datadog (https://docs.datadoghq.com/integrations/azure-eventgrid/)
- MongoDB (https://www.mongodb.com/company/blog/technical/using-azure-event-hubs-with-connector-apache-kafka)
#### Monitoring & Observability
- Built-in monitoring (https://learn.microsoft.com/en-us/azure/event-grid/monitor-event-delivery)
#### Pricing Model
- Price per unit per hour
- No additional fees for MQTT opperations until 1 million opperations
- Pay-per-use option
- (https://azure.microsoft.com/en-us/pricing/details/event-grid/)

#### Strengths & Weaknesses
##### Strengths
- Low-latency (https://prashantbiztalkblogs.wordpress.com/2025/06/21/event-grid-vs-service-bus-vs-event-hubs-vs-storage-queues-choosing-the-right-messaging-backbone-in-azure/)
- Felxible pricing options (pay-as-you-go or time-based)
##### Weaknesses
- Some regions are unable to supply resources, limiting its usefullness
- More costly than alternatives such as Event Grid (https://azurelessons.com/azure-event-hub-vs-event-grid/)

### Amazon EventBridge
#### Overview
- a serverless service that uses events to connect application components together, making it easier to build scalable event-driven applications. (https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-what-is.html)
#### Core Features
- Triggers (https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-what-is.html)
- Messaging https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html
- Eventing (https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-what-is.html)
#### Integration Options
##### Native
- Lambda
- Amazon SQS
- Amazon SNS
- (https://cyberpanel.net/blog/aws-eventbridge)
##### Third-party
- Datadog
- MongoDB
- Salesforce
- (https://aws.amazon.com/eventbridge/integrations/)
#### Monitoring & Observability
- CloudWatch (https://cloudburn.io/blog/amazon-eventbridge-pricing)
#### Pricing Model
- Cost per million events (https://aws.amazon.com/eventbridge/pricing/)
#### Strengths & Weaknesses
##### Strengths
- High level of customization and determining which services are dependent
- Excellent documentation
- (https://www.peerspot.com/products/amazon-eventbridge-pros-and-cons)

##### Weaknesses
- Doesn't have an event-replay feature
- Poor stability, where it is not triggering when it should be.
- (https://www.peerspot.com/products/amazon-eventbridge-pros-and-cons)

### Cloud IoT Core
#### Overview
- "Cloud IoT Core is a fully managed service that allows you to easily and securely connect, manage, and ingest data from millions of globally dispersed devices." (https://sourceforge.net/software/compare/Amazon-EventBridge-vs-Google-Cloud-IoT-Core/)
#### Core Features
- Messaging (https://cloud.google.com/blog/topics/developers-practitioners/what-cloud-iot-core)
#### Integration Options
##### Native
- Cloud Dataflow (https://docs.cloud.google.com/architecture/connected-devices/iot-platform-product-architecture)
- Cloud Pub/Sub (https://docs.cloud.google.com/architecture/connected-devices/iot-platform-product-architecture)
##### Third-party
- Telegraf
- Prometheus
- Grafana
- (https://logit.io/docs/integrations/google-cloud-iot-core/)
#### Monitoring & Observability
- Cloud Logging (https://docs.cloud.google.com/chronicle/docs/ingestion/default-parsers/gcp-cloudiot)
#### Pricing Model
- Discontinued
- Price per MB used (https://www.scrums.com/cloud-hub/google-cloud-iot-core)
#### Strengths & Weaknesses

##### Strengths
- SDK is available in all the mobile platform as well as web.
- Can help send data to elastic cache very easily.
- (https://www.trustradius.com/products/aws-iot-core/reviews?qs=pros-and-cons)

##### Weakness
- Monitoring and real-time dashboard features could be improved.
- Sometimes the server hangs and is unable to send data to cloud services.
- Discontinued
- (https://www.trustradius.com/products/aws-iot-core/reviews?qs=pros-and-cons)






## Azure Event Hubs
### Azure Event Hubs
#### Overview
This is a fully managed, real-time data streaming platform that can ingest millions of events per second with low latency to build data pipelines for IoT telemetry, application logging, clickstream analytics, financial transaction processing, and other scenarios that require high-throughput, reliable event ingestion.
#### Core Features
- Triggers (https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-event-hubs-trigger?tabs=python-v2%2Cisolated-process%2Cnodejs-v4%2Cfunctionsv2%2Cextensionv5&pivots=programming-language-python)
- Binding (https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-event-hubs-trigger?tabs=python-v2%2Cisolated-process%2Cnodejs-v4%2Cfunctionsv2%2Cextensionv5&pivots=programming-language-python)
- Messaging (https://learn.microsoft.com/en-ca/azure/event-hubs/event-hubs-about)
- Eventing (https://learn.microsoft.com/en-ca/azure/event-hubs/event-hubs-about)

#### Integration Options

##### Native
- Azure Stream Analytics
- Azure Data Explorer
- Azure Function Apps
(https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-about)

##### Third-party
- Apache Kafka (https://azure.microsoft.com/en-us/products/event-hubs/)
- Apache Spark (https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-kafka-spark-tutorial)
- Apache Kafka (https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-kafka-connect-tutorial)

#### Monitoring & Observability
- Azure Monitor (https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-about)

#### Pricing Model
- Pricing models providing
- Price per hour
- Price per million events
- Storage space
- Renention period
(https://azure.microsoft.com/en-us/pricing/details/event-hubs/)

#### Strengths & Weaknesses
##### Strengths
- Iot devices
- Application monitoring
- https://www.codestudy.net/blog/kafka-vs-kinesis-vs-event-hub/

##### Weaknesses
- Less flexibility in pricing options than Kinesis, and a less forgiving pricing model than Cloud Pub/Sub
- Integration with other services should be improved (https://www.trustradius.com/products/azure-event-hubs/reviews?qs=pros-and-cons)


### Amazon Kinesis
#### Overview
Amazon's service for managing real-time data streams to collect streaming data such as IoT device data with low latency, providing insights in minutes.
#### Core Features
- Supported triggers (https://docs.aws.amazon.com/lambda/latest/dg/services-kinesis-create.html)
- Messaging (https://docs.aws.amazon.com/streams/latest/dev/introduction.html)
- Eventing (https://docs.aws.amazon.com/lambda/latest/dg/with-kinesis.html)

#### Integration Options
##### Native
- AWS Lambda
- Amazon Redshift
- Amazon CloudWatch
(https://www.cloudoptimo.com/blog/getting-started-with-amazon-kinesis-for-real-time-data/)
##### Third-party
- Kafka Connector
- Apache Flink
- Debezium
(https://docs.aws.amazon.com/streams/latest/dev/using-other-services-third-party.html)

#### Monitoring & Observability
- CloudWatch (https://www.cloudoptimo.com/blog/getting-started-with-amazon-kinesis-for-real-time-data/)

#### Pricing Model
- Per stream
- Per hour
- Data stored
(https://aws.amazon.com/kinesis/data-streams/pricing/)
#### Strengths & Weaknesses
##### Strengths
-  "robust scalability and high data throughput, handling gigabytes within milliseconds."
- "supports real-time data streaming and offers replay features, beneficial for business troubleshooting."
-  "accessible to novice developers and offers significant flexibility for business applications."
- (https://www.peerspot.com/products/amazon-kinesis-pros-and-cons)

##### Weaknesses
- "could improve its pricing to be more competitive, especially for large volumes."
- "hard limits on Amazon Kinesis, and if users hit those, they will encounter a throughput exceed error."
- "lacks first in, first out queuing"
- (https://www.peerspot.com/products/amazon-kinesis-pros-and-cons)

### Google Cloud Pub/Sub

#### Overview
An asynchronous and scalable messaging service that decouples services producing messages from services processing those messages.

#### Core Features
- Triggers (https://docs.cloud.google.com/pubsub/docs/pubsub-basics)
- Binding isn't followed directly, but is subscriptions and delivery types can connect Pub/Sub to consumers or other services (https://docs.cloud.google.com/pubsub/docs/pubsub-basics)
- Messaging (https://docs.cloud.google.com/pubsub/docs/pubsub-basics)
- Eventing (https://docs.cloud.google.com/solutions/event-driven-architecture-pubsub)

#### Integration Options
##### Native 
- Dataflow
- BigQuery
- Cloud functions
(https://cloud.google.com/pubsub/integrations)
##### Third-party
- Apache Kafka Connector
- Datadog
- Grafana
(https://cloud.google.com/pubsub/integrations)
#### Monitoring & Observability
- Google Cloud Monitoring (https://cloud.google.com/pubsub/integrations)
- Google Logging (https://cloud.google.com/pubsub/integrations)
#### Pricing Model
- Throughput costs for message publishing and delivery
- Data transfer costs associated with throughput that crosses a Google Cloud zone or region boundary
- Storage costs associated with retaining messages
- Pay for what is used
(https://cloud.google.com/pubsub/pricing)

#### Strengths & Weaknesses
##### Strengths
- Pay-as-you-go model
- Easy integration (https://www.g2.com/products/google-cloud-pub-sub/reviews?qs=pros-and-cons)
##### Weaknesses
- slow processing for messages over 10MB
- issues with message duplication
- (https://www.g2.com/products/google-cloud-pub-sub/reviews?qs=pros-and-cons)

