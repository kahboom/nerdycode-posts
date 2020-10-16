---
title: Module Federation with Webpack 5
eleventyExcludeFromCollections: true
date: 2020-10-15
permalink: "/module-federation-webpack/"
dynamicPermalink: false
layout: post.njk
references:
    - {title: 'Module Federation', url: 'https://camel.apache.org/docs/'}
tags:
  - microfrontends
  - webpack
---

Webpack 5 was released not too long ago with many new exciting features. But the one I was most excited about is Module Federation. Today we'll be going over a few key concepts in module federation, and 
Module federation is a new technology that has been incorporated into Webpack 5 as a plugin.

## Problems with this approach

The main problem I have with module federation, and with designing components to be highly reusable in general, is that web applications and their data sources should really be designed as one. Otherwise, the application will never really have a chance at performance.
