---
title:  Trading Farms
summary: "How to set up a flexible and scalable crypto-trading farm running Superalgos distributed in multiple machines."
sidebar: suite_sidebar
permalink: suite-fundamental-trading-farms-concepts.html
toc: false
---

Superalgos is designed for flexible and scalable trading operations. 

In its current version, the system may be deployed in multiple machines&mdash;as many as desired&mdash;and each machine may constitute a node in a network of nodes. In fact, different networks of nodes may live within the same computer network.

Each node on a network may specialize in a single type of process or handle multiple processes of different types. At a larger scale, each network of nodes may have particular specialties.

For example, you may have a set of nodes running data mining operations extracting data from multiple markets and multiple exchanges. You may have a set of nodes specializing in processing indicators and technical studies. And you may have a set of nodes specializing in running trading sessions.

You may also create networks of nodes with different criteria. For example, you may have a node running combined data mining, data processing, and trading operations on a single exchange or market, and other nodes running similar combined operations on other exchanges or markets.

Or you may have a network of nodes for your testing environment and another network of nodes for your production environment.

In other words, the system allows building any arrangement of networks of nodes responding to the organizational logic of your preference.

What is unique about Superalgos is that the system keeps track of the network arrangements you create and makes sure that all components and data structures in the system can seamlessly track dependencies across the network. This means, for example, that trading sessions running on ```Node X``` may access data in ```Node Y``` and ```Node Z``` without requiring any sort of configuration.

On top of that, the operation may be administered entirely from any node on the network.

The explanations below assume that you are familiar with the basic workings of Superalgos, and in particular, of the Network hierarchy. If that is not the case, then please read the [Network pages](suite-network.html) before diving into building a trading farm.

{% include warning.html content="At this stage, Superalgos does not implement any form of security measures, therefore, the system is to be used in the context of a restricted Local Area Network only." %}