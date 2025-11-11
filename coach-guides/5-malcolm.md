# Malcolm Case Study: Coach Guide

## Key Management Learnings

### 1. Post-Acquisition Integration Requires Intentional Management
**Core Learning:** Acquisitions don't automatically integrate. Technical talent needs structured onboarding, relationship building, and explicit inclusion in decision-making.

**What Students Should Understand:**
- Acquired teams often feel like outsiders and may be treated as such
- Without intentional integration, silos form quickly and persist
- The acquiring team's "busyness" is not an excuse for isolation
- Early integration investments prevent costly problems later

**Key Insight:** Malcolm's decision to let Apex work independently on Flash while Acme was "busy" created the conditions for this crisis. Successful integration requires dedicated time and attention.

### 2. Trust is Built Through Action, Not Just Words
**Core Learning:** Leaders must actively demonstrate trust through involvement, consultation, and collaboration—not just delegation without support.

**What Students Should Understand:**
- Hoshi perceives bringing in Trip as "lack of trust" because Malcolm hasn't built sufficient trust foundation
- Trip wants "full authority" because he may not trust Hoshi will accept his input
- Trust deficits cannot be solved in crisis moments
- Autonomy without support can feel like abandonment

**Key Insight:** Malcolm gave Hoshi responsibility but perhaps not sufficient resources, mentorship, or integration support. Now interventions feel punitive rather than supportive.

### 3. Technical Decisions Have Organizational Consequences
**Core Learning:** Who makes technical decisions, how those decisions are made, and who is involved sends powerful messages about organizational values.

**What Students Should Understand:**
- Giving Trip "full authority" disempowers Hoshi and reinforces acquisition hierarchy
- Leaving it entirely with Hoshi risks prolonging customer pain
- The way conflicts are resolved teaches the organization how future conflicts will be handled
- Process matters as much as outcome

**Key Insight:** Malcolm needs to design a resolution process that both fixes the bug AND builds organizational capability.

### 4. Conflict Often Signals Systemic Issues
**Core Learning:** Interpersonal conflict is frequently a symptom of structural problems—unclear roles, poor processes, insufficient communication, or misaligned incentives.

**What Students Should Understand:**
- The Hoshi-Trip conflict isn't "just personalities"
- Missing: clear technical review processes, cross-team collaboration norms, integration ownership
- The conflict reveals gaps in engineering practices
- Solving only the interpersonal issue leaves structural vulnerabilities

**Key Insight:** A strong engineering organization would have mechanisms to prevent this: architecture review involving both teams, pair programming across teams, shared ownership of critical components.

### 5. Crisis Management Requires Balancing Competing Priorities
**Core Learning:** Engineering leaders must simultaneously address immediate customer needs, team dynamics, individual career development, and long-term organizational health.

**What Students Should Understand:**
- No single decision optimizes all dimensions
- Customer urgency doesn't excuse damaging team relationships
- Preserving morale doesn't justify prolonged customer pain
- Best solutions often involve creative combinations

**Key Insight:** Malcolm's challenge is not "Trip or Hoshi?" but "How do I resolve this crisis while strengthening the team and improving our systems?"

### 6. Prevention Through Systems is Better Than Heroic Intervention
**Core Learning:** Mature engineering organizations build systems that prevent crises rather than relying on individual heroics to resolve them.

**What Students Should Understand:**
- The "burned both ends of the candle" achievement masked underlying problems
- Lack of testing, staging environments, or gradual rollout allowed catastrophic failure
- Missing collaboration during development created knowledge silos
- Process gaps forced this to become a crisis requiring Malcolm's intervention

**Key Insight:** Malcolm should ask "How do I build a system where this type of crisis becomes impossible?" not just "How do I solve this particular crisis?"

### 7. Leaders Must Own Their Past Decisions
**Core Learning:** Current problems often stem from past leadership decisions. Effective leaders acknowledge their role and adjust course.

**What Students Should Understand:**
- Malcolm recommended the Apex acquisition
- Malcolm allowed Flash development to proceed in isolation
- Malcolm didn't ensure adequate integration
- Taking ownership enables better future decisions

**Key Insight:** The case prompts "What should Malcolm change if he could go back?" This reflection is valuable for extracting lessons that inform future decisions.

### 8. Communication Style Shapes Team Culture
**Core Learning:** How a leader communicates during conflict resolution sets expectations for feedback, collaboration, and psychological safety.

**What Students Should Understand:**
- What Malcolm says to Hoshi will be interpreted by the entire organization
- Communication should preserve dignity while addressing reality
- Different stakeholders need different messages
- Transparency about decision-making process builds trust

**Key Insight:** Students should practice crafting actual messages Malcolm might send, considering tone, content, and timing.

---

## Facilitation Overview

### Session Structure (60-75 minutes)
1. Introduction (5 min)
2. Initial Perspectives (10-15 min)
3. Stakeholder Deep Dive (15-20 min)
4. Options Analysis (15-20 min)
5. Systems Thinking (10-15 min)
6. Synthesis and Takeaways (10 min)

---

## Opening the Discussion

**Suggested Opening:**
"This case presents Malcolm with a situation where multiple stakeholders have legitimate concerns. Let's practice holding multiple perspectives simultaneously—there's no single 'right' answer, but some approaches are better than others."

**Initial Poll:** Give Trip full authority / Keep it with Hoshi / Another approach

---

## Discussion Flow

### Phase 1: Understanding Perspectives (15-20 min)

