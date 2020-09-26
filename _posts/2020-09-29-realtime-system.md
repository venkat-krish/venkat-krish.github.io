---
layout: post
title: "Real-Time System Architecture"
author: "Venkat Krish"
categories: journal
tags: [real-time,stream processing, distributed]
image: real_time_sytem.jpg
---

In the space of Big Data system the volume and variety of data play a majore role but when it comes to Velocity, the data processing system is expected not only to perform the operations in batch mode but also instantaneously, which is also known as *Real-Time Processing*.

## What is a real-time processing?

A *real-time processing* or *real-time computing* is nothing but an operation to process the data that are streaming into a system in a continuous manner. A streaming data is always in continuous and sequential in nature. 

Real-time systems are classified as *hard, soft* and *near*. These are categorized based on the latency of processing of data. 
- Hard : Microseconds to milliseconds in latency. Eg. Pacemaker, anti-lock breaker
- Soft : Milliseconds to seconds in latency. Eg. Airline reservation, online stock quotes, VoIP
- Near : Seconds to Minutes in latency. Eg. Skype video, home automation


<!-- 
[Getting Started]({{ site.github.url }}{% post_url 2015-10-10-getting-started %}): getting started with installing Lagrange, whether you are completely new to using Jekyll, or simply just migrating to a new Jekyll theme. -->
