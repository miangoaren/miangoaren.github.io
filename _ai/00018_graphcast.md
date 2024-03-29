---
title: "Post 18: GraphCast, an AI that predicts the weather 🌍"
collection: ai
permalink: /ai/00018_graphcast
date: 2023-11-08
---

&nbsp;

Sometimes I see AIs like this and I'm amazed at what can be modeled using only data 💻

A few days ago, Google introduced GraphCast, an AI that predicts the weather for the next 10 days and outperforms current systems based on physics equations. This is incredible because the AI was never taught physics topics; it only learns about these types of phenomena by observing the data. Additionally, GraphCast is open source!

Weather is very complicated to model due to the countless variables and their interactions, making it chaotic. But how did they do it? They used 38 years of weather data (from 1979 to 2017). They then divided the atmosphere into 37 levels from top to bottom, each divided into quadrants of 0.25° longitude-latitude; which means that each quadrant has hundreds of weather variables for each day/month/year. Then, they represent these quadrants as a network, with each one being an interconnected node with other quadrants.

Here they apply a specialized AI in learning relational patterns called a "graph neural network" that allows them to know which weather conditions at a specific point are determined given the weather variables of all the quadrants in the network. However, the training process starts from large-scale quadrants and is refined until it reaches the smallest quadrants of 0.25°. That is, this process allows estimating which weather variables at point X on Earth have an effect on another point at a specific time, starting on a global scale and refining to a specific scale.

![img](/images/ai/00018_graphcast.jpg)

And so, with this approach, they can ask what weather conditions are likely to occur given the conditions at other points on Earth, which allowed them to identify dangerous phenomena such as cyclones, extreme temperatures, etc.

Refs:
* [GraphCast ](https://deepmind.google/discover/blog/graphcast-ai-model-for-faster-and-more-accurate-global-weather-forecasting)
