# Operating-Platforms
Repository for SNHU Operating platforms.  Where I will upload all the project information

 Briefly summarize The Gaming Room client and their software requirements.
The client, The Gaming Room, requested a web‑based version of their existing Android game Draw It or Lose It. The game is a fast‑paced, team‑based drawing and guessing competition that requires real‑time interaction. Their requirements included scalability to support many concurrent players, secure authentication, responsive cross‑platform access (mobile and desktop), and low‑latency communication to preserve the pace of gameplay.

What did you do particularly well in developing this documentation?
I did particularly well in balancing technical depth with accessibility. Each section of the design document includes both technical descriptions (for developers) and non‑technical explanations (for stakeholders). I also provided a clear tradeoff matrix and detailed recommendations, which demonstrate foresight into real‑world deployment challenges.

What about the process of working through a design document did you find helpful when developing the code?
Working through the design document forced me to think systematically before coding. By mapping out architecture, constraints, and tradeoffs, I had a clear blueprint for implementation. This reduced guesswork during development and helped ensure that the code aligned with both functional requirements and user experience goals.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would revise the Domain Model section. While it outlines the relationships between classes, I would strengthen it by adding a UML diagram and explicitly naming all classes (e.g., , , , ). This would make the design more concrete and easier for future developers to follow.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I interpreted the user’s needs by focusing on real‑time responsiveness, cross‑platform accessibility, and security—all of which were central to the client’s request. Considering user needs is critical because software succeeds only if it delivers value to its audience. A technically elegant system that ignores usability or performance expectations will fail to engage players.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I approached the design using a modular, client‑server mindset with distributed microservices. I relied on strategies such as tradeoff analysis, layered architecture views, and explicit mapping of requirements to design decisions. In the future, I would continue using these strategies, while also incorporating iterative prototyping and user feedback loops earlier in the process to validate assumptions before full implementation.
