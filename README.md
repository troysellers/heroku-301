# Heroku 301

In this exercise we are going to look at Kafka Producer and Consumer application as well as a web/worker pattern as a means for distributing load in Heroku via a traditional queue as well.

## Prerequisites 
You should definitely have a look at the Heroku-101 prerequisites, as we use the same tools there again. 
We also need to install our first plugin to the Heroku CLI (that's right, it's extensible!) 

See [Preparing Your Environment](https://devcenter.heroku.com/articles/kafka-on-heroku#preparing-your-development-environment) for details on how to ensure the Kafka CLI commands are installed. 

## Kafka
The introduction section on the Kafka home does an excellent job of explaining what Kafka is, so I encourage you to head over and have a look. Also, have a look at the Heroku docs that talk about our service as well. 

For the purpose of this exercise today we will use the multi-tennant kafka service. 

## Create a Kafka Producer

Check out this [codebase](https://github.com/bigfoot/heroku-301-generator) for how to get a kafka generator

## Create a Kafka Consumer

Check out this [codebase](https://github.com/bigfoot/heroku-301-client) for how to get a kafka client

## Web / Worker Pattern

There is another pattern that you might be interested in investigating as well, that of the "Web / Worker" pattern in Heroku. We use this to offload processing to different dynos, "workers", while we free up the UI / API layer for processing more requests. 

I recommend have a look at this [dev center article](https://devcenter.heroku.com/articles/background-jobs-queueing) to get some excellent examples of how this works in your favourite development language. 



