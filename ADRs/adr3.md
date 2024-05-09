# ADR 3: Amazon GameLift as Hosting Site
## Decision 
AWS is one of the leading cloud providers out there, we will be using the AWS service GameLift for hosting our game.

## Background
When it comes to where we are wanting our game to be hosted there are alot of things to consider. Scalability, are we able to handle large spikes in customers and small amounts while maximizing the financial requirements. Security, how well does the servers handle cyber attacks like DDoS attacks. Speed and simplicity of testing and deploying new versions.

## Rationale 
Amazon GameLift allows for the ability to quickly test versions in a developer environment, and deploy out new versions of the game quickly and with minimal disturbance to the users. This is one of the biggest deciding factors as this is our studios first titles and experimental at that. In the early stages our main focus will be on user feedback and improving our game quickly. Amazon GameLift allows for the ability to scale our game easily by bringing up or down servers as needed that will allow for the handling of spikes in players. Being an AWS service also provides that reliability that comes with being a game server provider since 2016.

## Status
It is decided we will be using Amazon GameLift as our cloud servers for our game.

## Consequences
The cost of pay-as-you-go of Amazon GameLift could add up depending on the growth of this game, so keeping an eye on the size of the player base will need to continue to be obsereved. Having to conform to any standards required from GameLift.
