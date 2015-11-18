---
layout: post
title:  "Intersection Simulator"
date:   2015-11-17 14:41:33 -0700
categories: CS5600
---


Welcome to the project page for Intersection Simulator (aka Merry-Go-Round-About)

## Project Introduction:

As connected autonomous vehicles will become more and more common in the coming decades, this technology can be used to reduce traffic congestion, a big problem in major metropolitan areas.  Cars will be able to communicate with each other, as well as communicate with a central traffic management system. One interesting part of traffic control that can be evaluated is the use of roundabouts.

## Why:
Roundabouts are an efficient alternative to traditional 4-way stops. However, they can suffer from starvation under heavy traffic flow. Additionally, human drivers do not always most efficiently utilize the gaps in traffic available to them, and increase congestion. This gap-management could be made more efficient using connected autonomous vehicles. This can reduce fuel costs and travel time, as well reduce carbon footprint from fossil fuel vehicles.


## Implementation:
The roundabout can be thought of as a merry-go-round with 'slots' for each car that is on the roundabout. Roundabout entry points are where pop in a car into a slot. We can then 'spin' the merry-go-round until the desired leave point is reached, where we pop the car out of the slot. To find optimal configurations under heavy traffic and prevent car starvation, I will utilize an intelligent algorith.

#From this:
![Merry-go-round](https://upload.wikimedia.org/wikipedia/commons/d/d8/Man%C3%A8geLR1.jpg)

#To this:
![Roundabout](https://upload.wikimedia.org/wikipedia/commons/d/d4/LUMC-rotonde.JPG)

#Diagram:
![Diagram](http://i.imgur.com/mTN8RDb.png)

## Technologies Used:
Project is implemented in C# and will include a WinForms based visualization and controls. Intersections are modeled using QuickGraph .NET graph library.

## Links:
* Source code: [https://github.com/FabioCZ/IntersectionSim](https://github.com/FabioCZ/IntersectionSim)
* QuickGraph: [http://quickgraph.codeplex.com/](http://quickgraph.codeplex.com/)
* Images from: [http://wikipedia.org](http://wikipedia.org)