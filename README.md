# CST8917 - Assignment 2

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
#### Core Features
- Triggers (https://learn.microsoft.com/en-us/azure/event-grid/overview)
- Bindings (https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-event-grid-trigger?tabs=python-v2%2Cisolated-process%2Cnodejs-v4%2Cextensionv3&pivots=programming-language-python)
- Messaging (https://learn.microsoft.com/en-us/azure/event-grid/overview)
- Eventing (https://learn.microsoft.com/en-us/azure/event-grid/overview)
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses

### Amazon EventBridge
#### Overview
#### Core Features
- Triggers (https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-what-is.html)
- Messaging https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html
- Eventing (https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-what-is.html)

#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses

### Cloud IoT Core
#### Overview
#### Core Features
- Messaging (https://cloud.google.com/blog/topics/developers-practitioners/what-cloud-iot-core)
#### Integration Options
#### Monitoring & Observability
#### Pricing Model
#### Strengths & Weaknesses


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
#### Pricing Model
#### Strengths & Weaknesses

### Amazon Kinesis
#### Overview
Amazon's service for managing real-time data streams to collect streaming data such as IoT device data with low latency, providing insights in minutes.
#### Core Features
- Supported triggers (https://docs.aws.amazon.com/lambda/latest/dg/services-kinesis-create.html)
- Bindings, since functions can be mapped to processes (https://docs.aws.amazon.com/lambda/latest/dg/services-kinesis-create.html)
- Messaging through Kinesis Data Streams (https://docs.aws.amazon.com/streams/latest/dev/introduction.html)

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
#### Pricing Model
#### Strengths & Weaknesses

### Google Cloud Pub/Sub

#### Overview

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
#### Pricing Model
#### Strengths & Weaknesses

Overview – brief description of each service
Core Features – supported triggers, bindings, messaging/eventing capabilities
Integration Options – how it works with other cloud services or CI/CD pipelines
Monitoring & Observability – available tools/logging integrations
Pricing Model – high-level cost considerations
Strengths & Weaknesses – from a serverless architecture perspective
