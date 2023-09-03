# Confluent Kafka

For details, see Notion page
https://lennythedev.notion.site/Confluent-cloud-Node-js-01aa0049bb974773b3883f3e8a4aa72c?pvs=4

# When installing node-rdkafka, make sure to follow these instructions before `npm install`
https://github.com/Blizzard/node-rdkafka/blob/master/README.md#mac-os-high-sierra--mojave

# About the code
- consumer.js and producer.js is directly from the Confluent Kafka tutorial
- consumer2.js and producer2.js is modified for the `poems` topic

# CLI login

```
confluent login
```

Credentials:
see `confluent.io` in Last pass

cluster_0

environment:
env-7nvpzw

cluster:
lkc-v1z0dj


# Credentials
```
API Key and API Secret
- generate a new one on Confluent dashboard, or see on Last pass entry
```

### Login
confluent login --save

### Do commands

List topics
```
confluent kafka topic list
```

Produce to topic
```
confluent kafka topic produce topic_name --parse-key
```

Consume from topic
```
confluent kafka topic consume --from-beginning topic_name
```

# Bootstrap endpoint
pkc-419q3.us-east4.gcp.confluent.cloud:9092
