---
title: Containerization & Docker
eleventyExcludeFromCollections: true
date: 2020-09-25
permalink: "/containerization-docker/"
dynamicPermalink: false
layout: post.njk
tags:
  - integration
  - camel
  - java
  - kafka
---

Anyone architecting enterprise software knows that there is no such thing as a one-size-fits-all solution for data-driven organizations. Monoliths of data can also become exceedingly difficult (and expensive) to maintain. Trends in software are reflective of this as middleware and embedded systems have been reinvented and expanded to become more broken up or "componentized".

These components, usually in the form of services or containers, can communicate and exchange data using an enterprise service bus (ESB) or messaging system, respectively.

We've generally observed a move away from service-oriented architecture (SOA) and the enterprise service buses (ESBs) that coordinated and controlled its services, and toward a world of microservices with services that function independently of one another. With this, we've discovered that containerization is better suited to our newfound demands of easy and rapid scalability over its virtualization predecessor.

You're probably already familiar with the general concept of containers, but the gist of it is that each service gets deployed in a self-contained unit of software we know as a container, which means it contains everything it needs to run successfully (e.g. dependencies, libraries). You may use something like Kubernetes or OpenShift (or its community counterpart, OKD) to help orchestrate these containers, or manage them.
