# Malcolm Case Study: Coach Guide

## Key Management Learnings

This section outlines the critical management concepts and skills that students should develop through discussion of this case study.

### 1. **Post-Acquisition Integration Requires Intentional Management**

**Core Learning:** Acquisitions don't automatically integrate. Technical talent needs structured onboarding, relationship building, and explicit inclusion in decision-making processes.

**What Students Should Understand:**
- Acquired teams often feel like outsiders and may be treated as such
- Without intentional integration, silos form quickly and persist
- The acquiring team's "busyness" is not an excuse for isolation
- Early integration investments prevent costly problems later

**Key Insight:** Malcolm's decision to let Apex work independently on Flash while Acme was "busy" created the conditions for this crisis. Successful integration requires dedicated time and attention, even when resources are stretched.

---

### 2. **Trust is Built Through Action, Not Just Words**

**Core Learning:** Leaders must actively demonstrate trust through involvement, consultation, and collaboration—not just delegation without support.

**What Students Should Understand:**
- Hoshi perceives bringing in Trip as "lack of trust" because Malcolm hasn't built sufficient trust foundation
- Trip wants "full authority" because he may not trust that Hoshi will accept his input
- Trust deficits cannot be solved in crisis moments; they require ongoing relationship building
- Autonomy without support can feel like abandonment

**Key Insight:** The trust problem existed before the crisis. Malcolm gave Hoshi responsibility but perhaps not sufficient resources, mentorship, or integration support. Now in a crisis, interventions feel punitive rather than supportive.

---

### 3. **Technical Decisions Have Organizational Consequences**

**Core Learning:** Who makes technical decisions, how those decisions are made, and who is involved sends powerful messages about organizational values and power dynamics.

**What Students Should Understand:**
- Giving Trip "full authority" disempowers Hoshi and reinforces acquisition hierarchy
- Leaving it entirely with Hoshi risks prolonging customer pain and missing expertise
- The way conflicts are resolved teaches the organization how future conflicts will be handled
- Process matters as much as outcome

**Key Insight:** Malcolm needs to design a resolution process that both fixes the bug AND builds organizational capability. The "how" matters as much as the "what."

---

### 4. **Conflict Often Signals Systemic Issues**

**Core Learning:** Interpersonal conflict is frequently a symptom of structural problems—unclear roles, poor processes, insufficient communication channels, or misaligned incentives.

**What Students Should Understand:**
- The Hoshi-Trip conflict isn't "just personalities"
- Missing: clear technical review processes, cross-team collaboration norms, integration ownership
- The conflict reveals gaps in engineering practices that will cause future problems
- Solving only the interpersonal issue leaves structural vulnerabilities in place

**Key Insight:** A strong engineering organization would have mechanisms to prevent this scenario: architecture review involving both teams, pair programming across teams, shared ownership of critical components, or technical design authority that transcends team boundaries.

---

### 5. **Crisis Management Requires Balancing Competing Priorities**

**Core Learning:** Engineering leaders must simultaneously address immediate customer needs, team dynamics, individual career development, and long-term organizational health.

**What Students Should Understand:**
- No single decision optimizes all dimensions
- Customer urgency doesn't excuse damaging team relationships
- Preserving team morale doesn't justify prolonged customer pain
- The best solutions often involve creative combinations, not binary choices

**Key Insight:** Malcolm's challenge is not "Trip or Hoshi?" but "How do I resolve this crisis while strengthening the team and improving our systems?"

---

### 6. **Prevention Through Systems is Better Than Heroic Intervention**

**Core Learning:** Mature engineering organizations build systems that prevent crises rather than relying on individual heroics to resolve them.

**What Students Should Understand:**
- The "burned both ends of the candle" achievement masked underlying problems
- Lack of automated testing, staging environments, or gradual rollout allowed catastrophic failure
- Missing collaboration during development created knowledge silos
- Process gaps forced this to become a crisis requiring Malcolm's intervention

