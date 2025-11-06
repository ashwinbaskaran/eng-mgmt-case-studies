# Context
Acme Corp's Communications Infrastructure team, led by their manager Uhura, is responsible for the messaging systems that enable real-time notifications and data synchronization across the Carboni ecosystem. The team of seven engineers has deep expertise in distributed systems, message queues, and event-driven architectures. They maintain the critical MessageRelay service that processes millions of events per day for Acme's various products.

The Carboni team, led by Sulu, recently launched a major new feature that significantly increased message volume. Shortly after launch, customers began experiencing delayed notifications, some taking up to 30 minutes to arrive. The Carboni team quickly identified that MessageRelay was the bottleneck and filed a high-priority ticket asking the Communications Infrastructure team to "fix the performance issues."

Uhura's team investigated and discovered that the Carboni team's implementation was sending 10x more messages than expected, with many redundant or unnecessary events. The team had not followed the documented best practices for batching and filtering events before sending them to MessageRelay. When Uhura's team member Chekov commented on the ticket explaining this, the Carboni team responded defensively, saying the documentation was "unclear" and that MessageRelay should "just handle the load" since other services manage to scale better.

Meanwhile, the Banks team has been waiting three months for the Communications Infrastructure team to prioritize an integration project that would enable real-time notifications for their central bank partners. Pavel, the tech lead on the Banks team, has grown increasingly frustrated with what he perceives as slow response times and lack of engagement from Uhura's team. He's started building a custom notification solution rather than waiting, which concerns Uhura because it will fragment Acme's messaging infrastructure.

# Challenge
Uhura finds herself in the middle of multiple communication breakdowns. The Carboni team sees her team as a bottleneck that needs to "just scale better." The Banks team has given up on collaboration and is building around her team. Her own team members feel defensive and underappreciated, spending time handling urgent issues rather than planned work. Leadership is asking why there are suddenly so many messaging-related escalations.

Uhura knows these are symptoms of deeper communication issues, but she's not sure where to start. How can she rebuild trust, establish better collaboration patterns, and prevent these situations from recurring?

# Discussion Prompts
- What communication patterns or processes might have prevented these situations from arising?
- How should Uhura approach the immediate crisis with the Carboni team? What needs to be communicated to whom, and in what order?
- What might have led to the Banks team building their own solution rather than working with Communications Infrastructure? How should Uhura address this?
- Is this primarily a people problem, a process problem, or a technical problem? How does the answer influence the solution?
- What role should documentation play in cross-team collaboration? What are its limitations?
- How might Uhura's team need to change how they work with other teams? What about how other teams work with them?
- What organizational structures or practices could help prevent communication breakdowns between teams?
- How should Uhura communicate the situation to leadership? What support might she need from them?
