# Context

T'Pol recently became the engineering manager for Acme Corp's Security and Compliance team after the previous manager, Archer, left the company to start his own venture. The team of six engineers is responsible for critical security infrastructure, compliance monitoring, and audit systems that enable Acme to operate in highly regulated markets. The stakes are high - any security incident or compliance failure could result in significant regulatory penalties, loss of banking partnerships, or worse.

In her first few weeks, T'Pol has discovered a concerning pattern. Much of the team's critical knowledge exists only in the heads of a few engineers, particularly Phlox, who has been with Acme since the beginning and architected most of the security systems. When T'Pol asked for documentation on the compliance monitoring system's architecture, she was directed to a two-year-old wiki page that no longer reflects reality and a sprawling Slack thread from last year. The actual implementation has evolved significantly through numerous undocumented changes.

The knowledge concentration goes deeper than just documentation. Phlox is the only person who fully understands the encryption key management system. Reed is the sole expert on the audit trail implementation that regulators scrutinize. Travis owns all knowledge about the integration with external compliance vendors. While each engineer is happy to answer questions from teammates, the reality is that certain complex tasks can only be completed by specific people. This became painfully apparent last week when Reed was on vacation and the team discovered a critical issue with audit trail accuracy - they had to wait three days for Reed to return before they could properly diagnose and fix it.

The team culture has historically been one of individual ownership and expertise. Engineers take pride in being the "go-to person" for their domains. When T'Pol suggested pairing or mob programming as a way to spread knowledge, the response was mixed. Phlox argued that pairing would slow down development and that "knowledge transfer happens naturally through code reviews." Travis pointed out that their work is so specialized that it takes significant time for someone to build enough context to be useful, so pairing might mean two people working at half speed rather than one person at full speed.

The situation has become more urgent. Phlox mentioned casually in a 1:1 that he's been at Acme for four years and is thinking about what's next in his career. He's not actively looking, but he's open to interesting opportunities. T'Pol realizes that if Phlox leaves, the team would face a serious crisis - not just losing his deep expertise, but potentially being unable to maintain or modify critical security systems for months until someone else could ramp up.

T'Pol proposed dedicating 20% of sprint capacity to documentation and knowledge sharing efforts. The team's reaction was lukewarm. They don't disagree that better documentation would be valuable, but they're already stretched thin with ongoing security improvements and compliance requirements. Malcolm, the Head of Engineering, has made it clear that Acme cannot afford any slip in the team's delivery - they're in the middle of SOC 2 Type II certification and have committed timelines to several banking partners for new security features.

# Challenge

How can T'Pol address the knowledge concentration and bus factor risks in her team while respecting the immediate delivery pressures and the existing team culture? What's the right balance between documentation efforts and feature delivery? And how can she create sustainable knowledge-sharing practices that actually work rather than just creating more process overhead?

# Discussion Prompts

- What are the actual risks T'Pol is facing? How should she prioritize them?
- Is the 20% sprint capacity for documentation the right approach, or are there better ways to tackle knowledge transfer?
- How should T'Pol approach the team's cultural resistance to pairing and knowledge sharing? Is their skepticism valid?
- What should T'Pol do about the Phlox situation specifically? Should she try to retain him, plan for his departure, or both?
- Beyond documentation, what other mechanisms could help address knowledge concentration?
- How might different types of knowledge (architectural decisions, operational procedures, business context, code-level details) require different transfer approaches?
- What role should T'Pol play in forcing knowledge distribution versus letting the team self-organize solutions?
- If Phlox does leave, what would "good" preparation look like? What about if he stays?
- How can T'Pol make the case to Malcolm that some investment in knowledge transfer is necessary without it sounding like she's making excuses for slower delivery?
- What are some quick wins T'Pol could achieve to build momentum toward better knowledge sharing practices?
