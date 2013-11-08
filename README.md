City Camp MN 2013, Session idea notes: Open source organizations and government entities
=======================

## Full session idea text:

How can we see make it easier for citizens to contribute to government on a large, distributed scale? Can the open source model teach about effective government and civic activity? Can we write unit tests for governing to make sure that we understand the consequences of new legislation?

[View this session idea on IdeaScale](http://citycampmn2013.ideascale.com/a/dtd/Open-source-organizations-and-government-entities/9570-26383)<br>
[View all session ideas on IdeaScale](http://citycampmn2013.ideascale.com/)

## Pre-Session Notes, a completely unorganized brain dump by Jim Cummins

<br>
### Q1: How can we see make it easier for citizens to contribute to government on a large, distributed scale?

<br>
![Stop, collaborate and listen](/img/icestop.jpg)
<br>

**Enabling people and organizations:**

* Better technology? Sure, but tech improvements are usually a jump forward that don't last over time until the next jump. Between advances we probably want persistent gradual improvement if at all possible.
* Minimize unchecked centralized power or those that would limit others' individual rights to engage. In other words, downvote discrimination and those attempting to increasing barriers to entry.
* Let unsupported, poorly implemented or undocumented projects and laws DIAF. Fork them or don't. Either way it will open the door for a new idea, a new implemention, a new series of tests. It is hard to force government to address new problems with new solutions when old solutions are on the books for infinite periods of time.  How do open source projects handle releases and sunsetting? When do we release a law, when do we sunset a law?
* Prioritize commits, not lines added. Adding useless bloat is not governing. Adding useful features while making government more efficient is governing.
* Be suspicious of proprietary code. Be suspicious of proprietary laws.
* Minimize the cost for an average citizen to spin up a repo / law / group / organization.
* Subsidize organizations and laws that are inclusive and transparent (open source), tax the hell out of those that aren't (closed source, private).
* If companies have a particular area where they would like the government to improve, let them contribute to the process openly, not through lobbying. Let everyone see the information they push to government/master. No more sneaking it in through congressman/dev.

**Potential Problems:**

 * Jargon vs Plain Language? When is domain specific language appropriate in legislation? Can we expect everyone to know every DSL? When does a DSL become a significant barrier to entry? Is existing administrative language and tax code a significant barrier to entry or a strong basis to move forward?
 * Similarly, how do we address people that won't write documentation? Currently many projects documentation is README.MD and a few comments. Some laws have event less than this. How can this be improved?
 * How can we downmod trolls...? Some people just like to watch the world burn.
 * Lag time as adoption grows. Is there a point when a certain language is determined to be fundamentally flawed and then discounted completely?
 * Conversely, how do we balance the law's stability vs features? Are big laws better, or should we move some laws out of core over time and keep government lean?
 * Doesn't really answer this question: Who trumps who, transparency vs privacy? In this a governing system that is modeled on open source, you have to pay for your privacy and private repos. Does privacy then just become a perk of the wealthy or does openness just become the default position?
 * How do we determine how often to refactor a law or policy? Does government try to do too much by keeping existing laws on the books until overturned?

<br>
### Q2: Can the open source model teach about effective government and civic activity? 

<br>
![Don't mock me bro](/img/kittymock.jpg)
<br>

**Parallels between open source and government**

* Can we write laws with dependency injection via type hinting so that future changes flow through, but individual laws can be mocked in our tests?
* We don't all write/speak the same language.
* We don't all have the same goals.
* Working in a distributed fashion is great for fostering innovative approaches, but eventually we have to commit and deploy to prod. If we collaborate, who decides when to push?
* Unmaintainable code is bad. Unmaintainable laws are worse.

<br>
### Q3: Can we write unit tests for governing to make sure that we understand the consequences of new legislation?

<br>
![Business cat on supply and demand](/img/whyyou.jpg)
<br>

What can we do to test our laws (code)? 

We might be able to write tests for government entities by calculating and making assertions about the the sum of the total good vs the sum of the total bad! Sweetness, but oh noes, we have a problem, how do we quantify good vs bad, how do we identify need vs want. How do we estimate a finite but unknown supply of goods and services? Will a real economist please stand up?

Ok since I am not an economist, I'm going to put some personal opinions out there and hope that others can address the question better than I can.

** Q: Why is this a question I care about answering? **

A: Because I want to be proud of myself and the groups I am in, even if my group is currently a group of one!

** Random collection of thoughts: **

 * My belief: Voluntary collectivism is probably the best of some bad options we have. Individuals who voluntarily engage in improving the positon of themselves, their groups, or society are happier than people who are apathetic and disengaged!
 * What do we mean by engaging? 
  * Sometimes engaging means challenging the status quo. (eg. Civil rights expansions)
  * Sometimes this means furthering the status quo. (eg. Improving healthcare.gov)
 * Feeling proud of our contribution to society, family, community is a good thing and makes us feel warm fuzzies.
 * Feeling like we've contributed in a meaningful way is helpful in experiencing a sense of connection with our fellow members of society.
 * Not feeling like we can contribute can makes us feel apathetic.  Is it worse to be apathetic or wrong? I would say apathetic.
 * Why? Because we're not going to get it right every single time we try something, but that's ok as long as we learn from it and keep our minds open. Perhaps we just learn just enough to know that we don't know much. That's ok.
 * Apathy breeds disconnnection. Individuals should be free to contribute to the status quo or create a fork of an implementation of some government process.
 * Being critical of the status quo is not unpatriotic or apathetic if used to contribute, engage others, and assuming the criticisms are not descriminatory.
 * If you fork, you must be prepared for society to reject your pull request. If this happens, you've not made your case well enough or you have some code that is fundamentally at odds with some other code or you're just too bleeding edge for society. How do we start to educate people that this isn't a failure of their idea, but just an indication that it needs to be improved further. 

Economic modeling is imperfect:
* Why? Because models are created by humans and only encompass what we already know to be true or not true.
* So, is the best we can hope for to create a society that passes certain existing tests?
* When to refactor? How do we refactor fairly?

Demand:
* Can we model human desires (might be tough when the sum is infinite)?
* Can we model human needs (finite, but hard to estimate)?
* What does government do? Tags a given demand entity as a want vs a need.
* A need is something that society identifies as critical to live, desired or not.
* A want is something that society identifies as unneccesary to live, but desired nonetheless. 

So, with all this imperfection in quantifying human wants and needs, should we write tests if we know they are going to be wrong and imperfect?

Yes! As humans, we know our world is imperfect, but we're also hopeful, optimistic, and want a better life for ourselves, our kids, or our world. We are either selfish or unselfish, but either way we are able to understand that our world is unperfect.

Can we model a desire... We can try, but generally wants are infinite. 

Can we model supply... We can try.

 desire = {
 	"name" : "money",
 	"quantity" : infinity,
 	"tags": [
 		"want",
 		"transferable"
 	]
 }

 Since the sum of our wants in infinite, each want is infinite as well. This is a problem for testing. We're either going to have to manually balance resources or let these float. Supply is easier to map, but still hard when we introduce that everything is in theory transferable, but in practice is not. Various accounting methods attempt to address this by estimating depreciation, but these methods are imperfect and are more useful for addressing the value of assets at a given point in time and not estimating how a given change in the law will impact the future rate of depreciation of assets. The idea of economics as a science is not precise and as such, any tests assuming a known finite supply will be at the mercy of that margin of error.

 

Writing good tests of laws. 

assertTrue(sum(good) > sum(bad))

How do we put discrete values on goods and bads?

Economics: Economists need to write unit tests.
Sociologists: Sociologists need to write unit tests.






A pull request should not be rejected unless it is descriminatory or fundamentally conflicts with another part of the law.


 * Ultimately we cannot have 5 implementations of tax law.
 * Government is inflexible because we are a nation of laws.
 * Business demands stability.
 * Markets like stability.

 But...
 * Stability for stability's sake can breed:
 ** Inequality
 ** Poverty
 ** Resentment
 ** Apathy (ininite loop?)

 So what can we agree on?
 * More flexible government?

 * 

 Approaching things realistically:
 * We will not succeed every tiime.
 * We will not fail every time either.
 * 
 * Being critical of the status quo and 
 * Caring about having an effective, efficient government is good because it breeds pride.
 * Pride is good when it is rooted in the ideas of involvem
 * Apathy is bad, and comes from the idea that a single person cannot affect change
 *

 Ok Mr. Idealist, come on back to Earth.

Citizen contribution to government:
 * Volunteerism (service)
 * Donation ()
 * Idea contribution