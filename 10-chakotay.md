# Context

Acme Corp's Client Integration team, led by Chakotay, builds the connection layer that enables banks and financial institutions to integrate with CarboniChain. The team of seven engineers has deep expertise in financial protocols and compliance requirements. Over the past year, they've successfully delivered integrations for three major European banks, establishing Acme's reputation in the regulated finance sector.

Chakotay's team has just begun work on Meridian, an ambitious project to create a unified integration framework that will reduce the time to onboard new financial institutions from months to weeks. Success here could be transformative for Acme's growth trajectory. However, Meridian requires substantial changes to two core platform components owned by different teams: the identity service (owned by Paris's Platform Services team) and the transaction processing engine (owned by B'Elanna's Infrastructure team).

The challenge isn't technical capability - both teams have the skills needed. The issue is coordination. Paris's team operates on quarterly planning cycles aligned with enterprise customer commitments, and they've already committed their next quarter to scaling work for their largest customer. B'Elanna's team works in a more agile, interrupt-driven model, responding to production issues and optimization needs as they arise. Both teams are stretched thin and protective of their roadmaps.

Chakotay reached out early, six weeks ago, sharing Meridian's requirements and timelines. Paris responded that her team could slot the identity service work into Q2 next year - six months away. B'Elanna's team has been more responsive but keeps getting pulled away to handle production issues. They've started the transaction engine work three times now, each time having to pause for urgent infrastructure problems.

The situation has grown tense. In a recent architecture review meeting, when Chakotay pushed for committed delivery dates, Paris pointed out that Client Integration could have built their own identity solution instead of depending on Platform Services. B'Elanna suggested that if Meridian is so critical, maybe Chakotay's team should help with the infrastructure oncall rotation to free up her team's capacity. Chakotay felt both responses were reasonable but also missed the point - he's trying to avoid redundant work and leverage Acme's existing platform investments, which is exactly what leadership wants.

Meanwhile, Chakotay's team is growing frustrated. They've designed the framework and built what they can, but they're now blocked. Two engineers have started exploring workarounds that would bypass the platform components entirely, which Chakotay knows will create technical debt and undermine the unified platform vision that leadership has been pushing.

# Challenge

How can Chakotay navigate this cross-team coordination challenge to unblock Meridian while maintaining healthy relationships with Paris and B'Elanna's teams? What's the right balance between advocating forcefully for his team's needs and being respectful of other teams' constraints? And what systemic issues might be at play here that go beyond just this project?

# Discussion Prompts

- What are the underlying organizational or structural issues that might be contributing to this coordination challenge?
- How much of this is Chakotay's problem to solve versus something that requires intervention from leadership? At what point should he escalate?
- What are the trade-offs of the workaround approach his engineers are exploring? In what scenarios might it be the right choice?
- How might Chakotay approach Paris and B'Elanna differently given their teams' different operating models and constraints?
- What could Chakotay have done six weeks ago that might have prevented or mitigated this situation?
- If you were Paris or B'Elanna, what would make you more willing to prioritize Meridian's needs? What would make you defensive or resistant?
- What are some creative solutions beyond "get the other teams to commit to dates" or "build it ourselves"?
- How should Chakotay communicate with his own team about this situation? What should he tell them, and what should he shield them from?
- What systemic changes might help Acme avoid similar coordination challenges in the future?
