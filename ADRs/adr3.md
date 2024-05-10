# ADR 3: Microsoft PlayFab as Hosting Site

## Background
When it comes to where we are wanting our game to be hosted there are alot of things to consider. Scalability, are we able to handle large spikes in customers and small amounts while maximizing the financial requirements. Security, how well does the servers handle cyber attacks like DDoS attacks. Speed and simplicity of testing and deploying new versions.

## Rationale 
The two main cloud providers investigated were Amazon GameLift and Microsoft PlayFab. Both offer similar scalability in user base as well as similar pricing structures. Both offer high levels of security for handling cyber attacks as well as live monitoring tools. Simplicity is where they mainly differ. GameLift requires a much higher level of expertise when setting up, but does offer more control over the server management. PlayFab has a lower level of entry for expertise level, and very limited amount of control over the server management.

## Decision 
We will be using the Microsoft Play for hosting our game because it requires a lower level of expertise for entry which best supports our new company.

## Status
It is decided we will be using Microsoft PlayFab as our cloud servers for our game.

## Consequences
Vendor lock-in, integration of PlayFab is high so a swap away would require a very large amount of effort. Limited amount of customizing of the servers. 

## Future
Financial aspects will need to continue to be observed as PlayFab does offer a Plan payment which might make more sense financially at some point over pay-as-you-go.
