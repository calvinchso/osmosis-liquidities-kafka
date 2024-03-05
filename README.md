# osmosis-liquidities-kafka

This repository for keeping Kafka configurations and other supporting files.

**sink-configs** folder keeps the configuration files for different Kafka Connect sink connectors.

To start Redis Sink Connector:
```
${KAFKA_HOME}bin/connect-standalone.sh config/connect-standalone.properties sink-configs/redis.properties
```
