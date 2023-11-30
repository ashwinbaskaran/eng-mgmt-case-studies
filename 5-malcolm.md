# Context
Acme Corp's Carboni product to incentivize decarbonization using blockchain technology has been very successful. Its integrations have been widely adopted and are running infrastructure now considered critical to several central banks. The company has started work on a big new feature, codenamed Flash, to add utility companies into the Carboni infrastructure. Acme acquired Apex, a small company in a related space, based on the recommendation of Malcolm, Acme's Head of Engineering. The Apex team was assigned the task of building the new utilities-oriented functionality. Because the existing Acme team was still quite busy at the time on other big priorities, they were not closely involved in Flash beyond high-level design review.

The development effort was led by Hoshi, one of Apex's most highly regarded engineers. Hoshi identified that Gorilla, the core data integration component, needed substantial changes to enable Flash and expressed many strong negative opinions about Gorilla's implementation. Trip, the engineer who led Gorilla development (and coincidentally was one of the first Carboni engineers) responded to those opinions but was not closely involved in the follow-up decisions. The initial development progressed smoothly. However, the Gorilla work in particular caused significant integration issues and led to a big delay. Hoshi and team burned both ends of the proverbial candle and Acme finally launched Flash to great fanfare.

Within weeks, several customers - including central banks who really didn't care about the utility integrations - reported problems where the data integration completely broke, rendering the product useless until the application was restarted. Some customers resorted to automated nightly restarts, preferring the guaranteed small amount of data loss over unpredictable failures with unpredictable amounts of data loss.

# Challenge
Malcolm would love to bring Trip into the Flash project to help fix these data integration issues. Hoshi sees this as a sign that Malcolm doesn't trust him, so he pushes back on bringing Trip in. When Malcom asks Trip about this, he says he hasn't looked at it closely but is pretty convinced that Hoshi's changes are to blame. Trip is willing to help but wants full authority to make changes before getting involved.

# Discussion Prompts
- If Malcolm gives Trip the authority to take this forward, what could go right? What could go wrong?
- What should Malcolm communicate to Hoshi if he chooses to bring in Trip? How about if he chooses to leave it in Hoshi's hands?
- How much of this is a people issue and how much a technology and systems issue?
- Stepping back, are there other options, beyond asking either Hoshi or Trip to lead the troubleshooting and fix efforts?
- Acme has a strong set of engineers so the problem will eventually be resolved. In what shape does this leave the team? Does Malcolm need to do anything now or in the future?
- What should Malcom change if he could go back in time?
