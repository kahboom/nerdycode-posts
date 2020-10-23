---
title: Kafka
eleventyExcludeFromCollections: true
date: 2020-09-25
permalink: "/kafka/"
dynamicPermalink: false
layout: post.njk
tags:
  - kafka
---

Today we're gonna learn Apache Kafka together.

First and foremost, some key concepts:


A Kafka broker is 

Kafka clusters usually consist of several brokers.



## Getting Started

If you're just looking to try it out, you can run Kafka locally using just Kafka and Zookeeper. You can also use something like Strimzi to make it easy to run Kafka on Kubernetes.

## Additional Tips

You can use any data format you want (e.g. XML, JSON, Avro), but it should be an organizational choice. Your life will be much easier if you have one company-wide data format for events that you typically adhere to.

Model events, not commands. For instance, if you are sending a "Thank you" email to a user when they subscribe to your newsletter, prefer that the application creates a more general `UserSubscribed` event as opposed to a `SendThankYouEmail` event.