**Key Insight:** Malcolm should be asking "How do I build a system where this type of crisis becomes impossible?" not just "How do I solve this particular crisis?"

---

### 7. **Leaders Must Own Their Past Decisions**

**Core Learning:** Current problems often stem from past leadership decisions. Effective leaders acknowledge their role and adjust course.

**What Students Should Understand:**
- Malcolm recommended the Apex acquisition
- Malcolm allowed Flash development to proceed in isolation
- Malcolm didn't ensure adequate integration between teams
- Taking ownership enables better future decisions

**Key Insight:** The case prompts "What should Malcolm change if he could go back in time?" This reflection is valuable not for self-blame but for extracting lessons that inform future decisions about team structure, project oversight, and acquisition integration.

---

### 8. **Communication Style Shapes Team Culture**

**Core Learning:** How a leader communicates during conflict resolution sets expectations for feedback, collaboration, and psychological safety.

**What Students Should Understand:**
- What Malcolm says to Hoshi will be interpreted by the entire organization
- Communication should preserve dignity while addressing reality
- Different stakeholders need different messages tailored to their concerns
- Transparency about decision-making process builds trust

**Key Insight:** Students should practice crafting actual messages Malcolm might send, considering tone, content, and timing for different scenarios.

---

## Facilitation Overview

### Session Structure (Recommended: 60-75 minutes)

1. **Introduction** (5 min)
   - Frame the case and learning objectives
   - Set discussion norms

2. **Initial Perspectives** (10-15 min)
   - Quick poll: What should Malcolm do?
   - Surface initial reasoning

3. **Stakeholder Deep Dive** (15-20 min)
   - Explore perspectives of Hoshi, Trip, and Malcolm
   - Use role-play or perspective-taking exercises

4. **Options Analysis** (15-20 min)
   - Examine multiple approaches beyond binary choice
   - Pressure-test assumptions

5. **Systems Thinking** (10-15 min)
   - Root cause analysis
   - Prevention and process improvements

6. **Synthesis and Takeaways** (10 min)
   - Key learnings
   - Application to students' contexts

---

## Facilitation Guide

### Opening the Discussion

**Goal:** Create psychological safety and surface initial thinking

**Suggested Opening:**
> "This case presents Malcolm with a difficult situation where multiple stakeholders have legitimate concerns. As we discuss, I want us to practice holding multiple perspectives simultaneously—there's no single 'right' answer, but some approaches are better than others. Let's start by understanding what Malcolm is facing."

**Initial Poll (Anonymous or Show of Hands):**
- Give Trip full authority
- Keep it with Hoshi
- Another approach

*Note the distribution but don't judge responses. Use diversity of opinion as evidence that this is genuinely difficult.*

---

### Discussion Flow

#### Phase 1: Understanding Perspectives (15-20 min)

**Prompt:** "Let's start by understanding each stakeholder's perspective. What does the situation look like from Hoshi's point of view?"

**Guided Questions:**
- "What has Hoshi's experience been since the acquisition?"
- "Why might Hoshi interpret bringing in Trip as a lack of trust?"
- "What does Hoshi need from Malcolm right now?"

**Common Student Responses to Listen For:**
- ✓ "Hoshi feels isolated and unsupported"
- ✓ "Hoshi worked really hard and now feels criticized"
- ✗ "Hoshi is being defensive and unprofessional"
  - *If this comes up:* "What might explain that defensiveness? What context might we be missing?"

**Prompt:** "Now let's consider Trip's perspective. Why does Trip want full authority before helping?"

**Guided Questions:**
- "What concerns might Trip have based on past experience?"
- "Is Trip's position reasonable? Why or why not?"
- "What might Trip be trying to protect—technically and personally?"

**Common Student Responses to Listen For:**
- ✓ "Trip doesn't want to be blamed if the fix doesn't work"
- ✓ "Trip may have seen his original design compromised and wants to restore it"
- ✗ "Trip is being territorial and unhelpful"
  - *If this comes up:* "What system would make Trip feel safe contributing without demanding full control?"

