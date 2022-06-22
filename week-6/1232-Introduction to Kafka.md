# Introduction to Kafka

Slides 

<p><iframe allowfullscreen width="100%" height="569" class="google-slides-iframe" frameborder="0" scrolling="no" src="https://docs.google.com/presentation/d/1bCtdCba8v1HxJ_uMm9pwjRUC-NAMeB-6nOG2ng3KujA/embed?start=false&loop=false&delayms=3000"></iframe></p>


# Video: Intro to Kafka

<iframe width="100%" height="315" src="https://youtube.com/embed/P1u8x3ycqvg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Video: Configuration Terms 

<iframe width="100%" height="315" src="https://youtube.com/embed/Erf1-d1nyMY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Video: Avro and schema registry 

<iframe width="100%" height="315" src="https://youtube.com/embed/bzAsVNE5vOo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Configuration
Please take a look at all configuration from kafka [here](https://docs.confluent.io/platform/current/installation/configuration/
). 

# Docker

Starting cluster
`docker-compose up
`
# Command line for Kafka

Create topic
`./bin/kafka-topics.sh --create --topic demo_1 --bootstrap-server localhost:9092 --partitions 2
`