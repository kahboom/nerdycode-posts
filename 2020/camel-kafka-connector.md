---
title: Camel Kafka Connector
eleventyExcludeFromCollections: true
date: 2020-09-25
permalink: "/camel-kafka-connector/"
dynamicPermalink: false
layout: post.njk
tags:
  - integration
  - camel
  - java
  - kafka
---

I have previously talked about [using Camel for data integration](), and Kafka for streaming events on a large scale. Today we'll be looking at Camel Kafka Connectors, which provide a dead simple way of using Camel components as Kafka event sources and sinks. 


## With great power comes great responsibility

Because we don't have the same convenience of shared data and common governance that we had in service-oriented architecture, communication of data is typically done via REST APIs and simple messaging, such as Java Messaging Service (JMS). This setup lends itself very well to event streaming platforms like Apache Kafka as a central event bus. And, well, because data can be quite complicated, even in small quantities, we typically use specialized platforms to aid us, just as we did with integration.

We previously discussed how Apache Camel helps developers to work with data in a message-oriented fashion.