**Prompt:** "Let's understand each stakeholder's perspective. What does the situation look like from Hoshi's point of view?"

**Hoshi's Perspective:**
- Feels isolated and unsupported since acquisition
- Worked hard and now feels criticized
- Bringing in Trip feels like lack of trust

**Trip's Perspective:**
- Doesn't want to be blamed if fix doesn't work
- May have seen his original design compromised
- Wants authority to restore what he knows

**Malcolm's Perspective:**
- Customer crisis demands urgent response
- Must balance short-term (fix bug) and long-term (team health)
- Decisions set precedents for future conflicts

**Critical Question:** "What precedents might Malcolm's decision set?"

### Phase 2: Binary Options Analysis (10-15 min)

**Prompt:** "Let's examine the two obvious options: giving Trip full authority or keeping it with Hoshi."

**Build Matrix:**

| Dimension | Give Trip Full Authority | Keep with Hoshi |
|-----------|-------------------------|-----------------|
| Customer Impact | Faster resolution likely | May take longer |
| Hoshi's Development | Disempowering, undermines trust | Learning opportunity |
| Trip's Engagement | Willing to help | May disengage |
| Team Dynamics | Reinforces acquisition hierarchy | Shows trust in Apex team |
| Organizational Learning | Doesn't build Apex capability | Builds long-term strength |

**Key Point:** Both binary options have significant downsides. This should motivate exploration of alternatives.

### Phase 3: Alternative Approaches (15-20 min)

**Prompt:** "What else could Malcolm do?"

**Alternative Approaches:**

**1. Joint Problem-Solving Team**
- Hoshi and Trip work together with clear roles
- Malcolm facilitates initial working session
- Shared ownership of solution

**2. Bring in Neutral Expert**
- Another senior engineer reviews code
- Fresh perspective without political baggage
- Both Hoshi and Trip save face

**3. Structured Code Review Process**
- Trip reviews and provides feedback
- Hoshi retains implementation authority
- Clear escalation path if disagreement persists

**4. Pair Programming / Collaboration Model**
- Trip and Hoshi pair on investigation
- Learn from each other's approaches
- Build relationship while solving problem

**For Each:** "How would Malcolm frame this? What could go wrong? What would this require to succeed?"

**Role-Play Exercise:** Have volunteers role-play Malcolm's conversation with Hoshi and Trip.

### Phase 4: Root Cause and Systems Thinking (10-15 min)

**Prompt:** "How did we get here? What allowed this situation to develop?"

**Build Root Cause Analysis:**

| Root Cause | What Could Have Prevented It |
|------------|------------------------------|
| Apex team working in isolation | Integrated team structure, pair programming across teams |
| Hoshi and Trip not collaborating early | Explicit requirement for original engineers to consult on changes |
| Critical bugs reaching production | Better testing infrastructure, gradual rollout |
| Lack of code review | Mandatory cross-team review for core components |
| Architectural decisions without input | Technical design authority or architecture review board |
| Trust deficit between teams | Intentional team-building, rotation programs, shared goals |

**Critical Discussion:** "The case asks about the 'shape of the team' afterward. What does that mean?"

**Answer:** Crisis resolution can damage long-term team health. "Winning" the immediate battle might lose the long-term war.

### Phase 5: Going Back in Time (10 min)

**Prompt:** "What should Malcolm change if he could go back?"

**Capture Key Learnings:**

**During Acquisition:**
- Plan for integration from day one
- Create cross-team mentorship programs
- Establish shared ownership of critical components

**During Flash Planning:**
- Require architecture review with original Carboni engineers
- Set up collaboration expectations explicitly
- Allocate time from Acme team despite priorities

**During Flash Development:**
- Regular check-ins between Hoshi and Trip
- Code review requirements for Gorilla changes
- Integration testing with realistic scenarios

**Key Learning:** "Notice how many are about systems, not just asking people to 'communicate better.' What does that tell us?"

**Answer:** Culture is shaped by systems. Relying on individuals to spontaneously collaborate is less effective than creating structures that make collaboration the default.

---

## Key Teaching Points

✓ Trust built through consistent action
✓ Process prevents problems
✓ Communication matters as much as decision
✓ Technical and people issues are intertwined
✓ Balance short-term and long-term thinking
✓ Conflict reveals systemic gaps

---

## Handling Difficult Moments

**If Students Blame Hoshi:**
"What incentives and experiences might have shaped Hoshi's reaction? What would help Hoshi respond differently in the future?"

**If Students Blame Trip:**
"What might Trip have learned from experience that makes this feel necessary? What would a healthy organization look like where Trip wouldn't need this protection?"

**If Discussion Gets Stuck on Binary Choice:**
"I'm noticing we keep coming back to 'Trip or Hoshi.' That might be a sign neither option is great. What would an ideal resolution look like?"

---

## Debrief

**Personal Application:** "Where do you see similar dynamics in your organization? What might you do differently?"

**Key Takeaways:** "If you could share one insight from today's discussion with a colleague, what would it be?"

---

## Common Pitfalls to Avoid

- Letting discussion become character assassination
- Accepting "They should just communicate better" as solution
- Ignoring power dynamics of acquisition
- Focusing only on immediate crisis
- Treating technical and people issues as separate
- Assuming there's a "right answer"

---

*Remember: Your role as facilitator is to guide discovery, not to provide "the answer." The best learning comes from students wrestling with complexity and articulating their own insights.*
