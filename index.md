
---
title: Network Anomaly Dectection
---

# Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
	- [Prior Work](#prior-work)
	- [The Data](#the-data)
	- [Definition of an Anomaly](#definition-of-an-anomaly)
	- [EDA](#eda)
	- [Feature Engineering](#feature-engineering)
	- [Anomaly Detection Methods and Models](#exploration-of-anomaly-detection-methods)
- [Results](#results)
- [Future Work](#future-work)
	- [Bigger Questions](#bigger-questions)
	- [Improvements](##improvements)
- [References](#references)
- [Appendix](#appendix)

# Introduction
<p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Viasat Inc. is an American communications company that provides high-speed satellite broadband services and secure networking systems covering military and commercial markets.
Therefore, ensuring high quality network performance is crucial for their business success and maintaining customer satisfaction. Fundamental factors that affect network performance are packet loss and latency. When accessing the internet or any network, small units of data called packets are sent and received. Packet loss occurs when one or more of these packets fails to reach its intended destination. This results in slow service and network disruptions for the user. Latency is the delay between a user’s action and a web application’s response to that action, often referred to as the total round trip time it takes for a data packet to travel.</p> 
<p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The problem we are trying to explore is: can we detect anomalies within network traffic, whether it be an increase in the packet loss rate, larger latency or both. Packet loss can be caused by a number of issues, including: network congestion, problems with network hardware, software bugs and security threats. On the other hand, main factors that affect network latency are: the transmission medium (copper cable-based networks vs. modern optic fibers), propagation (how far apart the networks are), efficiency of routers and storage delays. The ability to detect anomalies on a data stream would be extremely useful as a monitoring & alerting system for poor network conditions.</p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We will be using data generated from DANE (Data Automation and Network Emulation Tool), a tool that automatically collects network traffic datasets in a parallelized manner without background noise and emulates a diverse range of network conditions that are representative of the real world. Using DANE, we are able to configure parameters such as latency and the packet loss ratio ourselves. More importantly, we are able to simulate an anomaly by changing the configuration settings of the packet loss rate and latency mid run. The data collected is already aggregated per second with these fields: timestamps, IP and port addresses of the source and destination, number of bytes and packets sent for each direction of traffic, the milliseconds of when each packet was sent, the size of each packet sent and the sequence of direction of each packet. By having the ability to change the parameters within DANE, we are able to generate as much data as we need with varying network conditions which is helpful in producing an accurate model. </p>

# Methodology

### Prior Work

### The Data

### Definition of an Anomaly

### EDA 

### Feature Engineering

### Exploration of Anomaly Detection Methods

# Results

# Future Work

### Bigger Questions

### Improvements

# References