**Prompt:** "Finally, Malcolm's perspective. What pressures is he facing?"

**Guided Questions:**
- "Who are Malcolm's stakeholders in this situation?"
- "What are the short-term vs. long-term considerations?"
- "What precedents might Malcolm's decision set?"

---

#### Phase 2: Binary Options Analysis (10-15 min)

**Prompt:** "Let's carefully examine the two most obvious options: giving Trip full authority or keeping it with Hoshi."

**Use a T-Chart or Matrix on Whiteboard/Virtual Board:**

| Dimension | Give Trip Full Authority | Keep with Hoshi |
|-----------|-------------------------|-----------------|
| Customer Impact | | |
| Hoshi's Development | | |
| Trip's Engagement | | |
| Team Dynamics | | |
| Organizational Learning | | |

**Guided Questions:**
- "If Malcolm gives Trip full authority, what message does that send?"
- "What are the risks of each approach?"
- "Are there ways to mitigate the downsides of either option?"

**Key Point to Surface:**
Both binary options have significant downsides. This should motivate exploration of alternatives.

---

#### Phase 3: Alternative Approaches (15-20 min)

**Prompt:** "We've identified problems with both obvious options. What else could Malcolm do?"

**Facilitation Technique:** If students struggle, offer scaffolding:
- "What if Malcolm brought both Hoshi and Trip together?"
- "What if Malcolm involved a third party?"
- "What if Malcolm changed the structure of the work?"

**Alternative Approaches Students Might Suggest:**

1. **Joint Problem-Solving Team**
   - Hoshi and Trip work together with clear roles
   - Malcolm facilitates initial working session
   - Shared ownership of solution

2. **Bring in Neutral Expert**
   - Another senior engineer reviews code
   - Fresh perspective without political baggage
   - Opportunity for both Hoshi and Trip to save face

3. **Structured Code Review Process**
   - Trip reviews and provides feedback
   - Hoshi retains implementation authority
   - Clear escalation path if disagreement persists

4. **Pair Programming / Collaboration Model**
   - Trip and Hoshi pair on the investigation
   - Learn from each other's approaches
   - Build relationship while solving problem

**For Each Alternative, Push Students to Consider:**
- "How would Malcolm frame this to Hoshi?"
- "What could go wrong with this approach?"
- "What would this require from Malcolm to succeed?"

**Role-Play Exercise (Optional but Powerful):**
Ask for volunteers to role-play Malcolm's conversation with:
1. Hoshi (explaining whatever decision is made)
2. Trip (explaining whatever decision is made)

This forces students to translate strategic thinking into actual communication.

---

#### Phase 4: Root Cause and Systems Thinking (10-15 min)

**Prompt:** "We've focused on resolving the immediate crisis. But how did we get here? What allowed this situation to develop?"

**Guided Questions:**
- "What happened during the acquisition integration?"
- "What was missing during Flash development?"
- "What systems or processes could have prevented this?"

**Key Issues to Surface:**

| **Root Cause** | **What Could Have Prevented It** |
|----------------|----------------------------------|
| Apex team working in isolation | Integrated team structure, pair programming across teams, joint architecture review |
| Hoshi and Trip not collaborating early | Explicit requirement for original engineers to consult on changes to their components |
| Critical bugs reaching production | Better testing infrastructure, gradual rollout, staging environments |
| Lack of code review | Mandatory cross-team review for core components |
| Architectural decisions without adequate input | Technical design authority or architecture review board |
| Trust deficit between teams | Intentional team-building, rotation programs, shared goals |

**Critical Discussion Point:**
"The case says the problem will 'eventually be resolved' and asks about the 'shape of the team' afterward. What does that mean?"

**What to Listen For:**
- Understanding that crisis resolution can damage long-term team health
- Recognition that "winning" the immediate battle might lose the long-term war
- Awareness that rushed solutions often create technical debt and resentment

