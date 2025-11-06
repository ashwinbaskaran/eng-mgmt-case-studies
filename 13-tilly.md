# Context

Tilly manages the Developer Experience team at Acme Corp, a group of six engineers focused on building internal tools and platforms that make other engineering teams more productive. Four months ago, the team kicked off Velocity, an ambitious project to create an integrated development environment tailored for CarboniChain development. The vision was clear: reduce the time it takes for engineers to set up local environments, run tests, and deploy changes from hours to minutes.

The initial project scope, documented in a detailed specification, included: standardized development containers, a CLI tool for common workflows, integration with Acme's CI/CD pipeline, and comprehensive documentation. The timeline was aggressive but achievable - six months to initial launch with a pilot team, then iterative improvements based on feedback. Leadership was excited about Velocity's potential impact on engineering productivity across the company.

Four months in, the project is three months behind schedule, and the scope has expanded significantly. Here's what happened:

During early user research with pilot teams, Chakotay's Client Integration team mentioned they need special database seeding tools for their financial compliance workflows. The request made sense - they're a key stakeholder, and database setup is a major pain point for them. Tilly's team estimated two weeks of work and added it to Velocity.

Then B'Elanna's Infrastructure team asked for integration with their observability stack so engineers could access production metrics during local development. It seemed aligned with Velocity's mission of improving developer experience, so the team said yes - another two weeks.

The Platform Services team needed support for running multiple microservices simultaneously in local environments. The Security team wanted secrets management integration. The Data team requested support for their specific data pipeline testing needs. Each request individually seemed reasonable, well-justified, and relatively scoped. Each time, Tilly and her team said yes.

Now, the original core features are only 70% complete, but Velocity has accumulated an additional eight weeks of committed work across these various integrations. The team is feeling the pressure. In a recent retrospective, Adira mentioned feeling frustrated that they keep "starting new things before finishing what we began." Hugh expressed concern that they're building a "Frankenstein tool" that tries to be everything to everyone rather than doing the core functionality exceptionally well.

Meanwhile, stakeholder expectations have grown. At last week's engineering all-hands, Malcolm mentioned Velocity as a key initiative that would "transform how we build software at Acme." Several teams are now waiting for Velocity to launch before starting major projects. The pilot teams who contributed requirements are asking when "their features" will be ready. The pressure to deliver is mounting.

Tilly realizes she's lost control of the scope, but she's not sure how it happened or how to fix it. Each individual decision to expand scope seemed right at the time - Acme values being customer-focused and responsive to internal teams' needs. The requests all came from legitimate use cases. Nobody was asking for frivolous features. Yet somehow, the project spiraled from achievable to overwhelming.

When Tilly mentioned potentially descoping some features, Stamets (the team's tech lead) argued that they've already committed to other teams and backing out now would damage trust. Ruth countered that if they don't focus, they'll deliver something mediocre late rather than something great on time. The team is divided on the path forward.

# Challenge

How can Tilly get Velocity back on track? Should she descope features, extend timelines, ask for more resources, or something else entirely? How does she rebuild clear boundaries around scope while maintaining good relationships with stakeholder teams? And what should Tilly change about how she manages projects to avoid this situation in the future?

# Discussion Prompts

- What went wrong in Tilly's decision-making process? Were there specific moments where different decisions could have prevented scope creep?
- How should Tilly prioritize among the various stakeholder requests? What criteria should she use?
- What are the trade-offs between descoping features, extending timelines, or adding resources? Which approach makes most sense here?
- How should Tilly communicate changes to stakeholder teams, especially those whose requests might get cut? What does she owe them?
- Is Stamets right that backing out of commitments would damage trust, or is Ruth right that focus is more important? How can Tilly navigate this team disagreement?
- What role did the "customer-focused" culture at Acme play in this situation? Is that culture a problem or just misapplied?
- How could Tilly have structured the project differently at the beginning to prevent or manage scope expansion?
- What should Tilly tell Malcolm and leadership about Velocity's status? How much detail is appropriate?
- Beyond this specific project, what processes or practices could help Tilly's team better manage scope in future projects?
- If you were one of the stakeholder teams whose feature might get cut, what would you want from Tilly? What would help you understand and accept that decision?
