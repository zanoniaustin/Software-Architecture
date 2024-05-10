# ADR 2: C# as Primary Language
## Status
Accepted

## Background
Our organization is still small and looking for new hires. Using a language that is easier to learn and popular amoung developers is our main objective.

## Rationale 
Both C++ and C# are both very popular for languages for game development. C++ allows for a much more optimization and programming of operating systems for better control over the hardware, but for such a small game this level of fine tuning in not needed at this time. C# is easy to learn and widely used for the development in the Unity Gaming Engine. To utilize the scripting API within Unity C# will need to be used.

## Decision 
There are two languages supported for the Unity Game Engine during run time, C++ and C#. We will be using C# as the coding language for the Unity Gaming Engine.

## Consequences
Potential slower run time as C# uses the CLR(common language runtime). Automatic garbage collection. 

## Future
Continue looking into customer feedback based on needing to optimize any part of our game to see if that warrents looking into the use of C++.
