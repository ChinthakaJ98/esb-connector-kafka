# Kafka EI Connector

The Kafka [connector](https://docs.wso2.com/display/EI650/Working+with+Connectors) allows you to access the [Kafka 
Producer API](http://kafka.apache.org/documentation.html#producerapi) through WSO2 EI and acts as a message producer 
that facilitates message publishing. The Kafka connector sends messages to the Kafka brokers. 

Kafka is a distributed publish-subscribe messaging system that maintains feeds of messages in topics. Producers write
data to topics and consumers read from topics. For more information on Apache Kafka, see [Apache Kafka documentation](http://kafka.apache.org/documentation.html). 



## Compatibility

| Connector version | Supported Kafka version | Supported WSO2 ESB/EI version |
| ------------- | ---------------|------------- |
| [3.0.0](https://github.com/wso2-extensions/esb-connector-kafka/tree/v3.0.0) | kafka_2.12-1.0.0 | EI 6.5.0, EI 6.6.0, EI 7.0.x   |
| [2.0.10](https://github.com/wso2-extensions/esb-connector-kafka/tree/org.wso2.carbon.connector.kafkaTransport-2.0.10) | kafka_2.12-1.0.0 | EI 6.5.0   |
| [2.0.9](https://github.com/wso2-extensions/esb-connector-kafka/tree/org.wso2.carbon.connector.kafkaTransport-2.0.9) | kafka_2.12-1.0.0 | EI 6.5.0   |
| [2.0.8](https://github.com/wso2-extensions/esb-connector-kafka/tree/org.wso2.carbon.connector.kafkaTransport-2.0.8) | kafka_2.12-1.0.0 | EI 6.5.0   |
| [2.0.7](https://github.com/wso2-extensions/esb-connector-kafka/tree/org.wso2.carbon.connector.kafkaTransport-2.0.7) | kafka_2.12-1.0.0 | EI 6.5.0   |
| [2.0.6](https://github.com/wso2-extensions/esb-connector-kafka/tree/org.wso2.carbon.connector.kafkaTransport-2.0.6) | kafka_2.12-1.0.0 | EI 6.5.0   |
| [2.0.5](https://github.com/wso2-extensions/esb-connector-kafka/tree/org.wso2.carbon.connector.kafkaTransport-2.0.5) | kafka_2.12-1.0.0 |ESB 4.9.0, EI 6.2.0, EI 6.3.0, EI 6.4.0, EI 6.5.0   |
| [2.0.4](https://github.com/wso2-extensions/esb-connector-kafka/tree/org.wso2.carbon.connector.kafkaTransport-2.0.4) | kafka_2.12-1.0.0 |ESB 4.9.0, ESB 5.0.0, EI 6.2.0   |
| [2.0.3](https://github.com/wso2-extensions/esb-connector-kafka/tree/org.wso2.carbon.connector.kafkaTransport-2.0.3) | kafka_2.12-1.0.0|ESB 4.9.0, ESB 5.0.0   |
| [1.0.1](https://github.com/wso2-extensions/esb-connector-kafka/tree/org.wso2.carbon.connector.kafkaTransport-1.0.1) | kafka_2.12-1.0.0, kafka_2.12-0.11.0.0, 2.9.2-0.8.1.1 |ESB 4.9.0, ESB 5.0.0    |

## Documentation

Please refer to documentation [here](https://ei.docs.wso2.com/en/latest/micro-integrator/references/connectors/kafka-connector/kafka-connector-overview/).

## Building From the Source

Follow the steps given below to build the Kafka connector from the source code:

1. Get a clone or download the source from [Github](https://github.com/wso2-extensions/esb-connector-kafka).
2. Run the following Maven command from the `esb-connector-kafka` directory: `mvn clean install`.
3. The Kafka connector zip file is created in the `esb-connector-kafka/target` directory

## How You Can Contribute

As an open source project, WSO2 extensions welcome contributions from the community.
Check the [issue tracker](https://github.com/wso2-extensions/esb-connector-kafka/issues) for open issues that interest you. We look forward to receiving your contributions.
