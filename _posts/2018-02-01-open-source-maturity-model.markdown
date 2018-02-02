---
layout: post
title:  "Open-source Maturity Model"
date:   2018-02-01 00:00:01 +0000
---

# Open-Source Maturity Model

Maturity stages of the open-source development process closely mirror phases of the widely used [Hype Cycle chart](https://en.wikipedia.org/wiki/Hype_cycle). An Open-Source Maturity Model can be used to evaluate an open source project at each stage. Take a look at this chart:  

![Hype Cycle Chart](/hype-cycle-chart.png){:class="img-responsive"}

For our purposes, this chart can be divided into four sections:
- __Trigger__ — the initial development stage
- __Hype__ — from the Trigger stage to the "crisis"
- __Crystallization__ — from the popularity spike to the Slope of Enlightenment
- __Productivity__ — rest of the chart

This model could be observed from two perspectives:
- Possible adopter of the project
- A contributor that works on a project

For each stage it is useful to know:
- __Why Adopt?__ — possible benefits of adopting a project at a given stage.  
- __Indicators__ that may assist in decision-making
- __Stage Risks__ that should be considered first
- __Pitfalls__ that may stall the project at this stage

Last but not least: as a project becomes more mature, it also becomes less innovative, so keep yours goal clear. On the other hand, more innovation means more risk.

Have fun!


## Trigger Stage
---
### Why Adopt?
The goal of the stage is to create a working prototype.
Projects on this stage are pretty hard to discover as they are small and have not gained popularity yet.
However, adopting a Trigger project is a good way to bring innovation to your environment.
The biggest advantage of early adoption is that you can steer the
innovation personally and address major problems early.

### Indicators
- Low contributions activity;
- Low number of installations/downloads;
- Most of the changes concern code.

### Stage Risks
Unpredictable. There are no guarantees, as both a problem and a solution are entirely new. Can only be used safely when isolated from the mission-critical part of your system.

### Pitfalls
Any action that does not directly lead to the simples and fastest solution must be considered _a waste of resources_ (e.g., avoid premature optimization).


## Hype Stage
---
### Why Adopt?
The goal of the stage is to collect enough attention to the problem and its solution and to verify the working prototype. Reasons to adopt re almost the same as for the Trigger stage, except two things:
- Hype does not always equal innovation, so a deeper research might be in order.
- A popularity spike allows to quickly verify if a solution works. If the project is currently trending, it might be better for an enterprise to wait until first _Indicators_ of the _Crystallization_ stage appear. This can eliminate the risk of "creating a false idol".

### Indicators
- Trending in media;
- Low contributions activity;
- Growing number of installations/downloads;
- Most of the changes concern documentation: README changes often, how-tos and introductory articles start appearing.

### Stage Risks
Still unpredictable and without guarantees. Still has to be used in isolation. Other things to watch out for:
- Popularity may still drop, which will lead to a longer period of time to verify solution;
- Risk of _issues overflow_ that can be hard to deal with for young teams of maintainers.

### Pitfalls
Too many bug reports. Can be reduced by clearly defining some _Initial Requirements_ of your solution. It will help users to better understand boundaries.


## Crystallization Stage
---
### Why Adopt?
The goal of the stage is to optimize an already verified solution and  make it "feature-rich" in order to increase adoption. Adopting at this stage allows to try out an innovation without worrying too much about instability. You should still follow the developer's feed, but the chances of being dissatisfied are rather low. At the same time, a solution could lack some important features and there is no guarantee that they will be implemented.

### Indicators
- Growing contributions activity;
- Still modest number of installations/downloads;
- Changes are both in code and in docs. At this stage project's team is focused on refactoring and optimization, but more documentation is still necessary, especially regarding the source code.

### Stage Risks
At this stage a solution have become mature enough to sustain higher adoption rates.
While there is still a chance to encounter a bug, most of debugging has already been done by the maintainers team. The majority of complaints are about sub-optimal behavior and lack of features.

From the maintainer's perspective, it is tricky to increase velocity while keeping the behavior bug-free. The risks are:
- _Support Capacity_ — how to balance between features and bug fixes.
- _Sustainability_ — as project became well-adopted its team should ensure the development can be continued, even if there's a change of  maintainer.

### Pitfalls
_Support Capacity_ problem can be hard to solve unless you define clear _Feature Requirements_ that allow to get rid of unnecessary and non-critical stuff.


## Productivity Stage
---
### Why Adopt?
The goal of the stage is to create a mature community, which will make solution resilient to possible problems in development. It's a chance to adopt an almost mature innovation that means less risks for enterprise use and a higher chance of long term support. One point to focus: possible overcomplexity of the solution and a lack of detailed documentation about corner cases and development processes.

### Indicators
- Stable but modest contribution activity;
- Stable and high number of installs/downloads;
- Changes at this stage mostly take place in documentation. As a project grows, a raising complexity leads to the lack of documentation.
The focus on bug-free and feature-rich project continues to drive the development process.
- The most important indicator is the growth of maintainers team. That may lead to problems with communication and the establishment of internal processes.

### Stage Risks
At this stage, rising adoption level can lead to contributions overflow. Maintenance team _must_ grow accordingly.

The critical risks are:
- _Confusing collaboration_ that stalls the development process.
- _Lack of "problem solving" documentation_ leads to overcomplexity of the project.

The best way to mitigate these risks is to define boundaries and add documentation that could community members to create _alternative_ solutions. It will help simplify the main project while encouraging more developers to participate in problem solving.

### Pitfalls
_Confusing collaboration_ problem can hardly be solved without clear _development process documentation_ that includes CONTRIBUTING.md, templates of Issues and Pull Requests, etc.

---

If you found any part of this document confusing or incomplete feel free to create an Issue on [GitHub](https://github.com/open-source-quality/open-source-quality.github.io/issues).
Contributions are welcome!
