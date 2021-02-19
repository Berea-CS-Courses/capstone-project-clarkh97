# Overview

I want to create an app designed for users to be able to track their own personal carbon footprint. 
My main goal is to use GPS tracking and keep track of carbon emissions created while driving. 
Ideally, the app would be able to sync with other apps such as grocery purchasing apps in order to be able to 
look at products purchased, and reference a database of emissions created by products in order to create a more
complete look at personal carbon footprint.

# Concept

I think an app that keeps track of carbon emissions by calculating driving emisisons based on GPS
is the most feasible project given the timeline. I want to be able to have the application automatically 
detect when the user is in a vehicle, and pull emissions information about the specific vehicle, then calculate
emissions based on the trip and add up trips cumulatively. I do not think I will go beyond vehicle emissions
given the time constraint of the course.

# Software Requirement Specifications

## Functional requirements

- software must keep track of the user's location.
- software must determine if user is parked or driving.
- software must store the vehicle information of the user.
- software must calculate emissions based on vehicle and driving info.
- software must add up emissions information and present it to user.

## Non-functional requirements

- software must run on iOS devices.
- software must run on Android devices.
