Reflection

Client Summary and Software Requirements

The client for this project was The Gaming Room, a company that previously developed an Android-based game called Draw It or Lose It. They wanted to expand their game into a web-based application capable of running across multiple platforms. Their primary requirements included supporting multiple concurrent games, multiple teams per game, and multiple players per team. They also required unique naming for games and teams, unique identifiers for all entities, and a system design that ensured only one instance of the game service existed in memory at any given time.

The goal was to create a scalable, maintainable, and platform-independent design that could support distributed access and future expansion.

What I Did Well

One of the strongest aspects of my documentation was clearly organizing the system architecture and domain model. I effectively explained how object-oriented principles such as inheritance, encapsulation, and abstraction were applied within the design. The use of the Singleton and Iterator design patterns was well justified and directly aligned with the client’s requirements.

I also believe I did well in evaluating operating platforms (Linux, Mac, Windows, and mobile devices) and making a clear recommendation based on cost, scalability, and performance considerations.

How the Design Document Helped Development

Working through the design document before coding was extremely helpful. It forced me to think about the structure of the application before implementation. By defining the domain model and relationships between Game, Team, Player, and GameService early on, I avoided confusion later in development.

The design document also clarified constraints such as enforcing unique names and maintaining a single instance of the service. Because these requirements were defined upfront, implementing them in code became much more straightforward. Overall, the design phase reduced trial-and-error coding and improved organization.

What I Would Revise

If I could revise one part of my work, I would expand the system architecture section to include a more detailed diagram and explanation of how components interact in a distributed web environment. While the logical multi-tier description is clear, adding a visual representation or more detailed breakdown of client-server communication would strengthen the document.

I would also refine certain explanations to be slightly more client-focused rather than technical, ensuring the document communicates equally well to both stakeholders and developers.

Interpreting User Needs

I interpreted the user’s needs by carefully analyzing both the functional requirements (multiple games, teams, players, unique names) and nonfunctional requirements (scalability, performance, maintainability, and platform independence). These needs were implemented into the design through object-oriented architecture and design patterns.

Considering the user’s needs is critical because software ultimately exists to solve real-world problems. If the design does not align with business goals and user expectations, even technically correct software can fail. Designing with the user in mind ensures usability, scalability, and long-term success.

My Approach to Designing Software

My approach to designing this software began with identifying core entities and their relationships. I focused on modeling real-world relationships first, then applied object-oriented principles to structure the solution. I selected design patterns (Singleton and Iterator) specifically to address system constraints and enforce rules.

In the future, I would continue using domain modeling, UML diagrams, and design patterns as foundational strategies. I would also incorporate additional techniques such as:

Creating more detailed architectural diagrams
Considering cloud-native design patterns
Performing early scalability analysis
Including security threat modeling during initial planning
These strategies would help ensure that future applications are robust, secure, and adaptable to growth.
