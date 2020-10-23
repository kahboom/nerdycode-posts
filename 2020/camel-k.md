---
title: Camel K
eleventyExcludeFromCollections: true
date: 2020-09-22
permalink: "/camel-k/"
dynamicPermalink: false
layout: post.njk
tags:
  - camel-k
  - integration
  - java
---

Today we'll be talking about Camel K, an open source cloud-integration platform that lets you automate your cloud configurations.

We previously discussed how Apache Camel helps developers to work with data in a message-oriented fashion, but how does it fit into our new and shiny cloud-native world? 

Here's a quick overview of how it works..

Camel K essentially takes the toolkit of Camel and runs it natively on Kubernetes, in a version specifically designed for serverless and microservice architectures.

(Users of Camel K can instantly run integration code written in Camel DSL on their preferred cloud, using Kubernetes or OpenShift).

Early this year it plans to add new tools including a Kafka Connector and Camel Spring Boot (moved out from main repository) — an open source Java-based framework used to create microservices that was developed by Pivotal.




Otherwise, you'll be running something like this in your terminal:

```bash
kamel run Example.java --dev
```

Where `--dev` will just tail the log for you, and you'll get a bit more information.