---

#### Phase 5: Going Back in Time (10 min)

**Prompt:** "The case asks: What should Malcolm change if he could go back in time? Let's create that list."

**Capture Student Suggestions:**

**During Acquisition:**
- [ ] Plan for integration from day one
- [ ] Create cross-team mentorship programs
- [ ] Establish shared ownership of critical components

**During Flash Planning:**
- [ ] Require architecture review with original Carboni engineers
- [ ] Set up collaboration expectations explicitly
- [ ] Allocate time from Acme team despite other priorities

**During Flash Development:**
- [ ] Regular check-ins between Hoshi and Trip
- [ ] Code review requirements for Gorilla changes
- [ ] Integration testing with realistic scenarios

**During Flash Testing/Launch:**
- [ ] More rigorous testing before launch
- [ ] Gradual rollout to catch issues early
- [ ] Better incident response planning

**Key Learning:**
"Notice how many of these are about systems and processes, not just asking people to 'communicate better' or 'be more collaborative.' What does that tell us?"

**Answer to Draw Out:** Culture is shaped by systems. Relying on individuals to spontaneously collaborate is less effective than creating structures that make collaboration the default.

---

### Handling Difficult Moments

#### If Discussion Becomes Personal/Judgmental

**If students blame Hoshi:**
> "I notice we're using strong language about Hoshi's response. Let's pause and ask: What incentives and experiences might have shaped Hoshi's reaction? What would help Hoshi respond differently in the future?"

**If students blame Trip:**
> "Trip's demand for 'full authority' sounds rigid. But what might Trip have learned from experience that makes this feel necessary? What would a healthy organization look like where Trip wouldn't need this protection?"

**If students blame Malcolm:**
> "It's easy to see Malcolm's mistakes in hindsight. What pressures might Malcolm have faced that made these choices seem reasonable at the time? What can we learn that helps us avoid similar situations?"

#### If Discussion Gets Stuck on Binary Choice

**Intervention:**
> "I'm noticing we keep coming back to 'Trip or Hoshi.' That might be a sign that neither option is great. What if we set aside both of those for a moment and asked: What would an ideal resolution look like? What would serve all the stakeholders?"

#### If Students Avoid the People Issues

**Intervention:**
> "We've done a great job analyzing the technical issues. But this case has a subtitle that's implied: 'How do you lead people through technical crises?' What are we learning about the human side of engineering leadership?"

#### If Discussion is Too Abstract

**Intervention:**
> "Let's get concrete. Someone draft the email or Slack message Malcolm should send to Hoshi. What would you actually say?"

---

## Key Teaching Points to Ensure Coverage

Make sure these concepts emerge during discussion:

### ✓ **Trust is built through consistent action**
- Trust isn't automatic after acquisition
- Delegation without support erodes trust
- Crisis intervention is harder when trust foundation is weak

### ✓ **Process prevents problems**
- Heroic individual effort is not a sustainable model
- Systems thinking prevents future crises
- Good process makes the right thing easy

### ✓ **Communication matters as much as decision**
- How Malcolm explains his decision shapes team culture
- Different stakeholders need different messages
- Transparency builds trust even in difficult situations

### ✓ **Technical and people issues are intertwined**
- Can't solve technical problem by ignoring people dynamics
- Can't solve people problem by ignoring technical realities
- Best solutions address both simultaneously

### ✓ **Short-term and long-term thinking are both necessary**
- Customer crisis demands urgent response
- Team health requires long-term investment
- Great leaders balance both

### ✓ **Conflict reveals systemic gaps**
- Interpersonal conflict often signals missing structure
- Resolving only the personal issue leaves vulnerabilities
- Use conflict as diagnostic information

---

## Debrief and Synthesis (10 min)

### Closing Questions

**Personal Application:**
> "Think about your own organization or experiences. Where do you see similar dynamics? What might you do differently now based on this discussion?"

