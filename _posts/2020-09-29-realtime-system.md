---
layout: post
title: "Real-Time System Architecture"
author: "Venkat Krish"
categories: architecture realtime
tags: [real-time,architecture,stream]
image: real_time_system.jpg
---

In the space of Big Data system the **Volume** and **Variety** of data play a major role but when it comes to **Velocity**, the data processing system is expected not only to perform the processing operations but also respond the output quickly, which is known as *Real-Time Processing*.

## What is a real-time processing?

A *real-time processing* or *real-time computing* is nothing but an operation to process the data that are streaming into a system in a continuous manner. A streaming data is always in continuous and sequential in nature. 

Real-time systems are classified as *hard, soft* and *near*. These are categorized based on the latency of processing of data. 
- **Hard** : Microseconds to milliseconds in latency. Eg. Pacemaker, anti-lock breaker
- **Soft** : Milliseconds to seconds in latency. Eg. Airline reservation, online stock quotes, VoIP
- **Near** : Seconds to Minutes in latency. Eg. Skype video, home automation

### A streaming data system

A streaming data system is known as a non-hard real-time system that makes the data available whenever its client application needs it. It does not fall into neither soft nor near time, it is streaming. 

In this definition of streaming data system, there are two entities, 
1. Data Computation, which is non-hard real-time system
2. Data Consumption, a client consumes the streaming data.

The following architecture diagram depicts the two entities of data streaming system. 

![A streaming architecture ](/assets/img/stream-architecture.png)
