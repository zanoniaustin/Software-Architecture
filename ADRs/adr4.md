# ADR 4: SQLLite Database
## Status
Accepted

## Background
We are looking for a type of database that is easy to setup and learn, is able to integrate efficiently with the Unity Gaming Engine, and is efficient for a small single player game that will mainly be storing the user's game data.

## Rationale 
Three types of databases were considered for this, NoSQL, MySQL, and SQLLite. The NoSQL database that Unity supports, Firebase, only works for mobile devices. The MySQL database is external from the Unity gaming engine, SQLLite is embedded into the Unity project itself making it more lightweight. MySQL does have a better ability at having more scalability compared to SQLLite. Integrating MySQL into Unity requires adding plugins and asset packages which will add to the complexity, and security will also need to be managed for the database servers by the team.

## Decision 
We will be moving forward using the SQLLite database for our game. The main reasons is the lightweight simplicity of SQLLite when integrating with the Unity Gaming Engine is better for engineers with less an experience level.

## Consequences
Version control of the database will be challenging since it is integrated into the Unity project. Simple integration of the database into the Unity project.