**Key Takeaways:**
> "If you could share one insight from today's discussion with a colleague who wasn't here, what would it be?"

**Commitment to Action:**
> "What's one specific thing you'll do differently as a result of this conversation?"

---

## Common Pitfalls to Avoid

### ❌ **Letting Discussion Become Character Assassination**
Students may want to blame Hoshi as "defensive," Trip as "territorial," or Malcolm as "weak." Redirect to systems and incentives.

### ❌ **Accepting "They Should Just Communicate Better" as Solution**
This is too vague. Push for: "What specific structure or process would enable better communication?"

### ❌ **Ignoring Power Dynamics**
Acquisition creates power imbalances. Apex team is vulnerable. These dynamics shape behavior.

### ❌ **Focusing Only on Immediate Crisis**
The case explicitly asks about long-term team health. Make sure discussion addresses this.

### ❌ **Treating Technical and People Issues as Separate**
They're deeply intertwined in this case. Integration requires addressing both.

### ❌ **Assuming There's a "Right Answer"**
Multiple thoughtful approaches could work. The reasoning matters more than the specific choice.

---

## Extended Discussion Topics (If Time Allows)

### Topic: Acquisition Integration Best Practices
- "What have you seen work well in company acquisitions?"
- "What makes technical talent integration especially challenging?"

### Topic: Code Ownership Models
- "How should organizations handle ownership of critical components?"
- "What are alternatives to individual code ownership?"

### Topic: Psychological Safety in Engineering
- "What would psychological safety look like in this situation?"
- "How do leaders build safety during technical crises?"

### Topic: When to Intervene as a Leader
- "How does Malcolm know when to step in vs. let teams work it out?"
- "What signals indicate a situation needs leadership intervention?"

---

## Assessment: What Good Discussion Looks Like

Students are learning well if they:

- ✅ Consider multiple stakeholder perspectives simultaneously
- ✅ Identify systemic issues beyond individual behavior
- ✅ Propose solutions that address both technical and people dimensions
- ✅ Acknowledge tradeoffs rather than claiming perfect solutions
- ✅ Connect case to their own experiences
- ✅ Ask thoughtful questions of each other
- ✅ Build on others' ideas rather than just advocating their own
- ✅ Show empathy for all parties involved
- ✅ Think about prevention, not just resolution

---

## Follow-Up Activities (Optional)

### Writing Exercise
Ask students to write:
1. The message Malcolm should send to Hoshi (150 words)
2. The message Malcolm should send to Trip (150 words)
3. A brief retro doc Malcolm should create for the engineering team about lessons learned (300 words)

### Small Group Work
Divide into groups:
- Group A: You are Malcolm's leadership coach. What advice do you give him?
- Group B: You are Hoshi's mentor. How do you help Hoshi navigate this?
- Group C: You are designing the engineering review process for future projects. What do you recommend?

### Debate Format
Set up structured debate:
- Team 1: Argue for bringing Trip in with full authority
- Team 2: Argue for keeping it with Hoshi
- Team 3: Argue for a collaborative third approach

Then switch positions and argue the opposite.

---

## Additional Resources

### Related Reading
- "The Manager's Path" by Camille Fournier (Chapter on managing acquisitions)
- "Debugging Teams" by Brian Fitzpatrick & Ben Collins-Sussman (Chapter on trust)
- "Thinking in Systems" by Donella Meadows (Systems thinking fundamentals)

### Related Case Studies (If Available in Your Library)
- Cases about post-acquisition integration
- Cases about technical conflict resolution
- Cases about building trust in engineering teams

---

## Facilitator Self-Reflection

After the session, consider:

- What perspectives were underrepresented in the discussion?
- Did I allow enough space for student thinking vs. my own perspectives?
- What surprised me about student insights?
- What would I do differently next time?
- What did I learn from this group?

---

*Remember: Your role as facilitator is to guide discovery, not to provide "the answer." The best learning comes from students wrestling with complexity and articulating their own insights.*
