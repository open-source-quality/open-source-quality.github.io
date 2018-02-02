---
layout: post
title:  "Open-source Maturity Model"
date:   2018-02-01 00:00:01 +0000
---

# Open-Source Maturity Model

This model was built to clarify Intention to use, Risks and Resource Wastage in the process specific for maturity stages based on Hype Cycle chart.

![Hype Cycle Chart](/hype-cycle-chart.png){:class="img-responsive"}

I've devided this chart in 4 sections:
- Trigger, as the initial development stage
- Hype, from Trigger stage to the Hype "crysis"
- Crystallization, from the popularity spike right to the Slope of Enlightment
- Productivity, the rest part of the chart

Model could be observed from 2 perspectives:
- Possible user of the project
- Participant of the project community

For each stage I'll provide:
- _Intention to Use_, short description of possible ways to safely adopt solution on any maturity stage
- _Indicators_, assistance in making decision about maturity stage
- _Stage Risks_, which should be considered first
- _Resource Wastage_, hint about the possible development process optimization

And the last thing. While project become more mature it's also become less innovative, so keep yours goal clear.
The more innovative tool you want to use the more risky it will be.
As usual.

Have fun!


## Trigger Stage
---
### Intention to Use
The goal of the stage is to create a working protype.
Projects on that stage pretty hard to discover as they are small and not popular yet.
However, Trigger projects could bring the innovation to your environment.
The biggest advantage of early adoption is that you could influence the innovation development and
also be on the peak in the problem area.

### Indicators
Low contributions activity
Low number of installations/downloads
The highest activity is changes in the source code

### Stage Risks
Unpredictable. No guarantees, absolutely new problem and solution.
The only safe way to use is to apply it in some isolation from the critical part of the system.

### Resource Wastage
Any action which will not lead you to the most simple and fast solution should be considered as _Resource Wastage_.


## Hype Stage
---
### Intention to Use
The goal of the stage is to collect enought attention to the problem and solution to verify the working prototype.
Intention to use is almost same as for Trigger except two things:
- Hype - not always mean innovation, so it is better to have more deep research about the problem
- High spike of popularity gives better chances to verify solution in shorter period of time. So if some project is really trending
it might be better for enterprise to wait until first _Indicators_ of the _Crysallization_ stage appear. This could eliminate risk of
"false idol".

### Indicators
Trending in media
Low contributions activity
Growing number of installations/downloads
Most of the changes in documention: Readme could be rewritten, different how-to or other articles appear.

### Stage Risks
Still unpredictable. No guarantees, absolutely new problem and solution.
The only safe way to use is to apply it in some isolation from the critical part of the system.
In addition, there should be mentioned:
- Risk of low popularity, which will lead to a longer period of time to verify solution.
- Risk of issues overflow, for the young maintainers team it could be hard to get through.

### Resource Wastage
There is a hack to cut amount of bug reports. You should explicitly define some _Initial Requirements_ of your solution.
It will help users to better understand boundaries of the solution, also.


## Crystallization Stage
---
### Intention to Use
The goal of the stage is to optimize the verified solution and also make it featurefull for higher adoption.
Intention to use is ability to try some innovation in rather stable state. You still should follow the development feed.
But on this stage chances of dissatisfing usage experience drop drastically.
At the same time solution could lack some important features and there is no guarantee that they will be implemented.

### Indicators
Growing contributions activity
Stably modest number of installations/downloads
Changes are both in implementation and docs. At the stage team is more focused on implementation refactoring and optimization.
Although, there is some necessity about further documentation, especialy source documentation.

### Stage Risks
At this stage solution became mature enough for higher adoption. So while still there could be a chance to have a bug the team is
already done hard work about debugging of the solution. So most of the complaints could be about sub-optimal behavior and lack of features.

So for the team the highest risk is the ability to grow up development velocity while focusing on the almost bug-free behavior. Literally, the risks are:
- Support Capacity, the problem is how to balance the development of features and bugs fixes
- Sustainability, as project became pretty adopted team should take actions about ability to recover development in case of maintainer switch.

### Resource Wastage
For the _Support Capacity_ problem it could be a huge optimization to define strict _Feature Requirements_, to get rid of unnecessary and non-critical stuff.


## Productivity Stage
---
### Intention to Use
The goal of the stage is to grow up mature community, which will make solution resillient to the possible problems in development.
Intention to use is ability to adopt almost mature innovationr, which means less risky enterprise usage and high chances of long term support.
One point to focus on is possible over-complexity of the solution and lack of detailed documentation about corner cases and development process.

### Indicators
Stable modest contribution activity
Stable high number of installs/downloads

Changes at this stage mostly take place in documentation. As project grow, the raising complexity leads to lack of documentation.
Although, the focus on bug-free and feature-fullness continue to move development process.
The most important indicator is maintainers team growth. Which, also leads to a problem about communication and dev process establishment.

### Stage Risks
At this stage solution the higher level of adoption could lead to contributions overflow. Maintanance team is critical to grow.
The critical risks are:
- Confusing collaboration, which stall the development process
- Lack of solved problem documentation leads to overcomplexity of the project, the best way is to define boundaries and add documentation
that could help members of community to create alternative solution. On one side it will help to simplify current project and on the other
encourage more developers to participate in problem solving.

### Resource Wastage
For the _Confusing collaboration_ problem the huge optimization is _Development process documetation_ which includes CONTRIBUTING.md, templates of Issues and Pull Requests, etc.


# Conclusion
---

If you found any part of the document confusing or incomplete feel free to create an Issue on [GitHub](https://github.com/open-source-quality/open-source-quality.github.io/issues).
Contributions are welcome!
