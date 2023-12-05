# Monolith

## Overview

A monolithic application is made up of a single unified unit, independent from other applications. There is one codebase which is responsible for all of the functions of the program. 

## Benefits

Monoliths are often beneficial early in the lifecycle of a project as the codebase will be smaller, and having one single unit to update and deploy can be easier than multiple smaller units, especially if the program's complexity has not yet significantly developed. 

Monoliths can also often offer increased performance as the functionality is included within one single API, rather than multiple sections needing to make calls to ecah other. Testing may also be easier within a unified codebase. 

## Drawbacks

Making a change to a monolith once the code has become more complex is more difficult, as the entire application may need to be rewritten or refactored in order to accommodate the change. This also makes it more difficult to scale individual components as needed. 

Deployment is also affected as the entire application will need to be redeployed every time a single change is made. 

A small error in one part of the monolith may also have knock-on effects to the reliability of other parts.

## Diagram
Source: https://www.atlassian.com/microservices/microservices-architecture/microservices-vs-monolith

![](diagram.png)

## Use case
A monolith could be useful in rapidly deploying a prototype or MVP application as the initial technical overhead may be lower than creating a distributed application. 

## Monolith vs microservices
A microservice architecture is the polar opposite of a monolith, where each function of the application is contained within its own unit, which then offers APIs or functionality to other services. 

The advantage of microservice architecture is that each individual unit can be amended or scaled without needing to impact the rest of the program. This also makes deployment of changes easier as only the affected unit needs to be redeployed. 

However, the initial setup of a microservice based system can be more resource intensive.
